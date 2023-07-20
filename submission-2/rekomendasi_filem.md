```python
!jupyter nbconvert --to markdown rekomendasi_filem.ipynb
```

    [NbConvertApp] Converting notebook rekomendasi_filem.ipynb to markdown
    [NbConvertApp] Support files will be in rekomendasi_filem_files/
    [NbConvertApp] Making directory rekomendasi_filem_files
    [NbConvertApp] Writing 265357 bytes to rekomendasi_filem.md


# Project Overview

Sistem pemberi rekomendasi atau sistem rekomendasi adalah subkelas dari sistem penyaringan informasi yang memberikan saran untuk item yang paling relevan dengan pengguna tertentu. [1] [2] Biasanya, saran mengacu pada berbagai proses pengambilan keputusan, seperti produk apa yang akan dibeli, musik apa yang akan didengarkan, atau berita online apa yang akan dibaca. [1] Sistem rekomendasi sangat berguna ketika seseorang perlu memilih item dari jumlah item yang mungkin ditawarkan oleh suatu layanan. [1] [3]

Sistem pemberi rekomendasi digunakan di berbagai area, dengan contoh umum yang dikenal dalam bentuk generator daftar putar untuk layanan video dan musik, pemberi rekomendasi produk untuk toko online, atau pemberi rekomendasi konten untuk platform media sosial dan pemberi rekomendasi konten web terbuka. [4] [5] Sistem ini dapat beroperasi menggunakan satu input, seperti musik, atau beberapa input di dalam dan lintas platform seperti berita, buku, dan permintaan pencarian. Ada juga sistem rekomendasi populer untuk topik tertentu seperti restoran dan kencan online . Sistem pemberi rekomendasi juga telah dikembangkan untuk mengeksplorasi artikel penelitian dan pakar, [6] kolaborator, [7] dan jasa keuangan. [8]

Banyaknya film yang telah diproduksi dari berbagai kategori seperti drama, komedi, horor, dan lain-lain menyebabkan penonton memiliki banyak pilihan film yang akan ditonton. Sistem rekomendasi merupakan sebuah sistem komputer yang membantu membuat suatu keputusan dengan memberikan saran kepada pengguna melalui pemrosesan data pada sistem. Dengan adanya pemanfaatan teknologi informasi dibutuhkan suatu sistem yang memudahkan penonton dalam memilih film yang ditonton. Tujuan dari kajian ini yaitu merancang sebuah sistem rekomendasi film bagi kalangan konsumen perfilman. [9]

# Business Understanding

Beberapa tujuan dan fungsi sistem rekomendasi secara umum adalah sebagai berikut:

- Meningkatkan jumlah item yang terjual.
Salah satu tujuan paling penting dari sistem rekomendasi di bidang komersial adalah meningkatkan jumlah item yang terjual. Tujuan ini bisa dicapai karena item yang direkomendasikan biasanya merupakan barang yang memang dibutuhkan oleh pengguna. Sementara itu, di bidang non-komersial peningkatan yang diharapkan dari sistem rekomendasi antara lain, conversion rate, click rate, dan jumlah kunjungan.

- Menjual item yang beragam.
Sistem rekomendasi memungkinkan pengguna untuk menemukan item yang sulit dicari. Sebagai contoh, organisasi atau bisnis tentu ingin mempromosikan semua item yang dimilikinya, tidak hanya item yang populer saja. Item non-populer seperti ini kadang tidak muncul di beranda item best-seller. Nah, organisasi atau bisnis bisa merekomendasikan item tersebut pada pengguna yang tepat. Dengan cara ini, item yang dijual pun tidak melulu item populer, melainkan lebih beragam.

- Meningkatkan kepuasan pengguna.
Sistem rekomendasi yang dirancang dengan baik dapat meningkatkan pengalaman pengguna saat menggunakan situs atau aplikasi. Pengguna akan menemukan rekomendasi yang menarik dan relevan. Kombinasi antara rekomendasi yang efektif dan akurat serta user-interface yang dirancang dengan baik akan meningkatkan kepuasan pengguna terhadap sistem. Sehingga, tingkat kemungkinan untuk rekomendasi tersebut diterima oleh pengguna juga semakin meningkat.

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


# Data Preparation

# Modeling and Result

# Evaluation

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



# Data Understanding
Data ini terdiri dari beberapa file yaitu :
- movies.csv : berisi data movieId, title dan genres, berjumlah 9742 data
- ratings.csv : berisi data userId, movieId, rating dan timestamp berjumlah 9742 data
- tags.csv : berisi data userId, movieId, tag dan timestamp, yang berjumlah 1572 data
- links.csv : berisi data movieId, imdbId dan tmdbId, berjumlah 9742 data


```python
import pandas as pd
```


```python
movies = pd.read_csv('drive/MyDrive/dicoding/ml-latest-small/movies.csv')
ratings = pd.read_csv('drive/MyDrive/dicoding/ml-latest-small/ratings.csv')
tags = pd.read_csv('drive/MyDrive/dicoding/ml-latest-small/tags.csv')
links = pd.read_csv('drive/MyDrive/dicoding/ml-latest-small/links.csv')

print('Jumlah data movies ', len(movies.movieId.unique()))
print('Jumlah data ratings ', len(ratings.movieId.unique()))
print('Jumlah data tags ', len(tags.movieId.unique()))
print('Jumlah data links ', len(links.movieId.unique()))
```

    Jumlah data movies  9742
    Jumlah data ratings  9724
    Jumlah data tags  1572
    Jumlah data links  9742


###Univariate Exploratory Data Analysis
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


Normalisasi data genres


```python
movies
```






  <div id="df-1e78dc4e-3e36-4181-82d3-5a88b4dfcbad">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>movieId</th>
      <th>title</th>
      <th>genres</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Jumanji (1995)</td>
      <td>Adventure|Children|Fantasy</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Grumpier Old Men (1995)</td>
      <td>Comedy|Romance</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>Waiting to Exhale (1995)</td>
      <td>Comedy|Drama|Romance</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>Father of the Bride Part II (1995)</td>
      <td>Comedy</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>9737</th>
      <td>193581</td>
      <td>Black Butler: Book of the Atlantic (2017)</td>
      <td>Action|Animation|Comedy|Fantasy</td>
    </tr>
    <tr>
      <th>9738</th>
      <td>193583</td>
      <td>No Game No Life: Zero (2017)</td>
      <td>Animation|Comedy|Fantasy</td>
    </tr>
    <tr>
      <th>9739</th>
      <td>193585</td>
      <td>Flint (2017)</td>
      <td>Drama</td>
    </tr>
    <tr>
      <th>9740</th>
      <td>193587</td>
      <td>Bungo Stray Dogs: Dead Apple (2018)</td>
      <td>Action|Animation</td>
    </tr>
    <tr>
      <th>9741</th>
      <td>193609</td>
      <td>Andrew Dice Clay: Dice Rules (1991)</td>
      <td>Comedy</td>
    </tr>
  </tbody>
</table>
<p>9742 rows × 3 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-1e78dc4e-3e36-4181-82d3-5a88b4dfcbad')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-743c7410-6f48-4b7e-b2a1-2c01262f387c">
      <button class="colab-df-quickchart" onclick="quickchart('df-743c7410-6f48-4b7e-b2a1-2c01262f387c')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-743c7410-6f48-4b7e-b2a1-2c01262f387c button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-1e78dc4e-3e36-4181-82d3-5a88b4dfcbad button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-1e78dc4e-3e36-4181-82d3-5a88b4dfcbad');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>




# Data Processing


```python
movies
```






  <div id="df-a83740cc-fb16-4787-be4b-28e6bc53d452">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>movieId</th>
      <th>title</th>
      <th>genres</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Jumanji (1995)</td>
      <td>Adventure|Children|Fantasy</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Grumpier Old Men (1995)</td>
      <td>Comedy|Romance</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>Waiting to Exhale (1995)</td>
      <td>Comedy|Drama|Romance</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>Father of the Bride Part II (1995)</td>
      <td>Comedy</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>9737</th>
      <td>193581</td>
      <td>Black Butler: Book of the Atlantic (2017)</td>
      <td>Action|Animation|Comedy|Fantasy</td>
    </tr>
    <tr>
      <th>9738</th>
      <td>193583</td>
      <td>No Game No Life: Zero (2017)</td>
      <td>Animation|Comedy|Fantasy</td>
    </tr>
    <tr>
      <th>9739</th>
      <td>193585</td>
      <td>Flint (2017)</td>
      <td>Drama</td>
    </tr>
    <tr>
      <th>9740</th>
      <td>193587</td>
      <td>Bungo Stray Dogs: Dead Apple (2018)</td>
      <td>Action|Animation</td>
    </tr>
    <tr>
      <th>9741</th>
      <td>193609</td>
      <td>Andrew Dice Clay: Dice Rules (1991)</td>
      <td>Comedy</td>
    </tr>
  </tbody>
</table>
<p>9742 rows × 3 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-a83740cc-fb16-4787-be4b-28e6bc53d452')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-9323090c-c85c-46f9-bd70-3e380de85519">
      <button class="colab-df-quickchart" onclick="quickchart('df-9323090c-c85c-46f9-bd70-3e380de85519')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-9323090c-c85c-46f9-bd70-3e380de85519 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-a83740cc-fb16-4787-be4b-28e6bc53d452 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-a83740cc-fb16-4787-be4b-28e6bc53d452');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
ratings
```






  <div id="df-cea9528f-97b0-42ea-9e93-eedacc50a1be">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userId</th>
      <th>movieId</th>
      <th>rating</th>
      <th>timestamp</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>1</td>
      <td>4.0</td>
      <td>964982703</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1</td>
      <td>3</td>
      <td>4.0</td>
      <td>964981247</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1</td>
      <td>6</td>
      <td>4.0</td>
      <td>964982224</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1</td>
      <td>47</td>
      <td>5.0</td>
      <td>964983815</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1</td>
      <td>50</td>
      <td>5.0</td>
      <td>964982931</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>100831</th>
      <td>610</td>
      <td>166534</td>
      <td>4.0</td>
      <td>1493848402</td>
    </tr>
    <tr>
      <th>100832</th>
      <td>610</td>
      <td>168248</td>
      <td>5.0</td>
      <td>1493850091</td>
    </tr>
    <tr>
      <th>100833</th>
      <td>610</td>
      <td>168250</td>
      <td>5.0</td>
      <td>1494273047</td>
    </tr>
    <tr>
      <th>100834</th>
      <td>610</td>
      <td>168252</td>
      <td>5.0</td>
      <td>1493846352</td>
    </tr>
    <tr>
      <th>100835</th>
      <td>610</td>
      <td>170875</td>
      <td>3.0</td>
      <td>1493846415</td>
    </tr>
  </tbody>
</table>
<p>100836 rows × 4 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-cea9528f-97b0-42ea-9e93-eedacc50a1be')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-fb15f34e-0007-439b-a2cc-83962af40f32">
      <button class="colab-df-quickchart" onclick="quickchart('df-fb15f34e-0007-439b-a2cc-83962af40f32')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-fb15f34e-0007-439b-a2cc-83962af40f32 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-cea9528f-97b0-42ea-9e93-eedacc50a1be button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-cea9528f-97b0-42ea-9e93-eedacc50a1be');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
links
```






  <div id="df-e0118b73-4e0a-4bf4-b377-cd50325a7b54">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>movieId</th>
      <th>imdbId</th>
      <th>tmdbId</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>114709</td>
      <td>862.0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>113497</td>
      <td>8844.0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>113228</td>
      <td>15602.0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>114885</td>
      <td>31357.0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>113041</td>
      <td>11862.0</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>9737</th>
      <td>193581</td>
      <td>5476944</td>
      <td>432131.0</td>
    </tr>
    <tr>
      <th>9738</th>
      <td>193583</td>
      <td>5914996</td>
      <td>445030.0</td>
    </tr>
    <tr>
      <th>9739</th>
      <td>193585</td>
      <td>6397426</td>
      <td>479308.0</td>
    </tr>
    <tr>
      <th>9740</th>
      <td>193587</td>
      <td>8391976</td>
      <td>483455.0</td>
    </tr>
    <tr>
      <th>9741</th>
      <td>193609</td>
      <td>101726</td>
      <td>37891.0</td>
    </tr>
  </tbody>
</table>
<p>9742 rows × 3 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-e0118b73-4e0a-4bf4-b377-cd50325a7b54')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-595bf69e-76cf-4528-97dc-47c37d45f529">
      <button class="colab-df-quickchart" onclick="quickchart('df-595bf69e-76cf-4528-97dc-47c37d45f529')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-595bf69e-76cf-4528-97dc-47c37d45f529 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-e0118b73-4e0a-4bf4-b377-cd50325a7b54 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-e0118b73-4e0a-4bf4-b377-cd50325a7b54');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
