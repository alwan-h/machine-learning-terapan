Laporan Proyek Machine Learning - Alwan Hasmadi

# Project Overview

Sistem pemberi rekomendasi atau sistem rekomendasi adalah subkelas dari sistem penyaringan informasi yang memberikan saran untuk item yang paling *relevan* dengan pengguna tertentu. [1] [2] Biasanya, saran mengacu pada berbagai proses pengambilan keputusan, seperti produk apa yang akan dibeli, musik apa yang akan didengarkan, atau berita online apa yang akan dibaca. [1] Sistem rekomendasi sangat berguna ketika seseorang perlu memilih item dari jumlah item yang mungkin ditawarkan oleh suatu layanan. [1] [3]

Sistem pemberi rekomendasi digunakan di berbagai area, dengan contoh umum yang dikenal dalam bentuk generator daftar putar untuk layanan video dan musik, pemberi rekomendasi produk untuk toko online, atau pemberi rekomendasi konten untuk *platform* media sosial dan pemberi rekomendasi konten web terbuka. [4] [5] Sistem ini dapat beroperasi menggunakan satu input, seperti musik, atau beberapa input di dalam dan lintas platform seperti berita, buku, dan permintaan pencarian. Ada juga sistem rekomendasi populer untuk topik tertentu seperti restoran dan kencan online . Sistem pemberi rekomendasi juga telah dikembangkan untuk mengeksplorasi artikel penelitian dan pakar, [6] kolaborator, [7] dan jasa keuangan. [8]

Banyaknya film yang telah diproduksi dari berbagai kategori seperti drama, komedi, horor, dan lain-lain menyebabkan penonton memiliki banyak pilihan film yang akan ditonton. Sistem rekomendasi merupakan sebuah sistem komputer yang membantu membuat suatu keputusan dengan memberikan saran kepada pengguna melalui pemrosesan data pada sistem. Dengan adanya pemanfaatan teknologi informasi dibutuhkan suatu sistem yang memudahkan penonton dalam memilih film yang ditonton. Tujuan dari kajian ini yaitu merancang sebuah sistem rekomendasi film bagi kalangan konsumen perfilman. [9]

# *Business Understanding*

Beberapa tujuan dan fungsi sistem rekomendasi secara umum adalah sebagai berikut:

- Meningkatkan jumlah item yang terjual.
Salah satu tujuan paling penting dari sistem rekomendasi di bidang komersial adalah meningkatkan jumlah item yang terjual. Tujuan ini bisa dicapai karena item yang direkomendasikan biasanya merupakan barang yang memang dibutuhkan oleh pengguna. Sementara itu, di bidang non-komersial peningkatan yang diharapkan dari sistem rekomendasi antara lain, *conversion rate*, click rate, dan jumlah kunjungan.

- Menjual item yang beragam.
Sistem rekomendasi memungkinkan pengguna untuk menemukan item yang sulit dicari. Sebagai contoh, organisasi atau bisnis tentu ingin mempromosikan semua item yang dimilikinya, tidak hanya item yang populer saja. Item non-populer seperti ini kadang tidak muncul di beranda item best-seller. Nah, organisasi atau bisnis bisa merekomendasikan item tersebut pada pengguna yang tepat. Dengan cara ini, item yang dijual pun tidak melulu item populer, melainkan lebih beragam.

- Meningkatkan kepuasan pengguna.
Sistem rekomendasi yang dirancang dengan baik dapat meningkatkan pengalaman pengguna saat menggunakan situs atau aplikasi. Pengguna akan menemukan rekomendasi yang menarik dan relevan. Kombinasi antara rekomendasi yang efektif dan akurat serta *user-interface* yang dirancang dengan baik akan meningkatkan kepuasan pengguna terhadap sistem. Sehingga, tingkat kemungkinan untuk rekomendasi tersebut diterima oleh pengguna juga semakin meningkat.

- Pemahaman yang lebih baik tentang preferensi pengguna
Deskripsi preferensi pengguna yang dikumpulkan secara eksplisit atau diprediksi oleh sistem dapat dimanfaatkan untuk berbagai aplikasi dan tujuan lain. Sebagai contoh, untuk meningkatkan pengelolaan stok barang atau items atau untuk mengiklankan promo tertentu pada sektor pengguna baru.

### Problem Statements (pernyataan masalah)
  - Berdasarkan data pengguna, Bagaimana membuat sistem rekomendasi yang dipersonalisasi, sehingga dapat meningkatkan kepuasan pengguna
  - Dengan data rating yang dimiliki, bagaimana caranya dapat merekomendasikan filem lain yang mungkin disukai dan belum pernah ditonton oleh pengguna. sehinnga dapat miningkatkan jumlah film yang terjual.

### Goals (tujuan)
  - Menghasilkan sejumlah rekomendasi film yang dipersonalisasi untuk pengguna dengan merekomendasikan film serupa yang pernah disukai atau ditonton dimasa lalu atau sedang ditonton dimasa kini.
  - Menghasilkan sejumlah rekomendasi film yang sesuai dengan preferensi pengguna dan belum pernah dikunjungi sebelumnya.

### Solution Approach
  - Solusi untuk dapat merekomendasikan pengguna yang dipersonalisasi dengan merekomendasikan film serupa yang pernah disukai atau ditonton dengan menggunakan tekink Content Based Filtering.
  - Solusi untuk menghasilkan sejumlah rekomendasi film yang sesuai dengan prefrensi pengguna dan belum pernah dikunjungi sebelumnya dengan menggunakan teknik Collaborative Filtering.

# Data Understanding
Data ini terdiri dari beberapa file yaitu :
- movies.csv : berisi data movieId, title dan genres, berjumlah 9742 data
- ratings.csv : berisi data userId, movieId, rating dan timestamp berjumlah 9742 data
- tags.csv : berisi data userId, movieId, tag dan timestamp, yang berjumlah 1572 data
- links.csv : berisi data movieId, imdbId dan tmdbId, berjumlah 9742 data



    Jumlah data movies  9742
    Jumlah data ratings  9724
    Jumlah data tags  1572
    Jumlah data links  9742


### Univariate Exploratory Data Analysis
Variabel - variabel pada MovieLens Latest small dataset adalah sebagai berikut :

- movies.csv
  - movieId : merpakan id dari data movie
  - title : merupakan title dari data movie
  - genres : merupakan genres dari data movie

- ratings.csv
  - userId : merpakan id data ratings
  - movieId : merupakan id refresni untuk data movies
  - rating : merupakan jumlah rating
  - timestamp : merupakan keterangan waktu

- tags.csv
  - userId : merupakan id refrensi untuk data ratings
  - movieId : merupakan id refrensi untuk data movies
  - tag : merupakan nama tag
  - timestamp : merupakan keterangan waktu

- links.csv
  - movieId : merupakan id refrensi untuk data movie
  - imdbId : merupakan id imdb movie
  - tmdbId : merupakan id tmdb mobie

#### Movies


```python
movies.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 9742 entries, 0 to 9741
    Data columns (total 3 columns):
     #   Column   Non-Null Count  Dtype 
    ---  ------   --------------  ----- 
     0   movieId  9742 non-null   int64 
     1   title    9742 non-null   object
     2   genres   9742 non-null   object
    dtypes: int64(1), object(2)
    memory usage: 228.5+ KB


#### Ratings


```python
ratings.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 100836 entries, 0 to 100835
    Data columns (total 4 columns):
     #   Column     Non-Null Count   Dtype  
    ---  ------     --------------   -----  
     0   userId     100836 non-null  int64  
     1   movieId    100836 non-null  int64  
     2   rating     100836 non-null  float64
     3   timestamp  100836 non-null  int64  
    dtypes: float64(1), int64(3)
    memory usage: 3.1 MB


#### Links


```python
links.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 9742 entries, 0 to 9741
    Data columns (total 3 columns):
     #   Column   Non-Null Count  Dtype  
    ---  ------   --------------  -----  
     0   movieId  9742 non-null   int64  
     1   imdbId   9742 non-null   int64  
     2   tmdbId   9734 non-null   float64
    dtypes: float64(1), int64(2)
    memory usage: 228.5 KB


#### Tags


```python
tags.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 3683 entries, 0 to 3682
    Data columns (total 4 columns):
     #   Column     Non-Null Count  Dtype 
    ---  ------     --------------  ----- 
     0   userId     3683 non-null   int64 
     1   movieId    3683 non-null   int64 
     2   tag        3683 non-null   object
     3   timestamp  3683 non-null   int64 
    dtypes: int64(3), object(1)
    memory usage: 115.2+ KB


Tabel 1. Daftar data ratings yang ada dalam dataset ratings.csv

|   #     | userId | movieId | rating | timestamp |
|--------|---------|--------|-----------|------------
| 0      | 1       | 1      | 4.0       | 964982703  |
| 1      | 1       | 3      | 4.0       | 964981247  |
| 2      | 1       | 6      | 4.0       | 964982224  |
| 3      | 1       | 47     | 5.0       | 964983815  |
| 4      | 1       | 50     | 5.0       | 964982931  |
| ...    | ...     | ...    | ...       | ...        |
| 100831 | 610     | 166534 | 4.0       | 1493848402 |
| 100832 | 610     | 168248 | 5.0       | 1493850091 |
| 100833 | 610     | 168250 | 5.0       | 1494273047 |
| 100834 | 610     | 168252 | 5.0       | 1493846352 |
| 100835 | 610     | 170875 | 3.0       | 1493846415 |

100836 rows × 4 columns

Dari tabel 1 dapat dilihat bahwa rating terdiri dari 4 kolom antara lain : 
- userId : identitas pengguna
- movieId : identitas movie
- rating : data rating movie
- timestamp : data waktu rating



#### Data movies

Table 2. Daftar movie yang ada dalam dataset movies.csv

| #       | movieId | title  | genres                                    |
|---------|--------|-------------------------------------------|---------------------|
| 0       | 1      | Toy Story (1995)                          | Adventure,Animation|Children|Comedy|Fantasy |
| 1       | 2      | Jumanji (1995)                            | Adventure,Children|Fantasy                  |
| 2       | 3      | Grumpier Old Men (1995)                   | Comedy|Romance                              |
| 3       | 4      | Waiting to Exhale (1995)                  | Comedy,Drama|Romance                        |
| 4       | 5      | Father of the Bride Part II (1995)        | Comedy                                      |
| ...     | ...    | ...                                       | ...                                         |
| 9737    | 193581 | Black Butler: Book of the Atlantic (2017) | Action,Animation|Comedy|Fantasy             |
| 9738    | 193583 | No Game No Life: Zero (2017)              | Animation,Comedy|Fantasy                    |
| 9739    | 193585 | Flint (2017)                              | Drama                                       |
| 9740    | 193587 | Bungo Stray Dogs: Dead Apple (2018)       | Action|Animation                            |
| 9741    | 193609 | Andrew Dice Clay: Dice Rules (1991)       | Comedy                                      |

9742 rows × 3 columns



#### Data ratings

Tabel 3. Daftar data ratings yang ada dalam dataset ratings.csv

|# | userId | movieId | rating | timestamp |
|--------|---------|--------|-----------|------------|
| 0      | 1       | 1      | 4.0       | 964982703  |
| 1      | 1       | 3      | 4.0       | 964981247  |
| 2      | 1       | 6      | 4.0       | 964982224  |
| 3      | 1       | 47     | 5.0       | 964983815  |
| 4      | 1       | 50     | 5.0       | 964982931  |
| ...    | ...     | ...    | ...       | ...        |
| 100831 | 610     | 166534 | 4.0       | 1493848402 |
| 100832 | 610     | 168248 | 5.0       | 1493850091 |
| 100833 | 610     | 168250 | 5.0       | 1494273047 |
| 100834 | 610     | 168252 | 5.0       | 1493846352 |
| 100835 | 610     | 170875 | 3.0       | 1493846415 |

100836 rows × 4 columns

#### Data Links


Tabel 4. Daftar data links yand ada dalam dataset links.csv


| # | movieId | imdbId | tmdbId  |
|---------|--------|---------|----------|
| 0       | 1      | 114709  | 862.0    |
| 1       | 2      | 113497  | 8844.0   |
| 2       | 3      | 113228  | 15602.0  |
| 3       | 4      | 114885  | 31357.0  |
| 4       | 5      | 113041  | 11862.0  |
| ...     | ...    | ...     | ...      |
| 9737    | 193581 | 5476944 | 432131.0 |
| 9738    | 193583 | 5914996 | 445030.0 |
| 9739    | 193585 | 6397426 | 479308.0 |
| 9740    | 193587 | 8391976 | 483455.0 |
| 9741    | 193609 | 101726  | 37891.0  |

9742 rows × 3 columns


#### Data Tags

Tabel 5. Daftar data tags yang ada dalam dataset tags.csv


| # | userId | movieId | tag    | timestamp        |
|--------|---------|--------|------------------|------------|
| 0      | 2       | 60756  | funny            | 1445714994 |
| 1      | 2       | 60756  | Highly quotable  | 1445714996 |
| 2      | 2       | 60756  | will ferrell     | 1445714992 |
| 3      | 2       | 89774  | Boxing story     | 1445715207 |
| 4      | 2       | 89774  | MMA              | 1445715200 |
| ...    | ...     | ...    | ...              | ...        |
| 3678   | 606     | 7382   | for katie        | 1171234019 |
| 3679   | 606     | 7936   | austere          | 1173392334 |
| 3680   | 610     | 3265   | gun fu           | 1493843984 |
| 3681   | 610     | 3265   | heroic bloodshed | 1493843978 |
| 3682   | 610     | 168248 | Heroic Bloodshed | 1493844270 |

