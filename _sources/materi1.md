# Sistem Linear
Sistem linier adalah sekumpulan persamaan matematika yang melibatkan variabel-variabel yang saling berhubungan secara linier. Tujuannya adalah mencari nilai variabel-variabel tersebut yang memenuhi semua persamaan dalam sistem. Sistem linier sering digunakan dalam berbagai bidang seperti fisika, ekonomi, dan teknik

## Komponen Sistem Linier
Variabel: Simbol yang mewakili nilai yang tidak diketahui (misalnya,x, y, z). Koefisien: Angka yang mengalikan variabel (misalnya, dalam 2x+3y=5, angka 2 dan 3 adalah koefisien).

Konstanta: Nilai tetap dalam persamaan (misalnya, angka 5 dalam persamaan di atas).

## Metode Penyelesaian Sistem Linier
Metode Substitusi: Mengganti satu variabel dengan ekspresi dari persamaan lain.

Metode Eliminasi: Menghilangkan satu variabel dengan menambah atau mengurangkan persamaan.

Metode Matriks: Menggunakan matriks untuk menyelesaikan sistem persamaan, seperti dengan metode eliminasi Gauss atau aturan Cramer.

Metode Eliminasi Metode ini menghilangkan satu variabel dengan menambah atau mengurangkan persamaan.

Langkah-langkah:

Atur persamaan sehingga koefisien salah satu variabel sama atau berlawanan.

Tambah atau kurangkan persamaan untuk mengeliminasi variabel tersebut.

Selesaikan persamaan untuk menemukan nilai variabel yang tersisa.

Gunakan nilai yang ditemukan untuk mencari variabel lainnya.

## Contoh Penyelesaian Metode Eliminasi

### Sistem Persamaan

