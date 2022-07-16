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
- After installation of the dependecies, there are two options to evaluate or use the model. </br>
**First option: Using the fine-tuned models:**
- Clone this repository or download it as zip file and extract the files manually
- Install the requirements on a newly created environment to prevent issues with other existing ones.
- Run the `model_evaluation.ipynb` notebook to proceedthe evaluation.
- Run `model_tester.ipynb` notebook to test them.
**The fine-tuned weightes of each model are stored inside the `weights/` folder.**