3683 rows × 4 columns


Tabel 6. Data describe ratings

| #      | userId | movieId       | rating        | timestamp     |
|--------|---------------|---------------|---------------|--------------|
| count  | 100836.000000 | 100836.000000 | 100836.000000 | 1.008360e+05 |
| mean   | 326.127564    | 19435.295718  | 3.501557      | 1.205946e+09 |
| std    | 182.618491    | 35530.987199  | 1.042529      | 2.162610e+08 |
| min    | 1.000000      | 1.000000      | 0.500000      | 8.281246e+08 |
| 25%    | 177.000000    | 1199.000000   | 3.000000      | 1.019124e+09 |
| 50%    | 325.000000    | 2991.000000   | 3.500000      | 1.186087e+09 |
| 75%    | 477.000000    | 8122.000000   | 4.000000      | 1.435994e+09 |
| max    | 610.000000    | 193609.000000 | 5.000000      | 1.537799e+09 |

Dari tabel 6 dapa dilihat bahwa nilai maksimum rating adalah 5 dan nilai minimum rating adalah 0. Artinya, skala rating antara 1 sampai 5.

Jumlah userId:  610
Jumlah movieId:  9742
Jumlah data rating:  100836


# Data Processing

#### Mengetahui jumlah seluruh movie

    Jumlah seluruh data movies berdasarkan movieId:  9742


#### Mengetahui jumlah seluruh user berdasarkan rating

    Jumlah seluruh data users berdasarkan userId:  610


### Menggabungkan data movie


Tabel 7. Data gabungan movie

| # | userId | movieId | rating | timestamp | title      | genres                         |
|--------|---------|--------|-----------|------------|--------------------------------|--------------------|
| 0      | 1       | 1      | 4.0       | 964982703  | Toy Story (1995)               | Adventure,Animation,Children,Comedy,Fantasy |
| 1      | 1       | 1      | 4.0       | 964982703  | NaN                            | NaN                                         |
| 2      | 1       | 3      | 4.0       | 964981247  | Grumpier Old Men (1995)        | Comedy,Romance                              |
| 3      | 1       | 3      | 4.0       | 964981247  | NaN                            | NaN                                         |
| 4      | 1       | 6      | 4.0       | 964982224  | Heat (1995)                    | Action,Crime,Thriller                       |
| ...    | ...     | ...    | ...       | ...        | ...                            | ...                                         |
| 201667 | 610     | 168250 | 5.0       | 1494273047 | NaN                            | NaN                                         |
| 201668 | 610     | 168252 | 5.0       | 1493846352 | Logan (2017)                   | Action,Sci-Fi                               |
| 201669 | 610     | 168252 | 5.0       | 1493846352 | NaN                            | NaN                                         |
| 201670 | 610     | 170875 | 3.0       | 1493846415 | The Fate of the Furious (2017) | Action,Crime,Drama,Thriller                 |
| 201671 | 610     | 170875 | 3.0       | 1493846415 | NaN                            | NaN                                         |

201672 rows × 6 columns



Missing value data movie


Tabel 8. Data missing value dari data movie

    | Nama          | Value  |
    |---------------|--------|
    | userId        |    0   |
    | movieId       |    0   |
    | rating        |    0   |
    | timestamp     |    0   |
    | title         | 100836 |
    | genres        | 100836 |
    
Dari tabel 8 dapat dilihat jumlah missing value dari fitur masing-masing fitur


Menghitung jumlah rating berdasarkan movieId

Tabel 9. Jumlah rating berdasarkan movieId

| movieId | userId  | rating | timestamp |
|---------|--------|-----------|--------------|
| 1       | 131808 | 1686.0    | 485828910958 |
| 2       | 72502  | 755.0     | 249877166644 |
| 3       | 29494  | 339.0     | 104531468772 |
| 4       | 3078   | 33.0      | 12580104096  |
| 5       | 29358  | 301.0     | 97281105188  |
| ...     | ...    | ...       | ...          |
| 193581  | 368    | 8.0       | 3074218164   |
| 193583  | 368    | 7.0       | 3074219090   |
| 193585  | 368    | 7.0       | 3074219610   |
| 193587  | 368    | 7.0       | 3074220042   |
| 193609  | 662    | 8.0       | 3074315212   |

9724 rows × 3 columns


Tabel 10. Data gabungan movie

| # | userId | movieId | rating | timestamp | title      | genres                         |
|--------|---------|--------|-----------|------------|--------------------------------|---------|
| 0      | 1       | 1      | 4.0       | 964982703  | Toy Story (1995)               | Adventure,Animation,Children,Comedy,Fantasy |
| 1      | 1       | 1      | 4.0       | 964982703  | NaN                            | NaN                                         |
| 2      | 1       | 3      | 4.0       | 964981247  | Grumpier Old Men (1995)        | Comedy,Romance                              |
| 3      | 1       | 3      | 4.0       | 964981247  | NaN                            | NaN                                         |
| 4      | 1       | 6      | 4.0       | 964982224  | Heat (1995)                    | Action,Crime|Thriller                       |
| ...    | ...     | ...    | ...       | ...        | ...                            | ...                                         |
| 201667 | 610     | 168250 | 5.0       | 1494273047 | NaN                            | NaN                                         |
| 201668 | 610     | 168252 | 5.0       | 1493846352 | Logan (2017)                   | Action,Sci-Fi                               |
| 201669 | 610     | 168252 | 5.0       | 1493846352 | NaN                            | NaN                                         |
| 201670 | 610     | 170875 | 3.0       | 1493846415 | The Fate of the Furious (2017) | Action,Crime,Drama,Thriller                 |
| 201671 | 610     | 170875 | 3.0       | 1493846415 | NaN                            | NaN                                         |

201672 rows × 6 columns

Data pada tabel 10 merupakan data yang akan digunakan untuk membuat sistem rekomendasi



# Data Preparation
### Mengatasi Missing Value


Cek missing value


    userId            0
    movieId           0
    rating            0
    timestamp         0
    title        100836
    genres       100836
    dtype: int64



Tabel 11. Data movie yang sudah di bersihkan dari data null


| # | userId | movieId | rating | timestamp | title      | genres                         |
|--------|---------|--------|-----------|------------|--------------------------------|-----|
| 0      | 1       | 1      | 4.0       | 964982703  | Toy Story (1995)               | Adventure,Animation,Children,Comedy,Fantasy |
| 2      | 1       | 3      | 4.0       | 964981247  | Grumpier Old Men (1995)        | Comedy|Romance                              |
| 4      | 1       | 6      | 4.0       | 964982224  | Heat (1995)                    | Action|Crime|Thriller                       |
| 6      | 1       | 47     | 5.0       | 964983815  | Seven (a.k.a. Se7en) (1995)    | Mystery|Thriller                            |
| 8      | 1       | 50     | 5.0       | 964982931  | Usual Suspects, The (1995)     | Crime|Mystery|Thriller                      |
| ...    | ...     | ...    | ...       | ...        | ...                            | ...                                         |
| 201662 | 610     | 166534 | 4.0       | 1493848402 | Split (2017)                   | Drama|Horror|Thriller                       |
| 201664 | 610     | 168248 | 5.0       | 1493850091 | John Wick: Chapter Two (2017)  | Action|Crime|Thriller                       |
| 201666 | 610     | 168250 | 5.0       | 1494273047 | Get Out (2017)                 | Horror                                      |
| 201668 | 610     | 168252 | 5.0       | 1493846352 | Logan (2017)                   | Action|Sci-Fi                               |
| 201670 | 610     | 170875 | 3.0       | 1493846415 | The Fate of the Furious (2017) | Action,Crime,Drama,Thriller                 |

100836 rows × 6 columns

Pada tabel 11 merupakan data yang movie yang nilai nullnya sudah dihilangkan


Tabel 12. Data movie dengan fitur genre yang kompleks

| # | userId | movieId | rating | timestamp | title      | genres                                    |
|--------|---------|--------|-----------|------------|-------------------------------------------|---------|
| 0      | 1       | 1      | 4.0       | 964982703  | Toy Story (1995)                          | Adventure,Animation|Children|Comedy|Fantasy |
| 163062 | 517     | 1      | 4.0       | 1487954343 | Toy Story (1995)                          | Adventure|Animation|Children|Comedy|Fantasy |
| 61034  | 213     | 1      | 3.5       | 1316196157 | Toy Story (1995)                          | Adventure|Animation|Children|Comedy|Fantasy |
| 162164 | 514     | 1      | 4.0       | 1533872400 | Toy Story (1995)                          | Adventure|Animation|Children|Comedy|Fantasy |
| 61202  | 214     | 1      | 3.0       | 853937855  | Toy Story (1995)                          | Adventure|Animation|Children|Comedy|Fantasy |
| ...    | ...     | ...    | ...       | ...        | ...                                       | ...                                         |
| 54512  | 184     | 193581 | 4.0       | 1537109082 | Black Butler: Book of the Atlantic (2017) | Action|Animation|Comedy|Fantasy             |
| 54514  | 184     | 193583 | 3.5       | 1537109545 | No Game No Life: Zero (2017)              | Animation|Comedy|Fantasy                    |
| 54516  | 184     | 193585 | 3.5       | 1537109805 | Flint (2017)                              | Drama                                       |
| 54518  | 184     | 193587 | 3.5       | 1537110021 | Bungo Stray Dogs: Dead Apple (2018)       | Action|Animation                            |
| 102724 | 331     | 193609 | 4.0       | 1537157606 | Andrew Dice Clay: Dice Rules (1991)       | Comedy                                      |

100836 rows × 6 columns



 Jumlah data movie   9724



