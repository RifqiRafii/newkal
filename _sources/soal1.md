## Bukti Transformasi Rotasi adalah Transformasi Linier

Diberikan transformasi linier$T:\mathbb{R}^2\to\mathbb{R}^2$ yang dinyatakan oleh matriks rotasi!

$$A=\begin{bmatrix}\cos\theta&-\sin\theta\\\sin\theta&\cos\theta\end{bmatrix}$$

Transformasi ini memutar vektor $\mathbf{v}=\begin{bmatrix}x\\y\end{bmatrix}$ sebesar sudut $\theta$ berlawanan arah jarum jam:

$$T(\mathbf{v})=A\mathbf{v}=\begin{bmatrix}\cos\theta&-\sin\theta\\\sin\theta&\cos\theta\end{bmatrix}\begin{bmatrix}x\\y\end{bmatrix}=\begin{bmatrix}x\cos\theta-y\sin\theta\\x\sin\theta+y\cos\theta\end{bmatrix}$$

Untuk membuktikan bahwa $T$ adalah transformasi linier, kita harus menunjukkan dua sifat:


$1.Aditivitas:$

$$T(\mathbf{u}+\mathbf{v})=T(\mathbf{u})+T(\mathbf{v})$$

2. Homogenitas:
$T(c\mathbf{v})=cT(\mathbf{v})$,untuk setiap skalar $c\in\mathbb{R}$


### 1. Aditivitas

Misalkan:

$Maka:$

$$\mathbf{u}=\begin{bmatrix}x_1\\y_1\end{bmatrix},\quad\mathbf{v}=\begin{bmatrix}x_2\\y_2\end{bmatrix}$$

$$T(\mathbf{u}+\mathbf{v})=A(\mathbf{u}+\mathbf{v})=A\begin{bmatrix}x_1+x_2\\y_1+y_2\end{bmatrix}=\begin{bmatrix}(x_1+x_2)\cos\theta-(y_1+y_2)\sin\theta\\(x_1+x_2)\sin\theta+(y_1+y_2)\cos\theta\end{bmatrix}$$

Dan:

$$T(\mathbf{u})+T(\mathbf{v})=\begin{bmatrix}x_1\cos\theta-y_1\sin\theta\\x_1\sin\theta+y_1\cos\theta\end{bmatrix}+\begin{bmatrix}x_2\cos\theta-y_2\sin\theta\\x_2\sin\theta+y_2\cos\theta\end{bmatrix}$$
$=\begin{bmatrix}(x_1+x_2)\cos\theta-(y_1+y_2)\sin\theta\\(x_1+x_2)\sin\theta+(y_1+y_2)\cos\theta\end{bmatrix}$
Karena hasilnya sama, maka sifat aditif terpenuhi

### 2. Homogenitas

$$\begin{aligned}&\text{alkan }c\in\mathbf{R},\text{dan }\mathbf{v}=\begin{bmatrix}x\\y\end{bmatrix}\\&T(c\mathbf{v})=A(c\mathbf{v})=A\begin{bmatrix}cx\\cy\end{bmatrix}=\begin{bmatrix}cx\cos\theta-cy\sin\theta\\cx\sin\theta+cy\cos\theta\end{bmatrix}=c\begin{bmatrix}x\cos\theta-y\sin\theta\\x\sin\theta+y\cos\theta\end{bmatrix}=cT(\mathbf{v})\end{aligned}$$

Sifat homoqenitas juqa terbukti.

Z Kesimpulan

Karena kedua sifat:

. Aditivitas

. Homogenitas

terpenuhi, maka transformasi rotasi!

$$T(\mathbf{v})=A\mathbf{v}$$

adalah transformasi linier.