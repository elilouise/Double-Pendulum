# Double Pendulum Prediction

This project uses machine learning to guess the movement of a two-part pendulum system using limited data. The goal is to predict its unpredictable swings.

![pendulum01-1837416705](https://github.com/elilouise/Double-Pendulum/assets/53550369/2c137b3b-1945-445d-b17e-facc51e89c6b)

## Features

Design and Training of RNN: Utilize a Recurrent Neural Network to forecast the future positions of masses 
$m_1$ and $m_2$ based on their cartesian coordinates, using the initial conditions 
$z_0 = [π/4,0,π/4,0] $

Stability Analysis: Investigate how initial condition variations influence the RNN's performance.

Prediction Extent: Assess the network's capability to predict long-term future positions.

Complex Path Prediction: Implement the above steps but with a different set of initial conditions, 
$z_0= [π/2,0,π/2,0]$, leading to more intricate pendulum behaviors.

Selective Training: Explore predictions when the RNN is trained solely using the coordinates of mass 
$m_2$, without insights from mass $m_1$.

