<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<!-- [![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![project_license][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url] -->






<!-- ABOUT THE PROJECT -->
## About The Project
sentement analysis with TF-IDF , bert and word2vec
the output is 9 models wich based on your review predict a ratting 

Dataset
consists of two columns one is the review and the other is the ratting

project steps

1. Load and preprocess data:

• Load the dataset and preprocess the reviews (e.g., lowercasing, re-
moving stop words and punctuation)

2. Vectorize reviews:

• TF-IDF:
– from sklearn.feature extraction.text import TfidfVectorizer

• Word2Vec:
– from gensim.models import Word2Vec

• BERT:
– from sentence transformers import SentenceTransformer

3. Hyperparameter tuning for classification Models:1

• Conduct a grid search on each model to identify the optimal hyper-
parameters, utilizing the F1 score for evaluation

– Logistic Regression

– Random Forests

– K-Nearest Neighbors


<p align="right">(<a href="#readme-top">back to top</a>)</p>




## Contact
Hossein Dehghani - h.deh1383@ggmail.com

Project Link: https://github.com/DEHOSS/IMBD-film-KNN-recommender

<p align="right">(<a href="#readme-top">back to top</a>)</p>


[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
