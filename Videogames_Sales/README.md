# Исследовательский анализ продаж видеоигр

### Цель проекта 
Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры.

### Описание данных

- Name — название игры
- Platform — платформа
- Year_of_Release — год выпуска
- Genre — жанр игры
- NA_sales — продажи в Северной Америке (миллионы проданных копий)
- EU_sales — продажи в Европе (миллионы проданных копий)
- JP_sales — продажи в Японии (миллионы проданных копий)
- Other_sales — продажи в других странах (миллионы проданных копий)
- Critic_Score — оценка критиков (максимум 100)
- User_Score — оценка пользователей (максимум 10)
- Rating — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.


### Используемые библиотеки 
pandas, matplotlib, numpy, scipy

### Результаты

**Куда лучше вложить рекламный бюджет**
Лучше всего бюджет вкладывать:
* В Северной Америки или Европе: 
    * Платформа: PS4
    * Жанр должен быть Shooter(так как он находится в топе по платформам для этих регионов и медиана продаж больше других).
    * ESRB должна быть 17+
    * Обязательно должны быть положительные отзывы критиков
    Это должно помочь максимально прогнозировать окупаемость рекламы и прибыли
* В Японии:
    * Платформа должна быть 3DS
    * Жанр: Role-Playing или Action
    * ESRB не сильно влияет на продажу в данном регионе
    * Должны быть положительные отзывы критиков
    Так как рынок Японии отличается, то и требования другие, эти рекомендации должны помочь для окупаемости рекламы и прибыли