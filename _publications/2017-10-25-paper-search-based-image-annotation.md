---
title: "Leveraging deep learning representation for search-based image annotation"
collection: publications
permalink: /publication/2017-10-25-paper-search-based-image-annotation
excerpt: 'This extended abstract paper is about  integrate our feature extractors with 2PKNN (2 pass KNN) approach to obtain relevant tags of an image.'
date: 2017-10-25
venue: 'In 2017 Artificial Intelligence and Signal Processing Conference (AISP)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/8324073'
citation: 'Kashani, M. M., & Amiri, S. H. (2017, October). &quot; Leveraging deep learning representation for search-based image annotation.&quot; <i>In 2017 Artificial Intelligence and Signal Processing Conference (AISP) (pp. 156-161). IEEE</i>.'
---
Image annotation aims to assign some tags to an image such that these tags provide a textual description for the content of image. Search-based methods extract relevant tags for an image based on the tags of nearest neighbor images in the training set. In these methods, similarity of two images is determined based on the distance between feature vectors of the images. Thus, it is essential to extract informative feature vectors from images. In this paper, we propose a framework that utilize deep learning to obtain visual representation of images. We apply different architectures of convolutional neural networks (CNN) to the input image and obtain a single feature vector that is a rich representation for visual content of the image. In this way, we eliminate the usage of multiple feature vectors used in the state-of-the-art annotation methods. We also integrate our feature extractors with a nearest neighbors approach to obtain relevant tags of an image. Our experiments on the standard datasets of image annotation (including Corel5k, ESP Game, IAPR) demonstrate that our approach reaches higher precision, recall and F1 than the state-of-the-art methods such as 2PKNN, TagProp, NMF-KNN and etc.