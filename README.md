# LLaVA Lifelong Unlearning
This codebase is developed based on the LLaVA source code. 
To use it, please install all the environment dependencies required by LLaVA.

# Benchmark
The QA pairs are in the folder of tasks.
The full MLUbench is available at https://1drv.ms/f/c/419e3e9d51ec307d/Ej7v9Yo_Q6BOsb5z2nzy1w8BMIvrEZUZG0fYg7DM2p-8ig 

# Unlearning
The code for baseline unlearning is in unlearning_auto.py.

# Eval
The code for model evaluation (get model response) is in eval_unlearned_model.py.

# Metrics
The code for automatic evaluation of model responses is in metrics.py.

# Gate Module
The code for automatic entity extraction of GLM and task match is in entity_extract.py.

# LUMoE
The code for the LUMoE method is in LUMoE.py.



