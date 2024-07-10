# How to unify Keras NLP and Hugging Face

I have been asked by a lot of folks about Open Source Contributions, and a way to start doing it. While most of the
times my answer to them were "hand wavy", today I would like to guide them with something more tangible.

Keras NLP now has an integration with Hugging Face. This means, you can load a model from Hugging Face Hub in
your Keras NLP pipeline. The problem with the integration is that, there needs to be a conversion script
**exclusive** to all the models in KerasNLP.

From the official [announcement](https://huggingface.co/blog/keras-nlp-integration):

> We're thrilled to announce a significant step forward for the NLP
community: Transformers and KerasNLP now have a shared model save format.
This means that models of the transformers library on the Hugging Face Hub
can now also be loaded directly into KerasNLP - immediately making a huge
range of fine-tuned models available to KerasNLP users. Initially, this
integration focuses on enabling the use of Gemma (1 and 2), Llama 3, and PaliGemma
models, with plans to expand compatibility to a wider range of architectures in
the near future.

At the time of writing this, I have contributed the Gemma, Gemma 2, Llama3, and the PaliGemma conversion
scripts. I did not want to keep this knowledge to myself, and figured this would open the gates of
contributions from everyone once shared.

I have made my learning public here in the repository.

All you have to do is go through the interactive notebooks in order and understand how the
integration would work. Once you grasp that, you are good to contribute your own conversion script!

Hope this helps.



I have created this repository for anyone to be able to quickly contribute to Keras NLP
using the integration. You would need to follow the two notebook in order to understand
what happens under the hood of the integration.