tags
```






  <div id="df-5b7bde5d-d338-40c0-a8f8-a5f1c96c628b">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userId</th>
      <th>movieId</th>
      <th>tag</th>
      <th>timestamp</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2</td>
      <td>60756</td>
      <td>funny</td>
      <td>1445714994</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>60756</td>
      <td>Highly quotable</td>
      <td>1445714996</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2</td>
      <td>60756</td>
      <td>will ferrell</td>
      <td>1445714992</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2</td>
      <td>89774</td>
      <td>Boxing story</td>
      <td>1445715207</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2</td>
      <td>89774</td>
      <td>MMA</td>
      <td>1445715200</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>3678</th>
      <td>606</td>
      <td>7382</td>
      <td>for katie</td>
      <td>1171234019</td>
    </tr>
    <tr>
      <th>3679</th>
      <td>606</td>
      <td>7936</td>
      <td>austere</td>
      <td>1173392334</td>
    </tr>
    <tr>
      <th>3680</th>
      <td>610</td>
      <td>3265</td>
      <td>gun fu</td>
      <td>1493843984</td>
    </tr>
    <tr>
      <th>3681</th>
      <td>610</td>
      <td>3265</td>
      <td>heroic bloodshed</td>
      <td>1493843978</td>
    </tr>
    <tr>
      <th>3682</th>
      <td>610</td>
      <td>168248</td>
      <td>Heroic Bloodshed</td>
      <td>1493844270</td>
    </tr>
  </tbody>
</table>
<p>3683 rows × 4 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-5b7bde5d-d338-40c0-a8f8-a5f1c96c628b')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-27c87d8a-21c1-4a17-8e18-b086fab118da">
      <button class="colab-df-quickchart" onclick="quickchart('df-27c87d8a-21c1-4a17-8e18-b086fab118da')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-27c87d8a-21c1-4a17-8e18-b086fab118da button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-5b7bde5d-d338-40c0-a8f8-a5f1c96c628b button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-5b7bde5d-d338-40c0-a8f8-a5f1c96c628b');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
ratings.describe()
```






  <div id="df-40653779-76f4-4784-acf8-bef4fa2829bd">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userId</th>
      <th>movieId</th>
      <th>rating</th>
      <th>timestamp</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>100836.000000</td>
      <td>100836.000000</td>
      <td>100836.000000</td>
      <td>1.008360e+05</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>326.127564</td>
      <td>19435.295718</td>
      <td>3.501557</td>
      <td>1.205946e+09</td>
    </tr>
    <tr>
      <th>std</th>
      <td>182.618491</td>
      <td>35530.987199</td>
      <td>1.042529</td>
      <td>2.162610e+08</td>
    </tr>
    <tr>
      <th>min</th>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>0.500000</td>
      <td>8.281246e+08</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>177.000000</td>
      <td>1199.000000</td>
      <td>3.000000</td>
      <td>1.019124e+09</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>325.000000</td>
      <td>2991.000000</td>
      <td>3.500000</td>
      <td>1.186087e+09</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>477.000000</td>
      <td>8122.000000</td>
      <td>4.000000</td>
      <td>1.435994e+09</td>
    </tr>
    <tr>
      <th>max</th>
      <td>610.000000</td>
      <td>193609.000000</td>
      <td>5.000000</td>
      <td>1.537799e+09</td>
    </tr>
  </tbody>
</table>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-40653779-76f4-4784-acf8-bef4fa2829bd')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-fe6760bd-bb0f-4beb-93f0-8a45c9a9b676">
      <button class="colab-df-quickchart" onclick="quickchart('df-fe6760bd-bb0f-4beb-93f0-8a45c9a9b676')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-fe6760bd-bb0f-4beb-93f0-8a45c9a9b676 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-40653779-76f4-4784-acf8-bef4fa2829bd button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-40653779-76f4-4784-acf8-bef4fa2829bd');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
print('Jumlah userId: ', len(ratings.userId.unique()))
print('Jumlah movieId: ', len(movies.movieId.unique()))
print('Jumlah data rating: ', len(ratings))
```

    Jumlah userId:  610
    Jumlah movieId:  9742
    Jumlah data rating:  100836


#### Mengetahui jumlah seluruh movie


```python
import numpy as np

movies_all = np.concatenate((
    movies.movieId.unique(),
    ratings.movieId.unique(),
    links.movieId.unique(),
    tags.movieId.unique(),
))

movies_all = np.sort(np.unique(movies_all))

print('Jumlah seluruh data movies berdasarkan movieId: ', len(movies_all))
```

    Jumlah seluruh data movies berdasarkan movieId:  9742


#### Mengetahui jumlah seluruh user berdasarkan rating


```python
users_all = np.concatenate((
    ratings.userId.unique(),
    tags.userId.unique()
))

users_all = np.sort(np.unique(users_all))

print('Jumlah seluruh data users berdasarkan userId: ', len(users_all))
```

    Jumlah seluruh data users berdasarkan userId:  610


### Menggabungkan data movie






```python
movie_info = pd.concat([movies, links])

movie = pd.merge(ratings, movie_info[['movieId','title', 'genres']], on='movieId', how='left')

movie
```






  <div id="df-74984cb5-f836-4696-94af-d37414f3e18f">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userId</th>
      <th>movieId</th>
      <th>rating</th>
      <th>timestamp</th>
      <th>title</th>
      <th>genres</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>1</td>
      <td>4.0</td>
      <td>964982703</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1</td>
      <td>1</td>
      <td>4.0</td>
      <td>964982703</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1</td>
      <td>3</td>
      <td>4.0</td>
      <td>964981247</td>
      <td>Grumpier Old Men (1995)</td>
      <td>Comedy|Romance</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1</td>
      <td>3</td>
      <td>4.0</td>
      <td>964981247</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1</td>
      <td>6</td>
      <td>4.0</td>
      <td>964982224</td>
      <td>Heat (1995)</td>
      <td>Action|Crime|Thriller</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>201667</th>
      <td>610</td>
      <td>168250</td>
      <td>5.0</td>
      <td>1494273047</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>201668</th>
      <td>610</td>
      <td>168252</td>
      <td>5.0</td>
      <td>1493846352</td>
      <td>Logan (2017)</td>
      <td>Action|Sci-Fi</td>
    </tr>
    <tr>
      <th>201669</th>
      <td>610</td>
      <td>168252</td>
      <td>5.0</td>
      <td>1493846352</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>201670</th>
      <td>610</td>
      <td>170875</td>
      <td>3.0</td>
      <td>1493846415</td>
      <td>The Fate of the Furious (2017)</td>
      <td>Action|Crime|Drama|Thriller</td>
    </tr>
    <tr>
      <th>201671</th>
      <td>610</td>
      <td>170875</td>
      <td>3.0</td>
      <td>1493846415</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>201672 rows × 6 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-74984cb5-f836-4696-94af-d37414f3e18f')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-7c6e1ed7-fafa-4a60-8704-2b899ad4a907">
      <button class="colab-df-quickchart" onclick="quickchart('df-7c6e1ed7-fafa-4a60-8704-2b899ad4a907')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-7c6e1ed7-fafa-4a60-8704-2b899ad4a907 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-74984cb5-f836-4696-94af-d37414f3e18f button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-74984cb5-f836-4696-94af-d37414f3e18f');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>







```python
movie.isnull().sum()
```




    userId            0
    movieId           0
    rating            0
    timestamp         0
    title        100836
    genres       100836
    dtype: int64



menghitung jumlah rating berdasarkan movieId


```python
movie.groupby('movieId').sum()
```

    <ipython-input-14-906aff00c8b5>:1: FutureWarning: The default value of numeric_only in DataFrameGroupBy.sum is deprecated. In a future version, numeric_only will default to False. Either specify numeric_only or select only columns which should be valid for the function.
      movie.groupby('movieId').sum()







  <div id="df-c1c677a0-b867-4c6f-bca8-8dd8b3a995ca">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userId</th>
      <th>rating</th>
      <th>timestamp</th>
    </tr>
    <tr>
      <th>movieId</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>131808</td>
      <td>1686.0</td>
      <td>485828910958</td>
    </tr>
    <tr>
      <th>2</th>
      <td>72502</td>
      <td>755.0</td>
      <td>249877166644</td>
    </tr>
    <tr>
      <th>3</th>
      <td>29494</td>
      <td>339.0</td>
      <td>104531468772</td>
    </tr>
    <tr>
      <th>4</th>
      <td>3078</td>
      <td>33.0</td>
      <td>12580104096</td>
    </tr>
    <tr>
      <th>5</th>
      <td>29358</td>
      <td>301.0</td>
      <td>97281105188</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>193581</th>
      <td>368</td>
      <td>8.0</td>
      <td>3074218164</td>
    </tr>
    <tr>
      <th>193583</th>
      <td>368</td>
      <td>7.0</td>
      <td>3074219090</td>
    </tr>
    <tr>
      <th>193585</th>
      <td>368</td>
      <td>7.0</td>
      <td>3074219610</td>
    </tr>
    <tr>
      <th>193587</th>
      <td>368</td>
      <td>7.0</td>
      <td>3074220042</td>
    </tr>
    <tr>
      <th>193609</th>
      <td>662</td>
      <td>8.0</td>
      <td>3074315212</td>
    </tr>
  </tbody>
</table>
<p>9724 rows × 3 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-c1c677a0-b867-4c6f-bca8-8dd8b3a995ca')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-43544f7a-4ec8-4333-a41c-f36eda9d50cc">
      <button class="colab-df-quickchart" onclick="quickchart('df-43544f7a-4ec8-4333-a41c-f36eda9d50cc')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-43544f7a-4ec8-4333-a41c-f36eda9d50cc button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-c1c677a0-b867-4c6f-bca8-8dd8b3a995ca button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-c1c677a0-b867-4c6f-bca8-8dd8b3a995ca');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
all_movie = movie
all_movie
```






  <div id="df-0fa131cd-5d6f-4970-b3f0-10f597a49161">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userId</th>
      <th>movieId</th>
      <th>rating</th>
      <th>timestamp</th>
      <th>title</th>
      <th>genres</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>1</td>
      <td>4.0</td>
      <td>964982703</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1</td>
      <td>1</td>
      <td>4.0</td>
      <td>964982703</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1</td>
      <td>3</td>
      <td>4.0</td>
      <td>964981247</td>
      <td>Grumpier Old Men (1995)</td>
      <td>Comedy|Romance</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1</td>
      <td>3</td>
      <td>4.0</td>
      <td>964981247</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1</td>
      <td>6</td>
      <td>4.0</td>
      <td>964982224</td>
      <td>Heat (1995)</td>
      <td>Action|Crime|Thriller</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>201667</th>
      <td>610</td>
      <td>168250</td>
      <td>5.0</td>
      <td>1494273047</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>201668</th>
      <td>610</td>
      <td>168252</td>
      <td>5.0</td>
      <td>1493846352</td>
      <td>Logan (2017)</td>
      <td>Action|Sci-Fi</td>
    </tr>
    <tr>
      <th>201669</th>
      <td>610</td>
      <td>168252</td>
      <td>5.0</td>
      <td>1493846352</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>201670</th>
      <td>610</td>
      <td>170875</td>
      <td>3.0</td>
      <td>1493846415</td>
      <td>The Fate of the Furious (2017)</td>
      <td>Action|Crime|Drama|Thriller</td>
    </tr>
    <tr>
      <th>201671</th>
      <td>610</td>
      <td>170875</td>
      <td>3.0</td>
      <td>1493846415</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>201672 rows × 6 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-0fa131cd-5d6f-4970-b3f0-10f597a49161')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-e0fb435d-179f-4321-829b-76138ac41297">
      <button class="colab-df-quickchart" onclick="quickchart('df-e0fb435d-179f-4321-829b-76138ac41297')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-e0fb435d-179f-4321-829b-76138ac41297 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-0fa131cd-5d6f-4970-b3f0-10f597a49161 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-0fa131cd-5d6f-4970-b3f0-10f597a49161');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>




data yang digunakan untuk membuat sistem rekomendasi

# Data Preparation
### Mengatasi Missing Value

Cek missing value dari data movie


```python
all_movie.isnull().sum()
```




    userId            0
    movieId           0
    rating            0
    timestamp         0
    title        100836
    genres       100836
    dtype: int64



menghapus data yang bernilai null


