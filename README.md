# Data augmentation for intent prediction
In intent detection, user needs to define some examples (phrases) of intent that he wants to be detected.

The NLP model needs as many as possible examples to be able to predict correct intents.

Nevertheless, it happens that user provides small intents with very few examples or even just one message; because of the lack of ideas on intent's phrases, the time constraints, etc..

In such cases, it is important to be able to automatically collect more data for small intents before making classification.

This notebook studies how to improve the intent detection performance using data augmentation techniques.

Three methodes to enrich the training data will be explored, including:

* Oversampling intent
* Back translation
* Paraphrase generation
