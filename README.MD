# Discrete Events Simulation - Queuing Theory

## Overview

This code aims to derive valuable insights into statistics, such as the mean time
spent in the queue, mean response time, mean utilization of services, and the 
distribution of requests within the queue. This is done by doing the following 
things:

- We wrote a DES program to verify that the average waiting times are shorter for an
M/M/n queue and a system load ρ and processor capacity µ than for a single M/M/1 queue
with the same load characteristics.

- Comparing the First In First Out M/M/1 result to that for an M/M/1 queue with 
shortest job first scheduling, where we always give priority to the smallest jobs.

- Experimenting with different service rate distributions. On the one hand we tried the
M/D/1 and M/D/n queues, on the other hand we tried a long-tail distribution. 
For the latter we used a distribution where 75% of the jobs have an exponential distribution
with an average service time of 1.0 and the remaining 25% an exponential distribution
with an average service time of 5.0 (an example of a hyperexponential distribution).

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)

## Installation

```bash
git clone https://github.com/koenweverink/stochastic_simulation_assignment_2.git
cd stochastic_simulation_assignment_1
pip install -r requirements.txt
```

## Usage

- Open DES_queue.ipynb
- Select a Python interpreter
- Press run all 