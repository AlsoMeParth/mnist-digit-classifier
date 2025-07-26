# MNIST Digit Classifier 🧠🔢

This project is a handwritten digit classifier built using the MNIST dataset and TensorFlow. It includes both model training and data visualization in separate Jupyter Notebooks.

## 🗂️ Project Structure

* `MNIST model.ipynb` – Builds, trains, and evaluates a neural network on the MNIST dataset using TensorFlow.
* `MNIST visualization.ipynb` – Visualizes MNIST images, predictions, and model performance.

## 🔧 Requirements

* Python 3.8 to 3.10 (recommended for TensorFlow 2.12 compatibility)
* TensorFlow
* Matplotlib
* Jupyter Notebook (for running `.ipynb` files)

Install required packages using:

```bash
pip install -r requirements.txt
```

> ⚠️ **Note:** Ensure you are using Python version 3.8–3.10. TensorFlow 2.12 does not support Python 3.11+.

## 🚀 Getting Started

1. Clone this repository:

```bash
git clone https://github.com/AlsoMeParth/mnist-digit-classifier.git
cd mnist-digit-classifier
```

2. (Optional) Create and activate a virtual environment:

```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:

```bash
jupyter notebook
```

## 📊 Output Sample

The model achieves over 98% accuracy on the MNIST test set. You can also visualize sample predictions and confusion matrices in the `MNIST visualization.ipynb` file.

