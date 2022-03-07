В этой папке находится проект - аналитическое исследование популярности игр и платформ.

## Формат

Проект сделан в Jupyter notebook: Games(EDA).ipynb

## Описание задачи

Заказчик - интернет-магазин, который продаёт по всему миру компьютерные игры.
Из открытых источников доступны исторические данные:
- о продажах игр
- оценки пользователей и экспертов
- жанры и платформы (например, Xbox или PlayStation)\
Нужно выявить, что определяет успешность игры.
Это позволит интернет-магазину сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

## Описание файла с данными

Использован файл games.csv.\
*в репозиторий не выложен

## Описание данных

Есть данные до 2016 года. Планируется рекламная кампания на 2017-й.
В наборе данных попадается аббревиатура ESRB (Entertainment Software Rating Board) — это ассоциация, определяющая возрастной рейтинг компьютерных игр.
ESRB оценивает игровой контент и присваивает ему подходящую возрастную категорию, например, «Для взрослых», «Для детей младшего возраста» или «Для подростков».

Поля в файле с данными:
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
- Rating — рейтинг от организации ESRB (англ. Entertainment Software Rating Board).
Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.\
*Данные за 2016 год неполные