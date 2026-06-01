Müşteri Churn Analizi Projesi
Bu projede Python kullanılarak basit bir müşteri analiz sistemi geliştirilmiştir. Projede müşteri bilgileri liste ve dictionary yapıları ile tutulmuştur. Sistem, müşterilerin aylık ücret ve kullanım bilgilerini inceleyerek churn (ayrılma) riski taşıyan müşterileri belirlemektedir.
Projede Kullanılan Konular
Liste (List) Kullanımı
Dictionary Kullanımı
For Döngüsü
Fonksiyon Tanımlama
Koşul Yapıları (if)
math Kütüphanesi
datetime Kütüphanesi
set() Kullanımı
Basit Churn Analizi
Projenin Çalışma Mantığı
Program müşteri listesini for döngüsü ile gezmektedir. Her müşteri için:
KDV’li ücret hesaplanır
Kullanım bilgileri kontrol edilir
Churn skoru oluşturulur
Riskli müşteriler belirlenir
Düşük kullanım ve düşük aylık ücret bilgileri churn riski için kriter olarak kullanılmıştır.
Kullanılan Kütüphaneler
Python
import math
from datetime import datetime
Özellikler
%20 KDV hesaplama
Toplam faturayı yukarı yuvarlama
Güncel tarih gösterme
Benzersiz hizmetleri listeleme
Churn riski taşıyan müşterileri tespit etme
Amaç
Bu proje Python’da temel programlama konularını kullanarak müşteri verileri üzerinde analiz yapmayı amaçlamaktadır.# d-nem-devleri
