# CNN for Colorectal Cancer detection

Colorectal Cancer Classification using Deep Convolutional Networks

In this work I am exploring the usage of artificial intelligence (in particular machine learning (in particular deep learning)) to assist in colon cancer detection. This type of cancer is the 2nd cause of deaths by cancer worldwide (862.000 deaths in 2018 - https://www.who.int/news-room/fact-sheets/detail/cancer). The second reason is that my wife is a coloproctologist and colonoscopist, so I feel the pain too.

I am then looking into two different approaches:

**1. Histological samples**

This is an experiment trying to explore the work described in the paper Colorectal Cancer Classification using Deep Convolutional Networks [https://www.scitepress.org/Papers/2018/66431/66431.pdf]. 

This seems to be more important to histopathology professionals, rather than colonoscopists or coloproctologists.

**2. Colonoscopy samples**

This seems to be of true value for colonoscopists if it is intergated into the current equipment used by them, i.e., if the machine can help the detection in real time, while the exam is on-going. The post-processing help is questionable, since the procedures try to cover as much as possible during the exam.

Anyway, there is a dataset with 8000 labeled images (Ksavir) available, so it enables further researches and experiments in this space. This is what I am trying to explore with this front #2.

DISCLAIMER: This work does not reproduce the papers literally and it doesn't not have any intention to the productized by any health professional neither be utilized by medical equipment manufacturers.

## Getting Started

I have tried to keep everything self containted in the notebook. So it should be ready to go.

### Prerequisites

The notebooka were executed using TensorFlow 2.2

Datasets are (so far) available in this git repository. However, if for some reason they are done, they can be retrieved in these repositories:

1. Histological samples: https://github.com/tampapath/lung_colon_image_set

2. Gastrointestinal (GI) tract (colonoscopy): https://datasets.simula.no/kvasir/ 

### Contents

colon_histological.h5: a model trained with the proposed CNN in 10 epochs (for front#1)
colon_colonoscopy.h5: a model trained with the proposed CNN in 10 epochs (for front#2)

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