```python
all_movie_clean = all_movie.dropna()

all_movie_clean
```






  <div id="df-b5dd96a2-3ea5-4174-b5f5-1d37a4e07a3c">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userId</th>
      <th>movieId</th>
      <th>rating</th>
      <th>timestamp</th>
      <th>title</th>
      <th>genres</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>1</td>
      <td>4.0</td>
      <td>964982703</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1</td>
      <td>3</td>
      <td>4.0</td>
      <td>964981247</td>
      <td>Grumpier Old Men (1995)</td>
      <td>Comedy|Romance</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1</td>
      <td>6</td>
      <td>4.0</td>
      <td>964982224</td>
      <td>Heat (1995)</td>
      <td>Action|Crime|Thriller</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1</td>
      <td>47</td>
      <td>5.0</td>
      <td>964983815</td>
      <td>Seven (a.k.a. Se7en) (1995)</td>
      <td>Mystery|Thriller</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1</td>
      <td>50</td>
      <td>5.0</td>
      <td>964982931</td>
      <td>Usual Suspects, The (1995)</td>
      <td>Crime|Mystery|Thriller</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>201662</th>
      <td>610</td>
      <td>166534</td>
      <td>4.0</td>
      <td>1493848402</td>
      <td>Split (2017)</td>
      <td>Drama|Horror|Thriller</td>
    </tr>
    <tr>
      <th>201664</th>
      <td>610</td>
      <td>168248</td>
      <td>5.0</td>
      <td>1493850091</td>
      <td>John Wick: Chapter Two (2017)</td>
      <td>Action|Crime|Thriller</td>
    </tr>
    <tr>
      <th>201666</th>
      <td>610</td>
      <td>168250</td>
      <td>5.0</td>
      <td>1494273047</td>
      <td>Get Out (2017)</td>
      <td>Horror</td>
    </tr>
    <tr>
      <th>201668</th>
      <td>610</td>
      <td>168252</td>
      <td>5.0</td>
      <td>1493846352</td>
      <td>Logan (2017)</td>
      <td>Action|Sci-Fi</td>
    </tr>
    <tr>
      <th>201670</th>
      <td>610</td>
      <td>170875</td>
      <td>3.0</td>
      <td>1493846415</td>
      <td>The Fate of the Furious (2017)</td>
      <td>Action|Crime|Drama|Thriller</td>
    </tr>
  </tbody>
</table>
<p>100836 rows × 6 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-b5dd96a2-3ea5-4174-b5f5-1d37a4e07a3c')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-27991a6c-3ba9-4621-bf6d-d6d9d403b9e6">
      <button class="colab-df-quickchart" onclick="quickchart('df-27991a6c-3ba9-4621-bf6d-d6d9d403b9e6')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-27991a6c-3ba9-4621-bf6d-d6d9d403b9e6 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-b5dd96a2-3ea5-4174-b5f5-1d37a4e07a3c button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-b5dd96a2-3ea5-4174-b5f5-1d37a4e07a3c');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>




Menormalisasi data genre


```python
fix_movie = all_movie_clean.sort_values('movieId', ascending=True)
fix_movie
```






  <div id="df-2617d07e-0bc7-4548-a12c-3b22805de972">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userId</th>
      <th>movieId</th>
      <th>rating</th>
      <th>timestamp</th>
      <th>title</th>
      <th>genres</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>1</td>
      <td>4.0</td>
      <td>964982703</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
    </tr>
    <tr>
      <th>163062</th>
      <td>517</td>
      <td>1</td>
      <td>4.0</td>
      <td>1487954343</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
    </tr>
    <tr>
      <th>61034</th>
      <td>213</td>
      <td>1</td>
      <td>3.5</td>
      <td>1316196157</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
    </tr>
    <tr>
      <th>162164</th>
      <td>514</td>
      <td>1</td>
      <td>4.0</td>
      <td>1533872400</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
    </tr>
    <tr>
      <th>61202</th>
      <td>214</td>
      <td>1</td>
      <td>3.0</td>
      <td>853937855</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>54512</th>
      <td>184</td>
      <td>193581</td>
      <td>4.0</td>
      <td>1537109082</td>
      <td>Black Butler: Book of the Atlantic (2017)</td>
      <td>Action|Animation|Comedy|Fantasy</td>
    </tr>
    <tr>
      <th>54514</th>
      <td>184</td>
      <td>193583</td>
      <td>3.5</td>
      <td>1537109545</td>
      <td>No Game No Life: Zero (2017)</td>
      <td>Animation|Comedy|Fantasy</td>
    </tr>
    <tr>
      <th>54516</th>
      <td>184</td>
      <td>193585</td>
      <td>3.5</td>
      <td>1537109805</td>
      <td>Flint (2017)</td>
      <td>Drama</td>
    </tr>
    <tr>
      <th>54518</th>
      <td>184</td>
      <td>193587</td>
      <td>3.5</td>
      <td>1537110021</td>
      <td>Bungo Stray Dogs: Dead Apple (2018)</td>
      <td>Action|Animation</td>
    </tr>
    <tr>
      <th>102724</th>
      <td>331</td>
      <td>193609</td>
      <td>4.0</td>
      <td>1537157606</td>
      <td>Andrew Dice Clay: Dice Rules (1991)</td>
      <td>Comedy</td>
    </tr>
  </tbody>
</table>
<p>100836 rows × 6 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-2617d07e-0bc7-4548-a12c-3b22805de972')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-8b4ba55a-1950-4b6b-8144-e4c21d7b7906">
      <button class="colab-df-quickchart" onclick="quickchart('df-8b4ba55a-1950-4b6b-8144-e4c21d7b7906')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-8b4ba55a-1950-4b6b-8144-e4c21d7b7906 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-2617d07e-0bc7-4548-a12c-3b22805de972 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-2617d07e-0bc7-4548-a12c-3b22805de972');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
len(fix_movie.movieId.unique())
```




    9724




```python
fix_movie.genres.unique()
```




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




```python
fix_movie['genre']=fix_movie['genres'].str.split('|').str[0]
fix_movie
```






  <div id="df-375bfe72-5c70-475c-ba21-cbf12020b35e">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userId</th>
      <th>movieId</th>
      <th>rating</th>
      <th>timestamp</th>
      <th>title</th>
      <th>genres</th>
      <th>genre</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>1</td>
      <td>4.0</td>
      <td>964982703</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>163062</th>
      <td>517</td>
      <td>1</td>
      <td>4.0</td>
      <td>1487954343</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>61034</th>
      <td>213</td>
      <td>1</td>
      <td>3.5</td>
      <td>1316196157</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>162164</th>
      <td>514</td>
      <td>1</td>
      <td>4.0</td>
      <td>1533872400</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>61202</th>
      <td>214</td>
      <td>1</td>
      <td>3.0</td>
      <td>853937855</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>54512</th>
      <td>184</td>
      <td>193581</td>
      <td>4.0</td>
      <td>1537109082</td>
      <td>Black Butler: Book of the Atlantic (2017)</td>
      <td>Action|Animation|Comedy|Fantasy</td>
      <td>Action</td>
    </tr>
    <tr>
      <th>54514</th>
      <td>184</td>
      <td>193583</td>
      <td>3.5</td>
      <td>1537109545</td>
      <td>No Game No Life: Zero (2017)</td>
      <td>Animation|Comedy|Fantasy</td>
      <td>Animation</td>
    </tr>
    <tr>
      <th>54516</th>
      <td>184</td>
      <td>193585</td>
      <td>3.5</td>
      <td>1537109805</td>
      <td>Flint (2017)</td>
      <td>Drama</td>
      <td>Drama</td>
    </tr>
    <tr>
      <th>54518</th>
      <td>184</td>
      <td>193587</td>
      <td>3.5</td>
      <td>1537110021</td>
      <td>Bungo Stray Dogs: Dead Apple (2018)</td>
      <td>Action|Animation</td>
      <td>Action</td>
    </tr>
    <tr>
      <th>102724</th>
      <td>331</td>
      <td>193609</td>
      <td>4.0</td>
      <td>1537157606</td>
      <td>Andrew Dice Clay: Dice Rules (1991)</td>
      <td>Comedy</td>
      <td>Comedy</td>
    </tr>
  </tbody>
</table>
<p>100836 rows × 7 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-375bfe72-5c70-475c-ba21-cbf12020b35e')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-2fbfe816-39f4-4959-afb3-9075400dbafb">
      <button class="colab-df-quickchart" onclick="quickchart('df-2fbfe816-39f4-4959-afb3-9075400dbafb')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-2fbfe816-39f4-4959-afb3-9075400dbafb button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-375bfe72-5c70-475c-ba21-cbf12020b35e button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-375bfe72-5c70-475c-ba21-cbf12020b35e');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
preparation = fix_movie
preparation.sort_values('movieId')
```






  <div id="df-a2a5f8fa-d2d4-40a9-83a0-3f5c0c033b17">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userId</th>
      <th>movieId</th>
      <th>rating</th>
      <th>timestamp</th>
      <th>title</th>
      <th>genres</th>
      <th>genre</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>1</td>
      <td>4.0</td>
      <td>964982703</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>179808</th>
      <td>584</td>
      <td>1</td>
      <td>5.0</td>
      <td>834987643</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>116192</th>
      <td>381</td>
      <td>1</td>
      <td>3.5</td>
      <td>1164383653</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>178632</th>
      <td>580</td>
      <td>1</td>
      <td>3.0</td>
      <td>1167792349</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>122240</th>
      <td>399</td>
      <td>1</td>
      <td>4.0</td>
      <td>1167220428</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>54512</th>
      <td>184</td>
      <td>193581</td>
      <td>4.0</td>
      <td>1537109082</td>
      <td>Black Butler: Book of the Atlantic (2017)</td>
      <td>Action|Animation|Comedy|Fantasy</td>
      <td>Action</td>
    </tr>
    <tr>
      <th>54514</th>
      <td>184</td>
      <td>193583</td>
      <td>3.5</td>
      <td>1537109545</td>
      <td>No Game No Life: Zero (2017)</td>
      <td>Animation|Comedy|Fantasy</td>
      <td>Animation</td>
    </tr>
    <tr>
      <th>54516</th>
      <td>184</td>
      <td>193585</td>
      <td>3.5</td>
      <td>1537109805</td>
      <td>Flint (2017)</td>
      <td>Drama</td>
      <td>Drama</td>
    </tr>
    <tr>
      <th>54518</th>
      <td>184</td>
      <td>193587</td>
      <td>3.5</td>
      <td>1537110021</td>
      <td>Bungo Stray Dogs: Dead Apple (2018)</td>
      <td>Action|Animation</td>
      <td>Action</td>
    </tr>
    <tr>
      <th>102724</th>
      <td>331</td>
      <td>193609</td>
      <td>4.0</td>
      <td>1537157606</td>
      <td>Andrew Dice Clay: Dice Rules (1991)</td>
      <td>Comedy</td>
      <td>Comedy</td>
    </tr>
  </tbody>
</table>
<p>100836 rows × 7 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-a2a5f8fa-d2d4-40a9-83a0-3f5c0c033b17')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-e28b4772-6bc2-436b-bcb8-eaa6e11b86e7">
      <button class="colab-df-quickchart" onclick="quickchart('df-e28b4772-6bc2-436b-bcb8-eaa6e11b86e7')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-e28b4772-6bc2-436b-bcb8-eaa6e11b86e7 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-a2a5f8fa-d2d4-40a9-83a0-3f5c0c033b17 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-a2a5f8fa-d2d4-40a9-83a0-3f5c0c033b17');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
preparation = preparation.drop_duplicates('movieId')
preparation
```






  <div id="df-ce23fe98-8a1f-463b-ba51-5339df3f7d87">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userId</th>
      <th>movieId</th>
      <th>rating</th>
      <th>timestamp</th>
      <th>title</th>
      <th>genres</th>
      <th>genre</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>1</td>
      <td>4.0</td>
      <td>964982703</td>
      <td>Toy Story (1995)</td>
      <td>Adventure|Animation|Children|Comedy|Fantasy</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>84230</th>
      <td>288</td>
      <td>2</td>
      <td>2.0</td>
      <td>978467973</td>
      <td>Jumanji (1995)</td>
      <td>Adventure|Children|Fantasy</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>86338</th>
      <td>289</td>
      <td>3</td>
      <td>2.5</td>
      <td>1143424657</td>
      <td>Grumpier Old Men (1995)</td>
      <td>Comedy|Romance</td>
      <td>Comedy</td>
    </tr>
    <tr>
      <th>76358</th>
      <td>262</td>
      <td>4</td>
      <td>1.0</td>
      <td>840306203</td>
      <td>Waiting to Exhale (1995)</td>
      <td>Comedy|Drama|Romance</td>
      <td>Comedy</td>
    </tr>
    <tr>
      <th>154448</th>
      <td>483</td>
      <td>5</td>
      <td>2.5</td>
      <td>1327277284</td>
      <td>Father of the Bride Part II (1995)</td>
      <td>Comedy</td>
      <td>Comedy</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>54512</th>
      <td>184</td>
      <td>193581</td>
      <td>4.0</td>
      <td>1537109082</td>
      <td>Black Butler: Book of the Atlantic (2017)</td>
      <td>Action|Animation|Comedy|Fantasy</td>
      <td>Action</td>
    </tr>
    <tr>
      <th>54514</th>
      <td>184</td>
      <td>193583</td>
      <td>3.5</td>
      <td>1537109545</td>
      <td>No Game No Life: Zero (2017)</td>
      <td>Animation|Comedy|Fantasy</td>
      <td>Animation</td>
    </tr>
    <tr>
      <th>54516</th>
      <td>184</td>
      <td>193585</td>
      <td>3.5</td>
      <td>1537109805</td>
      <td>Flint (2017)</td>
      <td>Drama</td>
      <td>Drama</td>
    </tr>
    <tr>
      <th>54518</th>
      <td>184</td>
      <td>193587</td>
      <td>3.5</td>
      <td>1537110021</td>
      <td>Bungo Stray Dogs: Dead Apple (2018)</td>
      <td>Action|Animation</td>
      <td>Action</td>
    </tr>
    <tr>
      <th>102724</th>
      <td>331</td>
      <td>193609</td>
      <td>4.0</td>
      <td>1537157606</td>
      <td>Andrew Dice Clay: Dice Rules (1991)</td>
      <td>Comedy</td>
      <td>Comedy</td>
    </tr>
  </tbody>
</table>
<p>9724 rows × 7 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-ce23fe98-8a1f-463b-ba51-5339df3f7d87')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-c8cc91b2-ead8-46ec-a0f6-185a018064d9">
      <button class="colab-df-quickchart" onclick="quickchart('df-c8cc91b2-ead8-46ec-a0f6-185a018064d9')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-c8cc91b2-ead8-46ec-a0f6-185a018064d9 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-ce23fe98-8a1f-463b-ba51-5339df3f7d87 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-ce23fe98-8a1f-463b-ba51-5339df3f7d87');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
movie_id = preparation['movieId'].tolist()
movie_title = preparation['title'].tolist()
movie_genre = preparation['genre'].tolist()

print(len(movie_id))
print(len(movie_title))
print(len(movie_genre))
```

    9724
    9724
    9724


