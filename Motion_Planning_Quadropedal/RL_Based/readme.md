# RL Based Motion planning for Quadropedal Robots
***
### [Learning Quadrupedal Locomotion over Challenging Terrain](/Motion_Planning_Quadropedal/RL_Based/Learning%20Quadrupedal%20Locomotion%20over%20Challenging%20Terrain.pdf)
This seminal paper is the brought to light the abbility to used RL method for complex motion planning tasks. The main result of this work is a highly robust controller for a quadropedal robot based solely on prioperceptive sensors capable of traversing extremly challenging terrains. It is this controller that wa used by cerberus team to win the DARPA subterenious challenge.
The main noval components are:
- **A novel teacher-student learning architectue** in which the teacher network learns both a latent space embedding and a policy via an RL method and the student learns the same elements (different architecture-TCN) learned with imitation learning in which the input to the embedding in a sequence of preoperceptive observations.
- **Curriculem learning**
- **Low level deployement of the policy**
 ***