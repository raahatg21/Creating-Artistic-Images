# Creating Artistic Images using Neural Style Transfer

  The repository uses **Neural Style Transfer**. It takes as input two images: *content image* (the main input image), and *style image* (the filter). It then creates a third image using high level features (contents) of the content image and lower level features (styles) of the style image. 
  
  The detailed workflow is explained in **style_transfer.ipynb**. An in-depth analysis of the results and comparision with the Prisma app is also shown in **images** folder.
  
## Summary of results:
  
Content | Style | Output
------- | ----- | ------

<img src="https://github.com/raahatg21/Creating-Artistic-Images/blob/master/images/original/original_2.jpg" width="250"> | <img src="https://github.com/raahatg21/Creating-Artistic-Images/blob/master/images/styles/heisenberg.jpg" width="250"> | <img src="https://github.com/raahatg21/Creating-Artistic-Images/blob/master/images/created-by-this/heisenberg_2.jpg" width="250">

<img src="https://github.com/raahatg21/Creating-Artistic-Images/blob/master/images/original/original_1.jpg" width="250"> | <img src="https://github.com/raahatg21/Creating-Artistic-Images/blob/master/images/styles/starry-night.jpg" width="250"> | <img src="https://github.com/raahatg21/Creating-Artistic-Images/blob/master/images/created-by-this/starry-night_1.jpg" width="250">
  
<img src="https://github.com/raahatg21/Creating-Artistic-Images/blob/master/images/original/original_1.jpg" width="250"> | <img src="https://github.com/raahatg21/Creating-Artistic-Images/blob/master/images/styles/mononoke.jpg" width="250"> | <img src="https://github.com/raahatg21/Creating-Artistic-Images/blob/master/images/created-by-this/mononoke_1.jpg" width="250">
  
<img src="https://github.com/raahatg21/Creating-Artistic-Images/blob/master/images/original/original_4.jpg" width="250"> | <img src="https://github.com/raahatg21/Creating-Artistic-Images/blob/master/images/styles/style-6.jpg" width="250"> | <img src="https://github.com/raahatg21/Creating-Artistic-Images/blob/master/images/created-by-this/style-6_4.jpg" width="250">  


## References

- [1] https://arxiv.org/abs/1508.06576
- [2] https://arxiv.org/abs/1603.08155
- [3] Deep Learning with Python by Francois Chollet
  
The files are created in Google Colab, and input and output images are fed through Google Drive. Link is included.