Data yang digunakan untuk membuat model


```python
movie_new = pd.DataFrame({
    'id': movie_id,
    'title': movie_title,
    'genre': movie_genre
})

movie_new
```






  <div id="df-de757f4e-1ab4-4579-9c16-384e35ce45a9">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>title</th>
      <th>genre</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Toy Story (1995)</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Jumanji (1995)</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Grumpier Old Men (1995)</td>
      <td>Comedy</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>Waiting to Exhale (1995)</td>
      <td>Comedy</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>Father of the Bride Part II (1995)</td>
      <td>Comedy</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>9719</th>
      <td>193581</td>
      <td>Black Butler: Book of the Atlantic (2017)</td>
      <td>Action</td>
    </tr>
    <tr>
      <th>9720</th>
      <td>193583</td>
      <td>No Game No Life: Zero (2017)</td>
      <td>Animation</td>
    </tr>
    <tr>
      <th>9721</th>
      <td>193585</td>
      <td>Flint (2017)</td>
      <td>Drama</td>
    </tr>
    <tr>
      <th>9722</th>
      <td>193587</td>
      <td>Bungo Stray Dogs: Dead Apple (2018)</td>
      <td>Action</td>
    </tr>
    <tr>
      <th>9723</th>
      <td>193609</td>
      <td>Andrew Dice Clay: Dice Rules (1991)</td>
      <td>Comedy</td>
    </tr>
  </tbody>
</table>
<p>9724 rows × 3 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-de757f4e-1ab4-4579-9c16-384e35ce45a9')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-9da376cc-e1ab-4c7d-ac46-d649a7615c41">
      <button class="colab-df-quickchart" onclick="quickchart('df-9da376cc-e1ab-4c7d-ac46-d649a7615c41')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-9da376cc-e1ab-4c7d-ac46-d649a7615c41 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-de757f4e-1ab4-4579-9c16-384e35ce45a9 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-de757f4e-1ab4-4579-9c16-384e35ce45a9');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>




# Model Development dengan Content Based Filtering


```python
data = movie_new
data.sample(5)
```






  <div id="df-24591e8c-741c-425c-9563-1bfda23a05a8">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>title</th>
      <th>genre</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>8925</th>
      <td>136503</td>
      <td>Tom and Jerry: Shiver Me Whiskers (2006)</td>
      <td>Animation</td>
    </tr>
    <tr>
      <th>3512</th>
      <td>4808</td>
      <td>Vanishing, The (1993)</td>
      <td>Mystery</td>
    </tr>
    <tr>
      <th>9353</th>
      <td>162598</td>
      <td>Deepwater Horizon (2016)</td>
      <td>Drama</td>
    </tr>
    <tr>
      <th>9291</th>
      <td>159403</td>
      <td>Neo Tokyo (1987)</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>4789</th>
      <td>7150</td>
      <td>Stuck on You (2003)</td>
      <td>Comedy</td>
    </tr>
  </tbody>
</table>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-24591e8c-741c-425c-9563-1bfda23a05a8')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-008a6686-4352-42a3-8b6d-4aad69ffbedb">
      <button class="colab-df-quickchart" onclick="quickchart('df-008a6686-4352-42a3-8b6d-4aad69ffbedb')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-008a6686-4352-42a3-8b6d-4aad69ffbedb button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-24591e8c-741c-425c-9563-1bfda23a05a8 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-24591e8c-741c-425c-9563-1bfda23a05a8');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>




### TF-IDF Vectorizer

Pada tahap ini, akan dibuat sistem rekomendasi sederhana berdasarkan genre film menggunakan TF-IDF Vectoriczer


```python
from sklearn.feature_extraction.text import TfidfVectorizer

tf = TfidfVectorizer()

tf.fit(data['genre'])

tf.get_feature_names_out()
```




    array(['action', 'adventure', 'animation', 'children', 'comedy', 'crime',
           'documentary', 'drama', 'fantasy', 'fi', 'film', 'genres',
           'horror', 'listed', 'musical', 'mystery', 'no', 'noir', 'romance',
           'sci', 'thriller', 'war', 'western'], dtype=object)



melakukan fit dan transformasi ke dalam bentuk matriks.


```python
tfidf_matrix = tf.fit_transform(data['genre'])

tfidf_matrix.shape
```




    (9724, 23)



Menjalan fungsi todense() untuk menghasilkan vektor tf-idf dalam bentuk matriks


```python
tfidf_matrix.todense()
```




    matrix([[0., 1., 0., ..., 0., 0., 0.],
            [0., 1., 0., ..., 0., 0., 0.],
            [0., 0., 0., ..., 0., 0., 0.],
            ...,
            [0., 0., 0., ..., 0., 0., 0.],
            [1., 0., 0., ..., 0., 0., 0.],
            [0., 0., 0., ..., 0., 0., 0.]])



Matriks tf-idf untuk bebrapa movie dan genre


```python
pd.DataFrame(
    tfidf_matrix.todense(),
    columns=tf.get_feature_names_out(),
    index=data.title
).sample(22, axis=1).sample(10, axis=0)
```






  <div id="df-3c8c2dcf-802e-4698-89e0-cb91c7fa171f">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>mystery</th>
      <th>noir</th>
      <th>thriller</th>
      <th>film</th>
      <th>no</th>
      <th>musical</th>
      <th>sci</th>
      <th>animation</th>
      <th>war</th>
      <th>action</th>
      <th>...</th>
      <th>fantasy</th>
      <th>fi</th>
      <th>romance</th>
      <th>listed</th>
      <th>adventure</th>
      <th>documentary</th>
      <th>western</th>
      <th>children</th>
      <th>genres</th>
      <th>crime</th>
    </tr>
    <tr>
      <th>title</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Incredible Shrinking Man, The (1957)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.707107</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.707107</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>Fullmetal Alchemist 2018 (2017)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>Andromeda Strain, The (1971)</th>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>Ladykillers, The (2004)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>Thor: Ragnarok (2017)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>Beethoven (1992)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>Hairspray (2007)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>Going in Style (1979)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>Midsummer Night's Sex Comedy, A (1982)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>Invasion, The (2007)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
  </tbody>
</table>
<p>10 rows × 22 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-3c8c2dcf-802e-4698-89e0-cb91c7fa171f')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-6b93e8fb-d55a-45a1-a4a4-eb122c4403b9">
      <button class="colab-df-quickchart" onclick="quickchart('df-6b93e8fb-d55a-45a1-a4a4-eb122c4403b9')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-6b93e8fb-d55a-45a1-a4a4-eb122c4403b9 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-3c8c2dcf-802e-4698-89e0-cb91c7fa171f button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-3c8c2dcf-802e-4698-89e0-cb91c7fa171f');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>




Output matriks di atas menujukan movie yang berjudul *Andromeda Strain, The (1971)* memiliki genre *mystery*, hal ini terlihat dari nilai matriks 1.0 pada kategori *mystery*.

### *Cosine Similarity*

Menghitung derajat kesamaan (similarity degree) antar restoran dengan teknik cosine similarity


```python
from sklearn.metrics.pairwise import cosine_similarity

# Menghitung cosine similarity pada matrix tf-idf
cosine_sim = cosine_similarity(tfidf_matrix)
cosine_sim
```




    array([[1., 1., 0., ..., 0., 0., 0.],
           [1., 1., 0., ..., 0., 0., 0.],
           [0., 0., 1., ..., 0., 0., 1.],
           ...,
           [0., 0., 0., ..., 1., 0., 0.],
           [0., 0., 0., ..., 0., 1., 0.],
           [0., 0., 1., ..., 0., 0., 1.]])



Keluarannya berupa matriks kesamaan dalam bentuk array.


```python
# Membuat dataframe dari variabel cosine_sim dengan baris dan kolom berupa nama resto
cosine_sim_df = pd.DataFrame(cosine_sim, index=data['title'], columns=data['title'])
print('Shape:', cosine_sim_df.shape)

# Melihat similarity matrix pada setiap resto
cosine_sim_df.sample(5, axis=1).sample(10, axis=0)
```

    Shape: (9724, 9724)







  <div id="df-c3a84c9b-5c70-44c5-bfa6-d1ebe05ce548">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>title</th>
      <th>Frankenstein (1931)</th>
      <th>If These Walls Could Talk 2 (2000)</th>
      <th>American Pie (1999)</th>
      <th>Mr Hublot (2013)</th>
      <th>The Last Witch Hunter (2015)</th>
    </tr>
    <tr>
      <th>title</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Union: The Business Behind Getting High, The (2007)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>Diabolique (Les diaboliques) (1955)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>Drag Me to Hell (2009)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>Deadpool 2 (2018)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
    </tr>
    <tr>
      <th>Terminal, The (2004)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>GLOW: The Story of the Gorgeous Ladies of Wrestling (2012)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>Glory (1989)</th>
      <td>1.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>Larry Crowne (2011)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>Super Troopers (2001)</th>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>2046 (2004)</th>
      <td>1.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
    </tr>
  </tbody>
</table>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-c3a84c9b-5c70-44c5-bfa6-d1ebe05ce548')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-3f079008-a8e5-47d0-b5d6-2066f8c85f90">
      <button class="colab-df-quickchart" onclick="quickchart('df-3f079008-a8e5-47d0-b5d6-2066f8c85f90')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-3f079008-a8e5-47d0-b5d6-2066f8c85f90 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-c3a84c9b-5c70-44c5-bfa6-d1ebe05ce548 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-c3a84c9b-5c70-44c5-bfa6-d1ebe05ce548');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>




Mengidentifikasi kesamaan antara satu restoran dengan restoran lainnya

### Mendapatkan Rekomendasi


```python
def movie_recommendations(title, similarity_data=cosine_sim_df, items=data[['title', 'genre']], k=5):
    """
    Rekomendasi Resto berdasarkan kemiripan dataframe

    Parameter:
    ---
    nama_resto : tipe data string (str)
                Nama Restoran (index kemiripan dataframe)
    similarity_data : tipe data pd.DataFrame (object)
                      Kesamaan dataframe, simetrik, dengan resto sebagai
                      indeks dan kolom
    items : tipe data pd.DataFrame (object)
            Mengandung kedua nama dan fitur lainnya yang digunakan untuk mendefinisikan kemiripan
    k : tipe data integer (int)
        Banyaknya jumlah rekomendasi yang diberikan
    ---


    Pada index ini, kita mengambil k dengan nilai similarity terbesar
    pada index matrix yang diberikan (i).
    """


    # Mengambil data dengan menggunakan argpartition untuk melakukan partisi secara tidak langsung sepanjang sumbu yang diberikan
    # Dataframe diubah menjadi numpy
    # Range(start, stop, step)
    index = similarity_data.loc[:,title].to_numpy().argpartition(
        range(-1, -k, -1))

    # Mengambil data dengan similarity terbesar dari index yang ada
    closest = similarity_data.columns[index[-1:-(k+2):-1]]

    # Drop nama_resto agar nama resto yang dicari tidak muncul dalam daftar rekomendasi
    closest = closest.drop(title, errors='ignore')

    return pd.DataFrame(closest).merge(items).head(k)
```


