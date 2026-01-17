# Rice Leaf Disease Detection 


Deep Learning based system to classify major rice leaf diseases using image data.

## Problem Statement
Rice crops are highly affected by leaf diseases which reduce crop yield and quality. Manual detection is time-consuming and error-prone. This project aims to automate disease detection using Deep Learning.

## Objective
To classify three major rice leaf diseases:
- Leaf Blast
- Bacterial Leaf Blight
- Brown Spot

## Approach
- Performed Exploratory Data Analysis (EDA) on image dataset
- Visualized class distribution and sample images
- Applied image preprocessing and data augmentation
- Built and trained a CNN model using TensorFlow & Keras
- Evaluated model performance on validation and test data
- Performed inference on unseen images

## Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy,Pandas,Matplotlib  
- Jupyter Notebook  

## Key Features
- Image preprocessing & normalization
- Data augmentation to improve generalization
- CNN-based multi-class classification
- Prediction confidence visualization
- Detailed EDA and analysis report (PDF)

## Repository Structure
- `PRCP-1001-RiceLeaf.ipynb` – Complete implementation
- `PRCP-1001-RiceLeaf.pdf` – Project report
- `model.h5` – Trained model

## Results
The model successfully classifies rice leaf diseases with high accuracy. Minor misclassifications highlight real-world challenges like visual similarity between disease patterns.

## Future Improvements
- Increase dataset size
- Use transfer learning (MobileNet, ResNet)
- Deploy model using Streamlit or Flask

## Conclusion
This project demonstrates the practical application of Deep Learning in agriculture for early disease detection and improved crop management.
