AxonDeepSeg is an open-source software using deep learning and aiming at automatically segmenting axons and myelin sheaths from microscopy images. It performs 3-class semantic segmentation using a convolutional neural network. AxonDeepSeg was developed at NeuroPoly Lab, Polytechnique Montreal, University of Montreal, Canada. See the [GitHub](https://github.com/axondeepseg/axondeepseg/) respository and [documentation](https://axondeepseg.readthedocs.io/en/latest/index.html) for more information.
AxonDeepSeg Runner is a headless (non-interactive) service that executes AxonDeepSeg via a Python entry-point inside a container. Supply raw images and an analysis script; the runner performs segmentation on cloud CPU/GPU resources and returns the artefact folder to the pipeline. 
If you use this work in your research, please cite Zaimi, A., Wabartha, M., Herman, V., Antonsanti, P.-L., Perone, C. S., & Cohen-Adad, J. (2018). AxonDeepSeg automatic axon and myelin segmentation from microscopy data using convolutional neural networks. Scientific Reports, 8(1), 3816. [Link to the paper](https://doi.org/10.1038/s41598-018-22181-4).
•	Interface: compute node; parameters passed via service inputs
•	Best for: large batch jobs, reproducible processing
•	Outputs: labelled masks + CSV morphometrics etc.

