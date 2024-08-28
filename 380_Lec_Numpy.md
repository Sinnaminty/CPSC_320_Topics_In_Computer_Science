# Numpy!

| Table of Contents | Slide Number |
| ------- | ------- |
| [Basics of Numpy](#basics-of-numpy) | 3 |
| [Array Indexing and Slicing](#array-indexing-and-slicing) | 18 |
| [Fancy Indexing](#fancy-indexing) | 21 |
| [Concatenation and Splitting](#concatenation-and-splitting) | 23 |
| [Array Mathematics](#array-mathematics) | 28 |
| [Statistics](#statistics) | 35 |
| [Broadcasting](#broadcasting) | 44 |
| [Boolean Array](#boolean-array) | 52 |
| [Sorting Arrays](#sorting-arrays) | 60 |

---

<a id = "basics-of-numpy"></a>
## Basics of Numpy
Provides tools for computing and data analysis.

### NdArray
Stores elements of the same data type
Must have a shape and a dtype
- 1D (x), 2D (y,x), 3D (y,x,z), etc..

### Array Creation Functions
**Array** : Convert some container to a ndarray
- arr = np.array([1,2,3], [4,5,6])
**arange** : Like range but returns a ndarray
**Ones** : Produces an array of all ones with given shape and dtype
**Zeros** : Like ones, but fills the array with zeros
- np.zeros(shape = (1,3), type = float)
**Full** : Produce an array of given shape and dtype with all values set to the indicated "fill value"
- np.full(shape = (2,3), fill_value = 7)
- Same thing as array([[7, 7, 7], [7, 7, 7]])
**eye, identity** : Creates a square N x N identity matrix

<a id = "array-indexing-and-slicing"></a>
## Array Indexing and Slicing

<a id = "fancy-indexing"></a>
## Fancy Indexing

<a id = "concatenation-and-splitting"></a>
## Concatenation and Splitting

<a id = "array-mathematics"></a>
## Array Mathematics

<a id = "statistics"></a>
## Statistics

<a id = "broadcasting"></a>
## Broadcasting

<a id = "boolean-array"></a>
## Boolean Array

<a id = "sorting-arrays"></a>
## Sorting Arrays
