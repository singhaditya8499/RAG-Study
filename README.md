# RAG Notes

## What are LLMs?

LLM is Large language model which is a new AI model that is trained on enormous amount of data. It is able to generate stuff (text, images, videos) based on its learning as part of its training process. When it comes to language, it can predict the next token based on what is being asked and what has already been generated.

The key issues with LLMs are:

1. They are generally outdated when it comes to real time information. If an LLM is trained on the data available till today, it will not be able to answer any question about events happening tomorrow.
2. They are prone to hallucinations (these are patterns that are non existent but machines thinks that they exist).

## Fine tuning


What if we want to have a model that can answer questions about recent events? That is where the term "fine tuning" comes in.

Fine tuning is way of transfer learning where the weights of the existing trained model are trained on the new data. But training the existing model on the new data has its own drawbacks and challenges that are explained below:

1. With fine tuning the performance of the model might degrade as it is trained on the new unseen data.
2. This approach is too costly both moneywise and computationally.
