# Cycle-GAN for domain transform

```
pip3 install visdom
```

### Setup the dataset

your dataset by setting up the following directory structure:

```
.
├── datasets                   
|   ├── <dataset_name>         # i.e. brucewayne2batman
|   |   ├── train              # Training
|   |   |   ├── A              # Contains domain A images (i.e. Bruce Wayne)
|   |   |   └── B              # Contains domain B images (i.e. Batman)
|   |   └── test               # Testing
|   |   |   ├── A              # Contains domain A images (i.e. Bruce Wayne)
|   |   |   └── B              # Contains domain B images (i.e. Batman)
```

