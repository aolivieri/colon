# CNN for Colorectal Cancer detection

Colorectal Cancer Classification using Deep Convolutional Networks

In this work I am exploring two different appraoaches:

1. Histological samples.

This is an experiment trying to explore the work described in the paper Colorectal Cancer Classification using Deep Convolutional Networks [https://www.scitepress.org/Papers/2018/66431/66431.pdf]. This seems to be more important to histopathology professionals, rather than colonoscopists or coloproctologists.



DISCLAIMER: Note that this work does not reproduce the papers literally and it doesn't not have any intention to the productized by any health professional neither be utilized by medical equipment manufacturers.

## Getting Started



### Prerequisites

The notebook was executed using TensorFlow 2.2

Datasets are (so far) available in this git repository. However, if for some reason they are done, they can be retrieved in these repositories:

1. Histological samples: https://github.com/tampapath/lung_colon_image_set

2. Gastrointestinal (GI) tract (colonoscopy): https://datasets.simula.no/kvasir/ 

### Contents

colon_histological.h5: a model trained with the proposed CNN in 10 epochs (for front#1)

colon_histological.ipynb: the notebook exploring front #1
colon_colonoscopy.ipynb: the notebook exploring from #2

/colon_image_sets: the dataset for front #1
/Kvasir: the dataset for front #2

## Author

* **Alexandre Olivieri** - *Initial work* - (https://github.com/aolivieri)

## License

NA

## Acknowledgments

* Carlos Padilha, who helped with the transfer learning piece of it.
