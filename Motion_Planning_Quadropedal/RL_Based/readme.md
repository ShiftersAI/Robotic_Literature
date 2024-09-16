# RL Based Motion planning for Quadropedal Robots

***
### [Learning Quadrupedal Locomotion over Challenging Terrain, 2022](/Motion_Planning_Quadropedal/RL_Based/Learning%20Quadrupedal%20Locomotion%20over%20Challenging%20Terrain.pdf)
This seminal paper is the brought to light the abbility to used RL method for complex motion planning tasks. The main result of this work is a highly robust controller for a quadropedal robot based solely on prioperceptive sensors capable of traversing extremly challenging terrains. It is this controller that wa used by cerberus team to win the DARPA subterenious challenge.
The main noval components are:
- **A novel teacher-student learning architectue** in which the teacher network learns both a latent space embedding and a policy via an RL method and the student learns the same elements (different architecture-TCN) learned with imitation learning in which the input to the embedding in a sequence of preoperceptive observations.
- **Curriculem learning**
- **Low level deployement of the policy**

 ***

 ### [Learning to Walk via Deep Reinforcement Learning, 2019](/Motion_Planning_Quadropedal/RL_Based/Learning%20to%20Walk%20via%20Deep%20Reinforcement%20Learning.pdf)
The problem of sample efficiany is addressed via a noval approach to the maximal entropy Reinforcement learning replacing the manual tunning of the temperature (traditionally set namually for each task) with a constraint on the entropy and solving the constraint problem with a dual Lagrangian method. The approach is implemented on a small quadropedal robot which achives acceptable performance within 2 hour of training (~400 rollouts) with no pre-training in simulation.

***

### [Learning to Walk in Minutes Using Massively Parallel Deep Reinforcement Learning, 2021](/Motion_Planning_Quadropedal/RL_Based/Learning%20to%20Walk%20in%20Minutes%20Using%20Massively%20Parallel%20Deep%20Reinforcement%20Learning.pdf)

***

### [Walk These Ways, 2022](/Motion_Planning_Quadropedal/RL_Based/Walk%20These%20Ways.pdf)

***

### [Extreme Parkour with Legged Robots, 2023](/Motion_Planning_Quadropedal/RL_Based/Extreme%20Parkour%20with%20Legged%20Robots.pdf)
This work  applies the same principle of teacher-student framwork in order to enable extreem manuvers. The teacher is learned with sampeled hight map and in addition an "expert" direction for the manuver. 
The student policy, learned by imitaion, takes as an input both the robot state and an head facing depth camera and the output is the estimated expert direction and the latent enviroment estimation.
In addition the work presents a simple reward function structure, in particular for the jap jump.

***