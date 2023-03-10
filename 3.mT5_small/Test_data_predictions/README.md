---
language:
- en
- hi
tags:
- generated_from_trainer
model-index:
- name: cmt_translation_output
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# cmt_translation_output

This model is a fine-tuned version of [best_checkpoint/](https://huggingface.co/best_checkpoint/) on an unknown dataset.
It achieves the following results on the evaluation set:
- eval_loss: 1.8673
- eval_bleu: 13.0
- eval_gen_len: 22.6868
- eval_runtime: 97.2754
- eval_samples_per_second: 9.684
- eval_steps_per_second: 0.812
- step: 0

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 5e-05
- train_batch_size: 12
- eval_batch_size: 12
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 25.0

### Framework versions

- Transformers 4.24.0
- Pytorch 1.13.0+cu117
- Datasets 2.6.1
- Tokenizers 0.13.2
