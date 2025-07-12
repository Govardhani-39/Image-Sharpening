# Image-Sharpening
Image-Classification-using-CNN
# Intel Image Classification using CNN #  This project implements a Convolutional Neural Network (CNN) to classify images from the Intel Image Classification dataset. The model is built using PyTorch and trained to distinguish between 6 types of natural scenes.
## 📂 Dataset

The dataset includes images classified into the following categories:

- Buildings
- Forest
- Glacier
- Mountain
- Sea
- Street

📌 You can download the dataset from [Intel Image Classification Dataset on Kaggle](https://www.kaggle.com/datasets/puneet6060/intel-image-classification).

##  Model Architecture

- Framework: PyTorch
- Layers: Conv2D, MaxPooling, ReLU, Fully Connected
- Loss: CrossEntropyLoss
- Optimizer: Adam

##  Training

- Batch Size: 32
- Epochs: 10 (customize as needed)
- Learning Rate: 0.001


##  How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/Govardhani_39/intel-image-classification.git
   cd intel-image-classification
Install dependencies:

bash
Copy code
pip install -r requirements.txt

📌 Requirements
Add the following in requirements.txt:

arduino
Copy code
numpy
torch
opencv-python
matplotlib
scikit-image


📌 Note
This project is for learning and demonstration purposes. Further improvements can be made with data augmentation, model tuning, and transfer learning.


### ✅ Next Steps for You

1. Add a file named `README.md` and paste the above content.
2. Create a `requirements.txt` with the packages mentioned.
3. (Optional) Remove outputs from the notebook to make it cleaner.
4. Upload the folder to GitHub:
   - Use GitHub Desktop **or**
   - Command line:
     ```bash
     git init
     git add .
     git commit -m "Initial commit"
     git remote add origin https://github.com/your-username/intel-image-classification.git
     git push -u origin main
     ```    
