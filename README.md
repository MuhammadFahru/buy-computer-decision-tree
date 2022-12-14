## College Assignment Needs

- NIM : 2108927
- Nama : Muhammad Fahru Rozi
- Kelas : Ilmu Komputer C1'21
- Mata Kuliah : Data Mining dan Warehouse

## Link Production

[fahru-decision-tree.herokuapp.com](https://fahru-decision-tree.herokuapp.com/)

## About The Project

Project ini merupakan aplikasi untuk memprediksi Buy Computer dengan menggunakan Algoritma Decision Tree. Untuk web framework nya saya menggunakan Flask sebagai kerangka kerja aplikasi dan tampilan untuk web nya. Agar bisa diakses semua orang saya menggunakan Heroku untuk deploy ke production.

## Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [Python](https://www.python.org/)
* [Buy Computer Dataset](https://www.kaggle.com/datasets/usman27/buy-computer)
* [Pandas](https://pandas.pydata.org/)
* [Scikit Learn](https://scikit-learn.org/stable/)
* [Flask](https://flask.palletsprojects.com/en/2.2.x/)
* [Heroku](https://www.heroku.com/)

## Getting Started

### Prerequisites

Sebelum menjalankan aplikasi ini pastikan Anda sudah memiliki atau sudah menginstall add-ons/plugins yang ada di atas.

### Installation

1. Clone the repo

   ```sh
   git clone https://github.com/MuhammadFahru/buy-computer-decision-tree.git
   ```

2. Change directory

   ```sh
   cd buy-computer-decision-tree
   ```

2. Run the project

   ```sh
   py app.py
   ```

## Deploy to Heroku

### Prerequisites

Sebelum melakukan deploy aplikasi pastikan Anda sudah memiliki atau sudah menginstall Heroku CLI.

### Installation

Dibawah ini merupakan langkah - langkah untuk deploy aplikasi menggunakan Heroku.

- Login ke dalam Heroku

   ```sh
   heroku login
   ```

- Install HTTP Server untuk Python

   ```sh
   pip install gunicorn
   ```

- Buat Procfile untuk menentukan perintah yang dijalankan pertama kali di Heroku

   ```sh
   touch Procfile
   ```

- Tambahkan keterangan aplikasi di Procfile

   ```sh
   web: gunicorn app:app
   ```

- Buat requirements yang akan digunakan di Heroku

   ```sh
   pip freeze > requirements.txt
   ```

- Hapus library/package yang tidak digunakan

- Buat repository

   ```sh
   git init
   ```

- Tambahkan file ke repository

   ```sh
   git add .
   ```

- Simpan perubahan

   ```sh
   git commit -m "Initial Commit"
   ```

- Login to Heroku

- Create new app

- Lakukan remote ke applikasi Heroku

   ```sh
   heroku git:remote -a [app_name]
   ```

- Push ke aplikasi Heroku

   ```sh
   git push heroku master
   ```