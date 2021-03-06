# Image-Conversion-of-Artistic-Style-Based-on-CNN
## An Implementation of A Neural Algorithm of Artistic Style
## But we improved the algorithm by combine three different images
1. Converted one random photo into an artistic style painting by remaining the content feature of it and extracting texture feature and color feature from other two different pictures.
2. Reconstructed the image by using the first 5 convolution layers in VGG Network.

## Result
### Color Input
![input_color](/input/color_1.png)
### Texture Input
![input_texture](/input/texture.png)
### Content Input
![input_content](/input/content.png)
### Output
![output](/output/res_1.png)

## Libraries
You need to install:
1. numpy
2. Pillow(PIL) 
3. scipy 
4. tensorflow-gpu >= 1.0

## Downloads
You need to download the [VGG net](http://www.vlfeat.org/matconvnet/models/imagenet-vgg-verydeep-19.mat)

## Reference
1. [VGG net](http://www.vlfeat.org/matconvnet/models/imagenet-vgg-verydeep-19.mat)
2. [A Neural Algorithm of Artistic Style](https://arxiv.org/pdf/1508.06576.pdf)
3. [https://github.com/anishathalye/neural-style](https://github.com/anishathalye/neural-style)
