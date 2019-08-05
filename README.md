# CartPole-A2C
The Advantage Actor Critic algorithm implementation for the OpenAI Gym's CartPole environment.


**My Hyperparameters:**

  Number of trajectories = 32

  Learning rate for policy parameters: 0.1

  Gamma: 0.99

  Actor network architecture: (FC-layer(input_shape, 128), FC-layer(128, n_actions))
  
  Critic network architecture: (FC-layer(input_shape, 512), FC-layer(512, 1))

  Advantage function: **R(t) - V(s_t)**
  
  c (Weightage of the critic MSE error in the criterion): 0.01 



**The Rewards (Y-Axis) vs Episodes plot (X-Axis):**
![PLOT](/myplot.png)
