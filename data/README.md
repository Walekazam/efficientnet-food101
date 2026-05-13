# Dataset
Food-101 is loaded automatically via TensorFlow Datasets.
Run the notebook and Cell 4 will download it automatically:
    import tensorflow_datasets as tfds
    tfds.load('food101', split=['train', 'validation'], as_supervised=True)
