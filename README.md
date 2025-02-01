# Image Recommendation System

This repository contains an Image Recommendation System that leverages deep learning techniques to recommend visually similar products. Instead of relying on textual attributes (price, model, brand, etc.), this system suggests similar items based on their appearance, including shape, color, and texture.

## Project Overview

This project aims to build a recommendation system that classifies images based on their similarity. It utilizes a pre-trained **VGG16** model as a feature extractor and computes **cosine similarity** between the query image and a catalog of images to find the most visually similar items.

## Features

- **Feature Extraction:** Uses a pre-trained VGG16 model to generate embeddings from images.
- **Similarity Computation:** Calculates cosine similarity between the query image and catalog images.
- **Recommendation System:** Displays the top 3 most similar images from the uploaded catalog.
- **Interactive Uploads:** Allows users to upload a catalog of images and a query image directly in Google Colab.

## Technologies Used

- **Python 3.x**
- **TensorFlow/Keras** (for loading the VGG16 model)
- **OpenCV** (optional, for additional image processing)
- **scikit-learn** (for similarity computation)
- **Matplotlib** (for result visualization)
- **Google Colab** (for interactive execution)

## How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/image-recommendation-system.git
   cd image-recommendation-system
   ```

2. **Open the notebook in Google Colab:**

   Open `image_recommendation_system.ipynb` in Google Colab.

3. **Execute the cells:**

   Follow the instructions in the notebook:
   - Upload multiple images to build the product catalog.
   - Upload a single query image.
   - The system will compute similarities and display the top 3 recommended images.

## Project Structure

```
image-recommendation-system/
├── image_recommendation_system.ipynb  # Main Jupyter Notebook for image recommendations
└── README.md                           # Project documentation
```

## Notes

- This is an educational project. For production applications, consider using larger datasets and more robust models.
- The recommendations are based on visual similarity using embeddings extracted from the VGG16 model.
- Feel free to contribute and suggest improvements!

## Acknowledgments

- [TensorFlow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)
- [scikit-learn](https://scikit-learn.org/)
- [VGG16 Model](https://keras.io/api/applications/vgg16/)

