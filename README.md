# CNN Autoencoder for MNIST Image Reconstruction
- This project implements a **Convolutional Autoencoder** to learn compact latent representations of handwritten digits from the MNIST dataset and reconstruct the original images.
- The focus of this project is to understand **representation learning and dimensionality reduction** using deep learning.

 🔍 Project Overview
Autoencoders are widely used for:
- Feature extraction
- Noise reduction
- Dimensionality reduction

In this project:
- A CNN-based encoder compresses input images
- A decoder reconstructs images from latent space
- The model learns meaningful compressed representations of digits


🧠 Model Details
- Input: 28×28 grayscale images
- Encoder: Convolution + pooling layers
- Latent space: Compressed feature representation
- Decoder: Convolutional transpose layers
- Loss function: Reconstruction loss (MSE)

 🛠 Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab (for training and experimentation)

📊 Results
- Successfully reconstructed handwritten digit images
- Learned compact latent representations
- Demonstrated dimensionality reduction using CNN Autoencoders

Sample outputs and visualizations are included in the notebook.

📁 Project Structure
cnn-autoencoder-mnist/
│
├── MNIST_AutoEncoder.ipynb
├── README.md

 ▶️ How to Run
1. Open the notebook in **Google Colab**
2. Run all cells sequentially
3. Model training, reconstruction, and visualization will execute end-to-end

 🔮 Future Improvements
- Experiment with different latent space sizes
- Add denoising autoencoder variants
- Save trained model weights
- Convert notebook logic into Python scripts

  