```python
data[data.title.eq('Felon (2008)')]
```






  <div id="df-54405729-6450-4df1-a7f6-1064b39e0943">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>title</th>
      <th>genre</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>6783</th>
      <td>60753</td>
      <td>Felon (2008)</td>
      <td>Crime</td>
    </tr>
  </tbody>
</table>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-54405729-6450-4df1-a7f6-1064b39e0943')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-9bcd7e97-a92a-4e63-adc5-c1b7d52909c8">
      <button class="colab-df-quickchart" onclick="quickchart('df-9bcd7e97-a92a-4e63-adc5-c1b7d52909c8')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-9bcd7e97-a92a-4e63-adc5-c1b7d52909c8 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-54405729-6450-4df1-a7f6-1064b39e0943 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-54405729-6450-4df1-a7f6-1064b39e0943');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
movie_recommendations('Felon (2008)')
```






  <div id="df-60c750eb-e641-4abd-9963-ed34190eae29">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>title</th>
      <th>genre</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Wolf Creek (2005)</td>
      <td>Crime</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Joint Security Area (Gongdong gyeongbi guyeok ...</td>
      <td>Crime</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Entrapment (1999)</td>
      <td>Crime</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Time Lapse (2014)</td>
      <td>Crime</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Secret in Their Eyes (2015)</td>
      <td>Crime</td>
    </tr>
  </tbody>
</table>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-60c750eb-e641-4abd-9963-ed34190eae29')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-1d55f668-2836-436a-8f5e-0843a488bd34">
      <button class="colab-df-quickchart" onclick="quickchart('df-1d55f668-2836-436a-8f5e-0843a488bd34')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-1d55f668-2836-436a-8f5e-0843a488bd34 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-60c750eb-e641-4abd-9963-ed34190eae29 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-60c750eb-e641-4abd-9963-ed34190eae29');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>




Sistem memeberikan 5 rekomendasi film yang mirip dengan film *Felon (2008)*

# Model Development dengan Collaborative Filtering

### *Data Understanding*


```python
# Import library
import pandas as pd
import numpy as np
from zipfile import ZipFile
import tensorflow as tf
from tensorflow import keras
from tensorflow.keras import layers
from pathlib import Path
import matplotlib.pyplot as plt
```


```python
df = ratings
df
```






  <div id="df-e23214b3-1914-4327-8b0d-50a0640948f7">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userId</th>
      <th>movieId</th>
      <th>rating</th>
      <th>timestamp</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>1</td>
      <td>4.0</td>
      <td>964982703</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1</td>
      <td>3</td>
      <td>4.0</td>
      <td>964981247</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1</td>
      <td>6</td>
      <td>4.0</td>
      <td>964982224</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1</td>
      <td>47</td>
      <td>5.0</td>
      <td>964983815</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1</td>
      <td>50</td>
      <td>5.0</td>
      <td>964982931</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>100831</th>
      <td>610</td>
      <td>166534</td>
      <td>4.0</td>
      <td>1493848402</td>
    </tr>
    <tr>
      <th>100832</th>
      <td>610</td>
      <td>168248</td>
      <td>5.0</td>
      <td>1493850091</td>
    </tr>
    <tr>
      <th>100833</th>
      <td>610</td>
      <td>168250</td>
      <td>5.0</td>
      <td>1494273047</td>
    </tr>
    <tr>
      <th>100834</th>
      <td>610</td>
      <td>168252</td>
      <td>5.0</td>
      <td>1493846352</td>
    </tr>
    <tr>
      <th>100835</th>
      <td>610</td>
      <td>170875</td>
      <td>3.0</td>
      <td>1493846415</td>
    </tr>
  </tbody>
</table>
<p>100836 rows × 4 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-e23214b3-1914-4327-8b0d-50a0640948f7')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-250cb848-0568-4ddd-960f-d4e4cf9806c9">
      <button class="colab-df-quickchart" onclick="quickchart('df-250cb848-0568-4ddd-960f-d4e4cf9806c9')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-250cb848-0568-4ddd-960f-d4e4cf9806c9 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-e23214b3-1914-4327-8b0d-50a0640948f7 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-e23214b3-1914-4327-8b0d-50a0640948f7');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
print(len(df['userId'].unique()))
```

    610


### *Data Preparation*

Melakukan persiapan data untuk menyandikan (encode) fitur userId dan movieId ke dalam indeks integer.