Daftar array genre movie yang unik

    array(['Adventure|Animation|Children|Comedy|Fantasy',
           'Adventure|Children|Fantasy', 'Comedy|Romance',
           'Comedy|Drama|Romance', 'Comedy', 'Action|Crime|Thriller',
           'Adventure|Children', 'Action', 'Action|Adventure|Thriller',
           'Comedy|Horror', 'Adventure|Animation|Children', 'Drama',
           'Action|Adventure|Romance', 'Crime|Drama', 'Drama|Romance',
           'Action|Comedy|Crime|Drama|Thriller', 'Comedy|Crime|Thriller',
           'Crime|Drama|Horror|Mystery|Thriller', 'Drama|Sci-Fi',
           'Children|Drama', 'Adventure|Drama|Fantasy|Mystery|Sci-Fi',
           'Mystery|Sci-Fi|Thriller', 'Children|Comedy', 'Drama|War',
           'Action|Crime|Drama', 'Action|Adventure|Fantasy',
           'Comedy|Drama|Thriller', 'Mystery|Thriller',
           'Animation|Children|Drama|Musical|Romance',
           'Crime|Mystery|Thriller', 'Adventure|Drama', 'Drama|Thriller',
           'Comedy|Crime', 'Action|Sci-Fi|Thriller',
           'Action|Comedy|Horror|Thriller', 'Comedy|Drama', 'Documentary',
           'Action|Crime|Drama|Thriller', 'Crime|Drama|Romance',
           'Action|Adventure|Drama', 'Action|Thriller',
           'Drama|Horror|Thriller', 'Comedy|Horror|Romance',
           'Adventure|Comedy|Crime|Romance',
           'Adventure|Children|Comedy|Musical', 'Action|Drama|War',
           'Crime|Drama|Thriller', 'Action|Adventure|Comedy|Crime',
           'Drama|Mystery', 'Drama|Mystery|Romance', 'Thriller',
           'Adventure|Drama|IMAX', 'Action|Drama|Romance|War', 'Drama|Horror',
           'Adventure|Drama|War', 'Comedy|War', 'Crime|Drama|Mystery',
           'Action|Adventure|Mystery|Sci-Fi', 'Drama|Thriller|War',
           'Action|Romance|Western', 'Crime|Film-Noir|Mystery|Thriller',
           'Comedy|Crime|Drama', 'Action|Drama|Romance',
           'Adventure|Children|Drama', 'Action|Adventure|Crime|Thriller',
           'Action|Crime|Sci-Fi', 'Horror', 'Action|Children',
           'Comedy|Horror|Thriller', 'Fantasy|Horror|Mystery',
           'Comedy|Fantasy', 'Horror|Sci-Fi',
           'Action|Crime|Drama|Mystery|Sci-Fi|Thriller',
           'Drama|Musical|Romance', 'Drama|Fantasy',
           'Action|Adventure|Sci-Fi', 'Western',
           'Adventure|Comedy|Crime|Mystery', 'Adventure|Comedy',
           'Action|Comedy|Romance', 'Animation|Children|Comedy|Romance',
           'Drama|Musical', 'Children|Comedy|Fantasy', 'Comedy|Sci-Fi',
           'Adventure|Children|Comedy|Fantasy|Romance',
           'Drama|Fantasy|Romance', 'Drama|Romance|War|Western',
           'Drama|Horror|Sci-Fi', 'Action|Crime',
           'Action|Drama|Sci-Fi|Thriller', 'Comedy|Crime|Drama|Thriller',
           'Action|Thriller|Western', 'Horror|Thriller', 'Animation|Children',
           'Children|Drama|Fantasy|Mystery', 'Action|Drama|Thriller',
           'Comedy|Drama|Fantasy', 'Film-Noir|Thriller',
           'Action|Comedy|Sci-Fi', 'Adventure|Drama|Sci-Fi',
           'Action|Crime|Horror', 'Children', 'Drama|Film-Noir|Romance',
           'Drama|Mystery|Thriller', 'Action|Crime|Fantasy|Thriller',
           'Comedy|Drama|Romance|War', 'Action|Comedy',
           'Adventure|Children|Romance',
           'Adventure|Animation|Children|Drama|Musical|IMAX',
           'Drama|Horror|Mystery|Thriller', 'Action|Comedy|Crime|Fantasy',
           'Adventure|Comedy|Western', 'Action|Romance|Thriller',
           'Action|Adventure|Comedy|Romance|Thriller',
           'Drama|Horror|Romance|Thriller', 'Drama|Romance|War',
           'Action|Fantasy', 'Comedy|Thriller',
           'Action|Comedy|Crime|Thriller', 'Horror|Sci-Fi|Thriller',
           'Drama|Mystery|Romance|Thriller', 'Action|Comedy|Drama',
           'Drama|Western', 'Action|Adventure|Crime|Drama|Romance|Thriller',
           'Action|Comedy|War', 'Action|Adventure|Sci-Fi|Thriller',
           'Action|Adventure|Comedy|Fantasy', 'Comedy|Western',
           'Comedy|Mystery', 'Comedy|Drama|Romance|Thriller',
           'Action|Children|Romance', 'Action|Drama|Sci-Fi', 'Action|Drama',
           'Comedy|Mystery|Romance', 'Action|Drama|Mystery',
           'Action|Crime|Drama|Sci-Fi|Thriller', 'Crime|Thriller',
           'Comedy|Crime|Horror', 'Action|Adventure|Fantasy|Mystery',
           'Comedy|Romance|Thriller',
           'Action|Adventure|Children|Comedy|Fantasy|Sci-Fi',
           'Action|Mystery|Thriller', 'Animation|Children|Fantasy|Musical',
           'Action|Adventure|Comedy|Romance', 'Action|Drama|Western',
           'Action|Adventure|Animation|Children|Fantasy',
           'Comedy|Drama|Fantasy|Romance|Thriller',
           'Adventure|Animation|Children|Comedy|Musical', 'Action|Sci-Fi',
           'Adventure|Drama|Western', 'Crime|Horror|Thriller',
           'Animation|Children|Drama|Fantasy|Musical',
           'Animation|Children|Fantasy|Musical|Romance|IMAX',
           'Adventure|Western', 'Action|Comedy|Crime', 'Fantasy|Horror',
           'Action|Adventure|Animation|Horror|Sci-Fi', 'Action|Horror|Sci-Fi',
           'Crime|Drama|Mystery|Thriller',
           'Adventure|Animation|Children|Fantasy|Musical|Romance', 'Romance',
           'Action|Crime|Drama|War', 'Action|Adventure|Mystery|Thriller',
           'Adventure|Animation|Children|Fantasy|Musical', 'Comedy|Drama|War',
           'Adventure|Animation|Children|Comedy|Fantasy|Sci-Fi',
           'Adventure|Comedy|Sci-Fi', 'Drama|Mystery|Romance|Sci-Fi|Thriller',
           'Action|Adventure|Comedy|War', 'Action|Adventure',
           'Drama|Mystery|Western', 'Comedy|Fantasy|Sci-Fi',
           'Adventure|Animation|Comedy', 'Drama|Fantasy|Horror|Thriller',
           'Action|Adventure|Romance|Thriller', 'Animation|Sci-Fi',
           'Animation|Children|Comedy', 'Horror|Mystery',
           'Comedy|Fantasy|Romance|Sci-Fi', 'Action|Adventure|Drama|Thriller',
           'Comedy|Fantasy|Musical', 'Crime|Drama|Romance|Thriller',
           'Crime|Drama|Musical|Thriller', 'Sci-Fi|Thriller',
           'Children|Drama|Fantasy', 'Adventure|Animation|Children|Musical',
           'Adventure|Drama|Romance|War', 'Comedy|Musical|Romance',
           'Musical|Romance', 'Comedy|Musical',
           'Action|Adventure|Mystery|Romance|Thriller',
           'Comedy|Crime|Mystery|Romance|Thriller', 'Film-Noir|Mystery',
           'Comedy|Drama|Musical|Romance', 'Musical',
           'Adventure|Children|Fantasy|Musical',
           'Drama|Film-Noir|Mystery|Thriller', 'Film-Noir|Romance|Thriller',
           'Mystery|Romance|Thriller', 'Crime|Mystery|Romance|Thriller',
           'Adventure', 'Crime|Film-Noir|Mystery', 'Drama|Romance|Western',
           'Children|Drama|Fantasy|Romance', 'Adventure|Comedy|Romance|War',
           'Adventure|Comedy|Crime|Drama|Romance', 'Romance|War',
           'Crime|Film-Noir', 'Children|Comedy|Western',
           'Children|Comedy|Fantasy|Romance', 'Children|Comedy|Romance',
           'Children|Comedy|Drama', 'Children|Comedy|Mystery',
           'Animation|Children|Fantasy|Musical|Romance',
           'Animation|Children|Musical', 'Children|Comedy|Fantasy|Musical',
           'Animation|Children|Drama|Musical', 'Adventure|Children|Musical',
           'Animation|Children|Drama', 'Action|Horror|Sci-Fi|Thriller',
           'Documentary|Drama',
           'Animation|Children|Comedy|Fantasy|Musical|Romance',
           'Drama|Romance|Thriller', 'Children|Drama|Sci-Fi',
           'Action|Romance', 'Adventure|Comedy|Fantasy',
           'Animation|Children|Comedy|Crime',
           'Animation|Comedy|Drama|Fantasy', 'Crime|Drama|Film-Noir',
           'Documentary|Musical', 'Action|Adventure|Comedy|Fantasy|Romance',
           'Fantasy|Sci-Fi', 'Action|Adventure|Horror|Sci-Fi',
           'Action|Adventure|Western', 'Crime|Drama|Sci-Fi|Thriller',
           'Film-Noir|Mystery|Thriller',
           'Action|Adventure|Comedy|Fantasy|Horror',
           'Adventure|Drama|Romance', 'Crime|Horror', 'Action|Comedy|Musical',
           'Adventure|Animation|Children|Comedy|Sci-Fi',
           'Drama|Mystery|Sci-Fi', 'Comedy|Fantasy|Horror',
           'Crime|Drama|Film-Noir|Thriller', 'Crime|Film-Noir|Thriller',
           'Action|Crime|Romance|Thriller', 'Drama|Sci-Fi|Thriller',
           'Action|Adventure|Drama|Western', 'Comedy|Horror|Sci-Fi',
           'Comedy|Musical|War', 'Action|Comedy|Fantasy|Horror',
           'Action|Adventure|Drama|War',
           'Action|Drama|Mystery|Romance|Thriller', 'Comedy|Fantasy|Romance',
           'Crime|Thriller|War', 'Comedy|Mystery|Thriller',
           'Comedy|Drama|Film-Noir', 'Action|Adventure|Animation|Sci-Fi',
           'Action|Western', 'Fantasy|Horror|Romance|Thriller',
           'Drama|Fantasy|Horror', 'Horror|Mystery|Thriller',
           'Adventure|Children|Comedy', 'Adventure|Sci-Fi',
           'Action|Mystery|Sci-Fi', 'Action|Comedy|Western', 'Action|Horror',
           'Action|Comedy|Crime|Drama|Sci-Fi',
           'Adventure|Animation|Comedy|Crime',
           'Comedy|Horror|Mystery|Thriller', 'Action|Romance|War|Western',
           'Comedy|Drama|Fantasy|Romance', 'Action|Adventure|Comedy|Thriller',
           'Crime', 'Crime|Drama|Fantasy|Film-Noir|Mystery|Romance',
           'Action|Comedy|Crime|Drama', 'Action|Romance|Sci-Fi|Thriller',
           'Comedy|Drama|Mystery|Romance', 'Action|Adventure|Children',
           'Comedy|Crime|Romance', 'Action|Adventure|Comedy',
           'Action|Adventure|Comedy|Sci-Fi',
           'Action|Adventure|Fantasy|Thriller', 'Children|Fantasy',
           'Adventure|Romance', 'Action|Thriller|War',
           'Children|Comedy|Romance|Sci-Fi', 'Romance|Thriller',
           'Comedy|Drama|Sci-Fi',
           'Adventure|Animation|Children|Drama|Musical',
           'Action|Adventure|Drama|Sci-Fi', 'Action|Children|Comedy',
           'Adventure|Film-Noir|Sci-Fi|Thriller',
           'Crime|Drama|Fantasy|Thriller', 'Crime|Romance|Thriller',
           'Crime|Drama|Mystery|Romance|Thriller', 'Documentary|IMAX',
           'Comedy|Crime|Drama|Mystery|Thriller', 'Comedy|Documentary',
           'Adventure|Children|Comedy|Fantasy', 'Crime|Drama|Romance|War',
           'Adventure|Comedy|Drama', 'Adventure|Comedy|Romance',
           'Adventure|Animation|Children|Comedy|Drama|Musical|Romance',
           'Action|Crime|Mystery|Sci-Fi|Thriller',
           'Comedy|Crime|Drama|Romance|Thriller',
           'Animation|Children|Fantasy|War', 'Comedy|Drama|Musical',
           'Adventure|Fantasy|Musical',
           'Action|Adventure|Children|Comedy|Fantasy',
           'Drama|Mystery|Sci-Fi|Thriller', 'Adventure|Comedy|Sci-Fi|Western',
           'Children|Fantasy|Musical', 'Adventure|Animation|Children|Fantasy',
           'Children|Sci-Fi', 'Children|Comedy|Sci-Fi',
           'Action|Adventure|Children|Comedy', 'Adventure|Children|Sci-Fi',
           'Action|Animation|Children|Crime',
           'Children|Comedy|Fantasy|Horror',
           'Adventure|Children|Comedy|Fantasy|Sci-Fi',
           'Action|Crime|Drama|Mystery|Thriller', 'Film-Noir',
           'Drama|Fantasy|Mystery', 'Animation|Children|Comedy|Musical',
           'Animation|Children|Comedy|Musical|Romance',
           'Children|Comedy|Musical', 'Children|Musical',
           'Adventure|Comedy|Musical',
           'Adventure|Animation|Children|Crime|Drama',
           'Children|Drama|Fantasy|Mystery|Thriller',
           'Adventure|Children|Fantasy|Western',
           'Animation|Children|Comedy|Drama|Fantasy',
           'Action|Crime|Mystery|Thriller',
           'Adventure|Animation|Children|Drama|Fantasy',
           'Adventure|Animation|Children|Drama', 'Adventure|Fantasy',
           'Adventure|Animation|Children|Comedy',
           'Adventure|Animation|Children|Musical|Western',
           'Adventure|Fantasy|Romance', 'Adventure|Drama|Fantasy',
           'Action|Comedy|Drama|Horror', 'Action|Horror|Thriller',
           'Drama|Film-Noir|Thriller', 'Adventure|Drama|Mystery|Thriller',
           'Horror|Mystery|Sci-Fi|Thriller', 'Drama|Fantasy|Thriller',
           'Adventure|Drama|Fantasy|Romance', 'Sci-Fi',
           'Drama|Fantasy|Mystery|Romance', 'Action|Sci-Fi|War',
           'Fantasy|Horror|Thriller', 'Horror|Western',
           'Action|Adventure|Fantasy|Horror',
           'Adventure|Fantasy|Romance|Sci-Fi|Thriller',
           'Comedy|Crime|Mystery', 'Action|Drama|Romance|Sci-Fi',
           'Animation|Musical', 'Action|Adventure|Thriller|War',
           'Comedy|Crime|Mystery|Thriller',
           'Action|Adventure|Children|Fantasy|Mystery|Thriller',
           'Action|Adventure|Children|Drama',
           'Action|Adventure|Drama|Fantasy|Thriller', 'Horror|Mystery|Sci-Fi',
           'Drama|Horror|Sci-Fi|Thriller', 'Action|Comedy|Romance|Thriller',
           'Action|War', 'Adventure|Comedy|Thriller',
           'Action|Sci-Fi|Thriller|Western', 'Drama|Romance|Sci-Fi|Thriller',
           'Drama|Film-Noir',
           'Action|Adventure|Comedy|Fantasy|Horror|Thriller',
           'Action|Adventure|Crime|Sci-Fi|Thriller',
           'Adventure|Drama|Mystery', 'Horror|Romance',
           'Comedy|Horror|Musical|Sci-Fi', 'War', 'Comedy|Romance|Sci-Fi',
           'Animation|Comedy|Musical', 'Action|Comedy|Sci-Fi|Western',
           'Action|Comedy|Fantasy', 'Adventure|Drama|Thriller',
           'Action|Adventure|Comedy|Fantasy|Mystery', 'Comedy|Horror|Musical',
           'Adventure|Animation|Children|Drama|Sci-Fi',
           'Drama|Horror|Mystery', 'Action|Mystery',
           'Comedy|Horror|Romance|Thriller', 'Action|Drama|Romance|Thriller',
           'Animation|Horror|Mystery|Thriller',
           'Adventure|Children|Comedy|Drama', 'Adventure|Sci-Fi|Thriller',
           'Adventure|Animation|Comedy|Fantasy|Musical',
           'Animation|Children|Fantasy', 'Action|Adventure|Comedy|Drama|War',
           'Crime|Drama|Western', 'Comedy|Crime|Drama|Fantasy',
           'Drama|Film-Noir|Mystery|Romance', 'Musical|Romance|War',
           'Adventure|Comedy|Fantasy|Sci-Fi', 'Drama|Fantasy|Musical',
           'Action|Crime|Sci-Fi|Thriller',
           'Adventure|Animation|Children|Comedy|Crime|Fantasy|Mystery',
           'Action|Adventure|Animation|Drama|Fantasy',
           'Adventure|Animation|Children|Fantasy|Sci-Fi',
           'Fantasy|Horror|Mystery|Romance',
           'Action|Fantasy|Horror|Mystery|Thriller', 'Drama|Romance|Sci-Fi',
           'Animation|Children|Musical|IMAX', 'Action|Comedy|Horror',
           'Action|Crime|Thriller|Western', 'Fantasy|Horror|Mystery|Thriller',
           'Romance|Western', 'Adventure|Crime|Drama|Romance',
           'Adventure|Crime|Drama', 'Animation|Comedy',
           'Action|Children|Comedy|Fantasy|Sci-Fi', 'Action|Children|Fantasy',
           'Action|Adventure|Drama|Thriller|Western',
           'Crime|Horror|Mystery|Thriller', 'Action|Adventure|Comedy|Western',
           'Action|Drama|Thriller|Western',
           'Adventure|Animation|Fantasy|Sci-Fi',
           'Comedy|Horror|Sci-Fi|Thriller', 'Adventure|Drama|Romance|Sci-Fi',
           'Film-Noir|Horror|Mystery|Thriller',
           'Action|Adventure|Animation|Children|Sci-Fi',
           'Action|Fantasy|Horror|Sci-Fi|Thriller',
           'Action|Comedy|Crime|Romance', 'Adventure|Horror|Sci-Fi',
           'Adventure|Animation|Children|Sci-Fi', 'Adventure|Comedy|Crime',
           'Action|Drama|War|Western',
           'Action|Crime|Mystery|Romance|Thriller', 'Romance|Sci-Fi',
           'Fantasy|Romance', 'Action|Adventure|Fantasy|Sci-Fi',
           'Adventure|Comedy|Horror', 'Animation|Comedy|Fantasy',
           'Action|Adventure|War', 'Action|Crime|Drama|Horror|Thriller',
           'Crime|Mystery', 'Adventure|Comedy|Mystery|Romance',
           'Adventure|Animation|Children|Comedy|Fantasy|Romance',
           'Adventure|War|Western', 'Comedy|Drama|Mystery|Thriller',
           'Comedy|Drama|Romance|Western', 'Action|Comedy|Sci-Fi|Thriller',
           'Adventure|Documentary|IMAX', 'Animation|Drama|Sci-Fi|IMAX',
           'Action|Comedy|Horror|Sci-Fi', 'Comedy|Musical|Sci-Fi',
           'Drama|Musical|Mystery', 'Crime|Musical', 'Comedy|Musical|Western',
           'Action|Animation|Comedy|Crime|Drama|Romance|Thriller',
           'Action|Adventure|Drama|Romance',
           'Comedy|Fantasy|Horror|Musical|Thriller', 'Crime|Horror|Mystery',
           'Action|Adventure|Drama|Romance|Thriller',
           'Action|Comedy|Romance|War', 'Action|Adventure|Comedy|Drama',
           'Adventure|Thriller', 'Crime|Drama|Film-Noir|Mystery|Thriller',
           'Action|Animation|Sci-Fi', 'Animation|Drama|Fantasy',
           'Drama|Fantasy|Mystery|Sci-Fi',
           'Drama|Fantasy|Horror|Thriller|War', 'Fantasy|Mystery|Thriller',
           'Action|Adventure|Comedy|Drama|Romance|Thriller',
           'Mystery|Romance|Sci-Fi|Thriller',
           'Adventure|Crime|Drama|Thriller', 'Comedy|Drama|Mystery',
           'Animation|Fantasy', 'Drama|Fantasy|Horror|Mystery|Thriller',
           'Drama|Fantasy|Mystery|Romance|Thriller',
           'Animation|Fantasy|Horror|Sci-Fi', 'Documentary|War',
           'Children|Horror|Mystery|Thriller', 'Musical|Western',
           'Action|Adventure|Sci-Fi|IMAX',
           'Adventure|Animation|Children|Western',
           'Adventure|Children|Comedy|Fantasy|Mystery',
           'Adventure|Drama|Horror|Mystery|Thriller',
           'Comedy|Sci-Fi|Thriller', 'Action|Animation|Children|Comedy',
           'Children|Drama|Musical', 'Comedy|Drama|Fantasy|Sci-Fi',
           'Action|Adventure|Fantasy|Romance',
           'Comedy|Crime|Romance|Thriller', 'Adventure|War',
           'Comedy|Crime|Musical|Mystery', 'Adventure|Animation|Fantasy',
           'Animation|Comedy|War', 'Action|Adventure|Comedy|Crime|Drama',
           'Animation|Drama|War', 'Documentary|Horror',
           'Action|Horror|Mystery|Sci-Fi', 'Action|Comedy|Documentary',
           'Adventure|Animation|Children|Sci-Fi|IMAX', 'Comedy|Drama|Horror',
           'Animation|Children|Drama|Fantasy', 'Comedy|Crime|Drama|Musical',
           'Action|Adventure|Animation|Fantasy|Sci-Fi',
           'Action|Adventure|Crime|Drama|Thriller',
           'Comedy|Crime|Drama|Romance', 'Comedy|Documentary|Musical',
           'Action|Animation|Sci-Fi|Thriller',
           'Adventure|Children|Comedy|Mystery', 'Mystery|Sci-Fi',
           'Adventure|Children|Comedy|Fantasy|Musical',
           'Action|Adventure|Animation|Children|Fantasy|Sci-Fi',
           'Action|Adventure|Sci-Fi|Thriller|IMAX',
           'Action|Drama|Horror|Sci-Fi|Thriller', 'Drama|War|Western',
           'Comedy|Crime|Mystery|Romance', 'Comedy|War|Western',
           'Action|Adventure|Comedy|Crime|Thriller', 'Action|Fantasy|Sci-Fi',
           'Action|Comedy|Thriller', 'Comedy|Crime|Drama|War',
           'Adventure|Comedy|Crime|Thriller',
           'Action|Adventure|Children|Fantasy',
           'Drama|Fantasy|Musical|Romance', 'Animation|Drama|Romance',
           'Comedy|Romance|Sci-Fi|Thriller', 'Action|Fantasy|Horror',
           'Fantasy|Horror|Sci-Fi|Thriller', 'Comedy|Musical|Romance|Western',
           'Drama|Fantasy|Sci-Fi', 'Children|Comedy|Crime|Musical',
           'Action|Adventure|Animation|Fantasy', 'Crime|Documentary',
           'Adventure|Comedy|Drama|Fantasy|Mystery|Sci-Fi|Thriller',
           'Action|Animation|Children|Fantasy', 'Comedy|Mystery|Sci-Fi',
           'Adventure|Thriller|Western', 'Comedy|Crime|Drama|Mystery|Romance',
           'Action|Crime|Fantasy|Sci-Fi|Thriller', 'Crime|Fantasy|Horror',
           'Action|Drama|Horror|Thriller', 'Comedy|Fantasy|Horror|Thriller',
           'Action|Drama|Romance|Western',
           'Adventure|Animation|Drama|Fantasy|Sci-Fi',
           'Animation|Drama|Sci-Fi|War', 'Action|Adventure|Drama|Fantasy',
           'Adventure|Drama|Romance|Thriller|War',
           'Crime|Drama|Film-Noir|Romance|Thriller',
           'Drama|Film-Noir|Mystery',
           'Action|Comedy|Crime|Drama|Horror|Thriller',
           'Adventure|Documentary', 'Action|Adventure|Children|Comedy|Crime',
           'Animation|Comedy|Fantasy|Musical',
           'Action|Adventure|Children|Comedy|Mystery', 'Action|Drama|Horror',
           'Musical|Romance|Western', 'Action|Drama|Thriller|War',
           'Comedy|Crime|Drama|Musical|Mystery|Romance',
           'Adventure|Comedy|War', 'Fantasy|Musical|Romance',
           'Drama|Thriller|Western', 'Crime|Horror|Sci-Fi',
           'Animation|Fantasy|Thriller', 'Children|Comedy|Fantasy|Sci-Fi',
           'Mystery', 'Action|Adventure|Animation|Comedy|Crime|Mystery',
           'Adventure|Animation|Children|Comedy|Musical|Romance',
           'Action|Adventure|Drama|Sci-Fi|Thriller', 'Adventure|Fantasy|IMAX',
           'Action|Crime|Horror|Mystery|Thriller', 'Comedy|Fantasy|Thriller',
           'Animation|Comedy|Drama|Fantasy|Sci-Fi',
           'Comedy|Documentary|Drama', 'Crime|Drama|Film-Noir|Romance',
           'Action|Adventure|Drama|Romance|Thriller|Western',
           'Crime|Drama|Horror', 'Adventure|Comedy|Fantasy|Musical',
           'Adventure|Animation|Drama', 'Comedy|Drama|Fantasy|Mystery',
           'Action|Crime|Fantasy', 'Comedy|Drama|Sci-Fi|War',
           'Adventure|Fantasy|Sci-Fi',
           'Adventure|Drama|Horror|Sci-Fi|Thriller',
           'Action|Adventure|Animation|Comedy',
           'Action|Adventure|Animation|Children|Comedy',
           'Adventure|Animation|Children|Fantasy|IMAX',
           'Action|Adventure|Drama|Mystery|Thriller',
           'Action|Fantasy|Horror|Thriller', 'Fantasy',
           'Crime|Documentary|War', 'Children|Comedy|Musical|Romance',
           'Drama|Horror|War', 'Action|Adventure|Comedy|Drama|Romance|War',
           'Fantasy|Western', 'Adventure|Comedy|Horror|Romance',
           'Action|Adventure|Animation|Children|Comedy|Fantasy',
           'Action|Adventure|Children|Crime|Mystery|Thriller',
           'Adventure|Children|Fantasy|Sci-Fi',
           'Action|Fantasy|Horror|Romance', 'Animation|Fantasy|Mystery',
           'Action|Animation|Crime|Drama|Film-Noir|Mystery|Sci-Fi|Thriller',
           'Animation|Drama', 'Action|Fantasy|Sci-Fi|Thriller|War',
           'Adventure|Animation|Comedy|Fantasy|Romance',
           'Drama|Romance|Thriller|War',
           'Adventure|Drama|Fantasy|Horror|Sci-Fi',
           'Drama|Fantasy|Horror|Mystery|Sci-Fi|Thriller', 'Action|Animation',
           'Adventure|Animation|Children|Musical|Romance',
           'Action|Documentary|Drama|Thriller',
           'Action|Adventure|Comedy|Sci-Fi|Thriller',
           'Action|Adventure|Drama|Fantasy|Romance',
           'Action|Animation|Drama|Fantasy|Sci-Fi',
           'Drama|Fantasy|Romance|Sci-Fi',
           'Action|Animation|Crime|Sci-Fi|Thriller',
           'Drama|Horror|Mystery|Romance|Thriller',
           'Action|Comedy|Crime|Fantasy|Thriller',
           'Crime|Drama|Mystery|Thriller|War', 'Comedy|Drama|Romance|Sci-Fi',
           'Action|Animation|Horror', 'Comedy|Crime|Horror|Mystery|Thriller',
           'Comedy|Fantasy|Mystery|Sci-Fi',
           'Comedy|Crime|Drama|Sci-Fi|Thriller',
           'Action|Comedy|Horror|Musical', 'Drama|Sci-Fi|War',
           'Action|Animation|Drama|Sci-Fi',
           'Action|Comedy|Horror|Sci-Fi|Thriller|Western',
           'Action|Comedy|Drama|War', 'Drama|Mystery|Romance|War',
           'Action|Animation|Drama|Sci-Fi|Thriller',
           'Children|Comedy|Crime|Drama|Fantasy', 'Action|Horror|Sci-Fi|War',
           'Animation|Drama|Mystery|Sci-Fi|Thriller',
           'Action|Drama|Fantasy|Sci-Fi', 'Comedy|Crime|Drama|Horror|Mystery',
           'Adventure|Children|Comedy|Fantasy|IMAX',
           'Drama|Horror|Mystery|Sci-Fi|Thriller',
           'Animation|Fantasy|Sci-Fi|War', 'Action|Animation|Fantasy|Sci-Fi',
           'Action|Adventure|Crime|Drama',
           'Action|Adventure|Comedy|Crime|Romance|Thriller',
           'Action|Adventure|Drama|Romance|War',
           'Adventure|Animation|Fantasy|Romance',
           'Action|Fantasy|Horror|Mystery|Sci-Fi|Thriller',
           'Adventure|Comedy|Crime|Drama|Mystery|Thriller',
           'Comedy|Crime|Drama|Mystery', 'Comedy|Crime|Musical',
           'Adventure|Animation|Children|Comedy|Fantasy|Sci-Fi|IMAX',
           'Adventure|Comedy|Documentary', 'Comedy|Crime|Drama|Western',
           'Adventure|Drama|War|Western', 'Animation|Fantasy|Sci-Fi|Thriller',
           'Action|Crime|Film-Noir|Mystery|Thriller',
           'Animation|Comedy|Sci-Fi', 'Animation|Fantasy|Horror',
           'Children|Documentary', 'Action|Crime|IMAX',
           'Adventure|Animation|Children|Comedy|Fantasy|War',
           'Action|Adventure|Horror|Mystery|Sci-Fi|Thriller',
           'Action|Crime|Drama|Thriller|War',
           'Fantasy|Mystery|Romance|Thriller', 'Crime|Drama|Horror|Thriller',
           'Animation|Comedy|Fantasy|Musical|Romance',
           'Adventure|Children|Drama|Fantasy',
           'Action|Horror|Mystery|Thriller',
           'Adventure|Comedy|Fantasy|Horror',
           'Action|Adventure|Animation|Children|Comedy|Sci-Fi',
           'Adventure|Drama|Horror|Thriller',
           'Adventure|Fantasy|Thriller|IMAX', 'Crime|Drama|Thriller|War',
           'Action|Adventure|Comedy|Drama|Romance',
           'Animation|Drama|Romance|Sci-Fi', 'Fantasy|Mystery|Western',
           'Adventure|Comedy|Drama|Fantasy', 'Action|Comedy|Crime|Western',
           'Action|Crime|Drama|Horror', 'Action|Fantasy|Sci-Fi|Thriller',
           'Action|Drama|Fantasy|Horror|Mystery|Sci-Fi|Thriller',
           'Action|Animation|Children|Sci-Fi', 'Action|Sci-Fi|Thriller|IMAX',
           'Comedy|Fantasy|Horror|Sci-Fi', 'Action|Crime|Mystery',
           'Crime|Drama|Film-Noir|Mystery',
           'Action|Animation|Film-Noir|Sci-Fi|Thriller',
           'Action|Adventure|Thriller|IMAX',
           'Adventure|Comedy|Drama|Fantasy|Romance',
           'Children|Comedy|Drama|Musical|Romance',
           'Comedy|Documentary|Romance', 'Animation|Children|Fantasy|Mystery',
           'Comedy|Fantasy|Mystery', 'Action|Comedy|Fantasy|IMAX',
           'Adventure|Animation|Children|Comedy|Fantasy|IMAX',
           'Adventure|Animation|Comedy|Fantasy|Romance|Sci-Fi',
           'Crime|Drama|Musical', 'Adventure|Comedy|Sci-Fi|Thriller',
           'Adventure|Animation|Children|Comedy|IMAX',
           'Documentary|Drama|War', 'Crime|Western',
           'Action|Adventure|Crime|Drama|Thriller|War',
           'Children|Comedy|Drama|Fantasy', 'Drama|Fantasy|Horror|Romance',
           'Action|Fantasy|Thriller', 'Action|Comedy|Crime|Mystery',
           'Action|Comedy|Drama|Horror|Thriller', 'Action|Fantasy|War|IMAX',
           'Comedy|Drama|Horror|Sci-Fi|Thriller',
           'Drama|Fantasy|Mystery|Thriller',
           'Action|Crime|Horror|Sci-Fi|Thriller',
           'Adventure|Drama|Sci-Fi|Thriller',
           'Action|Adventure|Animation|Comedy|Fantasy|Mystery|Sci-Fi',
           'Crime|Drama|Fantasy|Mystery|Thriller',
           'Action|Crime|Horror|Thriller', 'Animation|Mystery|Sci-Fi',
           'Adventure|Crime|Thriller',
           'Action|Adventure|Crime|Horror|Thriller',
           'Adventure|Drama|Fantasy|IMAX', 'Adventure|Comedy|Fantasy|Romance',
           'Action|Adventure|Fantasy|War', 'Action|Crime|Drama|Western',
           'Action|Adventure|Comedy|Drama|Thriller',
           'Action|Adventure|Animation|Crime|Fantasy',
           'Action|Adventure|Animation|Fantasy|IMAX',
           'Comedy|Drama|Sci-Fi|Thriller',
           'Adventure|Animation|Children|Comedy|Fantasy|Musical|Romance',
           'Action|Horror|Sci-Fi|Thriller|IMAX',
           'Drama|Horror|Musical|Thriller', 'Action|Mystery|Sci-Fi|Thriller',
           'Adventure|Animation|Drama|Horror',
           'Animation|Comedy|Drama|Romance|Sci-Fi', 'Crime|Sci-Fi',
           'Adventure|Children|Drama|Fantasy|IMAX',
           'Adventure|Romance|Thriller', 'Crime|Drama|War',
           'Action|Crime|Drama|IMAX', 'Documentary|Musical|IMAX',
           'Action|Children|Sci-Fi|IMAX',
           'Action|Animation|Children|Comedy|IMAX',
           'Comedy|Crime|Drama|Horror', 'Action|Comedy|Drama|Thriller',
           'Adventure|Animation|Children|Romance|Sci-Fi',
           'Action|Adventure|Comedy|Crime|Fantasy',
           'Action|Animation|Comedy|Romance|Sci-Fi',
           'Children|Comedy|Drama|Mystery',
           'Animation|Children|Comedy|Fantasy|Musical',
           'Action|Adventure|Horror|Sci-Fi|Thriller',
           'Adventure|Children|Comedy|Romance|Sci-Fi',
           'Action|Comedy|Fantasy|Horror|Thriller',
           'Action|Drama|Mystery|Sci-Fi|Thriller|IMAX',
           'Adventure|Fantasy|Thriller', 'Action|Animation|Crime',
           'Adventure|Comedy|Drama|Romance',
           'Animation|Documentary|Drama|War',
           'Action|Comedy|Fantasy|Thriller', 'Action|Animation|Comedy|Horror',
           'Action|Crime|Thriller|IMAX', 'Animation|Comedy|Fantasy|Sci-Fi',
           'Action|Adventure|Animation|Comedy|Fantasy|Sci-Fi',
           'Action|Adventure|Animation|Children|Comedy|IMAX',
           'Children|Fantasy|Musical|Romance',
           'Drama|Fantasy|Romance|Thriller',
           'Adventure|Animation|Comedy|Fantasy', 'Drama|Sci-Fi|Thriller|IMAX',
           'Action|Adventure|Animation', 'Action|Animation|Comedy|Sci-Fi',
           'Animation', 'Adventure|Comedy|Mystery',
           'Comedy|Drama|Musical|Sci-Fi', 'Comedy|Crime|Horror|Thriller',
           'Action|Drama|Mystery|Sci-Fi|Thriller', 'Animation|Sci-Fi|IMAX',
           'Drama|Fantasy|Sci-Fi|Thriller', 'Action|Comedy|IMAX',
           'Adventure|Fantasy|Musical|Romance',
           'Action|Animation|Mystery|Sci-Fi',
           'Action|Adventure|Animation|Drama',
           'Action|Adventure|Comedy|Horror',
           'Action|Adventure|Animation|Children|Comedy|Romance',
           'Action|Adventure|Animation|Horror',
           'Adventure|Fantasy|Mystery|Romance|IMAX',
           'Adventure|Children|Fantasy|Sci-Fi|Thriller',
           'Comedy|Documentary|Drama|Romance', 'Adventure|Animation|Sci-Fi',
           'Animation|Children|Fantasy|IMAX',
           'Action|Animation|Comedy|Horror|Thriller',
           'Animation|Comedy|Drama',
           'Action|Adventure|Drama|Fantasy|Romance|Sci-Fi|Thriller',
           'Action|Comedy|Drama|Romance',
           'Adventure|Animation|Children|Comedy|Crime',
           'Animation|Children|Drama|Fantasy|IMAX',
           'Animation|Children|Comedy|Fantasy',
           'Drama|Fantasy|Horror|Romance|Thriller',
           'Action|Adventure|Animation|Comedy|Thriller',
           'Crime|Drama|Fantasy|Horror|Thriller', 'Children|Drama|Romance',
           'Horror|Thriller|Western', 'Comedy|Musical|Sci-Fi|Western',
           'Action|Adventure|Fantasy|Romance|IMAX',
           'Fantasy|Romance|Thriller|IMAX',
           'Action|Crime|Drama|Mystery|Sci-Fi|Thriller|IMAX',
           'Action|Children|Drama', 'Action|Comedy|Fantasy|Musical|Romance',
           'Documentary|Drama|Mystery', 'Adventure|Animation|Fantasy|IMAX',
           'Documentary|Mystery',
           'Action|Adventure|Comedy|Crime|Drama|Film-Noir|Horror|Mystery|Thriller|Western',
           'Horror|IMAX', 'Action|Animation|Children|Comedy|Sci-Fi|IMAX',
           'Action|Adventure|Fantasy|IMAX',
           'Animation|Children|Comedy|Fantasy|Musical|Romance|IMAX',
           'Crime|Romance', 'Adventure|Documentary|Western',
           'Action|Comedy|Crime|Fantasy|Thriller|IMAX',
           'Action|Fantasy|Western', 'Action|Sci-Fi|Thriller|Western|IMAX',
           'Action|Adventure|Animation|Children|Comedy|Western',
           'Romance|Sci-Fi|Thriller', 'Adventure|Animation|Comedy|Sci-Fi',
           'Action|Adventure|Animation|Children|Comedy|Sci-Fi|IMAX',
           'Action|Fantasy|Thriller|IMAX', 'Animation|Children|Comedy|Horror',
           'Action|Adventure|Drama|Fantasy|IMAX',
           'Action|Crime|Drama|Thriller|IMAX', 'Drama|Mystery|War',
           'Action|Adventure|Sci-Fi|Thriller|War',
           'Mystery|Sci-Fi|Thriller|IMAX', 'Action|Adventure|Sci-Fi|War|IMAX',
           'Action|Adventure|Drama|Fantasy|Mystery|IMAX',
           'Horror|Thriller|IMAX', 'Sci-Fi|Thriller|IMAX',
           'Action|Drama|Sci-Fi|IMAX', 'Crime|Sci-Fi|Thriller',
           'Action|Drama|Mystery|Thriller',
           'Adventure|Animation|Comedy|Fantasy|IMAX',
           'Action|Animation|Mystery|IMAX', 'Children|Drama|Mystery',
           'Action|Drama|Fantasy', 'Animation|Children|Comedy|IMAX',
           'Animation|Children|Comedy|Drama', 'Action|Crime|Film-Noir',
           'Action|Adventure|Crime|IMAX',
           'Action|Adventure|Drama|Thriller|IMAX',
           'Action|Adventure|Comedy|Crime|Mystery|Thriller',
           'Action|Fantasy|Horror|IMAX', 'Crime|Drama|Fantasy',
           'Action|Adventure|Comedy|Sci-Fi|IMAX', 'Action|Adventure|Horror',
           'Crime|Thriller|Western', 'Animation|Fantasy|Musical|IMAX',
           'Action|Animation|Fantasy', 'Comedy|Horror|IMAX',
           'Action|Comedy|Sci-Fi|IMAX', 'Action|Horror|Sci-Fi|IMAX',
           'Action|Adventure|Animation|Children',
           'Action|Adventure|Animation|Sci-Fi|Thriller',
           'Comedy|Drama|Musical|IMAX', 'Children|Musical|Mystery',
           'Drama|Fantasy|Musical|Mystery|Sci-Fi',
           'Animation|Comedy|Horror|IMAX', 'Drama|Sci-Fi|IMAX',
           'Action|Adventure|Comedy|Documentary|Fantasy',
           'Action|Adventure|Crime', 'Children|Crime|Drama',
           'Adventure|Drama|Fantasy|Romance|IMAX', 'Animation|Comedy|Romance',
           'Drama|Musical|Romance|IMAX',
           'Adventure|Comedy|Fantasy|Romance|IMAX',
           'Animation|Comedy|Horror|Musical', 'Action|Animation|Comedy',
           'Children|Horror|Sci-Fi', 'Action|Drama|IMAX',
           'Documentary|Fantasy', 'Action|Adventure|Fantasy|Sci-Fi|IMAX',
           'Action|Drama|Horror|IMAX', 'Action|Drama|Thriller|IMAX',
           'Action|Adventure|Western|IMAX', 'Drama|Fantasy|Thriller|War',
           'Action|IMAX', 'Action|Sci-Fi|IMAX',
           'Adventure|Comedy|Musical|Sci-Fi', 'Adventure|Drama|Thriller|IMAX',
           'Children|Drama|War',
           'Adventure|Animation|Comedy|Fantasy|Musical|Romance',
           'Action|Animation|Drama', 'Drama|Horror|Romance',
           'Action|Animation|Fantasy|IMAX', 'Adventure|Romance|Sci-Fi|IMAX',
           'Adventure|Animation|Children|Comedy|Drama|Romance',
           'Action|Fantasy|Sci-Fi|IMAX', 'Action|Crime|Sci-Fi|IMAX',
           'Animation|Comedy|Drama|Romance', 'Sci-Fi|IMAX',
           'Animation|Romance', 'Action|Drama|War|IMAX',
           'Action|Animation|Children|Comedy|Musical',
           'Action|Adventure|Children|IMAX', 'Action|Animation|Children',
           'Animation|Drama|Fantasy|Mystery',
           'Action|Animation|Crime|Thriller', 'Documentary|Drama|Musical',
           '(no genres listed)', 'Adventure|Animation',
           'Adventure|Animation|Romance',
           'Animation|Children|Comedy|Musical|Sci-Fi',
           'Action|Adventure|Comedy|Drama|Fantasy|Thriller',
           'Documentary|Drama|Thriller', 'Adventure|Mystery|Thriller',
           'Horror|Romance|Thriller', 'Animation|Children|Mystery',
           'Comedy|Drama|Fantasy|Mystery|Romance',
           'Crime|Drama|Horror|Mystery', 'Adventure|Romance|Sci-Fi',
           'Animation|Documentary', 'Horror|Sci-Fi|Western',
           'Action|Adventure|Children|Comedy|Sci-Fi',
           'Action|Adventure|Animation|Comedy|Sci-Fi',
           'Horror|Romance|Sci-Fi',
           'Action|Adventure|Children|Mystery|Sci-Fi', 'Comedy|Crime|Sci-Fi',
           'Action|Comedy|Fantasy|Sci-Fi',
           'Adventure|Animation|Children|Comedy|Drama|Fantasy',
           'Adventure|Children|Comedy|Sci-Fi',
           'Action|Animation|Crime|Sci-Fi', 'Action|Adventure|Romance|Sci-Fi',
           'Action|Crime|Drama|Sci-Fi',
           'Animation|Children|Comedy|Drama|Romance',
           'Action|Fantasy|Mystery', 'Comedy|Horror|Mystery',
           'Comedy|Crime|Fantasy', 'Animation|Horror|Mystery',
           'Comedy|Romance|Western', 'Adventure|Drama|Fantasy|Sci-Fi',
           'Adventure|Children|Drama|Sci-Fi',
           'Adventure|Children|Comedy|Drama|Fantasy|Sci-Fi',
           'Animation|Fantasy|Horror|Mystery',
           'Adventure|Animation|Fantasy|Horror|Sci-Fi',
           'Action|Animation|Crime|Drama',
           'Action|Adventure|Animation|Drama|Fantasy|Sci-Fi',
           'Action|Animation|Mystery', 'Animation|Drama|Sci-Fi',
           'Animation|Drama|Fantasy|Romance',
           'Action|Adventure|Comedy|Fantasy|Sci-Fi|Thriller',
           'Action|Adventure|Fantasy|Horror|Thriller', 'Comedy|Sci-Fi|War',
           'Comedy|Mystery|Romance|Thriller', 'Fantasy|Horror|Sci-Fi|Western',
           'Animation|Crime|Drama', 'Adventure|Mystery|Sci-Fi|Thriller',
           'Action|Comedy|Crime|Horror', 'Action|Adventure|Children|Sci-Fi',
           'Action|Adventure|Comedy|Fantasy|Sci-Fi',
           'Action|Animation|Comedy|Fantasy'], dtype=object)



