# TensorFlow Experiments

This repo is all about my TensorFlow experiments that were carried out and executed on my PC, later uploaded here. These experiments generally derive from tutorials, guides and education videos that are collected from TensorFlow-related sites.

* Notebooks starting with `TXX` correspond to tutorials from official TensorFlow website.
* Notebooks starting with `GXX` correspond to guides from official TensorFlow website.

## Problems

Unfortunately, not all notebooks worked flawlessly, i.e. there were some inevitable errors occurred, despite the workarounds. This might be because of the differences of TensorFlow library versions, incompatible methods, unsuccessful component installations and/or forbidden access to the required datasets. Specific details are given below:

* **T06:** Target and output could not have the same shape while building the models, thus some parts afterwards are not possible to work.
* **T07:** A model being saved with `SavedModel` could not be done due to being deprecated in later versions of Keras.
* **T10:** The URL for the video dataset causes `403 Forbidden` client error.
* **T11:** The URL for the CSV file causes `403 Forbidden` client error.
* **T14:** There is an `AttributeError` for the Numpy Boolean object, which is not avoidable.
* **T15:** TensorFlow Text could not be installed because there was no compatible version for the latest TensorFlow.
* **T22:** The URL for cats and dogs images causes `403 Forbidden` client error.
* **G11:** Several `NameError` and `AttributeError` occurred although codes were written correctly.
* **G13:** 3 out of 4 code blocks cause exceptions.
* **G16:** This error occurs twice: `SparseCategoricalAccuracy` object has no attribute `reset_states`.
* **G17:** Errors encountered in the last two cells, because of inconsistent input shapes.
* **G20:** Several code blocks cannot be executed, due to an error that relates to not finding a required image file (different OS).
* **G23:** A few errors occurred that correspond to `_UserObject`.
* **G30:** The last two cells cannot be executed because of having no attribute `get_cmap` for `matplotlib.cm`.
* **G32:** This error occures twice: `_UserObject` object has no attribute `trainable_variables`.

If you know how to overcome these issues, please open an `Issue`, so I can redesign the notebooks appropriately.
