# pendulum_chaos
Sofa scene to simulate multiple inextensible double pendulums

![thumbnail](https://github.com/alxbilger/pendulum_chaos/raw/main/thumbnail.png)

A double pendulum motion is chaotic: it is highly sensitive to the initial conditions.
Here, the 1000 double pendulums are placed at an angle between 45° and 46°. The difference between two consecutive pendulums is only 1/999 (~0.001) degrees.

At the beginning, the pendulums seems to move all together. After some time, the difference becomes noticeable, until they all appear independent, as if they did not start together.

Inextensibility is solved with constraints.
ODE solver is implicit Euler.

See a video of the simulation:
https://youtu.be/j1WBztUCyms

Sofa:
https://www.sofa-framework.org/
