# Work Package for Week 1, 01/05/2020

***Note:*** All details are open to discuss and adjust, even the format of this instruction file itself.

## 1. Related Links

1. Github repository for matlab scripts: <https://github.com/LXYYY/iVip-MARL-Matlab.git>
2. I also forked the matlab mobile robotics simulation toolbox for future modification and reference: <https://github.com/LXYYY/mobile-robotics-simulation-toolbox.git>
3. Reference sharing in <https://github.com/LXYYY/iVip-MARL-References.git>, considering github really slow these days, we may need a better place to manage references.
3. A programming guide for ethz-asl is also forked here for future reference (it's not used for now): <https://github.com/LXYYY/programming_guidelines.git>

## 2. Tasks
The tasks for this week is mainly to dig into the mobile robotics simulation (MRS) toolbox.

1. *For Yicheng*, Review the example code in the toobox, especially the map building, Simulink, and Visualizer parts.
    - How to build an occupancy map, and reset, get lidar data, etc.
    - Understand the structure of the Simulink model given in [examples/navigation_rl/trainObstacleAvoidanceAgent.m](https://github.com/LXYYY/mobile-robotics-simulation-toolbox/blob/master/examples/navigation_rl/trainObstacleAvoidanceAgent.m).
    - If possible, how to modify the map and simulation to dynamic obstacles and multi robots circumstances.
    - If possible, how to build a map according to a environment configuration file, e.g. *.yaml/.txt* etc, as described in *Reference 3*.

2. *For Peixuan*, Review the literature in reinformence learning.
    - The difference between DQN, DDPG and TD3, *Reference 4* may be helpful.
    - The design principle for the actor and critic networks, and their realtionship with policy gradient and reward function, etc, i.e. what is the input and output of the networks, given a specified target and reward function.

3. *For Xiangyu*, Explore the example code in MRS toolbox.
    - How to implement obstacle avoidance and target position reaching simultaneously.
    - Assist other members, to make sure tasks finished in time.


## Known Issures
 - The training process of the example code is very time-consuming and cost a lot computation, we may need a server to run the training in cloud.

## Reference

1. [Matlab MRS toolbox official link](https://www.mathworks.com/matlabcentral/fileexchange/66586-mobile-robotics-simulation-toolbox)
2. [Matlab DQN agent official document](https://www.mathworks.com/help/reinforcement-learning/ug/dqn-agents.html)
3. [Neural networks based reinforcement learning for mobile robots obstacle avoidance, M Duguleana, et al.](https://github.com/LXYYY/iVip-MARL-References/blob/master/path%20planning/1-s2.0-S0957417416303001-main.pdf)
4. [Unmanned Ground Vehicle Indoor Navigation Based on Deep Reinforcement Learning, NTU Dissertation, Yueci Deng](https://github.com/LXYYY/iVip-MARL-References/blob/master/path%20planning/NTU_Master_Dissertation__yueci-signed.pdf)