Terlihat pada data di atas genre pada movie terlalu kompleks sehingga akan disederhanakan fitur genre dengan hanya mengambil genre yang pertama saja


Tabel 13. Data movie dengan fitur genre baru

| # | userId | movieId | rating | timestamp | title      | genres                                    | genre                                       |
|--------|---------|--------|-----------|------------|-------------------------------------------|---------------------------------------------|-----|
| 0      | 1       | 1      | 4.0       | 964982703  | Toy Story (1995)                          | Adventure,Animation,Children,Comedy,Fantasy | Adventure |
| 163062 | 517     | 1      | 4.0       | 1487954343 | Toy Story (1995)                          | Adventure,Animation,Children,Comedy,Fantasy | Adventure |
| 61034  | 213     | 1      | 3.5       | 1316196157 | Toy Story (1995)                          | Adventure,Animation,Children,Comedy,Fantasy | Adventure |
| 162164 | 514     | 1      | 4.0       | 1533872400 | Toy Story (1995)                          | Adventure,Animation,Children,Comedy,Fantasy | Adventure |
| 61202  | 214     | 1      | 3.0       | 853937855  | Toy Story (1995)                          | Adventure,Animation,Children,Comedy,Fantasy | Adventure |
| ...    | ...     | ...    | ...       | ...        | ...                                       | ...                                         | ...       |
| 54512  | 184     | 193581 | 4.0       | 1537109082 | Black Butler: Book of the Atlantic (2017) | Action,Animation,Comedy,Fantasy             | Action    |
| 54514  | 184     | 193583 | 3.5       | 1537109545 | No Game No Life: Zero (2017)              | Animation,Comedy,Fantasy                    | Animation |
| 54516  | 184     | 193585 | 3.5       | 1537109805 | Flint (2017)                              | Drama                                       | Drama     |
| 54518  | 184     | 193587 | 3.5       | 1537110021 | Bungo Stray Dogs: Dead Apple (2018)       | Action,Animation                            | Action    |
| 102724 | 331     | 193609 | 4.0       | 1537157606 | Andrew Dice Clay: Dice Rules (1991)       | Comedy                                      | Comedy    |

