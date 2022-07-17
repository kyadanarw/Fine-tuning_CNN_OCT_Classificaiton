# This Github repository demonstrates fine-tuning deep convolutional neural networks for classification of retinal diseases on OCT images

  
***:heavy_exclamation_mark:This GitHub repository serves as a demonstration for training, validating and testing fine-tuned convolutional neural networks for OCT classification.*** 


<p><strong>Keywords:</strong> <italic>OCT images; computer-aided diagnosis; retinal diseases; deep learning;fine-tuning; transfer learning</italic></p>

# Dataset: 
<p> The dataset used in this study comes from the following links.
<p><a href="https://https://data.mendeley.com/datasets/rscbjbr9sj/2">Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification.</a></p>

***:heavy_exclamation_mark:For a faster method, you may download the already prepared dataset from kaggle using the following link.*** 
https://www.kaggle.com/datasets/paultimothymooney/kermany2018

# Dependencis
Dependencies included in the `requirements.txt`: 
- jupyternotebook
- tensorflow
- keras
- os
- random
- matplotlib
- seaborn
- numpy
- pandas
- scikit-learn
<p>:heavy_exclamation_mark: The models were tranined using Kaggle supported GPU.
  
 # Convolutional Neural Networks
 In this respository, seven convolutional neural networks are employed were evaluted and compared.
 Adam optimizer with standard hyperparameters and categorial entropy loss are used as optimizer and loss function respectively.
- ResNet50
- DenseNet201
- MobileNetV2
- XceptionNet
- VGG19
- InceptionV3
- EfficientNetB2
  
 # How to use
- First download the dataset from the given links.
- Then, clone this repository using git or download and extract the files manually.
- Once the repository is cloned, CD into the folder and enter `pip install -r requirements.txt`. 
- After installation of the dependecies, there are two options to evaluate or use the model.</p>
  
***First option: Using the fine-tuned weights:***
> - Clone this repository or download it as zip file and extract the files manually
> - Install the requirements on a newly created environment to prevent issues with other existing ones.
> - Run the `evaluate_model.ipynb` notebook to proceed the evaluation.
> - Run `test_model.ipynb` notebook to test them.</br>
> ***:heavy_exclamation_mark:The fine-tuned weights of each model are stored inside the `weights/` folder.*** </p>
 
 ***Second option: Retraining and Simulating the Models:***
> - Make sure to download the dataset
> - Clone this repository or download it as zip file and extract the files manually
> - Install the requirements on a newly created environment to prevent issues with other existing ones.
> - Run the `train_model.ipynb` notebook to retrain the models.
> - Once the models are trained, you may now use the `evaluate_models.ipynb` and `test_models.ipynb` to evaluate and test the models.
> ***:heavy_exclamation_mark:This is long process to train and test the models.*** </p>

## Performance Results

<table style="width:100%">
  <tr>
    <th>Model</th>
    <th>Accuracy</th> 
    <th>AUC</th>
    <th>Cohem Kappa</th>
    <th>F1-Score</th>
  </tr>
 
   <tr>
    <td>ResNet50</td>
    <td><strong>0000%</strong></td>
    <td><strong>0000%</strong></td>
    <td><strong>0000%</strong></td>
    <td><strong>0000%</strong></td>
  </tr>
  
   <tr>
    <td>DenseNet201</td>
    <td><strong>0000%</strong></td>
    <td><strong>0000%</strong></td>
    <td><strong>0000%</strong></td>
    <td><strong>0000%</strong></td>
  </tr>
  
   <tr>
    <td>MobileNetV2</td>
    <td><strong>0000%</strong></td>
    <td><strong>0000%</strong></td>
    <td><strong>0000%</strong></td>
    <td><strong>0000%</strong></td>
  </tr>
</table>

# Authors
- Khin Yadanar Win

