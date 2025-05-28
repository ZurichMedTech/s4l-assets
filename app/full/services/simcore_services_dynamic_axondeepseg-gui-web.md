AxonDeepSeg is an open-source software using deep learning and aiming at automatically segmenting axons and myelin sheaths from microscopy images. It performs 3-class semantic segmentation using a convolutional neural network. AxonDeepSeg was developed at NeuroPoly Lab, Polytechnique Montreal, University of Montreal, Canada. See the [GitHub](https://github.com/axondeepseg/axondeepseg/) respository and [documentation](https://axondeepseg.readthedocs.io/en/latest/index.html) for more information.

AxonDeepSeg GUI is a fully-interactive wrapper around AxonDeepSeg’s napari plug-in, letting users launch *ads_napari*, visualize microscopy stacks, run CNN-based axon/-myelin segmentation, and hand-correct results directly in the browser notebook window.  

If you use this work in your research, please cite Zaimi, A., Wabartha, M., Herman, V., Antonsanti, P.-L., Perone, C. S., & Cohen-Adad, J. (2018). AxonDeepSeg automatic axon and myelin segmentation from microscopy data using convolutional neural networks. Scientific Reports, 8(1), 3816. [Link to the paper](https://doi.org/10.1038/s41598-018-22181-4).

- **Interface**: drag-and-drop GUI (Napari) 
- **Best for**: exploratory QC, teaching, rapid adjustment of parameters
- **Outputs**: labelled masks + CSV morphometrics etc.