$$
[\begin{cases} 3x + 2y = 8 \ 2x - y = 1 \end{cases} $$

### Langkah-langkah Penyelesaian:
1.  **Tulis sistem persamaan:**  $$ \begin{cases} 3x + 2y = 8 \quad \text{(Persamaan 1)} \ 2x - y = 1 \quad \text{(Persamaan 2)} \end{cases} $$
    
2.  **Eliminasi salah satu variabel:**
    
    -   Agar bisa mengeliminasi (y), kalikan Persamaan 2 dengan 2: $$ 2 \times (2x - y) = 2 \times 1 \ 4x - 2y = 2 \quad \text{(Persamaan 3)} $$
        
3.  **Tambahkan Persamaan 1 dan Persamaan 3:**  
       $$ [\begin{align*} 3x + 2y &= 8 \ -\quad 4x - 2y &= 2 \ 7x &= 10 \ \end{align*}]$$
    

-   Selesaikan untuk (x): [ x = \frac{10}{7} ]
    -   Selesaikan untuk (x): $$ x = \frac{10}{7} $$
        
4.  **Substitusi nilai (x) ke Persamaan 2:**  $$2\left(\frac{10}{7}\right) - y = 1 \ \frac{20}{7} - y = 1 \ -y = 1 - \frac{20}{7} \ -y = -\frac{13}{7} \ y = \frac{13}{7} $$
    
5.  **Solusi:**  $$ x = \frac{10}{7}, \quad y = \frac{13}{7} $$
## 1. Sistem Linier Konsisten (Memiliki Solusi)

Sistem linier dikatakan konsisten jika memiliki setidaknya satu solusi. Artinya, ada nilai-nilai variabel yang memenuhi semua persamaan dalam sistem tersebut.

### Contoh 1: Sistem dengan Solusi Tunggal

Sistem Persamaan:

$$\begin{cases} x + y = 5 \ 2x - y = 1 \end{cases} $$

Penyelesaian:

1.  Dari persamaan pertama, (x = 5 - y).
    
2.  Substitusi ke persamaan kedua:
    

$$2(5 - y) - y = 1 \ 10 - 2y - y = 1 \ 10 - 3y = 1 \ -3y = -9 \ y = 3 $$

3.  Substitusi (y = 3) ke (x = 5 - y):
    

$$x = 5 - 3 = 2 $$

4.  Solusinya adalah (x = 2) dan (y = 3).
    

### Contoh 2: Sistem dengan Solusi Tak Terhingga

Sistem Persamaan:

$$ \begin{cases} x + y = 3 \ 2x + 2y = 6 \end{cases} $$

Penyelesaian:

1.  Persamaan kedua adalah kelipatan dari persamaan pertama.
    
2.  Solusinya adalah semua pasangan ((x, y)) yang memenuhi (x + y = 3).
    
3.  Contoh solusi: ((1, 2)), ((2, 1)), ((0, 3)), dll.
    

## 3. Sistem Linier Tidak Konsisten (Tidak Memiliki Solusi)

Sistem linier dikatakan tidak konsisten jika tidak ada solusi yang memenuhi semua persamaan secara bersamaan. Ini terjadi ketika persamaan-persamaan tersebut menggambarkan garis-garis yang sejajar dan tidak pernah berpotongan.

Sistem Persamaan:

$$ \begin{cases} x + y = 4 \ 2x + 2y = 10 \end{cases} $$

Penyelesaian:

1.  Bagi persamaan kedua dengan 2:
    

$$ x + y = 5 $$

2.  Sekarang, sistem menjadi:
    

$$ \begin{cases} x + y = 4 \ x + y = 5 \end{cases} $$

3.  Tidak mungkin (x + y) sama dengan 4 dan 5 secara bersamaan.
    
4.  Jadi, sistem ini tidak memiliki solusi.

# Penyelesaian sistem persamaan linier

## Operasi Baris Elementer

## Eliminasi Gauss

### Contoh soal 1
Selesaikan dengan menggunakan Eliminasi Gauss
$$x_1 + 2x_2 + 3x_3 = 6 \\ 2x_1 + 4x_2 + 6x_3 = 12 \\ x_3 + x_2 = 2$$
### Contoh soal 2
Selesaikan dengan menggunakan Eliminasi Gauss
$$x_1 + x_2 + x_3 = 3 \\ 2x_1 + x_3 = 5 \\ x_1 + 2x_2 = 3$$
### Contoh soal 3
Selesaikan dengan menggunakan Eliminasi Gauss
$$2x_1 +2 x_2  = 4 \\ x_1 + 2x_2 = 2$$
### Contoh soal 4
Selesaikan dengan menggunakan Eliminasi Gauss
$$x_1 + x_2  = 5 \\ x_1 + 2x_3 = 6$$

### Jawaban:
### Contoh Soal 1

Selesaikan dengan menggunakan Eliminasi Gauss:
$$
x1+2x2+3x3=6\\2x1+4x2+6x3=12\\x2+x3=2$$ $$\begin{aligned} x_1 + 2x_2 + 3x_3 &= 6 \\ 2x_1 + 4x_2 + 6x_3 &= 12 \\ x_2 + x_3 &= 2 \end{aligned}$$

Matriks augmented:
$$
[123∣6246∣12011∣2]$$$$\begin{bmatrix} 1 & 2 & 3 & | 6 \\ 2 & 4 & 6 & | 12 \\ 0 & 1 & 1 & | 2 \end{bmatrix}$$

Langkah eliminasi:

-   Baris kedua dikurangi 2 kali baris pertama:$$ [123∣6000∣0011∣2]$$$$\begin{bmatrix} 1 & 2 & 3 & | 6 \\ 0 & 0 & 0 & | 0 \\ 0 & 1 & 1 & | 2 \end{bmatrix}$$
-   Dari baris kedua terlihat bahwa tidak ada informasi baru (baris nol). Menggunakan baris ketiga, kita dapat menyelesaikan: $$x2+x3=2x_2 + x_3 = 2 x3=t,x2=2−tx_3 = t, \quad x_2 = 2 - t x1+2(2−t)+3t=6x_1 + 2(2 - t) + 3t = 6 x1+4−2t+3t=6x_1 + 4 - 2t + 3t = 6 x1+t=2⇒x1=2−tx_1 + t = 2 \Rightarrow x_1 = 2 - t$$

Jadi, solusi umumnya adalah:$$ x1=2−t,x2=2−t,x3=tx_1 = 2 - t, \quad x_2 = 2 - t, \quad x_3 = t $$dengan $tt$ sebagai parameter bebas.

----------

### Contoh Soal 2

Selesaikan dengan menggunakan Eliminasi Gauss:

$$x1+x2+x3=32x1+x3=5x1+2x2=3$$$$\begin{aligned} x_1 + x_2 + x_3 &= 3 \\ 2x_1 + x_3 &= 5 \\ x_1 + 2x_2 &= 3 \end{aligned}$$

Matriks augmented:

$$[111∣3201∣5120∣3]$$$$\begin{bmatrix} 1 & 1 & 1 & | 3 \\ 2 & 0 & 1 & | 5 \\ 1 & 2 & 0 & | 3 \end{bmatrix}$$

Langkah eliminasi:

-   Eliminasi elemen pertama pada baris kedua dan ketiga: $$[111∣30−1−1∣−101−1∣0]$$$$\begin{bmatrix} 1 & 1 & 1 & | 3 \\ 0 & -1 & -1 & | -1 \\ 0 & 1 & -1 & | 0 \end{bmatrix}$$
-   Jumlahkan baris kedua dan ketiga: $$[111∣30−1−1∣−100−2∣−1]$$$$\begin{bmatrix} 1 & 1 & 1 & | 3 \\ 0 & -1 & -1 & | -1 \\ 0 & 0 & -2 & | -1 \end{bmatrix}$$
-   Dari baris ketiga: $$x3=12x_3 = \frac{1}{2}$$
-   Dari baris kedua:$$ −x2−x3=−1⇒x2=−1+12=−12-x_2 - x_3 = -1 \Rightarrow x_2 = -1 + \frac{1}{2} = -\frac{1}{2}$$
-   Dari baris pertama: $$x1+x2+x3=3⇒x1=3+12+12=4x_1 + x_2 + x_3 = 3 \Rightarrow x_1 = 3 + \frac{1}{2} + \frac{1}{2} = 4$$

Jadi, solusi uniknya adalah:$$ x1=4,x2=−12,x3=12x_1 = 4, \quad x_2 = -\frac{1}{2}, \quad x_3 = \frac{1}{2}$$

----------

### Contoh Soal 3

Selesaikan dengan menggunakan Eliminasi Gauss:
$$
2x1+2x2=4x1+2x2=2$$$$\begin{aligned} 2x_1 + 2x_2 &= 4 \\ x_1 + 2x_2 &= 2 \end{aligned}
$$
Matriks augmented:
$$
[22∣412∣2]$$$$\begin{bmatrix} 2 & 2 & | 4 \\ 1 & 2 & | 2 \end{bmatrix}$$

Eliminasi baris pertama dengan membagi 2:
$$
[11∣212∣2]$$$$\begin{bmatrix} 1 & 1 & | 2 \\ 1 & 2 & | 2 \end{bmatrix}$$

Kurangi baris kedua dengan baris pertama:

$$[11∣201∣0]$$$$\begin{bmatrix} 1 & 1 & | 2 \\ 0 & 1 & | 0 \end{bmatrix}$$

Dari baris kedua: $$x2=0x_2 = 0 $$
Dari baris pertama:$$ x1+0=2⇒x1=2x_1 + 0 = 2 \Rightarrow x_1 = 2$$

Jadi, solusi uniknya adalah: $$x1=2,x2=0x_1 = 2, \quad x_2 = 0$$

----------

### Contoh Soal 4

Selesaikan dengan menggunakan Eliminasi Gauss:

$$x1+x2=5x1+2x3=6$$$$\begin{aligned} x_1 + x_2 &= 5 \\ x_1 + 2x_3 &= 6 \end{aligned}$$

Matriks augmented:

$$
[110∣5102∣6]$$$$\begin{bmatrix} 1 & 1 & 0 & | 5 \\ 1 & 0 & 2 & | 6 \end{bmatrix}$$

Eliminasi baris pertama dengan mengurangkan baris kedua dari baris pertama:
$$
[110∣50−12∣1]$$$$\begin{bmatrix} 1 & 1 & 0 & | 5 \\ 0 & -1 & 2 & | 1 \end{bmatrix}$$

Dari baris kedua:$$ −x2+2x3=1⇒x2=2x3−1-x_2 + 2x_3 = 1 \Rightarrow x_2 = 2x_3 - 1 Dari baris pertama: x1+(2x3−1)=5⇒x1=6−2x3x_1 + (2x_3 - 1) = 5 \Rightarrow x_1 = 6 - 2x_3$$

Jadi, solusi umumnya adalah:$$ x1=6−2t,x2=2t−1,x3=tx_1 = 6 - 2t, \quad x_2 = 2t - 1, \quad x_3 = t dengan tt sebagai parameter bebas.$$

### Contoh soal:

$$\begin{aligned}-7x_1-6x_2-12x_3&=-33\\5x_1+5x_2+7x_3&=24\\x_1+4x_3&=5\end{aligned}$$

$A= \begin{bmatrix} -7& 6& - 12\\ 8& 8& 7\\ 1& 0& 4\end{bmatrix}$ $X= \begin{bmatrix} x_1\\ x_2\\ x_1\end{bmatrix}$ $b= \begin{bmatrix} - 33\\ 24\\ 0\end{bmatrix}$

Untuk menyelesaikan sistem persamaan linear berikut

$$\begin{aligned}-7x_1-6x_2-12x_3&=-33\\5x_1+5x_2+7x_3&=24\\x_1+4x_3&=5\end{aligned}$$

Kita dapat menggunakan metode eliminasi Gauss. Berikut langkah-langkahnya:

Langkah 1: Nyatakan $x_{1}$ dari Persamaan Ketiga

Dari persamaan ketiga:

$$x_1+4x_3=5\quad\Rightarrow\quad x_1=5-4x_3$$

Langkah 2: Substitusi $x_1$ ke Persamaan Pertama dan Kedua

Substitusi $x_1=5-4x_{\mathrm{g}}$ ke persamaan pertama:

$$\begin{array}{cc}-7(5-4x_3)-6x_2-12x_3=-33\\-35+28x_3-6x_2-12x_3=-33\\-6x_2+16x_3=2&\text{(Persamaan A)}\end{array}$$

Substitusi $x_1=5-4x_{\mathfrak{g}}$ ke persamaan kedua:

$$\begin{array}{c}5(5-4x_3)+5x_2+7x_3=24\\25-20x_3+5x_2+7x_3=24\\5x_2-13x_3=-1\quad\text{(Persamaan B)}\end{array}$$

Langkah 3: Selesaikan Sistem Dua Variabel

Dari Persamaan A:

$$-6x_2+16x_3=2\quad\Rightarrow\quad x_2=\frac{16x_3-2}{6}$$

Substitusi $x_{2}$ ke Persamaan B:

$$5\left(\frac{16x_3-2}6\right)-13x_3=-1\\\frac{80x_3-10}6-13x_3=-1\\\frac{80x_3-10-78x_3}6=-1\\\frac{2x_3-10}6=-1\\2x_3-10=-6\\2x_3=4\\x_{3}=2$$
Langkah 4: Temukan Nilai $x_2$ dan $x_1$

Substitusi $x_{\mathrm{g}}=2$ ke Persamaan A:

$$x_2=\dfrac{16(2)-2}{6}=\dfrac{32-2}{6}=\dfrac{30}{6}=5$$

Substitusi $x_{3}=2$ ke persamaan $x_1=5-4x_{3}$

$$x_1=5-4(2)=5-8=-3$$

### Solusi Akhir
$x_1=-3,\quad x_2=5,\quad x_3=2$

## Verifikasi

1. Substitusi ke persamaan pertama:

$$-7(-3)-6(5)-12(2)=21-30-24=-33$$

2. Substitusi ke persamaan kedua:

$$5(-3)+5(5)+7(2)=-15+25+14=24$$

3. Substitusi ke persamaan ketiga:

$$\begin{matrix}-3+4(2)=-3+8=5&\text{(Benar)}\end{matrix}$$