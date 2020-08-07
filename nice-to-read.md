# Worth reading material

#### [Reflections on Random Kitchen Sinks](http://www.argmin.net/2017/12/05/kitchen-sinks/)
a good talk by Ali Rahimi and Ben Recht that won the test of time award at NIPS 2017.

#### [MDP notation paper](https://arxiv.org/abs/1512.09075) 

#### [The Principle of Unchanged Optimality in RL Generalization](https://arxiv.org/abs/1906.00336)
if you change the dynamics, make this observable to your policy, or else your problem isn’t well-founded. It also talks about how model-based RL can improve sample efficiency at the cost of generalization, by constructing setups where modelling environment-specific features speeds up learning in that environment while generalizing poorly to other environments.

#### [Off-Policy Evaluation via Off-Policy Classification](https://arxiv.org/abs/1906.01624)
It’s about off-policy evaluation, the problem of evaluating an RL policy without directly running that policy in the final environment. Our aim was to evaluate policies using just a Q-function, without importance sampling or model learning. With some assumptions about the MDP, we can use classification techniques to evaluate policies, and we show this scales up to deep networks for image-based tasks, including evaluation of real-world grasping models.

#### [OpenAI's Rubik's Cube takeaway](https://www.alexirpan.com/2019/10/29/openai-rubiks.html)
it has lots of good insights about openAI rubic solving but  at the first read i couldn't get much out of it maybe read this one later again.

#### [nature paper for AlphaStar](https://www.nature.com/articles/s41586-019-1724-z)
read through it later.

#### about hyperparameter tuning:
- http://www.argmin.net/2016/06/20/hypertuning/
- http://www.argmin.net/2016/06/23/hyperband/
- https://arxiv.org/abs/1603.06560
- https://github.com/HIPS/Spearmint

#### general common knowldge
- https://arxiv.org/abs/1708.04133
- https://arxiv.org/abs/1709.06560
- http://amid.fish/reproducing-deep-rl
- courses:
  - http://rll.berkeley.edu/deeprlcourse/
  - https://www.davidsilver.uk/teaching/
  - https://sites.google.com/view/deep-rl-bootcamp/lectures
  - http://joschu.net/docs/nuts-and-bolts.pdf
