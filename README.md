---
title: NGC5128 SDXL
emoji: 🫓🥽
colorFrom: blue
colorTo: purple
sdk: gradio
sdk_version: 4.31.5
app_file: app.py
pinned: false
license: creativeml-openrail-m
---

![alt text](assets/SD.png)

🚀Check out the configuration reference at : https://huggingface.co/docs/hub/spaces-config-reference

🚀Huggingface space : https://huggingface.co/spaces/prithivMLmods/NGC5128-StableDiffusion-XL

🚀The GitHub Model Workspace : 
    
    # Make sure you have git-lfs installed (https://git-lfs.com)
    git lfs install
    
    git clone https://huggingface.co/spaces/prithivMLmods/NGC5128-StableDiffusion-XL
    
    # If you want to clone without large files - just their pointers
    
    GIT_LFS_SKIP_SMUDGE=1 git clone https://huggingface.co/spaces/prithivMLmods/NGC5128-StableDiffusion-XL


ℹ️Generated Result in Huggingface Spaces:

## 🔮The Sample Prompt1 Give to the AI Model for Generation :

![alt text](assets/sdxl.png)

## 🔮The Sample Prompt2 Give to the AI Model for Generation :

![alt text](assets/sdxl2.png)

## HD Generated Image Based on the prompt given:
Prompt 1

    Fashion shoot, Jacquemus and moncler collaboration: light pink translucent fur sneakers, hyper-realistic, detailed 8k, realistic.

prompt 2


    a  painting of an eye with purple and orange flowers, in the style of james jean, mysterious jungle, martin ansin, 32k uhd, papua new guinea art, light blue and red, poster --ar 37:61 --stylize 750 --v 6

prompt 3


    (Pirate ship sailing into a bioluminescence sea with a galaxy in the sky), epic, 4k, ultra,


prompt 4


    front view, capture a urban style, Hoodie, technical materials, fabric small point label on text 'Graytheory', the design is minimal, with a raised collar, fabric is a dark grey, low angle to capture the Hoodie's form and detailing, f/5.6 to focus on the hoodie's craftsmanship, solid grey background, studio light setting

## Samples 

| ![Image 1](assets/11.webp) | ![Image 2](assets/12.webp) |
|----------------------------|----------------------------|
| ![Image 3](assets/13.webp) | ![Image 4](assets/14.webp) |



## Requirement.txt / PyPI 

    gradio
    gradio-client

## Use this model with theInference API (serverless)

    import requests
    
    API_URL = "https://api-inference.huggingface.co/models/prithivMLmods/NGC5128-StableDiffusion-XL-v4"
    headers = {"Authorization": "Bearer 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"}
    
    def query(payload):
    	response = requests.post(API_URL, headers=headers, json=payload)
    	return response.content
    image_bytes = query({
    	"inputs": "Astronaut riding a horse",
    })
    # You can access the image with PIL.Image for example
    import io
    from PIL import Image
    image = Image.open(io.BytesIO(image_bytes))

---------------------------------------------------------------

.

.

.

.
