# Reinforcement Learning Final Project
## 1. Atari
### 1.1 Requirements
```
python=3.9
torch==2.0.0
CUDA 11.7
gymnasium[atari]
gymnasium[accept-rom-license]
```
### 1.2 Run
```
python DuelingDQN.py --env_name BoxingNoFrameskip-v4
```
## 2. Mujoco
### 2.1 Requirments
```
python=3.7
torch==1.8.2
CUDA 11.1
mujoco_py==2.0.2.8
```
### 2.2 Run
```
python PPO_Mujoco.py --env_name Hopper-v2
```
