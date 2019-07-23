# NeuralStyleTransfer
I made DaVinci style image of myself, using style transfer. From Monalisa to me. Da Vinci's es fumato style of brush strokes.

The network learns through a Loss between the Content Loss and the Style Loss.

Its pretty easy, take the VGG19, chop off the FC layers or the Dense Layers

Concatenate your image with the style image and a place holder

Then plug in the loss function as in the paper.
