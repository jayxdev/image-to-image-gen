# Image-to-Image Generation with Conditional GAN

This project implements a Conditional Generative Adversarial Network (CGAN) for image-to-image generation using the CIFAR-10 dataset. The model is capable of generating images for 10 different classes: Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, and Truck.

## Features

- Conditional GAN architecture
- TensorFlow and Keras implementation
- CIFAR-10 dataset integration
- Real-time training visualization
- Customizable hyperparameters

## Requirements

- TensorFlow
- Keras
- NumPy
- Matplotlib
- tqdm

## Usage

1. Clone the repository:
```git clone https://github.com/yourusername/image-to-image-gen.git cd image-to-image-gen

```
## Install the required dependencies:
```pip install tensorflow numpy matplotlib tqdm

```

3. Run the main script:
```python main.py```

## Model Architecture

The project consists of two main components:

1. Generator: A deep convolutional network that generates images based on random noise and class labels.
2. Discriminator: A convolutional network that distinguishes between real and generated images, considering the class labels.

## Training

The model is trained for 50 epochs by default. During training, you'll see:

- Progress bars for each epoch
- Generator and Discriminator loss values
- Generated image samples for each class

## Customization

You can modify the following parameters in the `main.py` file:

- `batch_size`: Number of images per batch (default: 16)
- `epoch_count`: Number of training epochs (default: 50)
- `noise_dim`: Dimension of the noise vector (default: 100)
- `n_class`: Number of classes (default: 10)

## Results

After training, the model will generate sample images for each class. These images will be displayed during the training process, allowing you to visualize the improvement in image quality over time.

## License

This project is open-source and available under the MIT License.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the issues page if you want to contribute.

## Acknowledgements

- CIFAR-10 dataset
- TensorFlow and Keras teams
