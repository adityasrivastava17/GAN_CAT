# GAN for Cat Image Generation

This project utilizes a Generative Adversarial Network (GAN) to generate realistic images of cats. The model is trained on a dataset of cat images, and through adversarial training, it learns to produce new, high-quality images that resemble the training data.

## Project Overview

Generative Adversarial Networks (GANs) are a class of machine learning frameworks designed to generate new data samples that resemble a given dataset. In this project, a GAN is trained on a dataset of cat images, enabling the generation of novel cat images.

### Key Features
- **Data Loading and Preprocessing**: Images of cats are loaded from a specified directory, preprocessed, and prepared for training.
- **Model Architecture**: The GAN consists of a generator and a discriminator, both implemented using deep neural networks.
- **Training Process**: The GAN is trained iteratively, where the generator creates images and the discriminator evaluates their authenticity.
- **Image Generation**: After training, the generator can produce new, realistic images of cats.

## Technologies Used

- **Python**
- **PyTorch**: For building and training the GAN model.
- **NumPy**: For numerical computations.
- **Matplotlib**: For visualizing the generated images and training process.
- **OS Library**: For file handling and directory management.

## How to Run the Project

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/gan-cat-image-generator.git
    cd gan-cat-image-generator
    ```

2. **Install Dependencies**:
    Ensure you have Python installed. Then, install the necessary Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. **Train the Model**:
    Run the Jupyter Notebook `GAN_CAT_Final.ipynb` to start training the GAN model. You can also adjust hyperparameters and training settings in the notebook.

4. **Generate Images**:
    After training, you can generate new cat images by running the appropriate cells in the notebook.

## Results

- The model successfully generates high-quality images of cats after sufficient training epochs.
- Examples of generated images can be found in the `results` directory.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