100836 rows × 7 columns



Tabel 14. Data movie yang sudah diurutkan berdasarkan movieId

| # | userId | movieId | rating | timestamp | title      | genres                                    | genre                                       |
|--------|---------|--------|-----------|------------|-------------------------------------------|---------------------------------------------|-----|
| 0      | 1       | 1      | 4.0       | 964982703  | Toy Story (1995)                          | Adventure,Animation,Children,Comedy,Fantasy | Adventure |
| 163062 | 517     | 1      | 4.0       | 1487954343 | Toy Story (1995)                          | Adventure,Animation,Children,Comedy,Fantasy | Adventure |
| 61034  | 213     | 1      | 3.5       | 1316196157 | Toy Story (1995)                          | Adventure,Animation,Children,Comedy,Fantasy | Adventure |
| 162164 | 514     | 1      | 4.0       | 1533872400 | Toy Story (1995)                          | Adventure,Animation,Children,Comedy,Fantasy | Adventure |
| 61202  | 214     | 1      | 3.0       | 853937855  | Toy Story (1995)                          | Adventure,Animation,Children,Comedy,Fantasy | Adventure |
| ...    | ...     | ...    | ...       | ...        | ...                                       | ...                                         | ...       |
| 54512  | 184     | 193581 | 4.0       | 1537109082 | Black Butler: Book of the Atlantic (2017) | Action,Animation,Comedy,Fantasy             | Action    |
| 54514  | 184     | 193583 | 3.5       | 1537109545 | No Game No Life: Zero (2017)              | Animation,Comedy,Fantasy                    | Animation |
| 54516  | 184     | 193585 | 3.5       | 1537109805 | Flint (2017)                              | Drama                                       | Drama     |
| 54518  | 184     | 193587 | 3.5       | 1537110021 | Bungo Stray Dogs: Dead Apple (2018)       | Action,Animation                            | Action    |
| 102724 | 331     | 193609 | 4.0       | 1537157606 | Andrew Dice Clay: Dice Rules (1991)       | Comedy                                      | Comedy    |

