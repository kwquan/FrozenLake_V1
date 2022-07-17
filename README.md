# FrozenLake_V1
This repo contains the code used to solve the FrozenLake[V1] problem using Dynamic Programming

# Description
![alt text](https://github.com/kwquan/FrozenLake_V1/blob/main/FrozenLakeV1.png)

In this notebook[FrozenLake.ipynb], we shall solve the environment Frozen Lake using Dynamic Programming. \
Aim: Frozen lake involves crossing a frozen lake from Start(S) to Goal(G) without falling into any Holes(H) by walking over the Frozen(F) lake. 
     The agent may not always move in the intended direction due to the slippery nature of the frozen lake. \
     Here, we only consider the deterministic problem[no slipping] \
Gridspace: 8x8 \
Action space: 0[LEFT], 1[DOWN], 2[RIGHT], 3[UP] \
Rewards:
1) Reach goal(G): +1
2) Reach hole(H): 0
3) Reach frozen(F): 0

