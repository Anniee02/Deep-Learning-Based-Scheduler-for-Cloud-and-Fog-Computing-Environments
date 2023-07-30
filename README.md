# Deep-Learning-Based-Scheduler-for-Cloud-and-Fog-Computing-Environments

Two specific issues, time scheduling and resource allocation, must be taken care of in order to plan jobs in edge computing. Time scheduling determines the order in which tasks are completed, while resource allocation is in charge of assigning tasks to suitable virtual resources execution on virtual machines (VMs). For the purpose of achieving a long-term objective, the Markov decision process (MDP) is a valuable tool for modelling the sequential decision-making problem.
Reinforcement learning (RL), in which the agent continuously interacts with the environment and makes sequential decisions, has been established as a potential means of resolving MDP problems. Instead of focusing on the local optimal solution in real time, the agent's ultimate goal is to create an ideal policy that maximises the cumulative reward. It is inconvenient, especially for large state spaces and continuous action spaces, for the mapping between state and action in real-world systems to be maintained in a tabular format.
When paired with the deep neural network (DNN), model-free deep reinforcement learning (DRL) can produce intelligent sequential decisions in challenging circumstances, and the RL table is thus replaced by the DNN's function approximation. In recent years, DRL has been successfully used for resource allocation and time scheduling in edge computing. The deep Q-network (DQN) technique uses numerous replay memories to improve overall latency and resource consumption. The compute resource allocation problem in edge computing is defined as an MDP.
We outline a model for intelligent job scheduling in edge computing in our study. To maximize the long-term value of QoE while accounting for the anticipated delay necessary, we focus on heterogeneous VM resources for task scheduling. The task satisfaction level is defined as the reward in order to accomplish this goal using the DRL approach. The task execution order is determined by the mechanism, and the work is then assigned to the appropriate VM in the second portion of its operation. An MDP is created from the work scheduling process in edge computing, and a policy-based DRL algorithm
