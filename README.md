# Large Language Models (work in progress)

## Table of Contents

1. [Probabilistic Foundation](#probabilistic-foundation)
   - 1.1 [Tightness](#tightness)
   - 1.2 [Finite State Language Models](#finite-state-language-models)
2. [Neural Network Modeling](#neural-network-modeling)
   - 2.1 [Recurrent Neural Language Models](#recurrent-neural-language-models)
   - 2.2 [Transformer-based Language Models](#transformer-based-language-models)
3. [Training and Fine-Tuning](#training-and-fine-tuning)
   - 3.1 [Transfer Learning](#transfer-learning)
   - 3.2 [Parameter Efficient Fine-Tuning](#parameter-efficient-fine-tuning)
4. [Applications](#applications)
   - 4.1 [In-context Learning and Prompting](#in-context-learning-and-prompting)
   - 4.2 [Multimodality](#multimodality)
5. [Security and Harms](#security-and-harms)
   - 5.1 [Harms and Ethics](#harms-and-ethics)
   - 5.2 [Adversarial Examples](#adversarial-examples)
   - 5.3 [Privacy in ML](#privacy-in-ml)
   - 5.4 [Explainability and AI Safety](#explainability-and-ai-safety)

---

## Probabilistic Foundation

Why should we care about the theoretical aspects of Large Language Models (LLMs)? Sure, you could just code a language model to complete some tasks without knowing much about the theory. I could tell you to put some neurons here, some activations there, but can you truly understand the object you've created? If you don't grasp the mathematical foundation, how can you be confident it will work as intended on a large scale? This section is for those who want to go **beyond** just using LLMs and seek to understand them.

### Tightness

In the context of language models, "tightness" refers to the property of not leaking probability mass into the space of infinite strings. Simply put, we don't want a language model to generate tokens indefinitely. A tight language model is one that doesn’t continue generating tokens forever when you sample from it.

### Finite State Language Models

**Concept:**
Finite-state models are simpler than neural network models but lay the groundwork for understanding more complex models.

---

## Neural Network Modeling

### Recurrent Neural Language Models

**Concept:**
Recurrent Neural Networks (RNNs) are fundamental in modeling sequential data. They maintain a memory of previous inputs, which is useful for tasks like language modeling.

### Transformer-based Language Models

**Concept:**
Transformers have revolutionized NLP by addressing the limitations of RNNs. They use attention mechanisms to weigh the importance of different words in a sentence.

---

## Training and Fine-Tuning

### Transfer Learning

**Concept:**
Transfer learning allows models to leverage pre-trained knowledge for specific tasks, reducing the amount of data and time required for training.

### Parameter Efficient Fine-Tuning

**Concept:**
Fine-tuning pre-trained models efficiently is crucial for practical applications. Techniques like LoRA enable efficient fine-tuning.

---

## Applications

### In-context Learning and Prompting

**Concept:**
In-context learning and prompting are powerful techniques for leveraging LLMs. They enable models to perform tasks with minimal task-specific training.

### Multimodality

**Concept:**
Multimodal models combine text with other data types like images, enabling more comprehensive understanding and generation capabilities.

---

## Security and Harms

### Harms and Ethics

**Concept:**
Understanding the ethical implications and potential harms of LLMs is crucial for responsible AI development. Issues like bias and toxicity in training data need careful consideration.

### Adversarial Examples

**Concept:**
Adversarial examples highlight vulnerabilities in LLMs. These are inputs designed to trick models into making mistakes.

### Privacy in ML

**Concept:**
Privacy concerns are paramount in ML, especially with large-scale data. Techniques like differential privacy are essential to ensure user data is protected.

### Explainability and AI Safety

**Concept:**
Explainability and safety are key for trustworthy AI. Understanding how models make decisions helps in improving their reliability and trustworthiness.

---

For the code implementations and practical examples, please refer to the relevant folders in this repository:

- TBD

---

## Improvements and Links

To make the links work and ensure a smoother reading experience, you can format the headers and content in markdown appropriately. Here's a refined version:

### Probabilistic Foundation

[Back to Table of Contents](#table-of-contents)

Why should we care about the theoretical aspects of Large Language Models (LLMs)? Sure, you could just code a language model to complete some tasks without knowing much about the theory. I could tell you to put some neurons here, some activations there, but can you truly understand the object you've created? If you don't grasp the mathematical foundation, how can you be confident it will work as intended on a large scale? This section is for those who want to go **beyond** just using LLMs and seek to understand them.

#### Tightness

[Back to Table of Contents](#table-of-contents)

In the context of language models, "tightness" refers to the property of not leaking probability mass into the space of infinite strings. Simply put, we don't want a language model to generate tokens indefinitely. A tight language model is one that doesn’t continue generating tokens forever when you sample from it.

#### Finite State Language Models

[Back to Table of Contents](#table-of-contents)

**Concept:**
Finite-state models are simpler than neural network models but lay the groundwork for understanding more complex models.

---

### Neural Network Modeling

[Back to Table of Contents](#table-of-contents)

#### Recurrent Neural Language Models

[Back to Table of Contents](#table-of-contents)

**Concept:**
Recurrent Neural Networks (RNNs) are fundamental in modeling sequential data. They maintain a memory of previous inputs, which is useful for tasks like language modeling.

#### Transformer-based Language Models

[Back to Table of Contents](#table-of-contents)

**Concept:**
Transformers have revolutionized NLP by addressing the limitations of RNNs. They use attention mechanisms to weigh the importance of different words in a sentence.

---

### Training and Fine-Tuning

[Back to Table of Contents](#table-of-contents)

#### Transfer Learning

[Back to Table of Contents](#table-of-contents)

**Concept:**
Transfer learning allows models to leverage pre-trained knowledge for specific tasks, reducing the amount of data and time required for training.

#### Parameter Efficient Fine-Tuning

[Back to Table of Contents](#table-of-contents)

**Concept:**
Fine-tuning pre-trained models efficiently is crucial for practical applications. Techniques like LoRA enable efficient fine-tuning.

---

### Applications

[Back to Table of Contents](#table-of-contents)

#### In-context Learning and Prompting

[Back to Table of Contents](#table-of-contents)

**Concept:**
In-context learning and prompting are powerful techniques for leveraging LLMs. They enable models to perform tasks with minimal task-specific training.

#### Multimodality

[Back to Table of Contents](#table-of-contents)

**Concept:**
Multimodal models combine text with other data types like images, enabling more comprehensive understanding and generation capabilities.

---

### Security and Harms

[Back to Table of Contents](#table-of-contents)

#### Harms and Ethics

[Back to Table of Contents](#table-of-contents)

**Concept:**
Understanding the ethical implications and potential harms of LLMs is crucial for responsible AI development. Issues like bias and toxicity in training data need careful consideration.

#### Adversarial Examples

[Back to Table of Contents](#table-of-contents)

**Concept:**
Adversarial examples highlight vulnerabilities in LLMs. These are inputs designed to trick models into making mistakes.

#### Privacy in ML

[Back to Table of Contents](#table-of-contents)

**Concept:**
Privacy concerns are paramount in ML, especially with large-scale data. Techniques like differential privacy are essential to ensure user data is protected.

#### Explainability and AI Safety

[Back to Table of Contents](#table-of-contents)

**Concept:**
Explainability and safety are key for trustworthy AI. Understanding how models make decisions helps in improving their reliability and trustworthiness.

---

For the code implementations and practical examples, please refer to the relevant folders in this repository:

- TBD

