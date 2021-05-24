# fastai_deployment
- example of a simple web deployment of a fastai deep learning model on Windows using Flask 

## File / Directory structure
- adult_sample_model.pkl - fastai deep learning model trained with the ADULT_SAMPLE dataset
- web_flask_deploy.py - Flask server module
- **templates** - HTML files
- **static/css** - CSS files


## To exercise the code

- Set up fastai on your Windows system following the instructions to [set up PyTorch](https://pytorch.org/get-started/locally/) and [set up fastai](https://docs.fast.ai/)

- Start the Flask server - in the directory where you cloned the repo, run this command

- ```
  python web_flask_deploy.py
  ```

- Open the following address in a browser tab:

- ```
  localhost:5000
  ```

- The file home.html should be loaded into your browser. You can select scoring parameters and click **Get prediction** to see the model's prediction of whether the individual with the scoring parameters you specified has an income above or below 50k


## Background

- [ADULT_SAMPLE dataset](http://robotics.stanford.edu/~ronnyk/nbtree.pdf)