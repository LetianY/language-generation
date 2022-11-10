# language-generation

This is a NLP project for language generation. Research paper summary and possible implementation will be recorded.

## Concepts Integration

### Zero-shot learning

xxxxxx

## Paper Reading

### ERNIE 3.0:  LARGE-SCALE KNOWLEDGE ENHANCED PRE-TRAINING FOR LANGUAGE UNDERSTANDING AND GENERATION

- Introduction
This paper proposes a model for pre-training large-scale knowledge enhanced models. Though previous work such as T5 and 
GPT-3 achieves good generalization abilities using scaled pre-trained models, they did not introduce linguistic related
knowledge while training. Besides, the auto-regressively trained models may fail for downstream language understanding 
tasks.

What presented in this paper is a unified framework that fuses both auto-regressive and auto-encoding networks, so that
it can be easily tailored for both language understanding and generation tasks with zero-shot learning, few-shot learning
or fine-tuning.