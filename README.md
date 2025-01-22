# Robot-3-DOF-Reinforcement-learning-control

> **Warning:** Project is being migrated to individual repository. Stay tuned for updates.

RL control of a 3-DOF robot using stable baselines to achieve certain positions.

The goal of this project is to be able to control a UR3e-like robot, as shown in the image below, to achieve specific positions based solely on the final effector position, using reinforcement learning (RL) for control.

<img src="https://github.com/user-attachments/assets/c408a8d5-1253-4abf-97cf-a6fb9339ab68" alt="UR3e-like robot" width="300">

## 3-DOF Robot

I designed an environment to simulate the dynamics of a 3-DOF robot and implemented a reinforcement learning algorithm (PPO) to achieve the required control.

### Training Progress

| Before Training | 
|-----------------|
| ![Before Training](https://github.com/user-attachments/assets/92e5f981-94b3-4f45-a8ed-d4abaee6008d) |

| After 100,000 Steps |
|---------------------|
| ![After Training 100k](https://github.com/user-attachments/assets/6f4025b6-8d30-4702-b31c-d8a78891e88a) |

| After 500,000 Steps |
|---------------------|
| ![After Training 500k](https://github.com/user-attachments/assets/e42b7651-4394-4c50-a5e6-0f62e65f6f22) |

### Key Features
- **Custom Simulation Environment**: Simulates the dynamics of a 3-DOF robot.
- **Reinforcement Learning Algorithm**: Uses Proximal Policy Optimization (PPO) for training.
- **End Effector Control**: Focused on achieving target positions based solely on end effector dynamics.

### Results
- The RL agent successfully learns to control the 3-DOF robot, achieving precise end effector positioning after training.

### Future Work
- Extend the environment to include obstacles for collision avoidance.
- Scale the implementation to control robots with higher degrees of freedom.
- Compare PPO with other RL algorithms like DDPG or SAC.

### Check Out My Other Projects
Explore more of my AI and ML work [here](https://github.com/devMuniz02/AI-ML-Code-and-projects/).

### License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
