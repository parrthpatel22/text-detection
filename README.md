# photoRead
A Scene Text Detection Model, that performs OCR in two steps, text detection followed by text recognition. Text Detection is performed by the MobileNetV2 model which was trained via transfer learning on a subset of the COCO dataset suitable for this task. The Text Recognition model is based on CNN followed by Bi-Directional LSTMs trained on MjSynth Dataset.

### Text Detection Dataset
* [Images](http://images.cocodataset.org/zips/train2017.zip)
* [Annotations](http://images.cocodataset.org/annotations/annotations_trainval2017.zip)
* [COCO API](https://github.com/cocodataset/cocoapi)
### Text Recognition Dataset
* [Synthetic Word Dataset](https://thor.robots.ox.ac.uk/~vgg/data/text/mjsynth.tar.gz)
### Language
[Python](https://www.python.org/)

### Tools/ Major Modules
* *Tools* :  [TensorFlow](https://www.tensorflow.org/), [Keras](https://keras.io/), [OpenCV](https://opencv.org/), [Pandas](https://pandas.pydata.org/)
* *Models* : [MobileNetV2](https://keras.io/api/applications/mobilenet/), [CRNN Model](https://wandb.ai/authors/text-recognition-crnn-ctc/reports/Text-Recognition-With-CRNN-CTC-Network--VmlldzoxNTI5NDI)

