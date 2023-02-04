# PyTorch implementation of multi-class semantic segmentation of high resolution images !

&emsp;● Used UNet with pre-trained ResNet-34 encoder to build a highly generalizable model 

&emsp;● Both evaluation metric and loss function used is Dice loss. Best model - train DL = 0.131, val DL = 0.134

&emsp;● Other things like **autocasting** and **gradient scaling**(for faster computation and improved convergence), **learning rate decay** and **early stopping**(for tackling overfitting), **saving the best model** have been implemented .

&emsp;● Train, validation losses vs epochs have been visualized .

Link to Kaggle dataset - https://www.kaggle.com/competitions/ann-segmentation-m2/data
