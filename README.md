# MMM Mutopia Guitar

Tutorial to train a GPT-2 model from scratch using Hugingg Face and publishing it as a Gradio demo using Spaces. The model generates guitar music. For encoding the guitar MIDI files of the Mutopia Project, I am using the excellent [implementation](https://github.com/AI-Guru/MMM-JSB) of Dr. Tristan Beheren of the paper: [MMM: Exploring Conditional Multi-Track Music Generation with the Transformer](https://arxiv.org/abs/2008.06048). 

By the end of this tutorial, you should have a Gradio demo similar to this one.

To start the tutorial, please visit the first notebook: 1. Collecting the data.

The dataset is built from the [Mutopia Project](https://www.mutopiaproject.org/). 

This tutorial is a work in progress. You can take a look at Hugging Face at the following:
 *  [Dataset](https://huggingface.co/datasets/juancopi81/mutopia_guitar_dataset)
 *  [Tokenizer](https://huggingface.co/juancopi81/mutopia_guitar_dataset_tokenizer)
 *  [Model](https://huggingface.co/juancopi81/mutopia_guitar_mmm)
 
After generating the music in the Hugging Face widget, you can listen to the results using [this notebook](https://colab.research.google.com/drive/14vlJwCvDmNH6SFfVuYY0Y18qTbaHEJCY?usp=sharing).