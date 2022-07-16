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
<p>:heavy_exclamation_mark: The models were tranined using Kaggle's GPU.
 
  # How to use
- First download the dataset from the given links.
- Then, clone this repository using git or download and extract the files manually.
- Once the repository is cloned, CD into the folder and enter `pip install -r requirements.txt`. 
- After installation of the dependecies, there are two options to evaluate or use the model.</p>
  
***First option: Using the fine-tuned weights:***
> - Clone this repository or download it as zip file and extract the files manually
> - Install the requirements on a newly created environment to prevent issues with other existing ones.
> - Run the `model_evaluation.ipynb` notebook to proceedthe evaluation.
> - Run `model_tester.ipynb` notebook to test them.</br>
> ***:heavy_exclamation_mark:The fine-tuned weights of each model are stored inside the `weights/` folder.*** </p>
 
 ***Second option: Retraining and Simulating the Models:***
> - Make sure to download the dataset
> - Clone this repository or download it as zip file and extract the files manually
> - Install the requirements on a newly created environment to prevent issues with other existing ones.
> - Run the `model_train.ipynb` notebook to retrain the models.
> - Once the models are trained, you may now use the `model_evaluation.ipynb` and `model_tester.ipynb` to evaluate and test the models.
> ***:heavy_exclamation_mark:This is long process to train and test the models.*** </p>

## Performance Results

<table style="width:100%">
  <tr>
    <th>Model</th>
    <th>Accuracy</th> 
    <th>Precision</th>
    <th>Recall</th>
    <th>F1-Score</th>
  </tr>
  <tr>
    <td>Fused-DenseNet-Tiny</td>
    <td><strong>97.99%</strong></td>
    <td><strong>98.38%</strong></td>
    <td><strong>95.15%</strong></td>
    <td><strong>95.26%</strong></td>
  </tr>
</table>

