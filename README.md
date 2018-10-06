![title](title.jpg)

# Small Book Image Dataset

This is a dataset of book images, but number of samples are quite small.

This is created for following blog posts.

- 日本語の記事 [Qiita '小さなデータセットで良い分類機を学習させるとき'](https://qiita.com/daisukelab/items/381099590f22e4f9ab1f)
- English blog post [medium 'Train A Strong Classifier with Small Dataset, From Scratch? ImageNet Weights? Or AutoML? — Part 1'](https://medium.com/@nizumical/train-a-strong-classifier-with-small-dataset-from-scratch-imagenet-weights-or-automl-part-1-6b6d375fc680)

## Jupyter Notebooks

- [Small Dataset -Train With Augmentation.ipynb](Small Dataset -Train With Augmentation.ipynb) - You can simply run this only. This has the best model.
- [Small Dataset -Ttrain Without Augmentation.ipynb](Small Dataset -Train Without Augmentation.ipynb) - What if we don't use augmentation? Check this.
- [Small Dataset -Train With fast.ai library - successful.ipynb](Small Dataset -Train With fast.ai library - successful.ipynb) - What if we use fast.ai library to train this dataset.
- [Dataset examples.ipynb](Dataset examples.ipynb) - For making dataset examples. You won't need this.

### How to run the notebooks

1. Run `download.sh` to get externally dependent python codes.
2. Run Jupyter notebooks.

## Sample visualizations

Result from [Small Dataset -Train With Augmentation.ipynb](Small Dataset -Train With Augmentation.ipynb):

![sample_keras.jpg](sample_keras.jpg)

Result from [Small Dataset -Train With fast.ai library - successful.ipynb](Small Dataset -Train With fast.ai library - successful.ipynb):

![sample_fastai.jpg](sample_fastai.jpg)

- - -

### Thanks to

- [yu4u/mixup-generator](https://github.com/yu4u/mixup-generator) - mixup implementation for Keras.
