---
title: sistem_persamaan_3variabel

---

---
title: sistem_persamaan_3variabel

---

# penyelesaian sistem linear dengan menggunakan sistem persamaan linear gaus
## Sistem Persamaan Linear dengan 3 Persamaan
$
\begin{cases}3x + 2y - z = 4 & \text { (Persamaan 1) } \\ 2x - y + 3z = 5 & \text { (Persamaan 2) } \\ x + 4y + 2z = 6 & \text { (Persamaan 3) }\end{cases}
$

Langkah 1: Membuat Matriks Augmented
Tulis sistem persamaan dalam bentuk matriks augmented:
$
\left[\begin{array}{ccc|c}
3 & 2 & -1 & 4 \\
2 & -1 & 3 & 5 \\
1 & 4 & 2 & 6
\end{array}\right]
$

Langkah 2: Eliminasi Gauss
Tujuan: Mengubah matriks menjadi bentuk eselon baris (row echelon form).

Langkah 2.1: Membuat elemen pertama pada baris pertama menjadi 1.
- Tukar baris pertama $\left(R_1\right)$ dengan baris ketiga $\left(R_3\right)$ agar elemen pertama pada baris pertama menjadi 1:
$
\left[\begin{array}{ccc|c}
1 & 4 & 2 & 6 \\
2 & -1 & 3 & 5 \\
3 & 2 & -1 & 4
\end{array}\right]
$

Langkah 2.2: Eliminasi elemen di bawah pivot pertama.
- Gunakan operasi baris:
- $\quad R_2 = R_2 - 2R_1$
- $\quad R_3 = R_3 - 3R_1$

Hasilnya:
$
\left[\begin{array}{ccc|c}
1 & 4 & 2 & 6 \\
0 & -9 & -1 & -7 \\
0 & -10 & -7 & -14
\end{array}\right]
$

Langkah 2.3: Membuat elemen kedua pada baris kedua menjadi 1.
- Bagi baris kedua $\left(R_2\right)$ dengan -9:
$
\left[\begin{array}{ccc|c}
1 & 4 & 2 & 6 \\
0 & 1 & \frac{1}{9} & \frac{7}{9} \\
0 & -10 & -7 & -14
\end{array}\right]
$

Langkah 2.4: Eliminasi elemen di atas dan di bawah pivot kedua.
- Gunakan operasi baris:
- $\quad R_1 = R_1 - 4R_2$
- $\quad R_3 = R_3 + 10R_2$

Hasilnya:
$
\left[\begin{array}{ccc|c}
1 & 0 & \frac{14}{9} & \frac{2}{9} \\
0 & 1 & \frac{1}{9} & \frac{7}{9} \\
0 & 0 & -\frac{61}{9} & -\frac{23}{9}
\end{array}\right]
$

Langkah 2.5: Membuat elemen ketiga pada baris ketiga menjadi 1.
- Bagi baris ketiga $\left(R_3\right)$ dengan $-\frac{61}{9}$:
$
\left[\begin{array}{ccc|c}
1 & 0 & \frac{14}{9} & \frac{2}{9} \\
0 & 1 & \frac{1}{9} & \frac{7}{9} \\
0 & 0 & 1 & \frac{23}{61}
\end{array}\right]
$

Langkah 2.6: Eliminasi elemen di atas pivot ketiga.
- Gunakan operasi baris:
- $\quad R_1 = R_1 - \frac{14}{9} R_3$
- $\quad R_2 = R_2 - \frac{1}{9} R_3$

Hasilnya:
$
\left[\begin{array}{lll|l}
1 & 0 & 0 & \frac{4}{9} \\
0 & 1 & 0 & \frac{6}{9} \\
0 & 0 & 1 & \frac{23}{61}
\end{array}\right]
$

Langkah 3: Solusi
Dari matriks terakhir, kita dapat membaca solusinya:
$
x = \frac{4}{9}, \quad y = \frac{6}{9}, \quad z = \frac{23}{61}
$

Verifikasi Solusi
Substitusikan nilai $x, y, z$ ke dalam persamaan asli untuk memverifikasi kebenaran solusi:

Kesimpulan
Solusi sistem persamaan linear tersebut adalah:
$
x = \frac{4}{9}, \quad y = \frac{6}{9}, \quad z = \frac{23}{61}
$

### Geogebra Persamaan Linear dengan 3
<iframe src="https://www.geogebra.org/classic/nwfj9rzw?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>
