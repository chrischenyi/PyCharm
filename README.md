# PyCharm

### Operator

```
myVar=6 
myVar+=2  -> 8
myVar-=2  -> 4
myVar*=2  -> 12
myVar/=2  -> 3
myVar//=8 -> 0 (floor -> 整除)
myVar%=2  -> 0 (remainder)
myVar**=2 -> 6^2 = 36 -> assign power 2 to a
myVar**=3 -> 6^3 = 216 -> assign power 3 to a
```
### Python Operator

```
'a' in 'b' -> check if 'b' contains 'a' -> return True/False value
'a' NOT in 'b'
```


### Install Theano

```sh
$ pip install Theano
$ npm  pip install --upgrade --no-deps theano
$ pip install --upgrade --no-deps git+git://github.com/Theano/Theano.git
```

### Simple Theano Example

``` python
# Example of Theano library 
import theano from theano 
import tensor 

# declare two symbolic floating-point scalars 
a = tensor.dscalar()
b = tensor.dscalar() 

# create a simple symbolic expression 
c = a + b 

# convert the expression into a callable object that takes (a,b) and computes c 
f = theano.function([a,b], c) 

# bind 1.5 to 'a', 2.5 to 'b', and evaluate 'c' 
result = f(1.5, 2.5) 
print(result)
```
