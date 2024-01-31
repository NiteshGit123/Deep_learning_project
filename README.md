# deep learning project
This is my deep learning project

The motive of the project is to perform action recognition on the UCF101 dataset

1.  Given the video and their classes,I exploited various deep learning techniques such as RNN, CNN to perform the task
2.  I extraced the frames from each video during training , then for each frame ,I extracted rich feature using a pretrained model such as VGG16 and ResNet50 which are already trained on large image dataset(ImageNet).Then this ordered sequence of image features is passed to either RNNs to also extarcted spatial and sequential features so that we can classify the action being performed in the given video
3.  For Train-Test split, I have used the split already provided on the UCF website
