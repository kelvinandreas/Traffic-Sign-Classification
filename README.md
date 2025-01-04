# Traffic Sign Classification

## Members:
- Kelvin Andreas – 2602121794
- Stefanus Albert Wilson – 2602221986
- Paul Tsai Adinata – 2602144816

## Dataset
The dataset used in this project is the **German Traffic Sign Recognition Benchmark (GTSRB)**. This dataset contains over 50,000 images of traffic signs, categorized into 43 distinct classes. Below is an example of traffic signs included in this dataset:
![Example Dataset](./Image%20For%20Readme/Example%20Dataset.png)

## Methods

### 1. Method 1 (HOG + PCA + SVC)
![Flowchart Method 1](./Image%20For%20Readme/Flowchart%20Metode%201.png)
### 2. Method 2 ((Color Histogram + HOG) + PCA + SVC)
![Flowchart Method 2](./Image%20For%20Readme/Flowchart%20Metode%202.png)
### 3. Method 3 (Data Augmentation + CNN)
![Flowchart Method 3](./Image%20For%20Readme/Flowchart%20Metode%203.png)
### 4. Method 4 (Vision Transformer)
![Flowchart Method 4](./Image%20For%20Readme/Flowchart%20Metode%204.png)
`
## Results
The table below presents the performance metrics of the models on the GTSRB dataset:

![Result](./Image%20For%20Readme/Result.png)

## Demo
The application utilizes the best-performing model from the experiments, which is based on the **Vision Transformer (ViT)**. This model achieved the highest accuracy and other performance metrics on the GTSRB dataset.

You can access the application at the following link:  
[Application Demo](https://huggingface.co/spaces/kelvinandreas/traffic-sign-classification)



## Colab Notebook

To view detailed implementation and complete outputs (including those hidden when downloaded as `.ipynb`), please visit the Colab notebook using the link below:  
[Colab Notebook](https://drive.google.com/drive/folders/1QiO_qy_i4KZOcvRO8srqpWkcuX9Y-cww?usp=sharing)