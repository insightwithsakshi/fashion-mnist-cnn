# Faasshion MNIST Classification using CNN

A Deep Learning project by ** Sakshi Gaikwad** 
to classify images of fashion clothing using Convolutional Neural Networks (CNN)
built with Tensorflow and Keras.

## 📌 Project Description

This project involves building a deep learning model to classify grayscale images of 10 different fashion
categories from the **Fashion MNIST** dataset. The CNN architechture is trained and tested on 70,000 labeled 28*28 pixel images.

## 👩🏻‍💻 tools & Libraries Used

- Python 3
- Tensorflow / Keras
- Numpy
- Matplotlib
- Jupyter Notebook

- ### Model Architecture

  '''python
- Con2D (32 filters, kernal sixe 3*3 activation='relu')
- MaxPooling2D (pool size 2*2)
- Conv2D (64 filters, kernal size 3*3, activation='relu')
- MaxPooling2D (POOL SIZE 2*2)
- Flatten
- Dense (123 units, activation='relu')
- Output Layer: Dense (10 units, activation ='softmax')


  📊 Results

  * Training Accuracy: ~95.9%
  * Validation Accuracy: ~91.1%
  * Loss: Significantly decreased over epochs
  * Predicted 25 test images and displayed results with green/red labels based on accuracy
 
   📷 Example Output

  *test Images with Predictions
  ✅ Green = correct Prediction
  ❌ red   = Incorrect Prediction



<img width="1470" alt="Screenshot 2025-06-28 at 1 39 11 PM" src="https://github.com/user-attachments/assets/10e9b7a8-cd52-4e26-9d3a-de2aa6b8bd41" />




<img width="1053" alt="Screenshot 2025-06-28 at 1 40 30 PM" src="https://github.com/user-attachments/assets/453869f7-28f5-40ea-971f-9f827b22fc37" />


          
🚀 How to Run

1. Clone this repo
2. Open the notebook in Jupyter
3. Run each cell in order
4. View predictions & modify to try new images !

   🙋🏻‍♀️ Author

   made by Sakshi Gaikwad
   Aspiring Data Scientist | BSc CS AIML | India

    📬 Connect with Me
   * 🌐 LinkdIn https://www.linkedin.com/in/sakshi-gaikwad-127ba8327 











  
