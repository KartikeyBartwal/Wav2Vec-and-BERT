---
license: apache-2.0
base_model: distilbert-base-uncased
tags:
- generated_from_trainer
model-index:
- name: results
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# results

This model is a fine-tuned version of [distilbert-base-uncased](https://huggingface.co/distilbert-base-uncased) on an unknown dataset.
It achieves the following results on the evaluation set:
- Loss: 356.9242

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
- train_batch_size: 1
- eval_batch_size: 1
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- lr_scheduler_warmup_steps: 500
- num_epochs: 20

### Training results

| Training Loss | Epoch | Step | Validation Loss |
|:-------------:|:-----:|:----:|:---------------:|
| 1033.4562     | 1.0   | 401  | 1658.2954       |
| 297.1692      | 2.0   | 802  | 841.6623        |
| 264.7683      | 3.0   | 1203 | 892.8900        |
| 381.3767      | 4.0   | 1604 | 835.1779        |
| 194.2236      | 5.0   | 2005 | 901.5334        |
| 180.7703      | 6.0   | 2406 | 552.7529        |
| 35.9909       | 7.0   | 2807 | 352.0545        |
| 184.5064      | 8.0   | 3208 | 356.3049        |
| 151.6956      | 9.0   | 3609 | 452.0968        |
| 58.0247       | 10.0  | 4010 | 390.8174        |
| 41.0552       | 11.0  | 4411 | 473.5340        |
| 19.0339       | 12.0  | 4812 | 472.2711        |
| 31.2277       | 13.0  | 5213 | 396.7701        |
| 38.499        | 14.0  | 5614 | 271.9209        |
| 48.1305       | 15.0  | 6015 | 334.2394        |
| 16.8594       | 16.0  | 6416 | 314.0363        |
| 9.0616        | 17.0  | 6817 | 351.6679        |
| 6.1224        | 18.0  | 7218 | 398.0360        |
| 16.5143       | 19.0  | 7619 | 372.0302        |
| 5.5345        | 20.0  | 8020 | 356.9242        |


### Framework versions

- Transformers 4.41.2
- Pytorch 2.1.2
- Datasets 2.19.2
- Tokenizers 0.19.1
