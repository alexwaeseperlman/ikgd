# ikgd
A simple demo of a simple inverse kinematics algorithm

## How it works
Define `loss(theta_1, ..., theta_n)` as the distance from the head of a robotic arm to a target point. We can solve for the derivative of loss with respect to each theta, and follow that gradient until loss is zero. This converges quickly on a solution. 
