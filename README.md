# ENNCA-agorski

This project focuses on advancing computer vision techniques, particularly in image segmentation and feature extraction. It includes a collection of Jupyter notebooks and scripts that leverage PyTorch for tasks such as data preprocessing, training, and model quantization. The repository explores state-of-the-art neural network architectures and methods, including feedforward networks, BiFPN, and multimodal approaches for video and audio emotion recognition. Designed for both research and practical applications, this project provides a hands-on approach to understanding and implementing cutting-edge computer vision solutions.

This repository contains a series of Jupyter notebooks and scripts for data processing, training, and quantization of neural networks using PyTorch. The project is designed to explore various neural network architectures and techniques, including feedforward networks, BiFPN, and video/audio emotion recognition.

## Project Structure

```
install_torch_gpu.sh
requirements.txt
notebooks/
    00_data_processing.ipynb
    01_training.ipynb
    02_training_quantized.ipynb
    03_qat_training.ipynb
    exercise_01_FFN.ipynb
    exercise_02_BiFPN.ipynb
    exercise_03_VideoAudioEmotionRecognition2024_student.ipynb
    exercise_04_quantization.ipynb
```

### Key Files and Directories

- **`install_torch_gpu.sh`**: A script to install PyTorch with GPU support.
- **`requirements.txt`**: Contains the Python dependencies required for the project.
- **`notebooks/`**: A directory containing Jupyter notebooks for various tasks:
  - `00_data_processing.ipynb`: Data preprocessing and preparation, including loading, cleaning, and splitting datasets.
  - `01_training.ipynb`: Training a neural network, defining architectures, and evaluating performance.
  - `02_training_quantized.ipynb`: Training a quantized model and comparing its performance with non-quantized models.
  - `03_qat_training.ipynb`: Quantization-Aware Training (QAT) to simulate quantization during training.
  - `exercise_01_FFN.ipynb`: Exercise on feedforward neural networks (FFNs), including implementation and optimization.
  - `exercise_02_BiFPN.ipynb`: Exercise on BiFPN architecture for feature extraction tasks.
  - `exercise_03_VideoAudioEmotionRecognition2024_student.ipynb`: Exercise on video and audio emotion recognition using multimodal inputs.
  - `exercise_04_quantization.ipynb`: Exercise on model quantization, exploring trade-offs between size, speed, and accuracy.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/ENNCA-agorski.git
   cd ENNCA-agorski
   ```

2. Install the required Python packages:
   ```sh
   pip install -r requirements.txt
   ```

3. (Optional) Install PyTorch with GPU support:
   ```sh
   sh install_torch_gpu.sh
   ```

## Usage

1. Navigate to the `notebooks/` directory.
2. Open any of the Jupyter notebooks using Jupyter Lab or Jupyter Notebook:
   ```sh
   jupyter lab
   ```
3. Follow the instructions in the notebooks to run the experiments.

## Requirements

- Python 3.8 or higher
- Jupyter Notebook or Jupyter Lab
- PyTorch (with GPU support recommended)

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.