```python
user_ids = df['userId'].unique().tolist()
print('list userID: ', user_ids)

# Melakukan encoding userID
user_to_user_encoded = {x: i for i, x in enumerate(user_ids)}
print('encoded userID : ', user_to_user_encoded)

# Melakukan proses encoding angka ke ke userID
user_encoded_to_user = {i: x for i, x in enumerate(user_ids)}
print('encoded angka ke userID: ', user_encoded_to_user)
```

    list userID:  [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 60, 61, 62, 63, 64, 65, 66, 67, 68, 69, 70, 71, 72, 73, 74, 75, 76, 77, 78, 79, 80, 81, 82, 83, 84, 85, 86, 87, 88, 89, 90, 91, 92, 93, 94, 95, 96, 97, 98, 99, 100, 101, 102, 103, 104, 105, 106, 107, 108, 109, 110, 111, 112, 113, 114, 115, 116, 117, 118, 119, 120, 121, 122, 123, 124, 125, 126, 127, 128, 129, 130, 131, 132, 133, 134, 135, 136, 137, 138, 139, 140, 141, 142, 143, 144, 145, 146, 147, 148, 149, 150, 151, 152, 153, 154, 155, 156, 157, 158, 159, 160, 161, 162, 163, 164, 165, 166, 167, 168, 169, 170, 171, 172, 173, 174, 175, 176, 177, 178, 179, 180, 181, 182, 183, 184, 185, 186, 187, 188, 189, 190, 191, 192, 193, 194, 195, 196, 197, 198, 199, 200, 201, 202, 203, 204, 205, 206, 207, 208, 209, 210, 211, 212, 213, 214, 215, 216, 217, 218, 219, 220, 221, 222, 223, 224, 225, 226, 227, 228, 229, 230, 231, 232, 233, 234, 235, 236, 237, 238, 239, 240, 241, 242, 243, 244, 245, 246, 247, 248, 249, 250, 251, 252, 253, 254, 255, 256, 257, 258, 259, 260, 261, 262, 263, 264, 265, 266, 267, 268, 269, 270, 271, 272, 273, 274, 275, 276, 277, 278, 279, 280, 281, 282, 283, 284, 285, 286, 287, 288, 289, 290, 291, 292, 293, 294, 295, 296, 297, 298, 299, 300, 301, 302, 303, 304, 305, 306, 307, 308, 309, 310, 311, 312, 313, 314, 315, 316, 317, 318, 319, 320, 321, 322, 323, 324, 325, 326, 327, 328, 329, 330, 331, 332, 333, 334, 335, 336, 337, 338, 339, 340, 341, 342, 343, 344, 345, 346, 347, 348, 349, 350, 351, 352, 353, 354, 355, 356, 357, 358, 359, 360, 361, 362, 363, 364, 365, 366, 367, 368, 369, 370, 371, 372, 373, 374, 375, 376, 377, 378, 379, 380, 381, 382, 383, 384, 385, 386, 387, 388, 389, 390, 391, 392, 393, 394, 395, 396, 397, 398, 399, 400, 401, 402, 403, 404, 405, 406, 407, 408, 409, 410, 411, 412, 413, 414, 415, 416, 417, 418, 419, 420, 421, 422, 423, 424, 425, 426, 427, 428, 429, 430, 431, 432, 433, 434, 435, 436, 437, 438, 439, 440, 441, 442, 443, 444, 445, 446, 447, 448, 449, 450, 451, 452, 453, 454, 455, 456, 457, 458, 459, 460, 461, 462, 463, 464, 465, 466, 467, 468, 469, 470, 471, 472, 473, 474, 475, 476, 477, 478, 479, 480, 481, 482, 483, 484, 485, 486, 487, 488, 489, 490, 491, 492, 493, 494, 495, 496, 497, 498, 499, 500, 501, 502, 503, 504, 505, 506, 507, 508, 509, 510, 511, 512, 513, 514, 515, 516, 517, 518, 519, 520, 521, 522, 523, 524, 525, 526, 527, 528, 529, 530, 531, 532, 533, 534, 535, 536, 537, 538, 539, 540, 541, 542, 543, 544, 545, 546, 547, 548, 549, 550, 551, 552, 553, 554, 555, 556, 557, 558, 559, 560, 561, 562, 563, 564, 565, 566, 567, 568, 569, 570, 571, 572, 573, 574, 575, 576, 577, 578, 579, 580, 581, 582, 583, 584, 585, 586, 587, 588, 589, 590, 591, 592, 593, 594, 595, 596, 597, 598, 599, 600, 601, 602, 603, 604, 605, 606, 607, 608, 609, 610]
    encoded userID :  {1: 0, 2: 1, 3: 2, 4: 3, 5: 4, 6: 5, 7: 6, 8: 7, 9: 8, 10: 9, 11: 10, 12: 11, 13: 12, 14: 13, 15: 14, 16: 15, 17: 16, 18: 17, 19: 18, 20: 19, 21: 20, 22: 21, 23: 22, 24: 23, 25: 24, 26: 25, 27: 26, 28: 27, 29: 28, 30: 29, 31: 30, 32: 31, 33: 32, 34: 33, 35: 34, 36: 35, 37: 36, 38: 37, 39: 38, 40: 39, 41: 40, 42: 41, 43: 42, 44: 43, 45: 44, 46: 45, 47: 46, 48: 47, 49: 48, 50: 49, 51: 50, 52: 51, 53: 52, 54: 53, 55: 54, 56: 55, 57: 56, 58: 57, 59: 58, 60: 59, 61: 60, 62: 61, 63: 62, 64: 63, 65: 64, 66: 65, 67: 66, 68: 67, 69: 68, 70: 69, 71: 70, 72: 71, 73: 72, 74: 73, 75: 74, 76: 75, 77: 76, 78: 77, 79: 78, 80: 79, 81: 80, 82: 81, 83: 82, 84: 83, 85: 84, 86: 85, 87: 86, 88: 87, 89: 88, 90: 89, 91: 90, 92: 91, 93: 92, 94: 93, 95: 94, 96: 95, 97: 96, 98: 97, 99: 98, 100: 99, 101: 100, 102: 101, 103: 102, 104: 103, 105: 104, 106: 105, 107: 106, 108: 107, 109: 108, 110: 109, 111: 110, 112: 111, 113: 112, 114: 113, 115: 114, 116: 115, 117: 116, 118: 117, 119: 118, 120: 119, 121: 120, 122: 121, 123: 122, 124: 123, 125: 124, 126: 125, 127: 126, 128: 127, 129: 128, 130: 129, 131: 130, 132: 131, 133: 132, 134: 133, 135: 134, 136: 135, 137: 136, 138: 137, 139: 138, 140: 139, 141: 140, 142: 141, 143: 142, 144: 143, 145: 144, 146: 145, 147: 146, 148: 147, 149: 148, 150: 149, 151: 150, 152: 151, 153: 152, 154: 153, 155: 154, 156: 155, 157: 156, 158: 157, 159: 158, 160: 159, 161: 160, 162: 161, 163: 162, 164: 163, 165: 164, 166: 165, 167: 166, 168: 167, 169: 168, 170: 169, 171: 170, 172: 171, 173: 172, 174: 173, 175: 174, 176: 175, 177: 176, 178: 177, 179: 178, 180: 179, 181: 180, 182: 181, 183: 182, 184: 183, 185: 184, 186: 185, 187: 186, 188: 187, 189: 188, 190: 189, 191: 190, 192: 191, 193: 192, 194: 193, 195: 194, 196: 195, 197: 196, 198: 197, 199: 198, 200: 199, 201: 200, 202: 201, 203: 202, 204: 203, 205: 204, 206: 205, 207: 206, 208: 207, 209: 208, 210: 209, 211: 210, 212: 211, 213: 212, 214: 213, 215: 214, 216: 215, 217: 216, 218: 217, 219: 218, 220: 219, 221: 220, 222: 221, 223: 222, 224: 223, 225: 224, 226: 225, 227: 226, 228: 227, 229: 228, 230: 229, 231: 230, 232: 231, 233: 232, 234: 233, 235: 234, 236: 235, 237: 236, 238: 237, 239: 238, 240: 239, 241: 240, 242: 241, 243: 242, 244: 243, 245: 244, 246: 245, 247: 246, 248: 247, 249: 248, 250: 249, 251: 250, 252: 251, 253: 252, 254: 253, 255: 254, 256: 255, 257: 256, 258: 257, 259: 258, 260: 259, 261: 260, 262: 261, 263: 262, 264: 263, 265: 264, 266: 265, 267: 266, 268: 267, 269: 268, 270: 269, 271: 270, 272: 271, 273: 272, 274: 273, 275: 274, 276: 275, 277: 276, 278: 277, 279: 278, 280: 279, 281: 280, 282: 281, 283: 282, 284: 283, 285: 284, 286: 285, 287: 286, 288: 287, 289: 288, 290: 289, 291: 290, 292: 291, 293: 292, 294: 293, 295: 294, 296: 295, 297: 296, 298: 297, 299: 298, 300: 299, 301: 300, 302: 301, 303: 302, 304: 303, 305: 304, 306: 305, 307: 306, 308: 307, 309: 308, 310: 309, 311: 310, 312: 311, 313: 312, 314: 313, 315: 314, 316: 315, 317: 316, 318: 317, 319: 318, 320: 319, 321: 320, 322: 321, 323: 322, 324: 323, 325: 324, 326: 325, 327: 326, 328: 327, 329: 328, 330: 329, 331: 330, 332: 331, 333: 332, 334: 333, 335: 334, 336: 335, 337: 336, 338: 337, 339: 338, 340: 339, 341: 340, 342: 341, 343: 342, 344: 343, 345: 344, 346: 345, 347: 346, 348: 347, 349: 348, 350: 349, 351: 350, 352: 351, 353: 352, 354: 353, 355: 354, 356: 355, 357: 356, 358: 357, 359: 358, 360: 359, 361: 360, 362: 361, 363: 362, 364: 363, 365: 364, 366: 365, 367: 366, 368: 367, 369: 368, 370: 369, 371: 370, 372: 371, 373: 372, 374: 373, 375: 374, 376: 375, 377: 376, 378: 377, 379: 378, 380: 379, 381: 380, 382: 381, 383: 382, 384: 383, 385: 384, 386: 385, 387: 386, 388: 387, 389: 388, 390: 389, 391: 390, 392: 391, 393: 392, 394: 393, 395: 394, 396: 395, 397: 396, 398: 397, 399: 398, 400: 399, 401: 400, 402: 401, 403: 402, 404: 403, 405: 404, 406: 405, 407: 406, 408: 407, 409: 408, 410: 409, 411: 410, 412: 411, 413: 412, 414: 413, 415: 414, 416: 415, 417: 416, 418: 417, 419: 418, 420: 419, 421: 420, 422: 421, 423: 422, 424: 423, 425: 424, 426: 425, 427: 426, 428: 427, 429: 428, 430: 429, 431: 430, 432: 431, 433: 432, 434: 433, 435: 434, 436: 435, 437: 436, 438: 437, 439: 438, 440: 439, 441: 440, 442: 441, 443: 442, 444: 443, 445: 444, 446: 445, 447: 446, 448: 447, 449: 448, 450: 449, 451: 450, 452: 451, 453: 452, 454: 453, 455: 454, 456: 455, 457: 456, 458: 457, 459: 458, 460: 459, 461: 460, 462: 461, 463: 462, 464: 463, 465: 464, 466: 465, 467: 466, 468: 467, 469: 468, 470: 469, 471: 470, 472: 471, 473: 472, 474: 473, 475: 474, 476: 475, 477: 476, 478: 477, 479: 478, 480: 479, 481: 480, 482: 481, 483: 482, 484: 483, 485: 484, 486: 485, 487: 486, 488: 487, 489: 488, 490: 489, 491: 490, 492: 491, 493: 492, 494: 493, 495: 494, 496: 495, 497: 496, 498: 497, 499: 498, 500: 499, 501: 500, 502: 501, 503: 502, 504: 503, 505: 504, 506: 505, 507: 506, 508: 507, 509: 508, 510: 509, 511: 510, 512: 511, 513: 512, 514: 513, 515: 514, 516: 515, 517: 516, 518: 517, 519: 518, 520: 519, 521: 520, 522: 521, 523: 522, 524: 523, 525: 524, 526: 525, 527: 526, 528: 527, 529: 528, 530: 529, 531: 530, 532: 531, 533: 532, 534: 533, 535: 534, 536: 535, 537: 536, 538: 537, 539: 538, 540: 539, 541: 540, 542: 541, 543: 542, 544: 543, 545: 544, 546: 545, 547: 546, 548: 547, 549: 548, 550: 549, 551: 550, 552: 551, 553: 552, 554: 553, 555: 554, 556: 555, 557: 556, 558: 557, 559: 558, 560: 559, 561: 560, 562: 561, 563: 562, 564: 563, 565: 564, 566: 565, 567: 566, 568: 567, 569: 568, 570: 569, 571: 570, 572: 571, 573: 572, 574: 573, 575: 574, 576: 575, 577: 576, 578: 577, 579: 578, 580: 579, 581: 580, 582: 581, 583: 582, 584: 583, 585: 584, 586: 585, 587: 586, 588: 587, 589: 588, 590: 589, 591: 590, 592: 591, 593: 592, 594: 593, 595: 594, 596: 595, 597: 596, 598: 597, 599: 598, 600: 599, 601: 600, 602: 601, 603: 602, 604: 603, 605: 604, 606: 605, 607: 606, 608: 607, 609: 608, 610: 609}
    encoded angka ke userID:  {0: 1, 1: 2, 2: 3, 3: 4, 4: 5, 5: 6, 6: 7, 7: 8, 8: 9, 9: 10, 10: 11, 11: 12, 12: 13, 13: 14, 14: 15, 15: 16, 16: 17, 17: 18, 18: 19, 19: 20, 20: 21, 21: 22, 22: 23, 23: 24, 24: 25, 25: 26, 26: 27, 27: 28, 28: 29, 29: 30, 30: 31, 31: 32, 32: 33, 33: 34, 34: 35, 35: 36, 36: 37, 37: 38, 38: 39, 39: 40, 40: 41, 41: 42, 42: 43, 43: 44, 44: 45, 45: 46, 46: 47, 47: 48, 48: 49, 49: 50, 50: 51, 51: 52, 52: 53, 53: 54, 54: 55, 55: 56, 56: 57, 57: 58, 58: 59, 59: 60, 60: 61, 61: 62, 62: 63, 63: 64, 64: 65, 65: 66, 66: 67, 67: 68, 68: 69, 69: 70, 70: 71, 71: 72, 72: 73, 73: 74, 74: 75, 75: 76, 76: 77, 77: 78, 78: 79, 79: 80, 80: 81, 81: 82, 82: 83, 83: 84, 84: 85, 85: 86, 86: 87, 87: 88, 88: 89, 89: 90, 90: 91, 91: 92, 92: 93, 93: 94, 94: 95, 95: 96, 96: 97, 97: 98, 98: 99, 99: 100, 100: 101, 101: 102, 102: 103, 103: 104, 104: 105, 105: 106, 106: 107, 107: 108, 108: 109, 109: 110, 110: 111, 111: 112, 112: 113, 113: 114, 114: 115, 115: 116, 116: 117, 117: 118, 118: 119, 119: 120, 120: 121, 121: 122, 122: 123, 123: 124, 124: 125, 125: 126, 126: 127, 127: 128, 128: 129, 129: 130, 130: 131, 131: 132, 132: 133, 133: 134, 134: 135, 135: 136, 136: 137, 137: 138, 138: 139, 139: 140, 140: 141, 141: 142, 142: 143, 143: 144, 144: 145, 145: 146, 146: 147, 147: 148, 148: 149, 149: 150, 150: 151, 151: 152, 152: 153, 153: 154, 154: 155, 155: 156, 156: 157, 157: 158, 158: 159, 159: 160, 160: 161, 161: 162, 162: 163, 163: 164, 164: 165, 165: 166, 166: 167, 167: 168, 168: 169, 169: 170, 170: 171, 171: 172, 172: 173, 173: 174, 174: 175, 175: 176, 176: 177, 177: 178, 178: 179, 179: 180, 180: 181, 181: 182, 182: 183, 183: 184, 184: 185, 185: 186, 186: 187, 187: 188, 188: 189, 189: 190, 190: 191, 191: 192, 192: 193, 193: 194, 194: 195, 195: 196, 196: 197, 197: 198, 198: 199, 199: 200, 200: 201, 201: 202, 202: 203, 203: 204, 204: 205, 205: 206, 206: 207, 207: 208, 208: 209, 209: 210, 210: 211, 211: 212, 212: 213, 213: 214, 214: 215, 215: 216, 216: 217, 217: 218, 218: 219, 219: 220, 220: 221, 221: 222, 222: 223, 223: 224, 224: 225, 225: 226, 226: 227, 227: 228, 228: 229, 229: 230, 230: 231, 231: 232, 232: 233, 233: 234, 234: 235, 235: 236, 236: 237, 237: 238, 238: 239, 239: 240, 240: 241, 241: 242, 242: 243, 243: 244, 244: 245, 245: 246, 246: 247, 247: 248, 248: 249, 249: 250, 250: 251, 251: 252, 252: 253, 253: 254, 254: 255, 255: 256, 256: 257, 257: 258, 258: 259, 259: 260, 260: 261, 261: 262, 262: 263, 263: 264, 264: 265, 265: 266, 266: 267, 267: 268, 268: 269, 269: 270, 270: 271, 271: 272, 272: 273, 273: 274, 274: 275, 275: 276, 276: 277, 277: 278, 278: 279, 279: 280, 280: 281, 281: 282, 282: 283, 283: 284, 284: 285, 285: 286, 286: 287, 287: 288, 288: 289, 289: 290, 290: 291, 291: 292, 292: 293, 293: 294, 294: 295, 295: 296, 296: 297, 297: 298, 298: 299, 299: 300, 300: 301, 301: 302, 302: 303, 303: 304, 304: 305, 305: 306, 306: 307, 307: 308, 308: 309, 309: 310, 310: 311, 311: 312, 312: 313, 313: 314, 314: 315, 315: 316, 316: 317, 317: 318, 318: 319, 319: 320, 320: 321, 321: 322, 322: 323, 323: 324, 324: 325, 325: 326, 326: 327, 327: 328, 328: 329, 329: 330, 330: 331, 331: 332, 332: 333, 333: 334, 334: 335, 335: 336, 336: 337, 337: 338, 338: 339, 339: 340, 340: 341, 341: 342, 342: 343, 343: 344, 344: 345, 345: 346, 346: 347, 347: 348, 348: 349, 349: 350, 350: 351, 351: 352, 352: 353, 353: 354, 354: 355, 355: 356, 356: 357, 357: 358, 358: 359, 359: 360, 360: 361, 361: 362, 362: 363, 363: 364, 364: 365, 365: 366, 366: 367, 367: 368, 368: 369, 369: 370, 370: 371, 371: 372, 372: 373, 373: 374, 374: 375, 375: 376, 376: 377, 377: 378, 378: 379, 379: 380, 380: 381, 381: 382, 382: 383, 383: 384, 384: 385, 385: 386, 386: 387, 387: 388, 388: 389, 389: 390, 390: 391, 391: 392, 392: 393, 393: 394, 394: 395, 395: 396, 396: 397, 397: 398, 398: 399, 399: 400, 400: 401, 401: 402, 402: 403, 403: 404, 404: 405, 405: 406, 406: 407, 407: 408, 408: 409, 409: 410, 410: 411, 411: 412, 412: 413, 413: 414, 414: 415, 415: 416, 416: 417, 417: 418, 418: 419, 419: 420, 420: 421, 421: 422, 422: 423, 423: 424, 424: 425, 425: 426, 426: 427, 427: 428, 428: 429, 429: 430, 430: 431, 431: 432, 432: 433, 433: 434, 434: 435, 435: 436, 436: 437, 437: 438, 438: 439, 439: 440, 440: 441, 441: 442, 442: 443, 443: 444, 444: 445, 445: 446, 446: 447, 447: 448, 448: 449, 449: 450, 450: 451, 451: 452, 452: 453, 453: 454, 454: 455, 455: 456, 456: 457, 457: 458, 458: 459, 459: 460, 460: 461, 461: 462, 462: 463, 463: 464, 464: 465, 465: 466, 466: 467, 467: 468, 468: 469, 469: 470, 470: 471, 471: 472, 472: 473, 473: 474, 474: 475, 475: 476, 476: 477, 477: 478, 478: 479, 479: 480, 480: 481, 481: 482, 482: 483, 483: 484, 484: 485, 485: 486, 486: 487, 487: 488, 488: 489, 489: 490, 490: 491, 491: 492, 492: 493, 493: 494, 494: 495, 495: 496, 496: 497, 497: 498, 498: 499, 499: 500, 500: 501, 501: 502, 502: 503, 503: 504, 504: 505, 505: 506, 506: 507, 507: 508, 508: 509, 509: 510, 510: 511, 511: 512, 512: 513, 513: 514, 514: 515, 515: 516, 516: 517, 517: 518, 518: 519, 519: 520, 520: 521, 521: 522, 522: 523, 523: 524, 524: 525, 525: 526, 526: 527, 527: 528, 528: 529, 529: 530, 530: 531, 531: 532, 532: 533, 533: 534, 534: 535, 535: 536, 536: 537, 537: 538, 538: 539, 539: 540, 540: 541, 541: 542, 542: 543, 543: 544, 544: 545, 545: 546, 546: 547, 547: 548, 548: 549, 549: 550, 550: 551, 551: 552, 552: 553, 553: 554, 554: 555, 555: 556, 556: 557, 557: 558, 558: 559, 559: 560, 560: 561, 561: 562, 562: 563, 563: 564, 564: 565, 565: 566, 566: 567, 567: 568, 568: 569, 569: 570, 570: 571, 571: 572, 572: 573, 573: 574, 574: 575, 575: 576, 576: 577, 577: 578, 578: 579, 579: 580, 580: 581, 581: 582, 582: 583, 583: 584, 584: 585, 585: 586, 586: 587, 587: 588, 588: 589, 589: 590, 590: 591, 591: 592, 592: 593, 593: 594, 594: 595, 595: 596, 596: 597, 597: 598, 598: 599, 599: 600, 600: 601, 601: 602, 602: 603, 603: 604, 604: 605, 605: 606, 606: 607, 607: 608, 608: 609, 609: 610}



