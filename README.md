# LDA: Linear Discriminant Analysis  

### Linear Algebra and Applications (SME0142)  

-A project made for a São Paulo University discipline

**Linear Discriminant Analysis (LDA)** is a supervised technique widely used in machine learning for classification and dimensionality reduction. It differs from **Principal Component Analysis (PCA)** because, while PCA focuses on maximizing the variance of the data, LDA seeks to maximize the separation between classes in the dataset while minimizing the variance within each class.  

## Goal of LDA  

The main goal of LDA is to find a feature space where the different classes of data are as separated as possible. To achieve this, LDA maximizes the **separability** between classes while minimizing the dispersion within each class.  

## Difference Between LDA and PCA  

Although both **LDA** and **PCA** are dimensionality reduction techniques, they differ in their objectives:  

- **PCA** seeks to capture the greatest possible variability in the data without considering the classes.  
- **LDA**, on the other hand, focuses on optimizing the separation between classes, making it more suitable for supervised classification tasks.  

## How Does LDA Work?  

As mentioned earlier, the focus of LDA is to maximize the ratio between the dispersion of different classes and the dispersion within classes, ensuring that different classes are far apart and that elements within the same class are well grouped. Initially, we will analyze the case with two classes and later generalize it.  

## Math

the math and python application is better explained in the notebook