100836 rows × 7 columns=



Tabel 15. Tabel movie setelah drop duplicate data

| # | userId | movieId | rating | timestamp | title      | genres                                    | genre                                       |
|--------|---------|--------|-----------|------------|-------------------------------------------|---------------------------------------------|------|
| 0      | 1       | 1      | 4.0       | 964982703  | Toy Story (1995)                          | Adventure,Animation,Children,Comedy,Fantasy | Adventure |
| 84230  | 288     | 2      | 2.0       | 978467973  | Jumanji (1995)                            | Adventure,Children,Fantasy                  | Adventure |
| 86338  | 289     | 3      | 2.5       | 1143424657 | Grumpier Old Men (1995)                   | Comedy,Romance                              | Comedy    |
| 76358  | 262     | 4      | 1.0       | 840306203  | Waiting to Exhale (1995)                  | Comedy,Drama,Romance                        | Comedy    |
| 154448 | 483     | 5      | 2.5       | 1327277284 | Father of the Bride Part II (1995)        | Comedy                                      | Comedy    |
| ...    | ...     | ...    | ...       | ...        | ...                                       | ...                                         | ...       |
| 54512  | 184     | 193581 | 4.0       | 1537109082 | Black Butler: Book of the Atlantic (2017) | Action,Animation,Comedy,Fantasy             | Action    |
| 54514  | 184     | 193583 | 3.5       | 1537109545 | No Game No Life: Zero (2017)              | Animation|Comedy|Fantasy                    | Animation |
| 54516  | 184     | 193585 | 3.5       | 1537109805 | Flint (2017)                              | Drama                                       | Drama     |
| 54518  | 184     | 193587 | 3.5       | 1537110021 | Bungo Stray Dogs: Dead Apple (2018)       | Action|Animation                            | Action    |
| 102724 | 331     | 193609 | 4.0       | 1537157606 | Andrew Dice Clay: Dice Rules (1991)       | Comedy                                      | Comedy    |

9724 rows × 7 columns

Pada tabel 15 terlihat bahwa jumlah sebelum dilakukan drop duplicate sebanyak 100836 setelah di drop menjadi 9724 data



Tabel 16. Data dictionari

| #    | id   | title  | genre                                     |
|------|--------|-------------------------------------------|-----------|
| 0    | 1      | Toy Story (1995)                          | Adventure |
| 1    | 2      | Jumanji (1995)                            | Adventure |
| 2    | 3      | Grumpier Old Men (1995)                   | Comedy    |
| 3    | 4      | Waiting to Exhale (1995)                  | Comedy    |
| 4    | 5      | Father of the Bride Part II (1995)        | Comedy    |
| ...  | ...    | ...                                       | ...       |
| 9719 | 193581 | Black Butler: Book of the Atlantic (2017) | Action    |
| 9720 | 193583 | No Game No Life: Zero (2017)              | Animation |
| 9721 | 193585 | Flint (2017)                              | Drama     |
| 9722 | 193587 | Bungo Stray Dogs: Dead Apple (2018)       | Action    |
| 9723 | 193609 | Andrew Dice Clay: Dice Rules (1991)       | Comedy    |

Pada tabel 16 merupakan data yang akan dimasukkan ke dalam permodelan sistem rekomendasi *Content Based Filtering*


# Model Development dengan Content Based Filtering


Tabel 17. Sampel data movie

| # | id   | title  | genre                                    |
|------|--------|------------------------------------------|-----------|
| 8925 | 136503 | Tom and Jerry: Shiver Me Whiskers (2006) | Animation |
| 3512 | 4808   | Vanishing, The (1993)                    | Mystery   |
| 9353 | 162598 | Deepwater Horizon (2016)                 | Drama     |
| 9291 | 159403 | Neo Tokyo (1987)                         | Adventure |
| 4789 | 7150   | Stuck on You (2003)                      | Comedy    |


### TF-IDF Vectorizer

Pada tahap ini, akan dibuat sistem rekomendasi sederhana berdasarkan genre film menggunakan TF-IDF Vectoriczer


Data genre movie setelah melakukan tf-idf vectorizer


    array(['action', 'adventure', 'animation', 'children', 'comedy', 'crime',
           'documentary', 'drama', 'fantasy', 'fi', 'film', 'genres',
           'horror', 'listed', 'musical', 'mystery', 'no', 'noir', 'romance',
           'sci', 'thriller', 'war', 'western'], dtype=object)



Melakukan fit dan transformasi ke dalam bentuk matriks.

Output :   (9724, 23)

Ukuran matrix (9724, 23), Nilai 9724 merupakan ukuran data dan 22 merupakan matrik kategori movie. 

Kemudian mengibah vektor tf-idf ke dalam bentuk matriks dengan fungsi todense()

Tabel 18. Matriks tf-idf untuk bebrapa movie dan genre


| | mystery                                | noir | thriller | film | no  | musical | sci | animation | war | action | ... | fantasy | fi  | romance  | listed | adventure | documentary | western | children | genres | crime |
|----------------------------------------|------|----------|------|-----|---------|-----|-----------|-----|--------|-----|---------|-----|----------|--------|-----------|-------------|---------|----------|--------|-------|---|
| title                                  |
| Incredible Shrinking Man, The (1957)   | 0.0  | 0.0      | 0.0  | 0.0 | 0.0     | 0.0 | 0.707107  | 0.0 | 0.0    | 0.0 | ...     | 0.0 | 0.707107 | 0.0    | 0.0       | 0.0         | 0.0     | 0.0      | 0.0    | 0.0   | 0.0 |
| Fullmetal Alchemist 2018 (2017)        | 0.0  | 0.0      | 0.0  | 0.0 | 0.0     | 0.0 | 0.000000  | 0.0 | 0.0    | 1.0 | ...     | 0.0 | 0.000000 | 0.0    | 0.0       | 0.0         | 0.0     | 0.0      | 0.0    | 0.0   | 0.0 |
| Andromeda Strain, The (1971)           | 1.0  | 0.0      | 0.0  | 0.0 | 0.0     | 0.0 | 0.000000  | 0.0 | 0.0    | 0.0 | ...     | 0.0 | 0.000000 | 0.0    | 0.0       | 0.0         | 0.0     | 0.0      | 0.0    | 0.0   | 0.0 |
| Ladykillers, The (2004)                | 0.0  | 0.0      | 0.0  | 0.0 | 0.0     | 0.0 | 0.000000  | 0.0 | 0.0    | 0.0 | ...     | 0.0 | 0.000000 | 0.0    | 0.0       | 0.0         | 0.0     | 0.0      | 0.0    | 0.0   | 0.0 |
| Thor: Ragnarok (2017)                  | 0.0  | 0.0      | 0.0  | 0.0 | 0.0     | 0.0 | 0.000000  | 0.0 | 0.0    | 1.0 | ...     | 0.0 | 0.000000 | 0.0    | 0.0       | 0.0         | 0.0     | 0.0      | 0.0    | 0.0   | 0.0 |
| Beethoven (1992)                       | 0.0  | 0.0      | 0.0  | 0.0 | 0.0     | 0.0 | 0.000000  | 0.0 | 0.0    | 0.0 | ...     | 0.0 | 0.000000 | 0.0    | 0.0       | 0.0         | 0.0     | 0.0      | 1.0    | 0.0   | 0.0 |
| Hairspray (2007)                       | 0.0  | 0.0      | 0.0  | 0.0 | 0.0     | 0.0 | 0.000000  | 0.0 | 0.0    | 0.0 | ...     | 0.0 | 0.000000 | 0.0    | 0.0       | 0.0         | 0.0     | 0.0      | 0.0    | 0.0   | 0.0 |
| Going in Style (1979)                  | 0.0  | 0.0      | 0.0  | 0.0 | 0.0     | 0.0 | 0.000000  | 0.0 | 0.0    | 0.0 | ...     | 0.0 | 0.000000 | 0.0    | 0.0       | 0.0         | 0.0     | 0.0      | 0.0    | 0.0   | 0.0 |
| Midsummer Night's Sex Comedy, A (1982) | 0.0  | 0.0      | 0.0  | 0.0 | 0.0     | 0.0 | 0.000000  | 0.0 | 0.0    | 0.0 | ...     | 0.0 | 0.000000 | 0.0    | 0.0       | 0.0         | 0.0     | 0.0      | 0.0    | 0.0   | 0.0 |
| Invasion, The (2007)                   | 0.0  | 0.0      | 0.0  | 0.0 | 0.0     | 0.0 | 0.000000  | 0.0 | 0.0    | 1.0 | ...     | 0.0 | 0.000000 | 0.0    | 0.0       | 0.0         | 0.0     | 0.0      | 0.0    | 0.0   | 0.0 |


