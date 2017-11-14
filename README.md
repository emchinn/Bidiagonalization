<p align="center"><h2> Bidiagonalization: Golub-Kahan Method with Householder Reflectors</h2></p>

This is a review of the Golub-Kahan Bidiagonalization Method, using Householder reflectors. The method was developed in 1965 by <a href="https://en.wikipedia.org/wiki/Gene_H._Golub">Gene H Golub</a> and <a href="https://en.wikipedia.org/wiki/William_Kahan">William M Kahan</a> to eliminate problems from ill-conditioned or rank-deficient matrices. This method used in numerous algorithms including LSQR and SVD. 

The notebook focuses on explaning the big picture overview of the Golub-Kahan method:

<p align="center">
<img src="images/overview.png" width="550"/> 
</p>


I include a digression on Householder reflectors and their role in bidiagonalization:

<p align="center">
<img src="images/reflector3.png" width="350"/> 
</p>

As well as an example of the algorithm:

<p align="center">
<img src="images/matrix_example.png" width="500"/> 
</p>



