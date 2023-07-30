# Portfolio Aufgabe 3

Author: Jana Lugeder
Course: WWI 20 DSB
Subject: Reinforcement Learning
Semester: 6
Lecturer: Janina Patzer

# Subject

Training of an agent to learn to walk

# Environment

<br>- PyBullet
<br>- Panda-gym

## action space

8 possible actions

<br>0: Front left hip
<br>1: Front left ankle
<br>2: Back left hip
<br>3: Back left ankle
<br>4: Back right hip
<br>5: Back right ankle
<br>6: Front right hip
<br>7: Front right ankle

## observation space

29-dimensional array

<br>0-2: Torso position --> (x,y,z)
<br>3-6: Orientation --> (x,y,z,w)
<br>7-8: Front left leg joint angles (JA) --> (Hip JA), (Ankle JA)
<br>9-10: Back left leg JAs --> (Hip JA), (Ankle JA)
<br>11-12: Back right leg JAs --> (Hip JA), (Ankle JA)
<br>13-14: Front right leg JAs --> (Hip JA), (Ankle JA)
<br>15-17: Torso velocity --> (x,y,z)
<br>18-20: Torso angular velocity --> (x,y,z)
<br>21-22: Front left leg velocity --> (Hip velocity), (Ankle velocity)
<br>23-24: Back left leg velocity --> (Hip velocity), (Ankle velocity)
<br>25-26: Back right leg velocity --> (Hip velocity), (Ankle velocity)
<br>27-28: Front right leg velocity --> (Hip velocity), (Ankle velocity)