Output matriks di atas menujukan movie yang berjudul *Andromeda Strain, The (1971)* memiliki genre *mystery*, hal ini terlihat dari nilai matriks 1.0 pada kategori *mystery*.


### *Cosine Similarity*

Menghitung derajat kesamaan (similarity degree) antar restoran dengan teknik cosine similarity. Keluarannya berupa matriks kesamaan dalam bentuk array.

kemudian melihat matriks kesamaan setiap movie dengan menampilkan title movie dalam 5 sampel kolom (axis = 1) dan 10 sampel baris (axis=0).


    Shape: (9724, 9724)

Tabel 19. Matriks kesamaan setiap movie

| title                                                      | Frankenstein (1931) | If These Walls Could Talk 2 (2000) | American Pie (1999) | Mr Hublot (2013) | The Last Witch Hunter (2015) |
|------------------------------------------------------------|---------------------|------------------------------------|---------------------|------------------|------------------------------|
| title                                                      |
| Union: The Business Behind Getting High, The (2007)        | 0.0                 | 0.0                                | 1.0                 | 0.0              | 0.0                          |
| Diabolique (Les diaboliques) (1955)                        | 0.0                 | 0.0                                | 0.0                 | 0.0              | 0.0                          |
| Drag Me to Hell (2009)                                     | 0.0                 | 0.0                                | 1.0                 | 0.0              | 0.0                          |
| Deadpool 2 (2018)                                          | 0.0                 | 0.0                                | 0.0                 | 0.0              | 1.0                          |
| Terminal, The (2004)                                       | 0.0                 | 0.0                                | 1.0                 | 0.0              | 0.0                          |
| GLOW: The Story of the Gorgeous Ladies of Wrestling (2012) | 0.0                 | 0.0                                | 0.0                 | 0.0              | 0.0                          |
| Glory (1989)                                               | 1.0                 | 1.0                                | 0.0                 | 0.0              | 0.0                          |
| Larry Crowne (2011)                                        | 0.0                 | 0.0                                | 1.0                 | 0.0              | 0.0                          |
| Super Troopers (2001)                                      | 0.0                 | 0.0                                | 1.0                 | 0.0              | 0.0                          |
| 2046 (2004)                                                | 1.0                 | 1.0                                | 0.0                 | 0.0              | 0.0                          |



Mengidentifikasi kesamaan antara satu restoran dengan restoran lainnya.

Angka 1.0 ymengindikasikan bahwa movie pada kolom X (horizontal) memiliki kesamaan dengan movie pada baris Y (vertikal). Sebagai contoh, film *Union: The Business Behind Getting High, The (2007)* teridentifikasi sama (similar) dengan film *American Pie (1999)*.


### Mendapatkan Rekomendasi

Membuat fungsi resto_recommendations dengan beberapa parameter sebagai berikut:

- title : Nama film (index kemiripan dataframe).
- similarity_data : Dataframe mengenai similarity yang telah kita definisikan sebelumnya.
- items : Nama dan fitur yang digunakan untuk mendefinisikan kemiripan, dalam hal ini adalah 'title' dan 'genre'.
- k : Banyak rekomendasi yang ingin diberikan.


Hasil rekomendasi dari permodelan yang telah dibuat

dalam kasus ini akan dicari rekomendasi berdasarkan title film *Felon (2008)*


