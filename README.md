<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://imgbb.com/">
    <img src="https://github.com/SuaraNusa/suaranusa-assets/blob/main/images/logo.png?raw=true" alt="Logo" width="100" height="120">
  </a>

  <h3 align="center">SuaraNusa Machine Learning Model</h3>
  </h3>

  <p align="center">
    SuaraNusa Machine Learning Model is a machine learning model that is used to predict sound classification.
    <br />
  </p>
</div>

# Introduction
<!-- jelaskan bahwa semua resource seperti list lagu ataupun dataset berasal dari web scrapping
seperti list judul lagu di dapatkan dari website A dan download lagu berasal dari youtube
  -->
SuaraNusa Machine Learning Model is a machine learning model that is used to predict sound classification. The dataset used in this project is obtained from web scraping. The list of songs is obtained from  [Dianisa](https://dianisa.com/lagu-daerah-indonesia-beserta-lirik-dan-asalnya/) and the songs are downloaded from [Youtube](https://youtube.com/).

# Dataset
The dataset used in this project is obtained from web scraping. The list of songs is obtained from  [Dianisa](https://dianisa.com/lagu-daerah-indonesia-beserta-lirik-dan-asalnya/) and the songs are downloaded from [Youtube](https://youtube.com/).

# Technologies
- [Python](https://www.python.org/)
- [requests](https://pypi.org/project/requests/)
- [Jupyter Notebook](https://jupyter.org/)
- [beautifulsoup4](https://pypi.org/project/beautifulsoup4/)
- [Pandas](https://pandas.pydata.org/)
- [youtube_search](https://pypi.org/project/youtube-search/)
- [pytube](https://pypi.org/project/pytube/)
- [ffmpeg](https://ffmpeg.org/)
- [pydub](https://pypi.org/project/pydub/)
- [Scikit-learn](https://scikit-learn.org/)
- [Tensorflow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)
- [Librosa](https://librosa.org/)
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)

# Installation
1. Clone the repo
   ```sh
   git clone (https://github.com/SuaraNusa/python-suara-nusa-model
    ```

2. Install the required packages
    ```sh
    pip install -r requirements.txt
    ```

# Usage
**Note: You must open Jupyter Notebook using Visual Studio Code or Jupyter Notebook**

## 1. Web Scraping
Open file [scraping_song_list.ipynb](/scraping_song_list.ipynb) and run the code to get the list of songs.

## 2. Download Songs
Open file [scraping.ipynb](/scraping.ipynb) and run the code to download the songs.

## 3. Feature Extraction and Training
In this project, there are three machine learning models that you can use:
- [main.ipynb](/main.ipynb) for SVM model
- [tf_main.ipynb](/tf_main.ipynb) for Neural Network model
- [tl_main.ipynb](/tl_main.ipynb) for Neural Network model with Transfer Learning

# License
Distributed under the MIT License. See `LICENSE` for more information.

