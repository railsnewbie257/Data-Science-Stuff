[Python NumPy Tutorial for Beginners](https://www.youtube.com/watch?v=QUT1VHiLmmI)

<pre>

a.ndim - dimensions
a.shape - m x n
d.dtype - data type
a.itemsize - number of bytes for datatype (16 bits is 2 bytes)
a.size - number of databytes (number of 16 bit elements)
a.size * a.itemsize = a.nbytes - total number of bytes

a.zeros(5)
a.zeros((2,3))
a.ones
a.full(shape, value)
a.full((2,4), 4)
a.full_like(previous array, value) or a.full(previous .shape, value)

a.random.rand(n,m)
a.randowm.random_sample(a)