Tabel 20. Hasil rekomendasi film
| title | genre                                             |
|-------|---------------------------------------------------|
| 0     | Wolf Creek (2005)                                 | Crime |
| 1     | Joint Security Area (Gongdong gyeongbi guyeok ... | Crime |
| 2     | Entrapment (1999)                                 | Crime |
| 3     | Time Lapse (2014)                                 | Crime |
| 4     | Secret in Their Eyes (2015)                       | Crime |


Dari tabel 20 dapat dilihat bahwa sistem memeberikan 5 rekomendasi film yang mirip dengan film *Felon (2008)*

# Model Development dengan Collaborative Filtering

### *Data Understanding*

Tabel 21. Daftar data rating
| # | userId | movieId | rating | timestamp |
|--------|---------|--------|-----------|------------|
| 0      | 1       | 1      | 4.0       | 964982703  |
| 1      | 1       | 3      | 4.0       | 964981247  |
| 2      | 1       | 6      | 4.0       | 964982224  |
| 3      | 1       | 47     | 5.0       | 964983815  |
| 4      | 1       | 50     | 5.0       | 964982931  |
| ...    | ...     | ...    | ...       | ...        |
| 100831 | 610     | 166534 | 4.0       | 1493848402 |
| 100832 | 610     | 168248 | 5.0       | 1493850091 |
| 100833 | 610     | 168250 | 5.0       | 1494273047 |
| 100834 | 610     | 168252 | 5.0       | 1493846352 |
| 100835 | 610     | 170875 | 3.0       | 1493846415 |

100836 rows × 4 columns



### *Data Preparation*

Berikut adalah hal-hal yang telah kita lakukan pada tahap persiapan:

- Memahami data rating.
- Menyandikan (encode) fitur ‘userId’ dan 'movieId' ke dalam indeks integer.
- Memetakan ‘userId’ dan ‘movieId’ ke dataframe yang berkaitan.
- Mengecek beberapa hal dalam data seperti jumlah user, jumlah movie, kemudian mengubah nilai rating menjadi float. jumlah user
  - Jumlah user : 610
  - jumlah movie : 9724
  - Rating minimum : 0.5
  - Rating maksimum : 5.0

### Membagi Data untuk Training dan Validasi

Tabel 22. Cek dataset
| userId | movieId | rating | timestamp | user       | movie |
|--------|---------|--------|-----------|------------|-------|
| 67037  | 432     | 77866  | 4.5       | 1335139641 | 431   | 4730 |
| 42175  | 288     | 474    | 3.0       | 978465565  | 287   | 474  |
| 93850  | 599     | 4351   | 3.0       | 1498524542 | 598   | 2631 |
| 6187   | 42      | 2987   | 4.0       | 996262677  | 41    | 194  |
| 12229  | 75      | 1610   | 4.0       | 1158989841 | 74    | 727  |
| ...    | ...     | ...    | ...       | ...        | ...   | ...  |
| 6265   | 42      | 4005   | 4.0       | 996259059  | 41    | 1873 |
| 54886  | 364     | 141    | 4.0       | 869443367  | 363   | 524  |
| 76820  | 480     | 6867   | 4.0       | 1179163171 | 479   | 2240 |
| 860    | 6       | 981    | 3.0       | 845556567  | 5     | 712  |
| 15795  | 103     | 6711   | 5.0       | 1431957425 | 102   | 2046 |


Kemudian, data akan dibagi menjadi train dan validasi dengan komposisi 80:20. Namun data dipetakan (mapping) terlebih dahulu, data user dan resto menjadi satu value.


    [[ 431 4730]
     [ 287  474]
     [ 598 2631]
     ...
     [ 479 2240]
     [   5  712]
     [ 102 2046]] [0.88888889 0.55555556 0.55555556 ... 0.77777778 0.55555556 1.        ]


Data sudah siap dimasukkan ke salam model


### Proses Training

Pada tahap ini, model menghitung skor kecocokan antara pengguna dan movie dengan teknik embedding. Pertama, melakukan proses embedding terhadap data user dan movie. Selanjutnya, melakukan operasi perkalian dot product antara embedding user dan movie. Selain itu juga dapat menambahkan bias untuk setiap user dan movie. Skor kecocokan ditetapkan dalam skala [0,1] dengan fungsi aktivasi sigmoid.

Model ini menggunakan Binary Crossentropy untuk menghitung loss function, Adam (Adaptive Moment Estimation) sebagai optimizer, dan root mean squared error (RMSE) sebagai metrics evaluation.

Proses training.

     Epoch 1/50
    8067/8067 [==============================] - 67s 8ms/step - loss: 0.5979 - root_mean_squared_error: 0.1902 - val_loss: 0.6068 - val_root_mean_squared_error: 0.1991
    Epoch 2/50
    8067/8067 [==============================] - 70s 9ms/step - loss: 0.5963 - root_mean_squared_error: 0.1882 - val_loss: 0.6064 - val_root_mean_squared_error: 0.1986
    Epoch 3/50
    8067/8067 [==============================] - 72s 9ms/step - loss: 0.5950 - root_mean_squared_error: 0.1867 - val_loss: 0.6060 - val_root_mean_squared_error: 0.1980
    Epoch 4/50
    8067/8067 [==============================] - 66s 8ms/step - loss: 0.5940 - root_mean_squared_error: 0.1855 - val_loss: 0.6055 - val_root_mean_squared_error: 0.1973
    Epoch 5/50
    8067/8067 [==============================] - 65s 8ms/step - loss: 0.5934 - root_mean_squared_error: 0.1848 - val_loss: 0.6057 - val_root_mean_squared_error: 0.1976
    Epoch 6/50
    8067/8067 [==============================] - 64s 8ms/step - loss: 0.5929 - root_mean_squared_error: 0.1841 - val_loss: 0.6060 - val_root_mean_squared_error: 0.1978
    Epoch 7/50
    8067/8067 [==============================] - 65s 8ms/step - loss: 0.5923 - root_mean_squared_error: 0.1834 - val_loss: 0.6060 - val_root_mean_squared_error: 0.1978
    Epoch 8/50
    8067/8067 [==============================] - 68s 8ms/step - loss: 0.5919 - root_mean_squared_error: 0.1829 - val_loss: 0.6060 - val_root_mean_squared_error: 0.1976
    Epoch 9/50
    8067/8067 [==============================] - 156s 19ms/step - loss: 0.5914 - root_mean_squared_error: 0.1823 - val_loss: 0.6060 - val_root_mean_squared_error: 0.1976
    Epoch 10/50
    8067/8067 [==============================] - 70s 9ms/step - loss: 0.5912 - root_mean_squared_error: 0.1820 - val_loss: 0.6061 - val_root_mean_squared_error: 0.1976
    Epoch 11/50
    8067/8067 [==============================] - 69s 9ms/step - loss: 0.5911 - root_mean_squared_error: 0.1819 - val_loss: 0.6063 - val_root_mean_squared_error: 0.1978
    Epoch 12/50
    8067/8067 [==============================] - 67s 8ms/step - loss: 0.5908 - root_mean_squared_error: 0.1815 - val_loss: 0.6061 - val_root_mean_squared_error: 0.1975
    Epoch 13/50
    8067/8067 [==============================] - 69s 9ms/step - loss: 0.5905 - root_mean_squared_error: 0.1812 - val_loss: 0.6065 - val_root_mean_squared_error: 0.1978
    Epoch 14/50
    8067/8067 [==============================] - 72s 9ms/step - loss: 0.5905 - root_mean_squared_error: 0.1811 - val_loss: 0.6064 - val_root_mean_squared_error: 0.1978
    Epoch 15/50
    8067/8067 [==============================] - 71s 9ms/step - loss: 0.5900 - root_mean_squared_error: 0.1805 - val_loss: 0.6071 - val_root_mean_squared_error: 0.1985
    Epoch 16/50
    8067/8067 [==============================] - 75s 9ms/step - loss: 0.5899 - root_mean_squared_error: 0.1804 - val_loss: 0.6073 - val_root_mean_squared_error: 0.1985
    Epoch 17/50
    8067/8067 [==============================] - 78s 10ms/step - loss: 0.5897 - root_mean_squared_error: 0.1802 - val_loss: 0.6069 - val_root_mean_squared_error: 0.1981
    Epoch 18/50
    8067/8067 [==============================] - 78s 10ms/step - loss: 0.5898 - root_mean_squared_error: 0.1803 - val_loss: 0.6070 - val_root_mean_squared_error: 0.1982
    Epoch 19/50
    8067/8067 [==============================] - 77s 10ms/step - loss: 0.5897 - root_mean_squared_error: 0.1802 - val_loss: 0.6071 - val_root_mean_squared_error: 0.1983
    Epoch 20/50
    8067/8067 [==============================] - 73s 9ms/step - loss: 0.5892 - root_mean_squared_error: 0.1796 - val_loss: 0.6072 - val_root_mean_squared_error: 0.1984
    Epoch 21/50
    8067/8067 [==============================] - 68s 8ms/step - loss: 0.5895 - root_mean_squared_error: 0.1800 - val_loss: 0.6073 - val_root_mean_squared_error: 0.1985
    Epoch 22/50
    8067/8067 [==============================] - 68s 8ms/step - loss: 0.5889 - root_mean_squared_error: 0.1792 - val_loss: 0.6078 - val_root_mean_squared_error: 0.1989
    Epoch 23/50
    8067/8067 [==============================] - 73s 9ms/step - loss: 0.5892 - root_mean_squared_error: 0.1796 - val_loss: 0.6080 - val_root_mean_squared_error: 0.1991
    Epoch 24/50
    8067/8067 [==============================] - 78s 10ms/step - loss: 0.5888 - root_mean_squared_error: 0.1793 - val_loss: 0.6078 - val_root_mean_squared_error: 0.1989
    Epoch 25/50
    8067/8067 [==============================] - 70s 9ms/step - loss: 0.5891 - root_mean_squared_error: 0.1795 - val_loss: 0.6077 - val_root_mean_squared_error: 0.1987
    Epoch 26/50
    8067/8067 [==============================] - 73s 9ms/step - loss: 0.5887 - root_mean_squared_error: 0.1791 - val_loss: 0.6084 - val_root_mean_squared_error: 0.1995
    Epoch 27/50
    8067/8067 [==============================] - 71s 9ms/step - loss: 0.5887 - root_mean_squared_error: 0.1790 - val_loss: 0.6084 - val_root_mean_squared_error: 0.1996
    Epoch 28/50
    8067/8067 [==============================] - 70s 9ms/step - loss: 0.5886 - root_mean_squared_error: 0.1790 - val_loss: 0.6083 - val_root_mean_squared_error: 0.1993
    Epoch 29/50
    8067/8067 [==============================] - 66s 8ms/step - loss: 0.5887 - root_mean_squared_error: 0.1791 - val_loss: 0.6086 - val_root_mean_squared_error: 0.1996
    Epoch 30/50
    8067/8067 [==============================] - 67s 8ms/step - loss: 0.5886 - root_mean_squared_error: 0.1789 - val_loss: 0.6089 - val_root_mean_squared_error: 0.1999
    Epoch 31/50
    8067/8067 [==============================] - 72s 9ms/step - loss: 0.5885 - root_mean_squared_error: 0.1790 - val_loss: 0.6087 - val_root_mean_squared_error: 0.1997
    Epoch 32/50
    8067/8067 [==============================] - 69s 9ms/step - loss: 0.5883 - root_mean_squared_error: 0.1785 - val_loss: 0.6085 - val_root_mean_squared_error: 0.1994
    Epoch 33/50
    8067/8067 [==============================] - 66s 8ms/step - loss: 0.5886 - root_mean_squared_error: 0.1788 - val_loss: 0.6085 - val_root_mean_squared_error: 0.1995
    Epoch 34/50
    8067/8067 [==============================] - 66s 8ms/step - loss: 0.5883 - root_mean_squared_error: 0.1786 - val_loss: 0.6087 - val_root_mean_squared_error: 0.1997
    Epoch 35/50
    8067/8067 [==============================] - 69s 9ms/step - loss: 0.5881 - root_mean_squared_error: 0.1785 - val_loss: 0.6092 - val_root_mean_squared_error: 0.2001
    Epoch 36/50
    8067/8067 [==============================] - 79s 10ms/step - loss: 0.5884 - root_mean_squared_error: 0.1787 - val_loss: 0.6091 - val_root_mean_squared_error: 0.2001
    Epoch 37/50
    8067/8067 [==============================] - 72s 9ms/step - loss: 0.5879 - root_mean_squared_error: 0.1782 - val_loss: 0.6095 - val_root_mean_squared_error: 0.2005
    Epoch 38/50
    8067/8067 [==============================] - 73s 9ms/step - loss: 0.5880 - root_mean_squared_error: 0.1784 - val_loss: 0.6098 - val_root_mean_squared_error: 0.2007
    Epoch 39/50
    8067/8067 [==============================] - 72s 9ms/step - loss: 0.5882 - root_mean_squared_error: 0.1785 - val_loss: 0.6098 - val_root_mean_squared_error: 0.2005
    Epoch 40/50
    8067/8067 [==============================] - 71s 9ms/step - loss: 0.5881 - root_mean_squared_error: 0.1783 - val_loss: 0.6097 - val_root_mean_squared_error: 0.2004
    Epoch 41/50
    8067/8067 [==============================] - 70s 9ms/step - loss: 0.5879 - root_mean_squared_error: 0.1782 - val_loss: 0.6092 - val_root_mean_squared_error: 0.2000
    Epoch 42/50
    8067/8067 [==============================] - 69s 9ms/step - loss: 0.5880 - root_mean_squared_error: 0.1783 - val_loss: 0.6096 - val_root_mean_squared_error: 0.2004
    Epoch 43/50
    8067/8067 [==============================] - 72s 9ms/step - loss: 0.5879 - root_mean_squared_error: 0.1782 - val_loss: 0.6100 - val_root_mean_squared_error: 0.2008
    Epoch 44/50
    8067/8067 [==============================] - 69s 9ms/step - loss: 0.5881 - root_mean_squared_error: 0.1784 - val_loss: 0.6098 - val_root_mean_squared_error: 0.2006
    Epoch 45/50
    8067/8067 [==============================] - 69s 9ms/step - loss: 0.5875 - root_mean_squared_error: 0.1777 - val_loss: 0.6099 - val_root_mean_squared_error: 0.2006
    Epoch 46/50
    8067/8067 [==============================] - 71s 9ms/step - loss: 0.5881 - root_mean_squared_error: 0.1784 - val_loss: 0.6102 - val_root_mean_squared_error: 0.2010
    Epoch 47/50
    8067/8067 [==============================] - 74s 9ms/step - loss: 0.5876 - root_mean_squared_error: 0.1779 - val_loss: 0.6105 - val_root_mean_squared_error: 0.2013
    Epoch 48/50
    8067/8067 [==============================] - 72s 9ms/step - loss: 0.5878 - root_mean_squared_error: 0.1781 - val_loss: 0.6104 - val_root_mean_squared_error: 0.2010
    Epoch 49/50
    8067/8067 [==============================] - 72s 9ms/step - loss: 0.5875 - root_mean_squared_error: 0.1777 - val_loss: 0.6097 - val_root_mean_squared_error: 0.2004
    Epoch 50/50
    8067/8067 [==============================] - 70s 9ms/step - loss: 0.5876 - root_mean_squared_error: 0.1779 - val_loss: 0.6106 - val_root_mean_squared_error: 0.2012


### Visualisasi Metrik evalusai model

![png](assets/gambar-2.png)
    
Gambar 1. Visuaslisasi Metriks proses training

Proses training model cukup smooth dan model konvergen pada epochs sekitar 50. Dari proses ini, kita memperoleh nilai error akhir sebesar sekitar 0.17 dan error pada data validasi sebesar 0.20. Nilai tersebut cukup bagus untuk sistem rekomendasi.


### Mendapatkan Rekomendasi Movie

Untuk mendapatkan rekomendasi movie, ambil sampel user secara acak dan definisikan variabel *movie_not_visited* yang merupakan daftar movie yang belum pernah dikunjungi oleh pengguna. mengapa kita perlu menentukan daftar *movie_not_visited*? Hal ini karena daftar *movie_not_visited* inilah yang akan menjadi resto yang kita rekomendasikan. 

Sebelumnya, pengguna telah memberi rating pada beberapa *movie* yang telah mereka kunjungi. gunakan rating ini untuk membuat rekomendasi *movie* yang mungkin cocok untuk pengguna. *Movie* yang akan direkomendasikan adalah *movie* yang belum pernah dikunjungi oleh pengguna. Oleh karena itu, perlu membuat variabel *movie_not_visited* sebagai daftar *movie* untuk direkomendasikan pada pengguna. 

Ini adalah hasil rekomendasi *movie* dari sistem rekomendasi menggunakan metode *Collaborative Filtering*


    301/301 [==============================] - 0s 1ms/step
    Showing recommendations for users: 465
    ===========================
    Resto with high ratings from user
    --------------------------------
    Aliens (1986) : Action
    Apocalypse Now (1979) : Action
    Patton (1970) : Drama
    Blazing Saddles (1974) : Comedy
    M*A*S*H (a.k.a. MASH) (1970) : Comedy
    --------------------------------
    Top 10 resto recommendation
    --------------------------------
    Heidi Fleiss: Hollywood Madam (1995) : Documentary
    Paths of Glory (1957) : Drama
    Cruise, The (1998) : Documentary
    Jonah Who Will Be 25 in the Year 2000 (Jonas qui aura 25 ans en l'an 2000) (1976) : Comedy
    Stunt Man, The (1980) : Action
    Belle époque (1992) : Comedy
    Trial, The (Procès, Le) (1962) : Drama
    Adam's Rib (1949) : Comedy
    Bad Boy Bubby (1993) : Drama
    Enter the Void (2009) : Drama


# Evaluasi

### *Precision*

#### Untuk *Content Based Filtering* menggunakan metode *Precission*

Precision merupakan sebuah
pengujian dasar yang biasanya digunakan untuk menguji sistem rekomendasi [6]. TP atau
true positive berarti sistem yang menghasilkan informasi relevan, sedangkan FP atau false
positive berarti sistem yang menghasilkan seluruh item yang tersedia. Dengan kata lain,
precision merupakan pengujian yang membandingkan hasil dari sistem dengan informasi
yang diminta oleh pengguna. Precision dapat dihitung menggunakan persamaan (4).

$$ P = {TP \over TP+FP} * 100 $$

keterangan : 
- P = Precision
- TP = *True Positif*
- FP = *False Positif*

Berikut hasil evaluasi *Content Based Filtering* dengan metode *Precission* dari 5 data

| # | Title | Genre | Precision |
|---|-------|-------|-------------|
| 1 | Absent-Minded Professor, The (1961) | Children | 100% |
| 2 | In the Bedroom (2001) | Drama | 100% |
| 3 | Weirdsville (2007) | Comedy | 100% |
| 4 | Funny Girl (1968) | Drama | 100% |
| 5 | Only Angels Have Wings (1939) | Adventure | 100%|


### *RMSE*

#### Untuk *Collaborative Filtering* menggunakan metode *MSE*
RMSE (Root Mean Squared Error) adalah metrik evaluasi yang umum digunakan dalam pemodelan regresi untuk mengukur sejauh mana selisih antara nilai prediksi dan nilai sebenarnya. RMSE menghitung akar kuadrat dari rata-rata kesalahan kuadrat antara nilai prediksi dan nilai sebenarnya.

Rumus *RMSE* dapat dituliskan sebagai berikut:

$$ MSE = \sqrt{1/N \sum_{k=1}^n (y_p - y_a)^2 } $$


Keterangan:

N = jumlah dataset

ya = nilai sebenarnya

yp = nilai prediksi

Berikut hasil evaluasi *Collaborative Filtering* dengan metode *RMSE*

|  metode  | train                   | test     |
|-------------------------|----------|----------|
| collaborative_filtering | 0.203803 | 0.211049 |



# Kesimpulan

Dari percobaan yang telah dilakukan dapat disimpulak bahwa pada metode *Content Base Filtering* mempelajari profil minat pengguna atau berdasarkan  baru berdasarkan data dari objek yang telah dinilai sebelumnya oleh pengguna. Sedangkan, *Collaborative filtering* bergantung pada pendapat komunitas pengguna atau jumlah rating. Ia tidak memerlukan atribut untuk setiap itemnya seperti pada sistem berbasis konten. 

# Daftar Refrensi

1. Ricci, Francesco; Rokach, Lior; Shapira, Bracha (2022). "Recommender Systems: Techniques, Applications, and Challenges". In Ricci, Francesco; Rokach, Lior; Shapira, Bracha (eds.). Recommender Systems Handbook (3 ed.). New York: Springer. pp. 1–35. doi:10.1007/978-1-0716-2197-4_1. ISBN 978-1-0716-2196-7.
2. "playboy Lead Rise of Recommendation Engines - TIME". TIME.com. 27 May 2010. Archived from the original on May 30, 2010. Retrieved 1 June 2015.
3. Resnick, Paul, and Hal R. Varian. "Recommender systems." Communications of the ACM 40, no. 3 (1997): 56-58.
4. Pankaj Gupta, Ashish Goel, Jimmy Lin, Aneesh Sharma, Dong Wang, and Reza Bosagh Zadeh WTF:The who-to-follow system at Twitter, Proceedings of the 22nd international conference on World Wide Web
5. Baran, Remigiusz; Dziech, Andrzej; Zeja, Andrzej (2018-06-01). "A capable multimedia content discovery platform based on visual content analysis and intelligent data enrichment". Multimedia Tools and Applications. 77 (11): 14077–14091. doi:10.1007/s11042-017-5014-1. ISSN 1573-7721. S2CID 36511631.
6. H. Chen, A. G. Ororbia II, C. L. Giles ExpertSeer: a Keyphrase Based Expert Recommender for Digital Libraries, in arXiv preprint 2015
7. H. Chen, L. Gou, X. Zhang, C. Giles Collabseer: a search engine for collaboration discovery, in ACM/IEEE Joint Conference on Digital Libraries (JCDL) 2011
8. Alexander Felfernig, Klaus Isak, Kalman Szabo, Peter Zachar, The VITA Financial Services Sales Support Environment, in AAAI/IAAI 2007, pp. 1692-1699, Vancouver, Canada, 2007.
9. https://journal.untar.ac.id/index.php/computatio/article/view/17081

