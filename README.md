# Double Pendulum Prediction

This project entails the use of a machine learning model to predict the position of a double pendulum's lower mass, given incomplete system information. The challenge is to forecast chaotic behavior, which emerges naturally from the pendulum's equations of motion.

Features

Design and Training of RNN: Utilize a Recurrent Neural Network to forecast the future positions of masses 
$m_1$ and $m_2$ based on their cartesian coordinates, using the initial conditions 
$z_0 = [π/4,0,π/4,0] $

Stability Analysis: Investigate how initial condition variations influence the RNN's performance.

Prediction Extent: Assess the network's capability to predict long-term future positions.

Complex Path Prediction: Implement the above steps but with a different set of initial conditions, 
$z_0= [π/2,0,π/2,0]$, leading to more intricate pendulum behaviors.

Selective Training: Explore predictions when the RNN is trained solely using the coordinates of mass 
$m_2$, without insights from mass $m_1$.

