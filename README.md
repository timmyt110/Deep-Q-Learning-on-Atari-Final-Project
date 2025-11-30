# Deep Q-Learning on Atari Final Project
Objective: This project aims to implement and analyze Deep Q-Networks (DQN) and their extensions by comparing and contrasting agent performance across two distinct Atari environments: Mario and Pong. The project will evaluate how both baseline DQN and extended DQN variants perform during early training phases versus later stages of learning, examining learning curves, behavioral patterns, and final performance metrics. Through this comparative analysis, the project seeks to understand how environmental complexity and algorithmic improvements interact to influence reinforcement learning outcomes in classic gaming environments.

## Early/Randomish vs Later/Learned
Watch how performance improves as training progresses:

### ALE/Mario-V5
| Episode    | Model             | Preview                                             | Video |
|------------|-------------------|-----------------------------------------------------|-------|
| Early      | Near-random       | <img src="src/early_pong.png" width="120"/>       | [▶ Watch](https://github.com/timmyt110/CS166_Fall2025/blob/main/src/early_seaquest.mp4)    |
| Later      | DQN               | <img src="src/later_baseline.png" width="120"/>   | [▶ Watch](https://github.com/timmyt110/CS166_Fall2025/blob/main/src/improved_seaquest.mp4) |
| Later      | DDQN              | <img src="src/later_DDQN.png" width="120"/>       | [▶ Watch](https://github.com/timmyt110/CS166_Fall2025/blob/main/src/improved_seaquest.mp4) |



 
### ALE/Pong-V5
| Episode    | Model             | Preview                                             | Video |
|------------|-------------------|-----------------------------------------------------|-------|
| Early      | Near-random       | <img src="src/early_pong.png" width="120"/>       | <a href="https://github.com/user-attachments/assets/f53a75e4-d522-42d5-809f-a70978024860" target="_blank">▶ Watch</a> |
| Later      | DQN               | <img src="src/later_baseline.png" width="120"/>   | [▶ Watch](https://github.com/timmyt110/CS166_Fall2025/blob/main/src/improved_seaquest.mp4) |
| Later      | DDQN              | <img src="src/later_DDQN.png" width="120"/>       | [▶ Watch](https://github.com/timmyt110/CS166_Fall2025/blob/main/src/improved_seaquest.mp4) |
 
