# Readme

repository ini berisi jawaban dari soal nomor 1 sampai 3


## Jawaban no 1

a) tidak teliti menganalisa sistem, biasanya ini banyak dilakukan oleh QA yang masih freshgraduate. Untuk menghindarinya. Bisa meminta saran dari rekan satu tim, apakah masih ada schenario yang bisa dilakukan. Atau bisa juga sebelum aplikasi naik dari development ke UIT atau SIT, pelajari systemnya dengan mendetail mulai dari user requerement, behavior aplikasi sampai table2 yang dipakai di database

b) melakukan testing terburu buru, seringkali ketika akan ada update patch baru, seorang QA dituntut untuk lebih teliti untuk testing dengan waktu yang sangat singkat. Untuk mensiasatinya bisa membuat automation UI pakai selenium, kalau untuk API testing bisa memakai postman + chaijs untuk assertionnya. Selain itu bisa juga dengan cara diskusi dengan tim development seperti programmer, system analist dan project manager untuk diskusi sehingga sprint nya bisa di lewatkan atau dimundurkan ke sprint selanjutnya.

c) kurang menyadari terhadap anomali data pada aplikasi, misalkan sebuah fitur import dengan metode baground process, tapi data yang muncul kadang sesuai dengan file yang diimport tapi kadang tidak sesuai. Untuk mengatasinya, seorang QA perlu explore lebih jauh untuk mengetahui anomali terjadi dan penyebabnya dimana, tentu seorang QA tidak bekerja sendiri untuk tracing issue nya bisa dengan cara berdiskusi dengan programmer dan system analist sehingga anomali data segera ditemukan dan aplikasi bisa segera di patch.

## Jawaban no 2

a) user requerement, penting karena jika tidak tau user requerementnya shcenario yang dibuat bisa jadi salah checkpoint nya.

b) pengetahuan tentang system, dengan menguasai sebuah system atau fiture, hal ini sangat penting karena bisa menentukan seberapa banyak schenario yang bisa dibuat karena pengetahuan seorang QA terhadap system tersebut.

c) behavior aplikasi, penting karena ketika seorang QA mebuat schenario untuk testing, supaya tidak membuat schenario yang belum ditentukan behaviornya, tapi ditanyakan ke system analist. Jadi tidak asal membuat schenario.

## Jawaban no 3

list endpoint :
1. https://apidev.mile.app/v1/org_login
2. https://apidev.mile.app/v1/login

catatan :
-belum bisa login karena tidak bisa daftar nya


## endpoint org_login

![image](https://user-images.githubusercontent.com/108724272/177288082-7156b4e1-0e51-4183-ac42-3eed9c4de99c.png)

## endpoint login
![image](https://user-images.githubusercontent.com/108724272/177288437-bd2d906d-6f8a-4d73-ae3d-29f94abcab58.png)

## hasil test suites katalon
![image](https://user-images.githubusercontent.com/108724272/177288536-08a748ff-9767-4296-b895-a4f12c846dad.png)

