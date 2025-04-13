## Toy Examples

This repository is a collection of Machine Learning tasks as toy examples. The purpose of this repository is to impart programming and machine learning knowledge in the form of short assignments. Tasks can range from beginner to moderate difficulty and do not require constructing large codebases. However, tasks require prior knowledge of machine learning and reinforcement learning systems along with their usage in running experiments.

## Guidelines and Honor Code

Each task is designed to be completed on a single GPU / TPU. While the training part does not take long, code implementation and debugging can take anywhere from 2 days to 2 weeks. Note that if you are beginner, it might take longer than 2 weeks to arrive at a few solutions. While there are no strict protocols on how the tasks should be completed, it is essential that learners complete the task independently, ie- without AI assistance.

## Tasks

Note that the personal completion time varies for each learner depending on time availability and learning speed. Learners with prior experience in machine learning and programming could take 2 days to 2 weeks to finish a task. Beginners would take longer.

|S.No|Task|Solution|Personal Completion Time|
|:--:|:--:|:------:|:----------------------:|
|1|Implement and train a shallow transformer model to generate random numbers between 0 and 100. Generate a new sequence using the model and visualize the learned distribution of random numbers. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`rand_transformer.ipynb`](./rand_transfomer.ipynb)|2 days|
|2|Implement and train a PPO agent to generate shakespeare pros using a small vocabulary of text. The pros need not be accurate as long as the agent can form meaningful sentences similar to poems. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`shakespeare_ppo.ipynb`](./shakespeare_ppo.ipynb)|3 days|
|3|Implement the chain of thought reasoning procedure in your random number generator transformer of task 1. Compare the performance by ablating between the reasoning mechanism. Visualize how the distribution of numbers changes when reasoning procedure is added to the model. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`cot.ipynb`](./cot.ipynb)|1 day|
|4|Implement flow matching on the two moons toy dataset. Visualize the learned distribution and movement of vector field during the sampling process. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`flow_matching.ipynb`](./flow_matching.ipynb)|3 days|
|5|Implement the hierarchical DQN algorithm in JAX. Test your implementation on the toy MDP proposed in the paper. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`hdqn.ipynb`](./hdqn.ipynb)|4 days|
|6|Implement a toy diffusion model to generate samples from the two moons dataset. The algorithm should make use of a small feedforward network and a small diffusion schedule. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`diffusion.ipynb`](./diffusion.ipynb)|-|
|7|Implement a finetuning pipeline for the Llama 3 model using a corpus of shakespeare's poems. Force the model to generate new pros in shakespeare's tone. Evaluate the quality and similarity of pros compared to the finetuning dataset. Your implementation should be written in PyTorch and submitted as a single `.py` or `.ipynb` file.|[`llama3_sft.ipynb`](./llama3_sft.ipynb)|-|
|8|Implement beam search in PyTorch. Use a beam width of 10 to sample examples from given set of contexts. Your implementation should be written in PyTorch and submitted as a single `.py` or `.ipynb` file.|[`beam_search.ipynb`](./beam_search.ipynb)|-|
|9|Implement all the components of a decoder-only transformer and overfit the model to reverse a sequence of random tokens. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`reverse_digits.ipynb`](./reverse_digits.ipynb)|-|
|10|Implement your own study of scaling laws on a CNN trained for digit classification on MNIST. Vary the model size and dataset in powers of 2 (1, 1/2, 1/4, etc.) and visualize the variation of validation loss against these values. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`scaling_laws.ipynb`](./scaling_laws.ipynb)|-|
|11|Implement SGD and Adam by hand and compare their optimization performance to the ones provided in a library such as `optax`. Performance should be comparable for a CNN trained on MNIST. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`optimization.ipynb`](./optimization.ipynb)|-|
|12|Implement the deep dream training scheme on a small CNN model trained to classify MNIST digits. Try to understand the outputs of the experiment and explain how the model is able to understand and recognize digits. Your explanation should be submitted as a report which should be a part of your script. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`interpret.ipynb`](./interpret.ipynb)|-|
|13|Red team with a GPT-2 model to find and mark inputs where it generates offensive language and biased outputs. Flag these outputs as toxic/non-toxic using an auxilary toxicity detection model such as Unitary's bERT-based model. Your implementation should be written in PyTorch and huggingface transformers and submitted as a single `.py` or `.ipynb` file.|[`red_team.ipynb`](./red_team.ipynb)|-|
|14|Implement the Bootstrapped Meta-Learning algorithm. Evaluate your implementation on a toy Reinforcement Learning task utilizing the A2C model. Your implementation should be written in JAX and submitted as a single `.py` or `.ipynb` file.|[`bmg.ipynb`](./bmg.ipynb)|-|


