# Machine Learning - Thisable

## 1. Currency Detection
[Currency Dataset](https://www.kaggle.com/datasets/najmaaaaaaaaa/currencyhp)

Using 9,100 primary images [data](https://www.kaggle.com/datasets/najmaaaaaaaaa/currencyhp) of Indonesian currency with 7 labels, we do transfer learning using the MobileNet V2 model and got a validation accuracy of **91%**. We use the MobileNet V2 model because it is a light weight model, has high accuracy, and trains quickly.

MobileNet-v2 is a convolutional neural network that has 53 layers deep. We use the pretrained version of the network trained on more than a million images from the [ImageNet](https://www.image-net.org/) database. As a result, the network has learned rich feature representations for a wide range of images. The network has an image input size of 224-by-224.
We adjust the network model and the input size so that it fits with the data we have.


![currency](https://user-images.githubusercontent.com/76579538/173192217-87d0bf4a-05eb-4aa2-8890-d92b00f89b85.png)


## 2. Object Detection
[Object Detection Dataset](https://www.kaggle.com/datasets/jfachrel/object-detection-thisabel)

## 3. Sign Language Detection
[Sign Language Dataset](https://www.kaggle.com/datasets/najmaaaaaaaaa/data-augment)

The data we use are pictures of half-bodied humans with plain backgrounds demonstrating BISINDO sign language. Using 16,800 primary images [data](https://www.kaggle.com/datasets/najmaaaaaaaaa/data-augment) with 3 labels, we do transfer learning using the MobileNet V2 model and got a validation accuracy of **90%**.

We adjust the network model and the input size so that it fits with the data we have.

![signlanguage](https://user-images.githubusercontent.com/76579538/173191442-1e2681c7-ba02-41a7-bc7c-e8cc201bb049.png)
