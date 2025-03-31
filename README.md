## Toy Examples

This repository is a collection of Machine Learning tasks as toy examples. The purpose of this repository is to impart programming and machine learning knowledge in the form of short assignments. Tasks can range from beginner to moderate difficulty and do not require constructing large codebases. However, tasks require prior knowledge of machine learning and reinforcement learning systems along with their usage in running experiments.

## Guidelines and Honor Code

Each task is designed to be completed on a single GPU / TPU. While the training part does not take long, code implementation and debugging can take anywhere from 2 days to 2 weeks. Note that if you are beginner, it might take longer than 2 weeks to arrive at a few solutions. While there are no strict protocols on how the tasks should be completed, it is essential that learners complete the task independently, ie- without AI assistance.

## Tasks

Note that the personal completion time varies for each learner depending on time availability and learning speed. Learners with prior experience in machine learning and programming could take 2 days to 2 weeks to finish a task. Beginners would take longer.

|S.No|Task|Solution|Personal Completion Time|
|:--:|:--:|:------:|:----------------------:|
|1|Implement and train a shallow transformer model to generate random numbers between 0 and 100. Generate a new sequence using the model and visualize the learned distribution of random numbers. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`rand_transformer.ipynb`](./rand_transfomer.ipynb)|2 days|
|2|Implement and train a PPO agent to generate shakespeare pros using a small vocabulary of text. The pros need not be accurate as long as the agent can form meaningful sentences similar to poems. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`shakespeare_ppo.ipynb`](./shakespeare_ppo.ipynb)|-|
|3|Implement the chain of thought reasoning procedure in your random number generator transformer of task 1. Compare the performance by ablating between the reasoning mechanism. Visualize how the distribution of numbers changes when reasoning procedure is added to the model. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`cot.ipynb`](./cot.ipynb)|-|
|4|Implement flow matching on the two moons toy dataset. Visualize the learned distribution and movement of vector field during the sampling process. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`flow_matching.ipynb`](./flow_matching.ipynb)|-|
|5|Implement the hierarchical DQN algorithm in JAX. Test your implementation on the toy MDP proposed in the paper. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`hdqn.ipynb`](./hdqn.ipynb)|-|
|6|Implement a toy diffusion model to generate samples from the two moons dataset. The algorithm should make use of a small feedforward network and a small diffusion schedule. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`diffusion.ipynb`](./diffusion.ipynb)|-|


