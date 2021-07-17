# Metrics


# Mean Squared Error



![Mean Squared Error](https://pbs.twimg.com/media/Etuc3lBXcAEH7wO.png)

- Mean Squared Error değerimiz; bizim gerçek değerlerimiz ile tahmin değerlerimizin farkının karesinin toplamlarının,veri değerimizin sayısına bölümü ile elde edilir.
### Neden Farkının Karesini alıyoruz ?
- Çünkü Gerçek değerlerimiz ile tahmin değerlerimizden çıkarırken negatif bir değer elde etmemiz mümkün.Daha sonra farklardan elde ettiğimiz pozitif ve negatif değerler toplanırken *0*'a yakın veya *0* elde edebiliriz.Böyle olduğunda da bizim hata oranımız *0*'a yakın bir değer çıkar.Bu durum ise modelimizin iyi bir sonuç verdiğini bize gösterir.Aslında öyle değildir.Karesini almadığımız için pozitif ve negatif değerler birbirini götürüp minimum bir değer elde ederiz.
- Böyle bir yanlış yapmamak için farklarının karesini alırız.
# Root Mean Squared Error
![Root Mean Squared Error](https://miro.medium.com/max/966/1*lqDsPkfXPGen32Uem1PTNg.png)
