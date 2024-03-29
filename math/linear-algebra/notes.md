## Mu Symbol (μ) 
it represents the population mean

## Population Standard Deviation
The population standard deviation is a measure of the spread (variability) of the scores on a given variable and is represented by:
```
σ = sqrt[ Σ ( Xi – μ )2 / N ]
```

## Population Variance
The population variance is the square of the population standard deviation and is represented by:
```
σ2 = Σ ( Xi – μ )2 / N
```
The symbol ‘σ2’ represents the population variance.

## `|u|`
norm, magnitude (or length) of u vector
or 
```
√a^2+b^2
∣r∣=√r⋅r
```


## Scalar projection 
https://www.nagwa.com/en/explainers/792181370490/

## Cector projection
https://flexbooks.ck12.org/cbook/ck-12-precalculus-concepts-2.0/section/7.5/primary/lesson/vector-projection-pcalc/

## Vector Basis
Given vectors 
<img src="http://www.sciweavers.org/tex2img.php?eq=v%20%3D%20%5Cbegin%7Bbmatrix%7D%205%20%5C%5C%20-1%20%20%5Cend%7Bbmatrix%7D%2C%20%20b_%7B1%7D%20%20%3D%20%5Cbegin%7Bbmatrix%7D%201%20%5C%5C%201%20%20%5Cend%7Bbmatrix%7D%2C%20b_%7B2%7D%20%20%3D%20%5Cbegin%7Bbmatrix%7D%201%20%5C%5C%20-1%20%20%5Cend%7Bbmatrix%7D%0A%0A&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt="v = \begin{bmatrix} 5 \\ -1  \end{bmatrix},  b_{1}  = \begin{bmatrix} 1 \\ 1  \end{bmatrix}, b_{2}  = \begin{bmatrix} 1 \\ -1  \end{bmatrix}" width="250" height="39" />

what is v in the basis defined by b1 and b2 ? You are given that b1 and b2 are orthogonal to each other.  

### ans
<img src="http://www.sciweavers.org/tex2img.php?eq=%20v_%7Bb1%7D%20%20%3D%20%20%20%5Cfrac%7B%20v%20%5Cbullet%20b1%7D%7B%20%20%20%7C%20b1%20%7C%20%5E%7B2%7D%20%7D%0A%0A%0A&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt=" v_{b1}  =   \frac{ v \bullet b1}{   | b1 | ^{2} }" width="103" height="46" />
= (5*1 + (-1)*1 / 1+1 ) = 2

<img src="http://www.sciweavers.org/tex2img.php?eq=%20v_%7Bb2%7D%20%20%3D%20%20%20%5Cfrac%7B%20v%20%5Cbullet%20b2%7D%7B%20%20%20%7C%20b2%20%7C%20%5E%7B2%7D%20%7D%0A%0A%0A&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt=" v_{b2}  =   \frac{ v \bullet b2}{   | b2 | ^{2} }" width="103" height="46" />
= (5*1 + (-1)*(-1) / 1+1 ) = 3

therefore:
<img src="http://www.sciweavers.org/tex2img.php?eq=%20%20v_%7Bb%7D%20%3D%20%20%5Cbegin%7Bbmatrix%7D%202%20%5C%5C%203%20%5Cend%7Bbmatrix%7D%20&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt="  v_{b} =  \begin{bmatrix} 2 \\ 3 \end{bmatrix} " width="72" height="39" />

[img]http://www.sciweavers.org/tex2img.php?eq=%20%20v_%7Bb%7D%20%3D%20%20%5Cbegin%7Bbmatrix%7D%202%20%5C%5C%203%20%5Cend%7Bbmatrix%7D%20&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0[/img]

## linearly dependency
We know that the vectors are linearly dependent if the determinant of the matrix is zero

https://www.maths.usyd.edu.au/u/geoffp/lm-ss/lectp7.pdf

 Are the following vectors linearly independent?
 
 ```
 a[1,0,0], b= [1,1,0], c=[1,0,1] 
 ```
 
 ans: yes
 
There are three vectors and they are linearly dependent, which means that the vectors span 3 dimensions.

## matric
### 2d matric multiplication

https://d2r55xnwy6nx47.cloudfront.net/uploads/2021/03/Matrix-graphic-2.svg

### Gaussian elimination (apples and bananas problem)
https://i.ytimg.com/vi/eDb6iugi6Uk/maxresdefault.jpg

https://rpubs.com/josemauriciobaezadiaz/imperialcollegelondon1

## Determinants

The determinant is useful for solving linear equations, capturing how linear transformation change area or volume, and changing variables in integrals. 

A=[[a b][c d]]
determinants = ad-bc

```
if the determinant is zero, it means that the basis vectors are linearly independent, which means the inverse doesn't exist
```

## Σ (Sigma)

## Einstein summation convention
https://slideplayer.com/5156248/16/images/slide_1.jpg

## Inverse of matrix

suppose we have matrix:
```
[a b]
[c d]
```

inverse of it will be:
```
1/2 * [d -b]
      [-c a]  
```

## Gram-Schmidt Process
The hardest concept I came across in this course so far, even I pass the lab with 10/10 score, I still fail to understand it.
https://www.cnblogs.com/bigmonkey/p/9988022.html

## Calculate matrix determinant 
det [[1 2][3 4]]
= 1*4 -2*3 = -2

## Eigenvectors & Eigenvalues
### Eigenvectors
eigenvectors are those which lie along the same span both
before and after applying a linear transform to a space.

*we never consider the zero-vector as an eigenvector of a matrix.

### Eigenvalues
eigenvalues are simply the amount that
each of those vectors has been stretched in the process. 


### Calculating eigenvectors
Ax = λx
A = transformation
x = vector
I = scaler // as eigenvectors only be scaled after transformation

(A-λ)x = 0
(A-λI)x = 0 // I = identity matrix

as we are not interested the case when x=0
we only interested in the case when A-λI=0


https://www.youtube.com/watch?v=IdsV0RaC9jM



## Calculate matrix T^2
T = C@D@C^-1

T^2 = C@D@C^-1 @ C@D@C^-1
= C@D@D@C^-2
= C@D^2@C^-1

## Characteristic polynomial
for example matrix A = [[a b][c d]]

det([[a b][c d]]-[[λ 0][0 λ]]) 
= det([[a-λ b][c d-λ]])
= (a-λ)(d-λ)-bc
= λ^2-λ(a+b)-bc

## Using eigenvectors to calculate pagerank count
suppose L = page weighting for page A-F
```
L = np.array([[0,   1/2, 1/3, 0, 0,   0 ],
              [1/3, 0,   0,   0, 1/2, 0 ],
              [1/3, 1/2, 0,   1, 0,   1/2 ],
              [1/3, 0,   1/3, 0, 1/2, 1/2 ],
              [0,   0,   0,   0, 0,   0 ],
              [0,   0,   1/3, 0, 0,   0 ]])
```

eignvectors R means the convergence vector after i step where R will not change anymore, so eignvectors is the page count.

Ra to Rf initial weighting will be 1/6

To get the page count:
R^i+1 = L @ R^i


## Tools
matrix calculator: https://www.symbolab.com/solver/matrix-multiply-calculator