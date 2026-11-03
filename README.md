# AnatomyLLM

LLM work for MediLearn, a VR anatomy tutor for medical students and my graduation project. The project received ITAC funding from ITIDA and won first place out of 15+ teams for best graduation project.

The notebooks here cover benchmarking candidate medical LLMs and GRPO fine-tuning experiments with Unsloth. They come from the earlier stages of the project, so their numbers differ from the final results.

## Final results

Qwen2.5-Aloe-Beta-7B, fine-tuned with GRPO + LoRA:

| Test | Before | After |
|---|---|---|
| Our medical exam test set | 61.8% | 78.2% |
| MMLU-Med benchmark | 79.5% | 85.1% |
| MedMCQA benchmark | 62.1% | 71.6% |

## Notebooks

- `AnatomyLLM_Base_Evaluation_5_Model.ipynb`: baseline evaluation of five models
- `AnatomyLLM_Base_Evaluation_1_Model.ipynb`: baseline evaluation of one model
- `Anatomy_LLM_Finetuning.ipynb`: GRPO fine-tuning experiments
