# Solve CartPole-v0 using a Fixed Deterministic Policy

Zhiqing Xiao

'CartPole-v0' is solved using a fixed deterministic policy.

**Environment**
- Description of 'CartPole-v0' problem: https://github.com/openai/gym/wiki/CartPole-v0
- Old environment page: https://gym.openai.com/envs/CartPole-v0/
- Leaderboard: https://github.com/openai/gym/wiki/Leaderboard

**Policy**

Push right when

3 * angle + angle_velocity > 0.

otherwise push left.

**File**

- code: https://github.com/ZhiqingXiao/OpenAIGymSolution/blob/master/CartPole-v0/cartpole_v0_close_form.ipynb
