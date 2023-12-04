# BLOOM - Quantized Inference + QLoRA Finetuning on T4

## Inference

| Model          | Notebook                       | Links |
|:---------------|:-------------------------------|:------|
| BLOOM 7B1/4bit | bloom_7b1_4bit_inference.ipynb | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lwieske/bloom-and-qlora/blob/main/bloom_7b1_4bit_inference.ipynb)   [![Open in SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/lwieske/bloom-and-qlora/blob/main/bloom_7b1_4bit_inference.ipynb) |
| BLOOM 3B/4bit  | bloom_3b_4bit_inference.ipynb  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lwieske/bloom-and-qlora/blob/main/bloom_3b_4bit_inference.ipynb)   [![Open in SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/lwieske/bloom-and-qlora/blob/main/bloom_3b_4bit_inference.ipynb) |
| BLOOM 1B7      | bloom_1b7_inference.ipynb      | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lwieske/bloom-and-qlora/blob/main/bloom_1b7_inference.ipynb)   [![Open in SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/lwieske/bloom-and-qlora/blob/main/bloom_1b7_inference.ipynb) |

## Finetuning

| Model          | Dataset | Notebook                                         | Links |
|:---------------|:--------|--------------------------------------------------|:------|
| BLOOM 3B/4bit  | Dolly   | bloom_3b_4bit_qlora_finetuning_with_dolly.ipynb | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lwieske/bloom-and-qlora/blob/main/bloom_3b_4bit_qlora_finetuning_with_dolly.ipynb)   [![Open in SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/lwieske/bloom-and-qlora/blob/main/bloom_3b_4bit_qlora_finetuning_with_dolly.ipynb) |

## Task List

- [ ] Finetuning with Tim Dettmers OASST
- [ ] Finetuning with Nvidia HelpSteer
- [ ] DeepSpeed
- [ ] GPTQ
