# ResNet50-and-VGG16-Image-Processing

This repository demonstrates **image classification** using the **ResNet50** model and **feature extraction** using the **VGG16** model, both pre-trained on the ImageNet dataset. It covers end-to-end steps from image loading and preprocessing to predicting class labels and extracting deep feature representations.

---

## 🖼️ Project Overview

- **ResNet50 Classification**: Predict top-3 class labels and probabilities for an input image.
- **VGG16 Feature Extraction**: Extract meaningful feature vectors that can be used for tasks like image clustering, retrieval, or transfer learning.

---

## 🚀 Models Used

1. **ResNet50**: A deep convolutional neural network known for its residual connections, making it highly effective for image classification tasks.

2. **VGG16**: A 16-layer deep convolutional network used here without the classification head, making it ideal for feature extraction.

---

## 📁 Directory Structure

```plaintext
ResNet50-and-VGG16-Image-Processing/
│
├── image1.jpg                # Sample image for testing
├── ResNet50-Classification.py # Script for image classification using ResNet50
└── VGG16-Feature-Extraction.py # Script for feature extraction using VGG16
```

---

## 📜 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/Vamsi404/ResNet50-and-VGG16-Image-Processing.git
   ```

2. Install dependencies:

   ```bash
   pip install keras tensorflow numpy
   ```

3. Run the ResNet50 classification script:

   ```bash
   python ResNet50-Classification.py
   ```

4. Run the VGG16 feature extraction script:

   ```bash
   python VGG16-Feature-Extraction.py
   ```

---

## 📊 Results

### ResNet50 Classification
```plaintext
Predicted: [('n02504458', 'African_elephant', 0.829), ('n01871265', 'tusker', 0.134), ('n02504013', 'Indian_elephant', 0.028)]
```

### VGG16 Feature Extraction
```plaintext
Feature Vector Shape: (1, 7, 7, 512)
```

---

## 🧑‍💻 Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue for any improvements or suggestions.

---

## 🌐 Connect

Feel free to reach out for collaboration or questions:

- **GitHub**: [Your Username](https://github.com/Vamsi404)
- **LinkedIn**: [Your LinkedIn](https://www.linkedin.com/in/vamsi-manda-b87151193/)

---

Enjoy experimenting with image processing and deep learning models!
