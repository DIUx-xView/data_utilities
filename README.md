## xView Data Utilities

This repository contains data processing scripts for the xView dataset.  The script 'process_wv.py' is runnable and processes a folder containing xView imagery along with a groundtruth geojson file to create a TFRecord containing shuffled, chipped, and augmented xView patches in JPEG format.  We provide several augmentation functions in 'aug_util.py' for rotating and shifting images and bounding boxes, as well as noise injecting techniques like salt-and-pepper and gaussian blurring.  Additionally in 'wv_util.py' we provide several functions for loading, processing, and chipping xView data.

The Jupyter Notebook provided in this repository interactively illustrates an example xView processing pipeline using the provided utility functions.