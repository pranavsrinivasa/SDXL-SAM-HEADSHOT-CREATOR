# SDXL-SAM-HEADSHOT-CREATOR
This project combines the power of Segment Anything Model by facebook and the power of inpainting in Stable diffusion V2 to create professional headshots for free 

# Overview:

SDXL-SAM-HEADSHOT-CREATOR seamlessly integrates Facebook's Segment Anything Model (SAM) and Stable Diffusion V2's inpainting to produce professional headshots at no cost. The project ensures precise subject segmentation and employs advanced inpainting techniques for polished results.

# Features:

-SAM Segmentation: Leverages Facebook's SAM for accurate and efficient subject segmentation in images.

-Stable Diffusion V2 Inpainting: Utilizes Stable Diffusion V2 for high-quality inpainting, ensuring natural and realistic headshots.

-Professional Results: Merges segmentation and inpainting to generate refined and professional-looking headshots.

# Usage: 
- Upload a square size image
- Click on the invert mask button(to select everything else)
- Repeatedly click on the desired masks.
- White represents the places which will replaced by SDXL generation
- Click on the masks untill all the unwanted pixels are white
- After perfect segementation click once more
- Enter the desired prompt (Prompt by default starts with "Realistic professinal Headshot of a man for a profile pic")
- Finally submit and enjoy the results

Acknowledgments: SAM by [Facebook](https://github.com/facebookresearch/segment-anything), Stable Diffusion-V2-Inpaint by https://huggingface.co/stabilityai/stable-diffusion-2-inpainting 
