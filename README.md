# KN-M6

[Materi.pdf](https://github.com/yozoracaelum/KN-M6/files/11340682/Materi.pdf)

<img src="https://user-images.githubusercontent.com/86104516/235096884-be1c92af-daf1-42f1-b43b-ac6503ddffdc.png" width=700, height=200>
<img src="https://user-images.githubusercontent.com/86104516/235096902-30df088a-d2b8-4dd4-852e-d810da160321.png" width=700, height=200>
<img src="https://user-images.githubusercontent.com/86104516/235096915-ea177c27-6eb4-41c9-84fb-5bda4a686452.png" width=450, height=400>

## Regresi

```mermaid
graph TD;
    A([Mulai])-->B[/Input n orde/];
    B-->C("Menyusun matriks<br> X sesuai formula <br>regresi polinomial <br>beserta matriks Y <br>sampai suku ke-n");
    C-->D("Mencari nilai a0,..,an <br>(koefisien polinomial) <br>sesuai formula dengan <br>metode Gauss atau <br>metode Iterasi");
    D-->E("Mensubstitusikan nilai a0,…,an pada <br>persamaan Polinomial menjadi hasil <br>regresi dari data X dan Y");
    E-->F(Memplotkan titik <br>X dan Y serta <br>grafik hasil regresi <br>X dan Y);
    F-->G([Tampil grafik x,y]);
    G-->H([Selesai]);
```
