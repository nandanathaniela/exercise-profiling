<h1>Profiling Exercise</h1>

### Nanda Nathaniela Meizari
### 2206824136

---

`/all-student` before optimize
![/all-student table before optimize](https://media.discordapp.net/attachments/1216986392614142003/1217302600333004890/image.png?ex=66038864&is=65f11364&hm=322d15b194b44af68f82078ad9fccdb690e2ead5d320b492e85ed11b5ba68de0&=&format=webp&quality=lossless&width=960&height=307)
![/all-student terminal before optimize](https://media.discordapp.net/attachments/1216986392614142003/1217305811714441326/image.png?ex=66038b61&is=65f11661&hm=9f2832b42bba45d407b7f40bb9057cc8b5c762597ebd9283f487feebaadcf481&=&format=webp&quality=lossless&width=960&height=183)

---

`/all-student-name` before optimize
![/all-student-name table before optimize](https://media.discordapp.net/attachments/1216986392614142003/1217306581662957698/image.png?ex=66038c19&is=65f11719&hm=95f387ed851b238b772045789a7142d96c4fe8db6b6912aab442f6a3e6c31aa3&=&format=webp&quality=lossless&width=960&height=308)
![/all-student-name terminal before optimize](https://media.discordapp.net/attachments/1216986392614142003/1217306919136657499/image.png?ex=66038c69&is=65f11769&hm=a4549b3470302e7b43d9db7b5a87a5f99b90ac197bef1246dc194940b52b65d6&=&format=webp&quality=lossless&width=960&height=184)

---

`highest-gpa` before optimize
![/highest-gpa table before optimize](https://media.discordapp.net/attachments/1216986392614142003/1217307547414036611/image.png?ex=66038cff&is=65f117ff&hm=de64f1f4e5df6b875ffdbffdabddabdfb88b2f1307819690ce0a3a50f110b327&=&format=webp&quality=lossless&width=960&height=307)
![/highest-gpa terminal before optimize](https://media.discordapp.net/attachments/1216986392614142003/1217307770186108999/image.png?ex=66038d34&is=65f11834&hm=62206cdf522b7099dab686e46b16fe20f98d915dfbe01c2f2d7dab185c929cee&=&format=webp&quality=lossless&width=960&height=180)

---

after optimize `/all-student` peningkatan 50%
![/all-student table after optimize](https://media.discordapp.net/attachments/1216986392614142003/1217311080573964350/image.png?ex=6603904a&is=65f11b4a&hm=bfa7c6dd8dda8baaae6e6df392b2bf0a707f4b8170dd7b5edc5dcf96cf281d8d&=&format=webp&quality=lossless&width=550&height=175)
![/all-student terminal after optimize](https://media.discordapp.net/attachments/1216986392614142003/1217312098712031302/image.png?ex=6603913c&is=65f11c3c&hm=68db4bb21f9583ed09fbadb8336cf24835f812448bb467089a6b09f32e773102&=&format=webp&quality=lossless&width=960&height=182)

---

after optimize `/all-student-name` peningkatan ~20%
![/all-student-name table after optimize](https://media.discordapp.net/attachments/1216986392614142003/1217312359576768534/image.png?ex=6603917b&is=65f11c7b&hm=9761fb9c54eb3b904e59d6709d464cf16655e3cc5b87b84bc7163a03efadcb8b&=&format=webp&quality=lossless&width=960&height=307)
![/all-student-name terminal after optimize](https://media.discordapp.net/attachments/1216986392614142003/1217312710455332864/image.png?ex=660391ce&is=65f11cce&hm=08c384dbcd29c0e48d89f41aa9136faeb6ed85d8723f2a41561a1856be6a7977&=&format=webp&quality=lossless&width=960&height=181)

---

after optimize `/highest-gpa` tidak ada peningkatan yang signifikan
![/highest-gpa table after optimize](https://media.discordapp.net/attachments/1216986392614142003/1217312920313139210/image.png?ex=66039200&is=65f11d00&hm=1542b130e7700fa4e8b567831aed642724655a721c61f16a3396b2cfa2809418&=&format=webp&quality=lossless&width=960&height=307)
![/highest-gpa terminal after optimize](https://media.discordapp.net/attachments/1216986392614142003/1217313086525014058/image.png?ex=66039228&is=65f11d28&hm=b57e0259fd1e40ba3d182c2cb30eb028dd25a6872ab074db2df1a65fe144f993&=&format=webp&quality=lossless&width=960&height=179)

---

# Reflection

### 1. JMeter bisa membantu untuk menguji performa keseluruhan aplikasi kita. Sementara itu, profiler IntelliJ bisa berguna untuk melacak bagian aplikasi kita yang memakan waktu paling lama.
### 2. Proses pemrofilan dapat menemukan fungsi atau metode yang memerlukan waktu eksekusi yang lama, membantu kita mengenali bagian aplikasi yang butuh dioptimalkan atau direstrukturisasi.
### 3. Ya, dengan proses profiler kita bisa melihat seberapa banyak waktu yang dibutuhkan oleh setiap fungsi atau metode selama aplikasi dieksekusi secara keseluruhan.
### 4. Tantangannya memang dapat menjadi memahami penggunaan Profiler IntelliJ. Membaca dokumentasi dan menonton tutorial dapat membantu memahami cara penggunaannya dengan lebih baik.
### 5. Profiler IntelliJ memudahkan kita untuk melihat bagian kode yang memakan waktu paling lama karena hasil profilnya ditampilkan sejajar dengan kode.
### 6. Perbedaan antara output Profiler IntelliJ dan JMeter mungkin terjadi karena Profiler secara langsung memantau waktu eksekusi, sementara JMeter hanya menguji performa keseluruhan aplikasi.
### 7. Saya menggunakan metode parallelStream() untuk meningkatkan kecepatan program. Dengan bantuan Profiler IntelliJ, saya menemukan dan mengoptimalkan bagian program yang memakan waktu paling lama. Karena kurangnya unit test dalam aplikasi, saya memeriksa hasil sebelum dan setelah optimasi untuk memastikan fungsionalitas tetap terjaga.