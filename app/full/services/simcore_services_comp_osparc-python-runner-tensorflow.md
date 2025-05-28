The compute-only counterpart Jupyter ML TensorFlow: drop in a dataset and [TensorFlow](https://www.tensorflow.org/tutorials)-dependent Python script, and the runner executes the training or inference job headless on the cluster, returning weights, logs and metrics to the workflow. 

- **Interface**: non interactive execution node (inputs in the form of scripts and data; outputs are artefacts, logs, metrics)
- **Best for**: automated training loops, hyper parameter sweeps, reproducible pipelines centered on PyTorch
- **Outputs**: trained model checkpoint files, inference result artefacts (NumPy arrays/CSV/images), JSON/CSV metrics, job stdout/stderr logs, etc.
