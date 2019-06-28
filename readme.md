# Experiments and examples

A bunch of different code notebooks of experiments and explorations. Should be `python3` with a big number of TensorFlow ones

## Experiments

- Loading TIFF images with TensorFlow - [link](TF2/tf2_tiff_images_dataset_pipeline.ipynb)
    * Example of custom function to load image with PIL
    * using [tensorflow_io](https://github.com/tensorflow/io) to load image with `TIFFDataset`

- TFHub activity recognition from mp4 video.
In the example, the video of Olympic Weightlifting activity is used, a squat clean to be more precise - [link](Working_with_Video_and_tfhub_activity_recognition.ipynb)
    * TFhub activity recognition - unfrotunately only TF1.x
    * `tensorflow_io` and `VideoDataset`

![alt text](images/oly-clean.gif "Oly Squat CLean")