# Text_to_Img_Generation_HuggingFace
A text-to-image generation project using Stable Diffusion with Hugging Face diffusers. Generate stunning images from text prompts with customizable parameters like inference steps, guidance scale, negative prompting, and image size.

Features

Text-to-image generation with Stable Diffusion

Supports multiple prompts per generation

Customizable parameters:

num_inference_steps

guidance_scale

height & width

num_images_per_prompt

negative_prompt for filtering undesired attributes

Visualize generated images with Matplotlib

Tech Stack

Python

diffusers (Hugging Face)

Transformers

PyTorch

Matplotlib

Setup

Clone the repo:

git clone https://github.com/apex-eros/Text_to_Img_Generation_HuggingFace.git
cd Text_to_Img_Generation_HuggingFace


Install dependencies:

pip install -r requirements.txt


Run the notebook:

jupyter notebook Text_to_Img_Generation_HuggingFace.ipynb

Usage

Edit the prompt variable with your text description

Adjust parameters in the params dictionary for custom generation

Call generate_image(pipe, prompt, params) to visualize results
If you want, I can also write a short 2–3 sentence description for the repo that can go in GitHub repo description and LinkedIn posts—this helps attract attention.

Do you want me to do that next?
