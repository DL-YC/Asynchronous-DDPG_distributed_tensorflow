Asynchronous-DDPG_distributed_tensorflow
===========

Distributed Tensorflow Implementation of asynchronous ddpg.

Implementation is on Tensorflow 1.3.

DDPG script is based on songrotek's repo. https://github.com/songrotek/DDPG.git

https://arxiv.org/abs/1706.06383

GYM Reacher-v1 game
-------------------

`
./auto_run.sh 
`

You need to set your hostname and port number in gym_addpg.py code. The number of parameter servers and workers can be set in auto_run.sh script file.


