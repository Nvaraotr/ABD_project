# 🎶 **Analisis Popularitas Musik Spotify** 🎶

Analisis Big Data A
Ardhika Yoga Pratama (202110370311458)
Romadhon Wiratama (202110370311471)

![Spotify](assets/Music.jpg)

## 💻 **Project Overview** 💻

Tersebarnya COVID-19 ke seluruh dunia pada awal 2020 mengakibatkan banyak aktivitas masyarakat yang terhambat demi mengurangi penyebaran virus tersebut. Mulai dari anak-anak yang bersekolah hingga orang dewasa yang bekerja terpaksa harus dilaksanakan di rumah. Hal ini menyebabkan banyak masyarakat yang merasa jenuh karena tidak dapat beraktivitas di luar rumah. Oleh karena itu, banyak warga yang mencari hiburan tanpa perlu keluar rumah salah satunya seperti mendengarkan lagu/musik. Musik adalah bagian integral dari kehidupan manusia. Dengan hadirnya platform streaming seperti Spotify, perilaku konsumsi musik telah berubah secara signifikan. Namun, pemahaman yang mendalam tentang bagaimana elemen-elemen musik tertentu, seperti popularitas, genre, atau karakteristik audio, mempengaruhi preferensi pengguna seringkali kurang dimanfaatkan. Sehingga, kami akan melakukan analisa mengenai selera musik masyarakat pada awal pandemi COVID-19.
Pendekatan yang kami usulkan untuk mengatasi masalah ini yaitu lakukan data cleaning terlebih dahulu, melihat statistik data, bisa dilanjutkan dengan melihat distribusi fitur, dan korelasi antar fitur.

Analisis ini diharapkan dapat membantu konsumen seperti kreator playlist agar dapat memahami tren musik yang populer sehingga playlist yang dibuat dapat membantu banyak pengguna Spotify mengatasi kejenuhan bukan hanya saat pandemi tetapi pada setiap saat. Selain itu, hasil ini juga relevan bagi musisi yang ingin membuat lagu agar sesuai dengan preferensi dan permintaan dari para penikmat lagu.
Dataset yang digunakan bersumber dari Spotify yang didapatkan dengan package spotifyr oleh Kaylin Pavlik dari 6 kategori/genre lagu yaitu EDM, Latin, Pop, R&B, Rap, & Rock. Dataset tersebut berisi 23 fitur dan 5000 lagu.

## 📦 **Package** 📦

```bash
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
import plotly.graph_objects as go
import plotly.express as px

from sklearn.preprocessing import MinMaxScaler
from sklearn.decomposition import PCA
from sklearn.linear_model import LinearRegression
```

## 🦕 **Project Preparation** 🦖

- Dataset yang digunakan: [Spotify](https://github.com/rfordatascience/tidytuesday/tree/main/data/2020/2020-01-21)
- Project repository: [Repo_ABD](https://github.com/Nvaraotr/ABD_project)
- Running the project:
```bash
# Sebelum menjalankan source code, harap cloning atau download datasetnya terlebih dahulu
!git clone https://github.com/Nvaraotr/ABD_project.git
```
