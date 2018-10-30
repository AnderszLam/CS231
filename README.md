# CS231
CS231n - Convolutional Neural Networks for Visual Recognition - Spring 2017

Started October 24, 2018 --> changes from previous assignments were deleted
Need to restart

## Virtual Environment <br/>

```
cd assignment1
sudo pip install virtualenv      # This may already be installed
virtualenv -p python3 .env       # Create a virtual environment (python3)
### Note: you can also use "virtualenv .env" to use your default python (usually python 2.7)
source .env/bin/activate         # Activate the virtual environment
pip install -r requirements.txt  # Install dependencies
### Work on the assignment for a while ...
source deactivate                       # Exit the virtual environment 
```

## Numpy Tips:
np.reshape ()
* used to reshape an array
* Example: array of dimension 2 x 10 x 10:
  * numpy.reshape(r, shape(5,5,8)) to an array of dimension 5 x 5 x 8
  * OR numpy.reshape (r, shape(5, 5, -1)) will do the same thing

- Anders Lam
