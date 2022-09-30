# SimSyn - Generate similar but synthetic images

Generate visually similar synthetic images using image captions as prompts to an image generation model.

[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>
[![Open In Colab][colab-badge]](https://colab.research.google.com/github/hasibzunair/simsyn/blob/main/generate_images.ipynb)

<p align="center">
    <a href="#"><img src="./media/1.png"></a> <br/>
    <a href="#"><img src="./media/2.png"></a> <br/>
    <em>
    </em>
</p>

### Why though?

Some possible use-cases are: 

1. Generate synthetic images/datasets of objects or concepts that are not known (i.e. don't know the prompt) 
2. Could be a form of art therapy, you give the image as an artist, get to see more images of the same kind 

### How does it work?

Given an input image, a `text` is generated which describes the image using an Image-To-Text model. Next, this `text` is used as a prompt to synthesize new `images` (hopefully similar to the input!) by using a Text-To-Image generative model. See flow chart below.

```mermaid
flowchart TD
    A(Input Image) --> B[Image-To-Text Model];
    B -->|text as prompt| C[Text-To-Image Model]; 
    C --> D(Synthetic Image);
```

<!--- Flowchart made using https://github.com/mermaid-js/mermaid#examples -->


### Todos
* Prompt blending
* Morph between multiple image inputs
* Some other cool stuff

### Acknowledgements 
* https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/stable_diffusion.ipynb
* https://huggingface.co/nlpconnect/vit-gpt2-image-captioning 

### License 
Whatever licenses the pretrained models have.
