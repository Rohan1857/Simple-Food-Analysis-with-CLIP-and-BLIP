# Simple Food Analysis with CLIP and BLIP

## Overview
Scripts to set up the environment, check for GPU, build an image database with CLIP embeddings, and generate captions using BLIP.  

• environment_setup.py: Imports necessary libraries and prints directory contents.  
• check_cuda.py: Checks CUDA availability with PyTorch.  
• database_building_and_analysis.py: Builds a subset of Food-101 images, generates embeddings, and runs similarity searches.  
• extra_visualization.py: Displays images and produces quick captions.

## Setup
1. Place Food-101 at /kaggle/input/food101/food-101.  
2. Run environment_setup.py and check_cuda.py to confirm environment readiness.  
3. Run database_building_and_analysis.py to build and test your local image database.  
4. Run extra_visualization.py to visualize and caption images.

## Requirements
• Python 3  
• NumPy, Pandas, Matplotlib, Pillow  
• PyTorch, Transformers  



## License
Provided as a minimal example for educational or experimental purposes.
