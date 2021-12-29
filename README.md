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
Pre processing yang digunakan dalam project ini yaitu ekstrak file, split data, dan data augmentasi menggunakan image generator

### Modeling
Model data yang digunakan dalam project kali ini terdapat 4 model, yakni VGG19, VGG16, ResNet-50, dan InceptionResnetV2

![image](https://user-images.githubusercontent.com/92361807/147631690-cf1062ae-2f6f-4009-83e7-8718c2ee78e1.png)

![image](https://user-images.githubusercontent.com/92361807/147631742-5f7c5c6d-9e2b-4c73-8997-7d2afe4287af.png)

![image](https://user-images.githubusercontent.com/92361807/147631788-65430cce-4cf5-4a3f-8a9b-baacc9ba096e.png)

![image](https://user-images.githubusercontent.com/92361807/147631823-d6e2348a-d313-45b2-98b1-eb93c706f143.png)

## Overview Dataset
Jumlah dan persentase splitting dataset :
train (persentase, jumlah data train) 80%
validation (persentase, jumlah data validation) 10%
test (persentase, jumlah data test) 10%
