# Capstone-Project
# Title project
Sentiment & Issue Classification of Airline Tweets Using IBM Granite

# Project overview
Tujuan Proyek :
Menganalisis tweet pelanggan maskapai penerbangan untuk mengidentifikasi sentimen (positif, negatif, campuran) serta kategori masalah layanan (keterlambatan, pelayanan kasar, atau bagasi hilang). Hal ini bertujuan untuk memberikan insight strategis terhadap peningkatan layanan pelanggan maskapai.

Latar Belakang :
Industri penerbangan sangat bergantung pada reputasi dan kepuasan pelanggan. Media sosial seperti Twitter menjadi sarana utama bagi pelanggan untuk menyuarakan pengalaman mereka. Dengan memanfaatkan analisis berbasis AI terhadap data tweet, maskapai dapat lebih cepat memahami dan menanggapi masalah pelanggan.

Permasalahan :
Tweet pelanggan memiliki volume tinggi, ragam bahasa informal, serta subjektivitas tinggi, sehingga sulit untuk dianalisis secara manual.

Pendekatan :
Menggunakan model IBM Granite (granite-3.3-8b-instruct) untuk memproses dan mengklasifikasikan tweet berdasarkan sentimen dan isu utama. Model ini diakses melalui API Replicate dan diintegrasikan dalam pipeline Python.

# Raw dataset link
Link datasets : https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment

Link Google Colab : https://colab.research.google.com/drive/1n-UiulQry9NtY-46o_nKYnjus_LabjO-?usp=sharing

# Insight & findings
Temuan Utama :
Sentimen Negatif Mendominasi :
Mayoritas tweet berisi keluhan daripada pujian.
Sentimen negatif lebih tinggi pada maskapai tertentu (dapat diverifikasi dengan kolom airline).

Masalah Utama Pelanggan :
Delay (Keterlambatan): Dominan dan paling sering dikeluhkan.
Rude Service (Pelayanan Kasar): Sering muncul di tweet bernada negatif.
Lost Baggage (Bagasi Hilang): Umumnya berasosiasi dengan sentimen negatif atau campuran.

Sentimen Campuran :
Banyak pengguna menyisipkan keluhan dan pujian dalam satu tweet, menandakan kompleksitas dalam persepsi layanan pelanggan.

# AI support explanation
Peran AI (IBM Granite LLM) :
Text Understanding : Mengurai bahasa informal dan ekspresif dalam tweet.
Sentiment Classification : Menggunakan pemahaman kontekstual untuk menilai sentimen pelanggan.
Issue Tagging : Mengelompokkan keluhan dalam kategori Delay, Rude Service, dan Lost Baggage secara otomatis.

