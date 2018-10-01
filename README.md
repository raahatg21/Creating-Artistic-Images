# Creating-Artistic-Images

  The repository uses **Neural Style Transfer**. It takes as input two images: *content image* (the main input image), and *style image* (the filter). It then creates a third image using high level features (contents) of the content image and lower level features (styles) of the style image. 
  
  The detailed workflow is explained in **style_transfer.ipynb**. An in-depth analysis of the results and comparision with the Prisma app is also shown in **results** folder.
  
  Summary of results is as follows:
  
  Implementations are made using **Keras**. This example was inspired by section 8.3 of the book **Deep Learning with Python** written by Keras author Francois Chollet. The original paper by Gatys et. al. can be found at https://arxiv.org/abs/1508.06576
  
  The files are created in Google Colab, and input and output images are fed through Google Drive. Link is included.
  
  Comments and Suggestions are welcome :)
  
  Author: Raahat Gupta
  Date: 1/10/18
