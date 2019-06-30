# Bike-Sharing-Prediction
A Neural Network to predict Bike Sharing Rides based on historical Data. Developed as a Coursework project for Udacity Deep Learning Nanodegree.

## Getting Started   

This dataset has the number of riders for each hour of each day from January 1 2011 to December 31 2012. The number of riders is split between casual and registered, summed up in the cnt column. You can see the first few rows of the data above.

Below is a plot showing the number of bike riders over the first 10 days or so in the data set. (Some days don't have exactly 24 entries in the data set, so it's not exactly 10 days.) You can see the hourly rentals here. This data is pretty complicated! The weekends have lower over all ridership and there are spikes when people are biking to and from work during the week. Looking at the data above, we also have information about temperature, humidity, and windspeed, all of these likely affecting the number of riders. You'll be trying to capture all this with your model.

![Alt dataset](/assets/dataset.png)

### Requirments    

- numpy   
- matplotlib   
- pandas   
- jupyter notebook


** Creating env and Installing packages
```
# conda create -n env_name python=3
# conda install numpy matplotlib pandas jupyter notebook

```   
    

** Running the Project
```
# jupyter notebook   

In your browser, open ``` Your_first_neural_network.ipynb ```
```

The neural network is implemented in the file ``` my_answer.py ```. The whole project can be run from the notebook.


### Hyperparameters

```
iterations = 5000
learning_rate = 0.5
hidden_nodes = 20
output_nodes = 1     
```    

### Neural Network Training

```
Progress: 0.1% ... Training loss: 10.23 ... Validation loss: 12.12    
Progress: 100.0% ... Training loss: 0.064 ... Validation loss: 0.159
```

![Alt training](/assets/training.png)


### Neural Network Predictions

![Alt training](/assets/prediction.png)



