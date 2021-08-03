# t-SNE Visualisation of CNN Features

t-SNE visualisation of CNN features can help understand how the CNN understands the relationship between different classes which it is trained on. This repository contains minimal code to visualise t-SNE embeddings of the features obtained after average pooling in the ResNet-18 architecture. For visualisation the validation set of [Imagenette](https://github.com/fastai/imagenette) was used.

## Usage
1. The jupyter notebook generates .tsv files containing the features (vis.tsv) and the corresponding labels (metadata.csv)
2. Upload both files to : https://projector.tensorflow.org/
3. Et voila!

![projector](https://user-images.githubusercontent.com/15849927/128094997-e47a28aa-fd8c-4256-8e22-fa260860ab2b.png)


