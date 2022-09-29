# SimSyn

Generate visually similar synthetic images using image captions as prompts.

[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>
[![Open In Colab][colab-badge]](https://colab.research.google.com/github/hasibzunair/simsyn/blob/main/generate_images.ipynb)

<p align="center">
    <a href="#"><img src="./media/1.png"></a> <br/>
    <em>
    </em>
</p>

### How does it works?

Given an input image, an image captioning model is used to first generate a `text` which describes the image. Next, this `text` is used as a prompt to synthesize `images` using Stable Diffusion. 

### Acknowledgements 
* https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/stable_diffusion.ipynb
* https://huggingface.co/nlpconnect/vit-gpt2-image-captioning 