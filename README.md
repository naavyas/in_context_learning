# in_context_learning
Exploring the flan-t5 model using prompt engineering

In this use case, we will be generating a summary of a dialogue with the pre-trained Large Language Model (LLM) FLAN-T5 from Hugging Face. The list of available models in the Hugging Face transformers package can be found here.

We upload some simple dialogues from the DialogSum Hugging Face dataset. This dataset contains 10,000+ dialogues with the corresponding manually labeled summaries and topics.

Then using the zero - shot, one - shot, and few - shot methods we explore the data set as well the ability of the model to summerize and better its responses using prompt engineering. 

We also explore the changes in the model's responses upn changing the generative configuration parameters. Through the notebook the main parameter that we have been setting was max_new_tokens=50, which defines the maximum number of tokens to generate. A full list of available parameters can be found in the Hugging Face Generation documentation.
We also explore how changes in temperature as well as using the top k and top p technique brings about changes in the output. 




