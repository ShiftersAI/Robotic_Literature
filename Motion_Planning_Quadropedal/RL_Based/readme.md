# RL Based Motion planning for Quadropedal Robots
***
## 2019

 ### [Learning to Walk via Deep Reinforcement Learning, 2019](/Motion_Planning_Quadropedal/RL_Based/Learning%20to%20Walk%20via%20Deep%20Reinforcement%20Learning.pdf)
The problem of sample efficiany is addressed via a noval approach to the maximal entropy Reinforcement learning replacing the manual tunning of the temperature (traditionally set namually for each task) with a constraint on the entropy and solving the constraint problem with a dual Lagrangian method. The approach is implemented on a small quadropedal robot which achives acceptable performance within 2 hour of training (~400 rollouts) with no pre-training in simulation.

***

## 2020

### [Learning Quadrupedal Locomotion over Challenging Terrain, 2020](/Motion_Planning_Quadropedal/RL_Based/Learning%20Quadrupedal%20Locomotion%20over%20Challenging%20Terrain.pdf)
This seminal paper is the brought to light the abbility to used RL method for complex motion planning tasks. The main result of this work is a highly robust controller for a quadropedal robot based solely on prioperceptive sensors capable of traversing extremly challenging terrains. It is this controller that wa used by cerberus team to win the DARPA subterenious challenge.
The main noval components are:
- **A novel teacher-student learning architectue** in which the teacher network learns both a latent space embedding and a policy via an RL method and the student learns the same elements (different architecture-TCN) learned with imitation learning in which the input to the embedding in a sequence of preoperceptive observations.
- **Curriculem learning**
- **Low level deployement of the policy**

***

## 2021

### [Learning to jump from pixels, 2021](/Motion_Planning_Quadropedal/RL_Based/Learning%20to%20Jump%20from%20Pixels.pdf)

***

### [Learning to Walk in Minutes Using Massively Parallel Deep Reinforcement Learning, 2021](/Motion_Planning_Quadropedal/RL_Based/Learning%20to%20Walk%20in%20Minutes%20Using%20Massively%20Parallel%20Deep%20Reinforcement%20Learning.pdf)

***

### [RMA: Rapid Motor Adaptation for Legged Robots, 2021](/Motion_Planning_Quadropedal/RL_Based/RMA%20Rapid%20Motor%20Adaptation%20for%20Legged%20Robots.pdf)

This paper introduces the adaptation modual.
***

### [Walk These Ways, 2022](/Motion_Planning_Quadropedal/RL_Based/Walk%20These%20Ways.pdf)

***

## 2022

### [Legged Locomotion in Challenging Terrains using Egocentric Vision, 2022](/Motion_Planning_Quadropedal/RL_Based/Legged%20Locomotion%20in%20Challenging%20Terrains%20using%20Egocentric%20Vision.pdf)


***

### [Learning vision-guided quadrupedal locomotion end-to-end with cross-modal transformers, 2022](/Motion_Planning_Quadropedal/RL_Based/Learning%20Vision-Guided%20Quadrupedal%20Locomotion%20End-to-End%20with%20Cross-Modal%20Transformers.pdf)

***
### [Deep Whole-Body Control: Learning a Unified Policy for Manipulation and Locomotion, 2022](/Motion_Planning_Quadropedal/RL_Based/Deep%20Whole-Body%20Control%20Learning%20a%20Unified%20Policy%20for%20Manipulation%20and%20Locomotion.pdf)

***

### [Adversarial Motion Priors Make Good Substitutes for Complex Reward Functions, 2022](/Motion_Planning_Quadropedal/RL_Based/Adversarial%20Motion%20Priors%20Make%20Good%20Substitutes%20for%20Complex%20Reward%20Functions.pdf)

***

### [DayDreamer: World Models for Physical Robot Learning, 2022](/Motion_Planning_Quadropedal/RL_Based/DayDreamer%20World%20Models%20for%20Physical%20Robot%20Learning.pdf)

