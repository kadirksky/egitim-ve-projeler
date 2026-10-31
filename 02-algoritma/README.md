### Örnek 1: Girilen 2 Sınavın Ortalamasını Hesaplayıp Karar Veren Program
- Değişkenler(sinav1,sinav2,ort)
> Adım 1: Başla
> Adım 2: 1. Sınavınızı Giriniz(sinav1)
> Adım 3: 2. Sınavınızı Giriniz(sinav2)
> Adım 4: ort = (sinav1 + sinav2) /2
> Adım 5: Eğer ort > 70 ise git Adım 7
> Adım 6: Ekrana "Ortalama Kötü" yazdır git Adım 8
> Adım 7: Ekrana "Ortalama İyi" yazdır 
> Adım 8: Bitir
> 

### Örnek 2 : Kısa ve Uzun Kenarı Girilen Dikdötgenin Alan Hesabı
- Değişkenler(uKenar,kKenar,Alan)
> Adım 1: Başla
> Adım 2: Uzun Kenarı Giriniz(uKenar)
> Adım 3: Eğer uKenar <= 0 ise git Adım 2
> Adım 4: Kısa Kenarı Giriniz(kKenar)
> Adım 5: Eğer kKenar <= 0 ise git Adım 4
> Adım 6: Alan = uKenar * kKenar
> Adım 7: Ekrana Alan'ı yazdır
> Adım 8: Bitir

### Örnek 3 : Girilen 5 Sayının Ortalamasını Hesaplayan ve Yazdıran Program
- Değişkenler (sayi,sayac,toplam,ort)
> Adım 1: Başla
> Adım 2: sayac=0, toplam=0
> Adım 3: Sayı Giriniz(sayi)
> Adım 4: toplam = toplam + sayi
> Adım 5: sayac = sayaç + 1
> Adım 6: Eğer sayaç < 5 ise git Adım 3
> Adım 7: ort = toplam / sayaç
> Adım 8: Ekrana ort'u yazdır
> Adım 9: Ekrana toplam'ı yazdır
> Adım 10: Bitir 

### Örnek 4 : Girilen Sayının Pozitif, Negatif ,Sıfır Olma Durumu
- Değişkenler(sayi)
> Adım 1: Başla
> Adım 2: Bir Sayı Giriniz(sayi)
> Adım 3: Eğer sayi < 0 ise git Adım 6
> Adım 4: Eğer sayi > 0 ise git Adım 7
> Adım 5: Ekrana "Sayı Sıfırdır" yazdır git Adım 8 
> Adım 6: Ekrana "Sayı Negatiftir" yazdır git Adım 8
> Adım 7: Ekrana "Sayı Pozitiftir" yazdır
> Adım 8: Bitir

### Örnek 5 : Faktoriyel Hesabı
- Değişkenler(sayi,sonuc,sayac)
> Adım 1: Başla
> Adım 2: Faktoriyeli Hesaplanacak Sayıyı Giriniz(sayi)
> Adım 3: sonuç = 1, sayac =1
> Adım 4: sonuc = sonuç * sayac
> Adım 5: sayac = sayaç + 1
> Adım 6: Eğer sayaç < sayi ise git Adım 4
> Adım 7: Ekrana sonuc'u yazdır 
> Adım 8: Bitir

### Örnek 6: Ortalama Hesabı
- Değişkenler(vize,final,ort,gNotu)
> Adım 1: Başla 
> Adım 2: gNotu = 45
> Adım 3: Vize Notunuzu Giriniz(vize)
> Adım 4: Final Notunuzu Giriniz(final)
> Adım 5: ort = (vize * 0.4) + (final * 0.6)
> Adım 6: Eğer ort < gNotu ise git Adım 8
> Adım 7: Ekrana "Geçti" yazdır git Adım 9
> Adım 8: Ekrana "Kaldı" yazdır 
> Adım 9: Bitir


### Örnek 7: Komisyon Hesabı
- Değişkenler(uFiyat,tKomisyon,uAdet,sayac)
> Adım 1: Başla
> Adım 2: uAdet = 5 , sayaç = 0, tKomisyon = 0
> Adım 3: Ürün Fiyatını Giriniz(uFiyat)
> Adım 4: sayaç = sayaç + 1
> Adım 5: Eğer uFiyat <= 50 ise git Adım 7
> Adım 6: tKomisyon = tKomisyon + (uFiyat * 0.02) git Adım 8
> Adım 7: tKomisyon = tKomisyon + (uFiyat *0.03)
> Adım 8: Eğer sayac < uAdet ise git Adım 3
> Adım 9: Ekrana tKomisyon'u Yazdır
> Adım 10: Bitir

