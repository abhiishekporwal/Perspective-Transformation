# Perspective-Transformation
Transform perspective of a document in an image to Bird-eye view. Can be useful to autoamatically detect corners of document and apply perspective transform to align the image.

I have prepared a Demo file "Perspective_Transform.ipynb" which contains my approach to solve this problem. I had used google colab platform. 

To run the Perspective_Transform.ipynb file. Make sure you are using colab notebook.

    • Run cells of the given file by using shift+enter or ctrl+enter.
    • After loading of model, upload all the images provided in samples_images folder or you can use your own images to input_img. 
      You can upload as many images. This will take sometime.
    • After uploading your images, run all the remaining cells.
Checkout our demo notebook for loading checkpoints
<br>[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1qb04DAcGKpx9DjedmwXtTr3MqG1A33EG?usp=sharing)<br>

# Example:
Successfully detected corner of document and align it to bird-eye view. 
### Input Image:
<img src ='https://raw.githubusercontent.com/abhiishekporwal/Perspective-Transformation/master/sample_images/img.jpg'>

### Output Image:
<img src ='https://raw.githubusercontent.com/abhiishekporwal/Perspective-Transformation/master/output_img/img_warped.png'>

source: https://github.com/khurramjaved96/Recursive-CNNs/tree/server_branch
		https://www.pyimagesearch.com/2014/08/25/4-point-opencv-getperspective-transform-example/