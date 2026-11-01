# AnatomyLLM

Early LLM work for MediLearn, a VR anatomy tutor for medical students and my graduation project. The project won first place out of 10+ teams for best graduation project.

The notebooks here cover the first stages: benchmarking candidate medical LLMs and early GRPO fine-tuning experiments with Unsloth. They include trial runs, so their numbers are not the final results.

In the final project, Qwen2.5-Aloe-Beta-7B was fine-tuned with GRPO + LoRA. Accuracy went from 61.8% to 78.2% on our medical exam test set and from 62.1% to 71.6% on MedMCQA.

- `AnatomyLLM_Base_Evaluation_5_Model.ipynb`: baseline evaluation of five models
- `AnatomyLLM_Base_Evaluation_1_Model.ipynb`: baseline evaluation of one model
- `Anatomy_LLM_Finetuning.ipynb`: GRPO fine-tuning experiments
