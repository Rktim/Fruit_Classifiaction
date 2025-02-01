# 🍇 Fruit Classification

Welcome to the **Fruit Classification** project! This initiative leverages deep learning to accurately identify various fruits using two distinct models. Dive in to explore the fascinating world of neural networks applied to fruit recognition.

## 📋 Table of Contents

- [Introduction](#introduction)
- [Models Overview](#models-overview)
- [Dataset Details](#dataset-details)
- [Results and Insights](#results-and-insights)
- [Contributing](#contributing)
- [License Information](#license-information)

## Introduction

In this project, we harness the power of deep learning to classify fruits. By leveraging two unique models, we aim to achieve high accuracy in fruit identification, showcasing the potential of neural networks in image classification tasks.

## Models Overview

We employ two powerful models for fruit classification:

1. **Custom Convolutional Neural Network (CNN) with PyTorch**: A tailor-made CNN designed to capture essential features of fruit images, implemented using PyTorch.

2. **Fine-Tuned VGG Network**: A pre-trained VGG model adapted to our dataset, providing a deeper architecture for enhanced performance.

⌨️## Dataset Details

### The dataset used in this project is organized into three main folders:

#### train: Contains training images
apple: Images of apples
banana: Images of bananas
mango: Images of mangoes

#### test: Contains testing images
apple: Images of apples for testing
banana: Images of bananas for testing
mango: Images of mangoes for testing
predict: Contains images for which predictions are to be made

## Results and Insights

🤖### Model Performance
The models' performance metrics are presented below:


###  |Model     | Accuracy| 	Precision	Recall |F1-Score |
#### |Custom CNN	| 73.67% |	74.80% |  73.67% |	73.99% |
#### |VGG16	    | 87.00%   |  87.00% |	87.00% | 	87.00% |

## Contributing

We welcome contributions! If you'd like to enhance the project, please fork the repository and submit a pull request with your proposed changes.

## License Information

This project is licensed under the GNU General Public License v3.0. For more details, refer to the [LICENSE](LICENSE) file.

---

Feel free to customize this README further to align with your project's specifics and any additional information you'd like to provide. 