```python
movie_ids = df['movieId'].unique().tolist()
movie_to_movie_encoded = {x: i for i, x in enumerate(movie_ids)}
movie_encoded_to_movie = {i: x for i, x in enumerate(movie_ids)}
```


```python
df['user'] = df['userId'].map(user_to_user_encoded)

df['movie'] = df['movieId'].map(movie_to_movie_encoded)
```


```python
df
```






  <div id="df-ede3c18a-9f5e-4acf-9231-8d0d15a4d4a2">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userId</th>
      <th>movieId</th>
      <th>rating</th>
      <th>timestamp</th>
      <th>user</th>
      <th>movie</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>1</td>
      <td>4.0</td>
      <td>964982703</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1</td>
      <td>3</td>
      <td>4.0</td>
      <td>964981247</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1</td>
      <td>6</td>
      <td>4.0</td>
      <td>964982224</td>
      <td>0</td>
      <td>2</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1</td>
      <td>47</td>
      <td>5.0</td>
      <td>964983815</td>
      <td>0</td>
      <td>3</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1</td>
      <td>50</td>
      <td>5.0</td>
      <td>964982931</td>
      <td>0</td>
      <td>4</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>100831</th>
      <td>610</td>
      <td>166534</td>
      <td>4.0</td>
      <td>1493848402</td>
      <td>609</td>
      <td>3120</td>
    </tr>
    <tr>
      <th>100832</th>
      <td>610</td>
      <td>168248</td>
      <td>5.0</td>
      <td>1493850091</td>
      <td>609</td>
      <td>2035</td>
    </tr>
    <tr>
      <th>100833</th>
      <td>610</td>
      <td>168250</td>
      <td>5.0</td>
      <td>1494273047</td>
      <td>609</td>
      <td>3121</td>
    </tr>
    <tr>
      <th>100834</th>
      <td>610</td>
      <td>168252</td>
      <td>5.0</td>
      <td>1493846352</td>
      <td>609</td>
      <td>1392</td>
    </tr>
    <tr>
      <th>100835</th>
      <td>610</td>
      <td>170875</td>
      <td>3.0</td>
      <td>1493846415</td>
      <td>609</td>
      <td>2873</td>
    </tr>
  </tbody>
</table>
<p>100836 rows × 6 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-ede3c18a-9f5e-4acf-9231-8d0d15a4d4a2')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-f2a7f0c5-874d-4599-9987-d43053b8b222">
      <button class="colab-df-quickchart" onclick="quickchart('df-f2a7f0c5-874d-4599-9987-d43053b8b222')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-f2a7f0c5-874d-4599-9987-d43053b8b222 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-ede3c18a-9f5e-4acf-9231-8d0d15a4d4a2 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-ede3c18a-9f5e-4acf-9231-8d0d15a4d4a2');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
num_users = len(user_to_user_encoded)
print(num_users)
num_movies = len(movie_to_movie_encoded)
print(num_movies)

# Nilai minimum rating
min_rating = min(df['rating'])

# Nilai maksimal rating
max_rating = max(df['rating'])

print('Number of User: {}, Number of Movie: {}, Min Rating: {}, Max Rating: {}'.format(
     num_users, num_movies, min_rating, max_rating
))
```

    610
    9724
    Number of User: 610, Number of Movie: 9724, Min Rating: 0.5, Max Rating: 5.0


Tahap persiapan telah selesai. Berikut adalah hal-hal yang telah kita lakukan pada tahap ini:

- Memahami data rating.
- Menyandikan (encode) fitur ‘userId’ dan 'movieId' ke dalam indeks integer.
- Memetakan ‘userId’ dan ‘movieId’ ke dataframe yang berkaitan.
- Mengecek beberapa hal dalam data seperti jumlah user, jumlah movie, kemudian mengubah nilai rating menjadi float.


```python
df = df.sample(frac=1, random_state=42)
df
```






  <div id="df-ddcf5d41-8769-4dfe-8192-77a7459ca293">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userId</th>
      <th>movieId</th>
      <th>rating</th>
      <th>timestamp</th>
      <th>user</th>
      <th>movie</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>67037</th>
      <td>432</td>
      <td>77866</td>
      <td>4.5</td>
      <td>1335139641</td>
      <td>431</td>
      <td>4730</td>
    </tr>
    <tr>
      <th>42175</th>
      <td>288</td>
      <td>474</td>
      <td>3.0</td>
      <td>978465565</td>
      <td>287</td>
      <td>474</td>
    </tr>
    <tr>
      <th>93850</th>
      <td>599</td>
      <td>4351</td>
      <td>3.0</td>
      <td>1498524542</td>
      <td>598</td>
      <td>2631</td>
    </tr>
    <tr>
      <th>6187</th>
      <td>42</td>
      <td>2987</td>
      <td>4.0</td>
      <td>996262677</td>
      <td>41</td>
      <td>194</td>
    </tr>
    <tr>
      <th>12229</th>
      <td>75</td>
      <td>1610</td>
      <td>4.0</td>
      <td>1158989841</td>
      <td>74</td>
      <td>727</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>6265</th>
      <td>42</td>
      <td>4005</td>
      <td>4.0</td>
      <td>996259059</td>
      <td>41</td>
      <td>1873</td>
    </tr>
    <tr>
      <th>54886</th>
      <td>364</td>
      <td>141</td>
      <td>4.0</td>
      <td>869443367</td>
      <td>363</td>
      <td>524</td>
    </tr>
    <tr>
      <th>76820</th>
      <td>480</td>
      <td>6867</td>
      <td>4.0</td>
      <td>1179163171</td>
      <td>479</td>
      <td>2240</td>
    </tr>
    <tr>
      <th>860</th>
      <td>6</td>
      <td>981</td>
      <td>3.0</td>
      <td>845556567</td>
      <td>5</td>
      <td>712</td>
    </tr>
    <tr>
      <th>15795</th>
      <td>103</td>
      <td>6711</td>
      <td>5.0</td>
      <td>1431957425</td>
      <td>102</td>
      <td>2046</td>
    </tr>
  </tbody>
</table>
<p>100836 rows × 6 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-ddcf5d41-8769-4dfe-8192-77a7459ca293')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-3f1516f2-30d9-4f15-8e9f-833cc4f6bbb4">
      <button class="colab-df-quickchart" onclick="quickchart('df-3f1516f2-30d9-4f15-8e9f-833cc4f6bbb4')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-3f1516f2-30d9-4f15-8e9f-833cc4f6bbb4 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-ddcf5d41-8769-4dfe-8192-77a7459ca293 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-ddcf5d41-8769-4dfe-8192-77a7459ca293');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>




### Membagi Data untuk Training dan Validasi



```python
# Membuat variabel x untuk mencocokkan data user dan resto menjadi satu value
x = df[['user', 'movie']].values

# Membuat variabel y untuk membuat rating dari hasil
y = df['rating'].apply(lambda x: (x - min_rating) / (max_rating - min_rating)).values

# Membagi menjadi 80% data train dan 20% data validasi
train_indices = int(0.8 * df.shape[0])
x_train, x_val, y_train, y_val = (
    x[:train_indices],
    x[train_indices:],
    y[:train_indices],
    y[train_indices:]
)

print(x, y)
```

    [[ 431 4730]
     [ 287  474]
     [ 598 2631]
     ...
     [ 479 2240]
     [   5  712]
     [ 102 2046]] [0.88888889 0.55555556 0.55555556 ... 0.77777778 0.55555556 1.        ]


Data sudah siap dimasukkan ke salam model

# Proses Training

Pada tahap ini, model menghitung skor kecocokan antara pengguna dan movie dengan teknik embedding. Pertama, melakukan proses embedding terhadap data user dan movie. Selanjutnya, melakukan operasi perkalian dot product antara embedding user dan movie. Selain itu juga dapat menambahkan bias untuk setiap user dan movie. Skor kecocokan ditetapkan dalam skala [0,1] dengan fungsi aktivasi sigmoid.

Membuat class RecommenderNet dengan keras Model class


```python
class RecommenderNet(tf.keras.Model):

  def __init__(self, num_users, num_movies, embedding_size, **kwargs):
    super(RecommenderNet, self).__init__(**kwargs)
    self.num_users = num_users
    self.num_movies = num_movies
    self.embedding_size = embedding_size
    self.user_embedding = layers.Embedding( # layer embedding user
        num_users,
        embedding_size,
        embeddings_initializer = 'he_normal',
        embeddings_regularizer = keras.regularizers.l2(1e-6)
    )
    self.user_bias = layers.Embedding(num_users, 1) # layer embedding user bias
    self.movie_embedding = layers.Embedding( # layer embeddings resto
        num_movies,
        embedding_size,
        embeddings_initializer = 'he_normal',
        embeddings_regularizer = keras.regularizers.l2(1e-6)
    )
    self.movie_bias = layers.Embedding(num_movies, 1) # layer embedding resto bias

  def call(self, inputs):
    user_vector = self.user_embedding(inputs[:,0]) # memanggil layer embedding 1
    user_bias = self.user_bias(inputs[:, 0]) # memanggil layer embedding 2
    movie_vector = self.movie_embedding(inputs[:, 1]) # memanggil layer embedding 3
    movie_bias = self.movie_bias(inputs[:, 1]) # memanggil layer embedding 4

    dot_user_movie = tf.tensordot(user_vector, movie_vector, 2)

    x = dot_user_movie + user_bias + movie_bias

    return tf.nn.sigmoid(x) # activation sigmoid
```

Melakukan proses compile terhadap model.


```python
model = RecommenderNet(num_users, num_movies, 50) # inisialisasi model

# model compile
model.compile(
    loss = tf.keras.losses.BinaryCrossentropy(),
    optimizer = keras.optimizers.Adam(learning_rate=0.001),
    metrics=[tf.keras.metrics.RootMeanSquaredError()]
)
```

Model ini menggunakan Binary Crossentropy untuk menghitung loss function, Adam (Adaptive Moment Estimation) sebagai optimizer, dan root mean squared error (RMSE) sebagai metrics evaluation.

Proses training.


```python
# Memulai training

history = model.fit(
    x = x_train,
    y = y_train,
    batch_size = 10,
    epochs = 50,
    validation_data = (x_val, y_val)
)
```

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


### Visualisasi Metrik


```python
plt.plot(history.history['root_mean_squared_error'])
plt.plot(history.history['val_root_mean_squared_error'])
plt.title('model_metrics')
plt.ylabel('root_mean_squared_error')
plt.xlabel('epoch')
plt.legend(['train', 'test'], loc='upper left')
plt.show()
```


    
![png](rekomendasi_filem_files/rekomendasi_filem_95_0.png)
    


### Mendapatkan Rekomendasi Movie


```python
movie_df = movie_new
df = pd.read_csv('drive/MyDrive/dicoding/ml-latest-small/ratings.csv')

user_id = df.userId.sample(1).iloc[0]
movie_visited_by_user = df[df.userId == user_id]

# Operator bitwise (~), bisa diketahui di sini https://docs.python.org/3/reference/expressions.html
movie_not_visited = movie_df[~movie_df['id'].isin(movie_visited_by_user.movieId.values)]['id']
movie_not_visited = list(
    set(movie_not_visited)
    .intersection(set(movie_to_movie_encoded.keys()))
)

