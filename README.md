# genFib

A Generator is a function that returns an object which can be iterated over, one value at a time. 

When creating a generator in python, use 'yield' instead of 'return' in the function, you can still use return elsewhere in the function where conditional sequences may require it. 

A return statement ends the function immediately and returns the interpreter to the outer scope. T
The Yield function on the other hand, pauses the function, saving the current state and later continues when called again. 

This is a much more efficient way of managing calls instead of iterations, where large amounts of data is wasted after being iterated through, possibly on multiple attempts. 
