# Solve MoutainCarContinuous-v0 using a Fixed Deterministic Policy

Zhiqing Xiao

'MoutainCarContinuous-v0' is solved using a fixed deterministic policy.

**Environment**
- Description of 'MoutainCarCountinous-v0' problem: https://github.com/openai/gym/wiki/MountainCarContinuous-v0
- Old environment page: https://gym.openai.com/envs/MountainCarContinuous-v0/
- Leaderboard: https://github.com/openai/gym/wiki/Leaderboard

**Policy**

Action (a.k.a. force) equals +1 when

position > -4 * velocity or position < 13 * velocity - 0.6,

otherwise action equals -1.

**File**

- code: https://github.com/ZhiqingXiao/OpenAIGymSolution/blob/master/MountainCarContinuous-v0/mountaincarcontinuous_v0_close_form.ipynb