***

## 2023

### [Robot Parkour Learning, 2023](/Motion_Planning_Quadropedal/RL_Based/Robot_Parkour_Learning.pdf)

***

### [Extreme Parkour with Legged Robots, 2023](/Motion_Planning_Quadropedal/RL_Based/Extreme%20Parkour%20with%20Legged%20Robots.pdf)
This work  applies the same principle of teacher-student framwork in order to enable extreem manuvers. The teacher is learned with sampeled hight map and in addition an "expert" direction for the manuver. 
The student policy, learned by imitaion, takes as an input both the robot state and an head facing depth camera and the output is the estimated expert direction and the latent enviroment estimation.
In addition the work presents a simple reward function structure, in particular for the jap jump.

***

### [Legs as Manipulator: Pushing Quadrupedal Agility Beyond Locomotion, 2023](/Motion_Planning_Quadropedal/RL_Based/Legs%20as%20Manipulator%20Pushing%20Quadrupedal%20Agility%20Beyond%20Locomotion.pdf)

***

### [Hybrid Internal Model: Learning agile legged locomotion with simulated robot responcse](/Motion_Planning_Quadropedal/RL_Based/HYBRID%20INTERNAL%20MODEL%20LEARNING%20AGILE%20LEGGED.pdf)

[Project page](https://junfeng-long.github.io/HIMLoco/)

The HIM (Hybrid Internal Model) motion control architecture takes insperation from the Internal Mode Control applied in classical control theory. The method adds an intrnal model of the system which outputs a latent next step estimation of the robot which is then fed into the policy to obtain the next action. 
The critic is exposed to priveledge knowledge (higth map and external forces) while the Internal Model (Source incoder) is exposed to a trajectory of Proprioceptive states.
The Internal nodel is trained with a form of contrastive learning.
In all this is a highly robust yet seems overly convoluded, in addition the current from does not include any etraproceptive observation (e.g., camera) however they may be easily integrated.
 
***

### [DreamWaQ: Learning Robust Quadrupedal Locomotion With Implicit Terrain Imagination via Deep Reinforcement Learning, 2022](/Motion_Planning_Quadropedal/RL_Based/DreamWaQ:%20Learning%20Robust%20Quadrupedal%20Locomotion%20With%20Implicit%20Terrain%20Imagination%20via%20Deep%20Reinforcement%20Learning.pdf)

## 2024

### [Agile Continuous jumping in Discontinuous Terrain, 2024](/Motion_Planning_Quadropedal/RL_Based/Agile%20Continuous%20Jumping%20in%20Discontinuous%20Terrains.pdf)

***

### [RL + Model-based Control: Using On-demand Optimal Control to Learn Versatile Legged Locomotion, 2024](/Motion_Planning_Quadropedal/RL_Based/RL%20+%20Model-based%20Control.pdf)


***

### [Stage-Wise Reward Shaping for Acrobatic Robots: A Constrained Multi-Objective Reinforcement Learning Approach, 2024](/Motion_Planning_Quadropedal/RL_Based/Stage-Wise%20Reward%20Shaping%20for%20Acrobatic%20Robots.pdf)

***

### [Deep Compliant Control for Legged Robots, 2024](/Motion_Planning_Quadropedal/RL_Based/Deep%20Compliant%20Control%20for%20Legged%20Robots.pdf)

***

### [Learning to Open and Traverse Doors with a Legged Manipulator, 2024](/Motion_Planning_Quadropedal/RL_Based/Learning%20to%20Open%20and%20Traverse%20Doors%20with%20Legged%20Manipulator.pdf)

***

### [Perceptive Pedipulation with Local Obstacle Avoidance, 2024](/Motion_Planning_Quadropedal/RL_Based/Perceptive%20Pedipulation%20with%20Local%20Obstacle%20Avoidance.pdf)
