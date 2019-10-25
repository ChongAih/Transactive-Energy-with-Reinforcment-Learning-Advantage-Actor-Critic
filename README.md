# Transactive-Energy-with-Reinforcment-Learning-Advantage-Actor-Critic

* The script is coded in Google Colab, thus there exist commands to retrieve files from and store files to google drive. Modification is required for any personal use.

* The data used in the project is modified from GEFCom2014 (load & real time pricing) and Energy Market Authority (solar). The energy storage system (ESS) used in the project is rated 1000kW and 5000kWh.

* In this project, a model free policy based reinforcement learning method - advantage actor critic (A2C) is trained to execute energy trading decision using energy storage system according to real time pricing, load, solar and etc. Actor decides the action of ESS while critic feedbacks the advantage of such action. 

* From the training result, it is found that the model is able to find the suboptimal decision. As compared to DQN (https://github.com/ChongAih/Transactive-Energy-with-Reinforcment-Learning-Deep-Q-Network/blob/master/README.md), A2C provides a smoother ESS operation but it tends to converge to a local maxima.

