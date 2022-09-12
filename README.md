# Подготовка данных для проведения анализа тональности. Preparing Data for Sentiment Analysis.

**Данные**:
Имеется текстовый файл со списком статей. Каждая новая статья начинается с новой строки и представляет собой словарь,
содержащий 3 значения:
- url
- title
- article

**Задача**:
Подготовить данные для sentiment analysis.

Подготовка включает в себя:
- чистка данных, без потери самого текста статьи
- нормализация данных
- обработка данных


**Data**:
There is a text file with a list of articles. Each new entry starts on a new line and is a dictionary containing 3 values:
- url
- title
- article

**A task**:
Prepare data for sentiment analysis.

Preparation includes:
- data cleaning, without losing the text of the article itself
- data normalization
- data processing

-------------------------------

Результаты (results):
| File Name | Description |
| --- | --- |
| **NLP_test2.ipynb** | Предобработка и подготовка данных в виде векторного представления с применением TF-IDF. Preprocessing and preparation of data as a vector representation using TF-IDF. |
| **sentiment_analysis.ipynb** | Анализ тональности для каждой из статей с использованием библиотеки dostoevsky. Sentiment analysis for each of the articles using the dostoevsky library. |
