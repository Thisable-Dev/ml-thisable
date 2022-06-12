# Machine Learning - Thisable

## 1. Currency Detection
[Currency Dataset](https://www.kaggle.com/datasets/najmaaaaaaaaa/currencyhp)

Using 9,100 primary images [data](https://www.kaggle.com/datasets/najmaaaaaaaaa/currencyhp) of Indonesian currency with 7 labels, we do transfer learning using the MobileNet V2 model and got a validation accuracy of **91%**. We use the MobileNet V2 model because it is a light weight model, has high accuracy, and trains quickly.

MobileNet-v2 is a convolutional neural network that has 53 layers deep. We use the pretrained version of the network trained on more than a million images from the [ImageNet](https://www.image-net.org/) database. As a result, the network has learned rich feature representations for a wide range of images. The network has an image input size of 224-by-224.
We adjust the network model and the input size so that it fits with the data we have.


![currency](https://user-images.githubusercontent.com/76579538/173192217-87d0bf4a-05eb-4aa2-8890-d92b00f89b85.png)


## 2. Object Detection
[Object Detection Dataset](https://www.kaggle.com/datasets/jfachrel/object-detection-thisabel)

We used an open-source dataset that consists of 7 classes. [person](https://www.kaggle.com/datasets/laurentmih/aisegmentcom-matting-human-datasets), [car](https://ai.stanford.edu/~jkrause/cars/car_dataset.html), [cat](https://www.kaggle.com/c/dogs-vs-cats), [dog](https://www.kaggle.com/c/dogs-vs-cats), [flower](http://www.image-net.org), [fruit](https://www.kaggle.com/moltean/fruits), and [motorbike](http://host.robots.ox.ac.uk/pascal/VOC). Each class contains about 1000 datasets.

The dataset was trained by using the MobilenetV2 transfer learning model. For the base model, we loaded pre-trained weights from imagenet dataset and froze the first 150 layers and unfroze the rest, so the state of a frozen layer won't be updated during training. The results obtained from the validation accuracy reached 98%. As a result, we obtained the validation accuracy of **98%**.

![Object Detection](https://user-images.githubusercontent.com/44915001/173232407-cdae40d2-9884-4837-b0b0-ce517f0f9d8b.png)

## 3. Sign Language Detection
[Sign Language Dataset](https://www.kaggle.com/datasets/najmaaaaaaaaa/data-augment)

The data we use are pictures of half-bodied humans with plain backgrounds demonstrating BISINDO sign language. Using 16,800 primary images [data](https://www.kaggle.com/datasets/najmaaaaaaaaa/data-augment) with 3 labels, we do transfer learning using the MobileNet V2 model and got a validation accuracy of **90%**.

We adjust the network model and the input size so that it fits with the data we have.

![signlanguage](https://user-images.githubusercontent.com/76579538/173191442-1e2681c7-ba02-41a7-bc7c-e8cc201bb049.png)


## Architecture of SSD MobileNet V2

![image](https://user-images.githubusercontent.com/76579538/173220485-6999cc1d-d9cf-4ec5-8558-91e873dd2b81.png)
