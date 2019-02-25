# Solve MoutainCar-v0 using a Fixed Deterministic Policy

Zhiqing Xiao

'MountainCar-v0' is solved using a fixed deterministic policy.

**Environment**
- Description of 'MountainCar-v0' problem: https://github.com/openai/gym/wiki/MountainCar-v0
- Old environment page: https://gym.openai.com/envs/MountainCar-v0/
- Leaderboard: https://github.com/openai/gym/wiki/Leaderboard

**Policy**

Push right when

$\min \left(-0.09 (\text{position} + 0.25) ^ 2 + 0.03, 0.3 (\text{position} + 0.9) ^ 4 - 0.008 \right) \le \text{velocity} \le -0.07 (\text{position} + 0.38) ^2 + 0.07$,

otherwise push left.

**File**
- code: https://github.com/ZhiqingXiao/OpenAIGymSolution/blob/master/MountainCar-v0_close_form/mountaincar_v0_close_form.ipynb
