# Alat-Penyortir-Warna
Alat penyortir warna merupakan alat penyortir barang/ benda berdasarkan warnanya
Alat Penyortir warna
![26da6b8d-ef2a-47fd-a6ad-4090e1ba9293](https://user-images.githubusercontent.com/122527825/212050116-3617b652-adef-4980-9c3c-7cc88b25e549.jpg)
![31f0b5b5-b3a0-4b49-9583-4d3dd6f24710](https://user-images.githubusercontent.com/122527825/212050169-ae142d58-3afe-4900-8d99-f220c2cb1a2c.jpg)
Pemilah barang/benda jamak dilakukan di industri. Pemilahan barang dapat dilakukan
dengan mengelompokkan jenis, warna, atau bentuk barang. Sistem pemilahan dapat dilakukan
dengan sistem manual menggunakan tenaga manusia, sistem barcode, ataupun otomatisasi dengan
mesin.
Sistem pemilahan berdasarkan warna merupakan hal yang dapat dikembangkan dengan
berbagai metode. Untuk pendeteksian warna dapat memanfaatkan pantulan cahaya yang
dipantulkan oleh benda yang terpapar cahaya putih. Dengan pemanfaatan pemantulan cahaya ini,
deteksi warna suatu benda dapat dilakukan dengan sebuah alat yang bisa menangkap pantulan
cahaya dan mendefinisikan warna yang ditangkap

Alat dan bahan : Arduino uno ,motor servo sg 90,sensor waarna TCS320

Digram alir

![8a6e511a-6481-4bdc-a6c6-4dfe5cb2f53c](https://user-images.githubusercontent.com/122527825/212051704-9e8e2b72-49b4-4a79-97be-d2538848835a.jpg)

Diagram skematik

![image](https://user-images.githubusercontent.com/122527825/212051926-5365f466-38f2-4046-9745-3fedfbcd5851.png)

Cara Kerja
Alat ini bekerja untuk menyortir benda/ barang berdasarkan warna. Pertama, servo 1 bergerak menggeser benda ke bawah sensor. Kemudian sensor membaca warna benda untuk menggerakkan servo 2 sehingga benda akan diarahkan ke dalam wadah yang berbeda berdasarkan warna yang terdeteksi. Jika terdeteksi warna coklat maka servo akan bergerak sebesar 50° dan warna biru 100°. Proses ini berulang untuk benda selanjutnya.
