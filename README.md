# RL_balance
Using PPO within Myosuite framework to predict the process of motor learning in human
created a new environment within myosuite framework to simulate perturbed balance training.
a platform moves underneath the musculoskeletal model and the PPO agent learns how to respond
to different levels of periodic perturbation imposed by the platform acting as a moving treadmill.
this project is still in progress
installation guide:
https://myosuite.readthedocs.io/en/latest/install.html
steps to create a new environment:
- create an instance of the parent MyoSuite and MuJoCo class, defining new observations, rewards, termination conditions etc....
- needed XML files for the musculoskeletal model used in the simulation, any new part and or scene as well as initial positions and velocities are defined here,
- Register the new environment within the framework
- Write the relevant Python script to run your simulation
