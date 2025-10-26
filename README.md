# HastaneOtomasyonu61

#İlişkiler

İlişki Adi ---------------- Varlik Arasi ------------ Durum -------------- Aciklama

Çalışır                     Polikinlik-Doktor          1 : N                Her polikinlikte birden fazla doktor çalışabilir
Muayne olur                 Hasta – Poliklinik         N : M                Hastalar birden fazla poliklinikte muayene olabilir
Yaptırır (Doktor ister)     Hasta – Tahlil             N : M                Hastalar doktorların isteğiyle tahlil yaptırabilir
Yapılır                     Laboratuvar – Tahlil       1 : N                Her tahlil bir laboratuvarda yapılır
Aittir                      Poliklinik – Servis        1 : N                Her poliklinik bir veya birden fazla servise sahiptir
Görev Yapar (Çalışır)       Servis – Hemşire           1 : N                Her serviste birden fazla hemşire görev yapabilir.
