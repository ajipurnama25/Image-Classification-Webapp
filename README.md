# KLASIFIKASI PENYAKIT TANAMAN DENGAN CNN

## Deskripsi Dataset
Dalam pembuatan project ini, dataset yang kami gunakan merupakan dataset yang berupa daun padi yang didapatkan dari situs [kaggle.com](http://www.kaggle.com) yang berjudul [Rice Leaf Diseases Dataset](http://www.kaggle.com/vbookshelf/rice-leaf-diseases). Dataset ini berisi 120 gambar padi dan terdapat 3 kategori, yaitu Bacterial Leaf Blight, Brown Spot, dan Leaf Smut yang masing-masing terdapat 120 gambar bertipe .jpg

## Jurnal Referensi
Jurnal referensi yang digunakan dalam pembuatan project ini berjudul [Rice Leaf Diseases Prediction Using Deep Neural Networks with Transfer Learning](http://www.doi.org/10.1016/j.envres.2021.111275). Krishnamoorthy N., L.V. Narasimha Prasad, C.S. Pavan Kumar, Bharat Subedi, Haftom Baraki Abraha, Sathishkumar V.E.

## Author
Kontributor dalam pengerjaan project ini adalah
1. M. Aji Purnama Wibowo [ajipurnama25@gmail.com](http://www.gmail.com)
2. Auliya Tara SL [auliyatara11@gmail.com](http://www.gmail.com)

### Pre-Processing
Pre processing yang digunakan dalam project ini yaitu ekstrak file, split data, dan data augmentasi menggunakan image data generator

### Modeling
Model data yang digunakan dalam project kali ini adalah model CNN biasa yang terdapat 4 layer

![image](https://user-images.githubusercontent.com/92361807/147632286-fe9bbcfc-ad09-44cc-a992-a86a9fae64d6.png)

## Overview Dataset
Jumlah persentase dalam proses splitting dataset kali ini adalah train data 80%, validation data 10%, dan test data 10%
