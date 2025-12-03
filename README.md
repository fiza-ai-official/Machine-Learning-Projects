# CIFAR-10 Image Classification using ResNet-18

This project implements a **ResNet-18** based image classification model trained on the **CIFAR-10** dataset using **PyTorch**.

As a beginner, this project helped me understand core deep learning concepts such as model architecture, training loops, data augmentation, GPU training, evaluation metrics, and debugging ML pipelines.

---

## 🚀 Features

* Custom implementation of **ResNet-18** adapted for CIFAR-10
* Training & validation loops using PyTorch
* Image transformations & augmentations
* GPU support for faster model training
* Visualizations:

  * Accuracy & loss curves
  * Confusion matrix
  * Sample predictions
  * Optional Grad-CAM for heatmaps
* Best model checkpoint saving


---

## 🧠 Key Concepts Learned

* How CNNs work and why ResNet's skip connections help
* CIFAR-10 normalization, batching, and augmentations
* Writing full training loops (forward + backward propagation)
* Optimizers, schedulers, loss functions
* Handling common ML issues: shape mismatches, dataloader workers, slow training
* Generating and interpreting evaluation plots

---

## 🖥️ How to Run

1. Install dependencies:

   ```bash
   pip install torch torchvision matplotlib scikit-learn tqdm
   ```
2. Open the notebook:

   ```bash
   jupyter notebook CIFAR10_ResNet18.ipynb
   ```
3. Set runtime to GPU (recommended if using Google Colab).
4. Run all cells — the notebook downloads CIFAR-10 automatically.
5. After training, you will get:

   * Accuracy curves
   * Confusion matrix
   * Sample predictions
   * Model checkpoint (`best_checkpoint.pth`)

---

## 📊 Results

* Achieved strong accuracy on CIFAR-10 using ResNet-18
* Clear improvement with augmentations & tuned hyperparameters
* Visualizations helped analyze model performance effectively

---

## 🙌 Acknowledgment

Special thanks to **Sir Shoaib Farooq** for assigning this project, which significantly improved my understanding of machine learning.

---

## 🏷️ Tags

`Machine Learning` `Deep Learning` `PyTorch` `CIFAR10` `ResNet` `Beginners` `AI Project`
