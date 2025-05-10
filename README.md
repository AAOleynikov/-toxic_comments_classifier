# Toxic comments classifier

### Основные цели и задачи проекта

Разработать бинарный классификатор, у которого на входе будет текст комментария, на выходе 2 класса - токсичный/нет комментарий.

**Метрики:** Нужно максимизировать кол-во удаленных негативных комментариев, при этом не удаляя нейтральные. Максимизировать recall, precision

### Краткая информация о данных

Датасет из токсичных комментариев с сайтов Двач и Пикабу: [Internet_Movie_Database](https://www.kaggle.com/datasets/blackmoon/russian-language-toxic-comments).  
Самосборный датасет токсичных комментариев с сайтов Двач [2ch_parser](https://github.com/AAOleynikov/2ch_parser).
с разметкой через deepseek [toxic_comment_autolabeling_deepseek_api](https://github.com/AAOleynikov/toxic_comment_autolabeling_deepseek_api).

### Результаты
Обучена в качестве baseline модель LogisticRegression с результатами precision = 0.8069, recall = 0.7452. 
