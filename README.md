# Art-Style-Transfert
 Use AI to create master painting from pictures <br>

The goal of this project is training a neural network to generate a painting with the content of a real image and Van Gogh's style.

## Extract the content and the style of the inputs

This AI generate a noise vector with the following characteristics:
- Activations of the content layer of VGG16 is similar for the picture and the random noise (apply picture content)
- Activations of the styles layers of VGG16 are similar for the Grammian matrix (Correlation between pixels raws) of Van Gogh's painting and the noise (apply painting style)

![alt text](https://github.com/nakmuaycoder/Art-Style-Transfert/blob/master/img/vgg16-1-e1542731207177.png)

## Results

### Pont Van Gogh
![alt text](https://github.com/nakmuaycoder/Art-Style-Transfert/blob/master/img/output/coomparisonArles.png)

### Farm in Isan
![alt text](https://github.com/nakmuaycoder/Art-Style-Transfert/blob/master/img/output/res2.png)


### Bangkok Saphan Taksin (สถานีสะพานตากสิน)
![alt text](https://github.com/nakmuaycoder/Art-Style-Transfert/blob/master/img/original/1.jpg)
![alt text](https://github.com/nakmuaycoder/Art-Style-Transfert/blob/master/img/output/generated_transfert_9%2010%203.png)
