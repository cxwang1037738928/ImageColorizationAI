# ImageColorizationAI
An image colorization AI that uses two  convolutional neural network architectures, PoolUpsampleNet and ConvTransposeNet, to predict pixel-wise colors from grayscale images

# What this looks like on a series of test images

<img width="679" height="653" alt="image" src="https://github.com/user-attachments/assets/14b799b9-745f-44ae-bb2d-79f0d7f5ab02" />


The model was trained on 25 epochs with the following parameters:

    "gpu": True,
    "valid": False,
    "checkpoint": "",
    "colours": "./data/colours/colour_kmeans24_cat7.npy",
    "model": "ConvTransposeNet",
    "kernel": 3,
    "num_filters": 32,
    'learn_rate':0.001,
    "batch_size": 100,
    "epochs": 25,
    "seed": 0,
    "plot": True,
    "experiment_name": "colourization_cnn",
    "visualize": False,
    "downsize_input": False,
