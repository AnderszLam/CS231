# CS231
CS231n - Convolutional Neural Networks for Visual Recognition - Spring 2017

Started October 24, 2018 --> changes from previous assignments were deleted
Need to restart

## Virtual Environment <br/>

```
cd assignment1
sudo pip install virtualenv                     # This may already be installed
virtualenv -p python3 .env                      # Create a virtual environment (python3)
### Note: you can also use "virtualenv .env" to use your default python (usually python 2.7)
source .env/bin/activate                        # Activate the virtual environment
pip install -r requirements.txt                 # Install dependencies
### Work on the assignment for a while ...
source deactivate                               # Exit the virtual environment
```

## Download Data
```
cd cs231n/datasets
./get_datasets.sh
```

## Numpy Tips
```
np.reshape ()
> used to reshape an array
> Example: array of dimension 2 x 10 x 10:
  > numpy.reshape(r, shape(5,5,8)) to an array of dimension 5 x 5 x 8
  > OR numpy.reshape (r, shape(5, 5, -1)) will do the same thing
```
```
np.argsort
> x = numpy.array([1.48,1.41,0.0,0.1])
> print x.argsort()
>[2 3 1 0]

2 is the index of 0.0.
3 is the index of 0.1.
1 is the index of 1.41.
0 is the index of 1.48
```
```
np.argmax
> returns indices of the maximum values along axis
> a = array ([[0,1,2],[3,4,5]])
> np.argmax(a)
> 5
```
```
np.bincount
> count number of occurences of each value in array of non-negative ints
> np.bincount(np.arange(5))
> array [(1,1,1,1,1)]
```
