# Implementation-of-Neural-Style-Transfer-in-Keras

Neural Style Transfer (NST) is an optimization technique used to take two images - a content image and a style reference image and blend them together so the output image looks like the content image, but painted in the style of the style reference image.

Here, a pretrained VGG19 model is used to perform style transfer using the Keras framework. The style transfer is achieved through the optimization of a loss function that has 3 components - style loss, content loss and total variation loss.

&nbsp;

An example of Taj Mahal painted in the style of Van Gogh’s Starry Night.

![style_transfer_gif](https://user-images.githubusercontent.com/76877184/103671073-6c950800-4fa0-11eb-91a8-13864826974c.gif)
