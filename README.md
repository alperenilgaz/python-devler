# temel python objeleri ve veri yapıları__ödevler
-------------------
 ## 1.problem : Kullanıcıdan aldığınız 3 tane sayıyı çarparak ekrana yazdırın. Ekrana yazdırma işlemini format metoduyla yapmaya çalışın.
kendi cevabım :
 ----------
 a=int(input("bir a sayısı giriniz :"))
b=int(input("bir c sayısı giriniz :"))
c=int(input("bir b sayısı giriniz :"))
print("{} x {} x {}  = {} ".format(a,b,c,a*b*c))
hocanın cevabı :
-----------------
a = int(input("a:"))
b = int(input("b:"))
c = int(input("c:"))
çarpım = a * b * c
print("{} x {} x {} = {} dir".format(a,b,c,çarpım))
---------------------------------------------------------------------------------------------------------------------------
## 2.problem : Kullanıcıdan aldığınız boy ve kilo değerlerine göre kullanıcının beden kitle indeksini bulun.
Beden Kitle İndeksi : Kilo / Boy(m) Boy(m)
-------------
kendi cevabım :
-----------
boy=float(input("boyunuzu metre cinsinde giriniz : "))
kilo=int(input("kilonuzu giriniz : "))
beden_kütle_indeksi=kilo/(boy*boy)
print("beden kitle indeksiniz : {}".format(beden_kütle_indeksi
hocanın cevabı :
-----------------
boy = float(input("Boy:"))
kilo = int(input("Kilo:"))
print("Beden Kitle İndeksi:",kilo / (boy ** 2))
---------------------------------------------------------------------------------------------------------------------------
## 3.problem :Bir aracın kilometrede ne kadar yaktığı ve kaç kilometre yol yaptığı bilgilerini alın ve sürücünü toplam ne kadar ödemesini gerektiğini hesaplayın.
kendi cevabım :
----------
km=int(input("Aracın km'de kaç TL yaktığını  giriniz :"))
yol=int(input("Araçla kaç km yol yaptığınızı yazınız :"))
tutar = km*yol
print("ödeyeceğiniz tutar : {}Tl iyi günler :)".format(tutar))
hocanın cevabı :
-----------------
yakan_miktar = float(input("Kilometrede yakan miktar:"))
kilometre = int(input("Kaç km yol yaptınız:"))
print("Tutar: {} tl".format(yakan_miktar * kilometre))
---------------------------------------------------------------------------------------------------------------------------
## 4.problem : Kullanıcıdan ad,soyad ve numara bilgisini alarak bunları alt alta ekrana yazdırın.
kendi cevabım :
--------
print("HASTA KAYIT")
ad=input("Hastanın adı : ")
soyad=input("Hastanın soyadı : ")
numara=int(input("Hastanının numarası : "))
print("bilgiler kaydediliyor...")
bilgi=[ad,soyad,numara]
print("hastanın adı : {}\nhastanın soyadı : {}\nhastanın numarası : {}\n".format(bilgi[0],bilgi[1],bilgi[2]))
print("bilgiler kaydedildi .")
hocanın cevabı :
-----------------
ad = input("Ad:")
soyad = input("Soyad:")
numara = input("Numara:")
print("\nBilgiler...\n")
print("{}\n{}\n{}".format(ad,soyad,numara))
---------------------------------------------------------------------------------------------------------------------------
## 5.problem :Kullanıcıdan iki tane sayı isteyin ve bu sayıların değerlerini birbirleriyle değiştirin.
kendi cevabım :
---------
a=input("ilk sayınızı giriniz :")
b=input("ikinci sayınızı giriniz :")
print("sayılar yer değiştirmeden önceki hali\n a : {}\n b : {}\n".format(a,b))
a,b = b,a
print("sayıların yer değiştirdikten sonraki halin\n a : {}\n b : {}\n ".format(a,b))
hocanın cevabı :
-----------------
a = input("a:")
b = input("b:")
print("Değiştirilmeden Önce Değerler\na: {} b: {}\n".format(a,b))
a,b = b,a
print("Değiştirildikten Sonraki Değerler\na: {} b: {}\n".format(a,b))
---------------------------------------------------------------------------------------------------------------------------
## 6.problem : Kullanıcıdan bir dik üçgenin dik olan iki kenarını(a,b) alın ve hipotenüs uzunluğunu bulmaya çalışın.

Hipotenüs Formülü: a^2 + b^2 = c^2
kendi cevabım :
--------
k1=int(input("dik üçgenin birinci kenarını giriniz :  "))
k2=int(input("dik üçgenin  ikinci kenarını giriniz :  "))
hipotenus = ((k1**2)+(k2**2))**0.5
print("dik üçgenin hipotenüs değeri : {}".format(hipotenus))
hocanın cevabı :
-----------------
a = int(input("a:"))
b = int(input("b:"))
c =  (a ** 2 + b ** 2) ** 0.5
print("Hipotenüs: ",c)
---------------------------------------------------------------------------------------------------------------------------


















