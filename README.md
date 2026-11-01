Copy this into a file named **`README.md`** in the root of your `cifar100-project` folder:

```markdown
# CIFAR-100 Image Classification

This project compares two deep-learning models on the CIFAR-100 image dataset:

- A custom Convolutional Neural Network (CNN)
- A fine-tuned MobileNetV2 model using transfer learning

## Dataset

CIFAR-100 contains 60,000 color images, each 32 × 32 pixels, divided into 100 classes. It has 50,000 training images and 10,000 test images.

The dataset is not included in this repository. Prepare or upload it as required by the notebook before running the data-loading cells. See the [official CIFAR-100 page](https://www.cs.toronto.edu/~kriz/cifar.html) for dataset information.

## Project files

- `models/main.ipynb` — notebook for preparing the data, training and evaluating the models
- `cnn comparison.png` — model comparison chart
- `cnn confusion matrix.png` — custom CNN confusion matrix
- `mobilenet confusion matrix.png` — MobileNetV2 confusion matrix
- `output.png` — project output image

## Run the project

1. Install Python, Jupyter Notebook, TensorFlow, NumPy, Matplotlib, and scikit-learn.
2. Open `models/main.ipynb` in Jupyter Notebook or VS Code.
3. Set the dataset path in the notebook to where you saved the CIFAR-100 data.
4. Run the notebook cells in order.

Training can take longer on a CPU. A compatible GPU may speed it up.

## Results

| Model | Test accuracy |
|---|---:|
| Custom CNN | 44.67% |
| Fine-tuned MobileNetV2 | 68.02% |

In this run, fine-tuned MobileNetV2 achieved higher test accuracy than the custom CNN. Results may vary with training settings and software or hardware.

## Notes

- The notebook's best recorded MobileNetV2 validation accuracy was 69.02%.
- Do not add the dataset, virtual environments, or credentials to the repository.
```