### Örnek 8: Üçgende İki Açısı Verilen Üçgenin 3. Açısını Bulma
- Değişkenler(aci1,aci2,aci3,toplam)
> Adım 1: Başla
> Adım 2: 1. Açıyı Girin(aci1)
> Adım 3: 2. Açıyı Girin(aci2)
> Adım 4: toplam = 0 
> Adım 5: Eğer (aci1 + aci2) > 180 ise git Adım 2
> Adım 6: toplam = aci1 + aci2 
> Adım 7: aci3 = 180 - toplam
> Adım 8: Ekrana "3. Açı: ",aci3 yazdır
> Adım 9: Bitir  
> 
### Örnek 9: 1 ile 100 Arasındaki Çift Sayıların Toplamı
- Değişkenler(toplam, sayi, kalan)
> Adım 1: Başla
> Adım 2: sayi = 1, toplam = 0
> Adım 3: kalan = sayi % 2
> Adım 4: kalan =! 0 ise git Adım 5
> Adım 5: toplam = toplam + sayi
> Adım 6: sayi = sayi + 1
> Adım 7: Eğer sayi <= 100 ise git Adım 2
> Adım 8: Ekrana toplam'ı yaz
> Adım 9: Bitir 

### Örnek 10: Çocuk Sayısına Göre Alınan Ek Maaş Hesabı
- Değişkenler(maas,cSayisi)
> Adım 1: Başla
> Adım 2: Maaşınızı Giriniz(maas)
> Adım 3: Çocuk Sayısını Giriniz(cSayisi)
> Adım 4: Eğer cSayisi = 1 ise git Adım 8
> Adım 5: Eğer cSayisi = 2 ise git Adım 9
> Adım 6: Eğer cSayisi >=3 ise git Adım 10
> Adım 7: Ekrana "Çocuğunuz yok ek maaş alamazsınız" yazdır git Adım 11
> Adım 8: maas = (maas * 0.05) git Adım 11
> Adım 9: maas = (maas * 0.1) git Adım 11
> Adım 10: maas = (maas * 0.15) Adım 11
> Adım 11: Ekrana maas'ı yazdır
> Adım 12: Bitir

### Örnek 11: Çalışma Saatine Göre Maaş Hesaplama
- Değişkenler(cSaat,sUcreti,maas)
> Adım 1: Başla
> Adım 2: Toplam Çalıştığınız Saati Girin(cSaat)
> Adım 3: Saatlik Ücretinizi Girin(sUcreti)
> Adım 4: Eğer saat > 40 ise git Adım 6
> Adım 5: maas = cSaat * sUcreti git Adım 8
> Adım 6: cSaat = cSaat + (cSaat-40) * 2
> Adım 7: maas = cSaat * sUcreti
> Adım 8: Ekrana maas'ı yazdır
> Adım 9: Bitir 

Örnek 12: 1 ile N Arasındaki Tek Sayıların Toplamı ve Çarpımı, Çift Sayıların Karelerinin Toplamını Bulan Program
- Değişkenler(sayi,tToplam,tCarpim,cToplam, sayaç, kalan)
> Adım 1: Başla
> Adım 2: sayi , sayac = 1 , tToplam=0, tCarpim = 1, cToplam = 0)
> Adım 3: Hesaplanacak Sayıyı Giriniz(sayi)
> Adım 4: Eğer sayac > sayi ise git Adım 11
> Adım 5: kalan = sayac % 2
> Adım 6: Eğer kalan = 0 ise git Adım 9
> Adım 7: tToplam = tToplam + sayac
> Adım 8: tCarpim = tCarpim * sayaç git Adım 10
> Adım 9: cToplam = cToplam + (sayac*sayac) 
> Adım 10: sayaç = sayaç + 1 git Adım 4
> Adım 11: Ekrana tToplam'ı yazdır
> Adım 12: Ekrana tCarpim'ı yazdır
> Adım 13: Ekrana cToplam'ı yazdır
> Adım 14: Bitir


### Örnek 13: Klavyeden Girilen 3 Basamaklı Sayının 1,2 ve 3. Basamağını Veren Program
- Değişkenler(sayi,bolum,kalan)
> Adım 1: Başla
> Adım 2: Sayı Giriniz(sayi)
> Adım 3: Eğer sayi<100 && sayi >=1000 ise git Adım 2
> Adım 4: bolum / 100
> Adım 5: kalan = sayi % 100
> Adım 6: Ekrana bolum'u yazdır
> Adım 7: bolum / 10
> Adım 8: kalan = sayi % 10
> Adım 9: Ekrana bolum'u yazdır
> Adım 10: Ekrana kalan'ı yazdır
> Adım 11: Bitir
> 
### Örnek 14: Dört İşlem
- Değişkenler(islemNo,sayi1,sayi2,sonuc)
> Adım 1: Başla
> Adım 2: 1. Sayıyı Girin(sayi1)
> Adım 3: 2. Sayıyı Girin(sayi2) 
> Adım 4: sonuc = 0
> Adım 5: Ekrana "Topla = 1 ,Cıkar = 2 ,Carp = 3 ,Bol = 4" yazdır
> Adım 6: İşlem Numarası Giriniz(islemNo)
> Adım 7: Eğer islemNo = 1 ise git Adım 12 
> Adım 8: Eğer islemNo = 2 ise git Adım 13
> Adım 9: Eğer islemNo = 3 ise git Adım 14
> Adım 10: Eğer islemNo = 4 ise git Adım 15
> Adım 11: git Adım 6
> Adım 12: sonuc = sayi1 + sayi2 git Adım 16
> Adım 13: sonuc = sayi1 - sayi2 git Adım 16
> Adım 14: sonuc = sayi * sayi2 git Adım 16
> Adım 15: sonuc = sayi1 / sayi2 
> Adım 16: Ekrana sonuc'u yazdır
> Adım 17: Bitir