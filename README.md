# Metrics

![Regression](https://w7.pngwing.com/pngs/612/141/png-transparent-linear-regression-regression-analysis-machine-learning-lasso-variables-line-angle-text-triangle.png)

- Metrikler,Regresyon modellerimizin hatasını hesaplarken kullandığımız hata metriklerimizdir.

# Mean Squared Error

![Mean Squared Error](https://pbs.twimg.com/media/Etuc3lBXcAEH7wO.png)

- Mean Squared Error değerimiz; bizim gerçek değerlerimiz ile tahmin değerlerimizin farkının karesinin toplamlarının,veri değerimizin sayısına bölümü ile elde edilir.

### Neden Farkının Karesini alıyoruz ?

- Çünkü Gerçek değerlerimiz ile tahmin değerlerimizden çıkarırken negatif bir değer elde etmemiz mümkün.Daha sonra farklardan elde ettiğimiz pozitif ve negatif değerler toplanırken *0*'a yakın veya *0* elde edebiliriz.Böyle olduğunda da bizim hata oranımız *0*'a yakın bir değer çıkar.Bu durum ise modelimizin iyi bir sonuç verdiğini bize gösterir.Aslında öyle değildir.Karesini almadığımız için pozitif ve negatif değerler birbirini götürüp minimum bir değer elde ederiz.
- Böyle bir yanlış yapmamak için farklarının karesini alırız.

# Root Mean Squared Error

![Root Mean Squared Error](https://community.qlik.com/legacyfs/online/128958_2016-06-23%2013_45_36-Root%20Mean%20Squared%20Error%20_%20Kaggle.png)

- Root Mean Squared Error ; Ortalama Kare Hatasının Kareköküdür.
- Root Mean Squared Error değerinin iyi ya da kötü olduğunu anlamak için **Bağımlı Değişkenin** varyansı ile karşılaştırırız.
- Root Mean Squared Error , **Residuals**'ın **Standart Sapmasıdır**.

# Mean Absolute Error 

![Mean Absolute Error](https://www.statisticshowto.com/wp-content/uploads/2016/10/MAE.png)

- **Mean Absolute Error**; İki sürekli değişken arasındaki farkın ölçüsüdür.
- **Mean Absolute Error**; Her gerçek değer ile veriye en iyi uyan çizgi arasında ki ortalama dikey mesafedir.

# Mean Squared Log Error 

![Mean Squared Log Error](https://lindevs.com/wp-content/uploads/2020/10/formula_to_calculate_msle.png)
