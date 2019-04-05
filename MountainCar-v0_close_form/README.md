# Solve MoutainCar-v0 using a Fixed Deterministic Policy

Zhiqing Xiao

'MountainCar-v0' is solved using a fixed deterministic policy.

**Environment**
- Description of 'MountainCar-v0' problem: https://github.com/openai/gym/wiki/MountainCar-v0
- Old environment page: https://gym.openai.com/envs/MountainCar-v0/
- Leaderboard: https://github.com/openai/gym/wiki/Leaderboard

**Policy**

Push right when

min(-0.09 (position + 0.25)² + 0.03, 0.3 (position + 0.9)⁴ - 0.008) < velocity < -0.07 (position + 0.38)² + 0.07,

otherwise push left.

**File**

- code: https://github.com/ZhiqingXiao/OpenAIGymSolution/blob/master/MountainCar-v0_close_form/mountaincar_v0_close_form.ipynb

**BibTeX**

This solution has been published in Chapter 1 of the following book:

    @book{xiao2019,
     title     = {Reinforcement Learning: Theory and {Python} Implementation},
     author    = {Zhiqing Xiao}
     year      = 2019,
     publisher = {China Machine Press},
    }

