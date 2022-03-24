## NL-means

**Non Local means** algorithm is based on the simple formula

<img src="https://render.githubusercontent.com/render/math?math=N L[u](x)=\displaystyle\frac{1}{C(x)} \int_{\Omega} e^{-\frac{\left(G_{a} *|u(x+.)-u(y+.)|^{2}\right)(0)}{h^{2}}} u(y) d y">

Here <img src="https://render.githubusercontent.com/render/math?math=C"> is a normalizing constant,
<img src="https://render.githubusercontent.com/render/math?math=G_a"> is a Gaussian kernel and
<img src="https://render.githubusercontent.com/render/math?math=h"> acts as a filtering parameter.
This formula amounts to say that the denoised value at
<img src="https://render.githubusercontent.com/render/math?math=x">
                                                                  is a mean of the values of all points whose gaussian neighborhood looks like the neighborhood of
<img src="https://render.githubusercontent.com/render/math?math=x">. 


## BM3D

BM3D is a recent denoising method based on the fact that an image has a locally sparse representation in transform domain. 
BM3D was designed by combining sliding window process with block matching. It can be denoted as multipoint approach which comprises of two steps.
