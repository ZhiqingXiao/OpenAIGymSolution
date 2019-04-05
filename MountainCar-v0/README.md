# Solve MountainCar-v0 using SARSA(_λ_) + TileCoding

Zhiqing Xiao

'MountainCar-v0' is solved within 75 episodes using SARSA(_λ_) and tile coding.

**Environment**
- Description of 'MountainCar-v0' problem: https://github.com/openai/gym/wiki/MountainCar-v0
- Old environment page: https://gym.openai.com/envs/MountainCar-v0/
- Leaderboard: https://github.com/openai/gym/wiki/Leaderboard

**Method**
- SARSA(_λ_) with _λ_ = 0.9 and replacement trace. Learning rate _α_ = 0.03.
- No discount _γ_ = 1. Exploration _ε_ = 0.001.
- Tile coding with asymmetrical offsets. 8 layers and ≤ 2000 features.
- No reward engineering.

**Files**
- code: https://github.com/ZhiqingXiao/OpenAIGymSolution/blob/master/MountainCar-v0/mountaincar_v0_sarsa_lambda_tilecode.ipynb
- videos for both training and testing: https://github.com/ZhiqingXiao/OpenAIGymSolution/tree/master/MountainCar-v0/records
- pickled agent: https://github.com/ZhiqingXiao/OpenAIGymSolution/blob/master/MountainCar-v0/resources/agent.pkl
- Anaconda environment yml file: https://github.com/ZhiqingXiao/OpenAIGymSolution/blob/master/MountainCar-v0/resources/anaconda_env_win10_py371.yml

**BibTeX**

This solution has been published in Chapter 6 of the following book:

    @book{xiao2019,
     title     = {Reinforcement Learning: Theory and {Python} Implementation},
     author    = {Zhiqing Xiao}
     year      = 2019,
     publisher = {China Machine Press},
    }
