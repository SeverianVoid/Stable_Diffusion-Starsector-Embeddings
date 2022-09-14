# Stable Diffusion Starsector Embeddings

A collection of trained textual inversion embedding files for generating various starsector themed art assets using stable diffusion

![ContactSheet-001](https://user-images.githubusercontent.com/5420686/190090520-638abc45-3aa5-4666-af2f-c72f0e7079cc.png)


## Embedding Training Type

Strict embeddings were trained using parameters that push towards results that more closesly match the training data for a greater number of style matching results but sacrifices adaptability in concept

Free embeddings were trained using parameters that allow the network more freedom in adapting prompt concepts but generate more results that dont match the target style

![Portrait Embeddings](https://user-images.githubusercontent.com/5420686/190090991-0595f0d8-b99d-4cb6-bd9a-88fb2cadecca.png)

## Usage instructions

Follow the installation steps for the stable diffusion webui from this repo
https://github.com/AUTOMATIC1111/stable-diffusion-webui

To make use of the pretrained embedding files, create a directory called embeddings (in the same place as webui.py) and put the .pt or .bin embedding files into it. 

![instructions](https://user-images.githubusercontent.com/5420686/190095467-54ea9ed9-2489-4fff-acd2-26fe5420280d.png)

The filename (without .pt/.bin) will be the term you'll use in the prompt to get that embedding. Generally asking for "an image of embedding" or "style of embedding" should be sufficent along with whatever other prompt you want to include.

![instructions2](https://user-images.githubusercontent.com/5420686/190097213-2fc3f795-5542-4e68-9e8a-69163df9437a.png)


