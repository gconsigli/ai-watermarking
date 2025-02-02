# Recreating SynthID: Watermarking AI-generated Content (Images and Text)

## Inspiration

AI has been accelerating the spread of misinformation and disinformation online, and it’s been harder to tell AI-generated and human-generated text apart. Roughly 57% of AI-generated content on the internet is most likely AI-generated. At the same time, tons of photorealistic AI-generated images have been fooling the internet despite algorithms designed to demote and remove AI-generated content.

Recently, Google unveiled SynthID: an algorithm that inserts digital watermarks in AI-generated content, including images, videos, text, and audio. These watermarks can be used to track AI-generated content circulating the internet. For my second replicate at The Knowledge Society, I recreated SynthID's basic function for watermarking images and text. Feel free to use this code in any AI-watermarking projects as long as you follow the Apache 2.0 license. 

**DISCLAIMER: Please note that this project replicates the way that SynthID watermarks and detects AI-generated text on a smaller scale, and does not have the full functionality of SynthID.**

Read more on Medium about this project and how watermarking works: https://medium.com/@consigli/ai-vs-reality-whats-real-watermarking-1c1d2277d2db

## Currently this repository consists of code for:

* An image watermarking system (Jupyter Notebook Python file)
* A text watermarking system (coming soon)

## Requirements:

The Jupyter Notebooks in this repository can be used in Google Colab or locally. If you are interested in running this locally, make sure to install the latest version of (python.org/downloads)[Python] that is (PyTorch)[compatible with PyTorch](https://pytorch.org/get-started/locally/) and the necessary libraries:

```
pip install torch transformers pillow diffusers
```

## Acknowledgments

I wanted to give a special thanks to @sdathath and Pushmeet Kohli who helped me better understand how SynthID works as I continue exploring it for my focus on Artificial Intelligence at The Knowledge Society!
