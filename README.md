# TensorFlow Experiments

This repo is all about my TensorFlow experiments that were carried out and executed on my PC, later presented here. These experiments generally derive from tutorials, guides and education videos that are collected from TensorFlow-related sites.

Notebooks starting with `TXX` correspond to tutorials of official TensorFlow website.

I assure you that more stuff will be uploaded in the future.

### Issues

Unfortunately, not all notebooks worked flawlessly, i.e. there were some errors occurred inevitably, despite the workarounds. This might be because of the differences of TensorFlow library versions, incompatible methods, unsuccessful component installations and/or forbidden access to the required dataset. Details are given below:

* **T06:** Target and output could not have the same shape while building the models, thus some parts afterwards are not possible to work.
* **T07:** A model being saved with `SavedModel` could not be done due to being deprecated in later versions of Keras.
* **T10:** The URL for the video dataset causes `403 Forbidden` client error.
* **T11:** The URL for the CSV file causes `403 Forbidden` client error.
* **T14:** There is an `AttributeError` for the Numpy Boolean object, which is not avoidable.
* **T15:** TensorFlow Text could not be installed because there was no compatible version for the latest TensorFlow.
* **T22:** The URL for cats and dogs images causes `403 Forbidden` client error.

If you know how to overcome these issues, please open an `Issue`, so I can redesign the notebooks.
