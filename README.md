# SimSyn

Generate visually similar synthetic images using image captions as prompts.

[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>
[![Open In Colab][colab-badge]](https://colab.research.google.com/github/hasibzunair/simsyn/blob/main/generate_images.ipynb)

<p align="center">
    <a href="#"><img src="./media/1.png"></a> <br/>
    <em>
    </em>
</p>

### How does it work?

Given an input image, a `text` is generated which describes the image via Image Captioning. Next, this `text` is used as a prompt to synthesize new `images` (hopefully similar to the input!) via Text-To-Image Generation.

### Todos
* Prompt blending
* Morph between multiple image inputs
* ???

### Acknowledgements 
* https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/stable_diffusion.ipynb
* https://huggingface.co/nlpconnect/vit-gpt2-image-captioning 

### License 
MIT