movie_not_visited = [[movie_to_movie_encoded.get(x)] for x in movie_not_visited]
user_encoder = user_to_user_encoded.get(user_id)
user_resto_array = np.hstack(
    ([[user_encoder]] * len(movie_not_visited), movie_not_visited)
)
```


```python
movie_df
```






  <div id="df-f98f59ac-a51d-49d6-94a6-e9d305c1d2d7">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>title</th>
      <th>genre</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Toy Story (1995)</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Jumanji (1995)</td>
      <td>Adventure</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Grumpier Old Men (1995)</td>
      <td>Comedy</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>Waiting to Exhale (1995)</td>
      <td>Comedy</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>Father of the Bride Part II (1995)</td>
      <td>Comedy</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>9719</th>
      <td>193581</td>
      <td>Black Butler: Book of the Atlantic (2017)</td>
      <td>Action</td>
    </tr>
    <tr>
      <th>9720</th>
      <td>193583</td>
      <td>No Game No Life: Zero (2017)</td>
      <td>Animation</td>
    </tr>
    <tr>
      <th>9721</th>
      <td>193585</td>
      <td>Flint (2017)</td>
      <td>Drama</td>
    </tr>
    <tr>
      <th>9722</th>
      <td>193587</td>
      <td>Bungo Stray Dogs: Dead Apple (2018)</td>
      <td>Action</td>
    </tr>
    <tr>
      <th>9723</th>
      <td>193609</td>
      <td>Andrew Dice Clay: Dice Rules (1991)</td>
      <td>Comedy</td>
    </tr>
  </tbody>
</table>
<p>9724 rows × 3 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-f98f59ac-a51d-49d6-94a6-e9d305c1d2d7')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-41483557-4b6b-4753-a0db-810950714c2c">
      <button class="colab-df-quickchart" onclick="quickchart('df-41483557-4b6b-4753-a0db-810950714c2c')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-41483557-4b6b-4753-a0db-810950714c2c button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-f98f59ac-a51d-49d6-94a6-e9d305c1d2d7 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-f98f59ac-a51d-49d6-94a6-e9d305c1d2d7');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
df
```






  <div id="df-59db9b5c-7446-4880-8def-234f0b070ece">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userId</th>
      <th>movieId</th>
      <th>rating</th>
      <th>timestamp</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>1</td>
      <td>4.0</td>
      <td>964982703</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1</td>
      <td>3</td>
      <td>4.0</td>
      <td>964981247</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1</td>
      <td>6</td>
      <td>4.0</td>
      <td>964982224</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1</td>
      <td>47</td>
      <td>5.0</td>
      <td>964983815</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1</td>
      <td>50</td>
      <td>5.0</td>
      <td>964982931</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>100831</th>
      <td>610</td>
      <td>166534</td>
      <td>4.0</td>
      <td>1493848402</td>
    </tr>
    <tr>
      <th>100832</th>
      <td>610</td>
      <td>168248</td>
      <td>5.0</td>
      <td>1493850091</td>
    </tr>
    <tr>
      <th>100833</th>
      <td>610</td>
      <td>168250</td>
      <td>5.0</td>
      <td>1494273047</td>
    </tr>
    <tr>
      <th>100834</th>
      <td>610</td>
      <td>168252</td>
      <td>5.0</td>
      <td>1493846352</td>
    </tr>
    <tr>
      <th>100835</th>
      <td>610</td>
      <td>170875</td>
      <td>3.0</td>
      <td>1493846415</td>
    </tr>
  </tbody>
</table>
<p>100836 rows × 4 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-59db9b5c-7446-4880-8def-234f0b070ece')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-6c7f9259-d2b1-4844-a43f-70bb7114433b">
      <button class="colab-df-quickchart" onclick="quickchart('df-6c7f9259-d2b1-4844-a43f-70bb7114433b')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-6c7f9259-d2b1-4844-a43f-70bb7114433b button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-59db9b5c-7446-4880-8def-234f0b070ece button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-59db9b5c-7446-4880-8def-234f0b070ece');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
ratings = model.predict(user_resto_array).flatten()

top_ratings_indices = ratings.argsort()[-10:][::-1]
recommended_movie_ids = [
    movie_encoded_to_movie.get(movie_not_visited[x][0]) for x in top_ratings_indices
]

print('Showing recommendations for users: {}'.format(user_id))
print('===' * 9)
print('Resto with high ratings from user')
print('----' * 8)

top_movie_user = (
    movie_visited_by_user.sort_values(
        by = 'rating',
        ascending=False
    )
    .head(5)
    .movieId.values
)

movie_df_rows = movie_df[movie_df['id'].isin(top_movie_user)]
for row in movie_df_rows.itertuples():
    print(row.title, ':', row.genre)

print('----' * 8)
print('Top 10 resto recommendation')
print('----' * 8)

recommended_movie = movie_df[movie_df['id'].isin(recommended_movie_ids)]
for row in recommended_movie.itertuples():
    print(row.title, ':', row.genre)
```

    300/300 [==============================] - 1s 1ms/step
    Showing recommendations for users: 47
    ===========================
    Resto with high ratings from user
    --------------------------------
    Green Mile, The (1999) : Crime
    Half Nelson (2006) : Drama
    Reign Over Me (2007) : Drama
    Whiplash (2014) : Drama
    I Origins (2014) : Drama
    --------------------------------
    Top 10 resto recommendation
    --------------------------------
    Heidi Fleiss: Hollywood Madam (1995) : Documentary
    Paths of Glory (1957) : Drama
    Jonah Who Will Be 25 in the Year 2000 (Jonas qui aura 25 ans en l'an 2000) (1976) : Comedy
    Stunt Man, The (1980) : Action
    Belle époque (1992) : Comedy
    Trial, The (Procès, Le) (1962) : Drama
    Adam's Rib (1949) : Comedy
    Memories of Murder (Salinui chueok) (2003) : Crime
    Enter the Void (2009) : Drama
    Band of Brothers (2001) : Action


# Evaluasi

### Precision


```python
sample_data = data.sample(n=5,replace=True)

sample_data
```






  <div id="df-be8aef78-25b8-4a87-8a74-cb0bdd37aa3f">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>title</th>
      <th>genre</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1489</th>
      <td>2015</td>
      <td>Absent-Minded Professor, The (1961)</td>
      <td>Children</td>
    </tr>
    <tr>
      <th>3575</th>
      <td>4903</td>
      <td>In the Bedroom (2001)</td>
      <td>Drama</td>
    </tr>
    <tr>
      <th>6578</th>
      <td>55294</td>
      <td>Weirdsville (2007)</td>
      <td>Comedy</td>
    </tr>
    <tr>
      <th>3578</th>
      <td>4912</td>
      <td>Funny Girl (1968)</td>
      <td>Drama</td>
    </tr>
    <tr>
      <th>2138</th>
      <td>2847</td>
      <td>Only Angels Have Wings (1939)</td>
      <td>Adventure</td>
    </tr>
  </tbody>
</table>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-be8aef78-25b8-4a87-8a74-cb0bdd37aa3f')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-7a452890-1f19-4316-a25f-59cf27c1bdac">
      <button class="colab-df-quickchart" onclick="quickchart('df-7a452890-1f19-4316-a25f-59cf27c1bdac')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-7a452890-1f19-4316-a25f-59cf27c1bdac button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-be8aef78-25b8-4a87-8a74-cb0bdd37aa3f button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-be8aef78-25b8-4a87-8a74-cb0bdd37aa3f');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
for index, row in sample_data.iterrows():
  print(row['title'], row['genre'])

  title = row['title']
  genre = row['genre']
  mr = movie_recommendations(title)
  print(mr)

  p = (len(mr)/len(mr['genre']==genre)) * 100
  print("Precision", p)


```

    Absent-Minded Professor, The (1961) Children
                                          title     genre
    0  Dreamer: Inspired by a True Story (2005)  Children
    1                  Ramona and Beezus (2010)  Children
    2                  Mighty Ducks, The (1992)  Children
    3           Another Cinderella Story (2008)  Children
    4        Muppet Christmas Carol, The (1992)  Children
    Precision 100.0
    In the Bedroom (2001) Drama
                                                   title  genre
    0  Monsieur Ibrahim (Monsieur Ibrahim et les fleu...  Drama
    1                                   Apt Pupil (1998)  Drama
    2                             Langoliers, The (1995)  Drama
    3                                    Margaret (2011)  Drama
    4                           Elephant Man, The (1980)  Drama
    Precision 100.0
    Weirdsville (2007) Comedy
                                     title   genre
    0  Andrew Dice Clay: Dice Rules (1991)  Comedy
    1              Mr. & Mrs. Smith (1941)  Comedy
    2                  Garden State (2004)  Comedy
    3                   Let It Snow (1999)  Comedy
    4    Heartbreaker (L'Arnacoeur) (2010)  Comedy
    Precision 100.0
    Funny Girl (1968) Drama
                                                   title  genre
    0  Monsieur Ibrahim (Monsieur Ibrahim et les fleu...  Drama
    1                                   Apt Pupil (1998)  Drama
    2                             Langoliers, The (1995)  Drama
    3                                    Margaret (2011)  Drama
    4                           Elephant Man, The (1980)  Drama
    Precision 100.0
    Only Angels Have Wings (1939) Adventure
                                          title      genre
    0                          Toy Story (1995)  Adventure
    1                         Copenhagen (2014)  Adventure
    2            All Dogs Go to Heaven 2 (1996)  Adventure
    3                         Sweetgrass (2009)  Adventure
    4  Charlie and the Chocolate Factory (2005)  Adventure
    Precision 100.0



```python
ratings_n = pd.read_csv('drive/MyDrive/dicoding/ml-latest-small/ratings.csv')
ratings_n.head()
```






  <div id="df-ef84fc9f-d963-4249-a814-e3c26f26ee4d">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userId</th>
      <th>movieId</th>
      <th>rating</th>
      <th>timestamp</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>1</td>
      <td>4.0</td>
      <td>964982703</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1</td>
      <td>3</td>
      <td>4.0</td>
      <td>964981247</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1</td>
      <td>6</td>
      <td>4.0</td>
      <td>964982224</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1</td>
      <td>47</td>
      <td>5.0</td>
      <td>964983815</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1</td>
      <td>50</td>
      <td>5.0</td>
      <td>964982931</td>
    </tr>
  </tbody>
</table>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-ef84fc9f-d963-4249-a814-e3c26f26ee4d')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-ea659a1b-b7bc-48ce-830a-405e0ed4ba5a">
      <button class="colab-df-quickchart" onclick="quickchart('df-ea659a1b-b7bc-48ce-830a-405e0ed4ba5a')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-ea659a1b-b7bc-48ce-830a-405e0ed4ba5a button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-ef84fc9f-d963-4249-a814-e3c26f26ee4d button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-ef84fc9f-d963-4249-a814-e3c26f26ee4d');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>





```python
from sklearn.metrics import mean_squared_error

rmse = pd.DataFrame(columns=['train', 'test'], index=['collaborative_filtering'])

# rmse = mean_squared_error(y_pred = model.predict(x_train), y_true=y_train, squared=False)

rmse.loc['collaborative_filtering', 'train'] = mean_squared_error(y_pred = model.predict(x_train), y_true=y_train, squared=False)
rmse.loc['collaborative_filtering', 'test'] = mean_squared_error(y_pred = model.predict(x_val), y_true=y_val, squared=False)

rmse
```

    2521/2521 [==============================] - 7s 3ms/step
    631/631 [==============================] - 1s 2ms/step







  <div id="df-90ac3564-6eb8-4be4-8a67-2ca0bd18c3af">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>train</th>
      <th>test</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>collaborative_filtering</th>
      <td>0.203803</td>
      <td>0.211049</td>
    </tr>
  </tbody>
</table>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-90ac3564-6eb8-4be4-8a67-2ca0bd18c3af')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>



    <div id="df-0dbb8569-9e42-4873-90fb-53046b232bc4">
      <button class="colab-df-quickchart" onclick="quickchart('df-0dbb8569-9e42-4873-90fb-53046b232bc4')"
              title="Suggest charts."
              style="display:none;">

<svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
     width="24px">
    <g>
        <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/>
    </g>
</svg>
      </button>
    </div>

<style>
  .colab-df-quickchart {
    background-color: #E8F0FE;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    fill: #1967D2;
    height: 32px;
    padding: 0 0 0 0;
    width: 32px;
  }

  .colab-df-quickchart:hover {
    background-color: #E2EBFA;
    box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
    fill: #174EA6;
  }

  [theme=dark] .colab-df-quickchart {
    background-color: #3B4455;
    fill: #D2E3FC;
  }

  [theme=dark] .colab-df-quickchart:hover {
    background-color: #434B5C;
    box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
    filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
    fill: #FFFFFF;
  }
</style>

    <script>
      async function quickchart(key) {
        const containerElement = document.querySelector('#' + key);
        const charts = await google.colab.kernel.invokeFunction(
            'suggestCharts', [key], {});
      }
    </script>

      <script>

function displayQuickchartButton(domScope) {
  let quickchartButtonEl =
    domScope.querySelector('#df-0dbb8569-9e42-4873-90fb-53046b232bc4 button.colab-df-quickchart');
  quickchartButtonEl.style.display =
    google.colab.kernel.accessAllowed ? 'block' : 'none';
}

        displayQuickchartButton(document);
      </script>
      <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-90ac3564-6eb8-4be4-8a67-2ca0bd18c3af button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-90ac3564-6eb8-4be4-8a67-2ca0bd18c3af');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>



