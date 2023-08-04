# Предобработка данных для составления дашборда в Microsoft Power BI.

## Данные

В данных представлена статистика с различными метриками социальных сетей (репосты, лайки, просмотры и т.д.). Используются данные за один месяц (декабрь 2022 года).

Полный датасет можно найти по ссылке: https://www.kaggle.com/datasets/ramjasmaurya/top-1000-social-media-channels.

## Используемые файлы
```
- social media influencers-INSTAGRAM - -DEC 2022.csv - статистика по Instagram
- social media influencers-TIKTOK - ---DEC 2022.csv - статистика по TikTok
- social media influencers-YOUTUBE - --DEC 2022.csv - статистика по YouTube
```

## Описание данных

### social media influencers-INSTAGRAM - -DEC 2022.csv

```
- Rank - колонка с индексом
- name - имя блогера
- instagram name - ник блогера в Instagram
- Category_1 - категория производимого блогером контента 1
- Category_2 - категория производимого блогером контента 2
- followers - количество подписчиков
- country - в какой стране проживает основная аудитория блогера
- Eng. (Auth.) - вовлеченность подписчиков (взаимодействия подписчиков с контентом блогера)
- Eng. (Avg.) - общая вовлеченность (взаимодействия как подписчиков так и не подписчиков)
```

### social media influencers-TIKTOK - ---DEC 2022.csv

```
- Rank - колонка с индексом
- Tiktoker name - ник блогера в TikTok
- Tiktok name - имя блогера
- followers - количество подписчиков
- views(avg) - среднее число просмотров
- likes(avg.) - среднее число лайков
- comments(avg.) - среднее число комментариев
- shares(avg.) - среднее число репостов
```

### social media influencers-YOUTUBE - --DEC 2022.csv

```
- s.no - колонка с индексом
- Youtube channel - название канала
- youtuber name - имя блогера
- Category - категория производимого блогером контента 1
- Category-2 - категория производимого блогером контента 2
- Followers - количество подписчиков
- Country - в какой стране проживает основная аудитория блогера
- Views (Avg.) - среднее число просмотров
- Likes (Avg.) - среднее число лайков
- Comments (Avg.) - среднее число комментариев
```

## Задача

Предобработать данные для составления дашборда в Microsoft Power BI. Дашборд должен упрощать поиск блогеров, соответствующих определенным условиям.

### Instagram

Сортировка по:

- рангу (числу подписчиков)
- категории контента
- стране, в которой проживает основная аудитория

### TikTok

Сортировка по:

- рангу (числу подписчиков)
- уровню вовлеченности подписчиков
- уровню привлекательности контента блогера

### YouTube

Сортировка по:

- рангу (числу подписчиков)
- категории контента
- стране, в которой проживает основная аудитория

## Используемые библиотеки

![Ipynb](https://img.shields.io/badge/Python-pandas-blue.svg?style=flat&logo=python&logoColor=white)
![Ipynb](https://img.shields.io/badge/Python-numpy-blue.svg?style=flat&logo=python&logoColor=white)
![Ipynb](https://img.shields.io/badge/Python-re-blue.svg?style=flat&logo=python&logoColor=white)

# Визуализации в Power BI

### Instagram

![dashboard_instagram](https://github.com/mellow-moon/social_media_dashboard_preprocessing/assets/106676401/114f0dcf-1e6d-4929-bce0-4fa64c9b84b6)

### TikTok

![dashboard_tiktok](https://github.com/mellow-moon/social_media_dashboard_preprocessing/assets/106676401/d5211da4-d9e9-4949-b8df-b08ab99c0365)

### YouTube

![dashboard_youtube](https://github.com/mellow-moon/social_media_dashboard_preprocessing/assets/106676401/e5855c24-fbea-4ff3-9a72-3c7b338a4106)
