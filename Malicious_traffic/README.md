В этой папке находится проект по классификации злонамеренного трафика.

## Формат

Проект сделан в Jupyter notebook: Malicious_traffic.ipynb

## Описание задачи

Компания онлайн-сервис с высоким уровнем входящего трафика имеет специализированный отдел безопасности, который занимается фильтрацией и анализом трафика.\
Сотрудники этого отдела обратились за помощью в автоматизации выявления аномального и злонамеренного трафика.\
В рамках проекта разработана модель, которая классифицирует трафик на нормальный и злонамеренный, включая следующие типы атак: DDoS, SQL-инъекции, брутфорс, вредоносные программы и т.д.\
Настроенная модель Catboost работает максимально качественно, так как цена ошибки может быть очень высока.\
Качество модели оценено по различным метрикам классификации: precision, recall, f1_score, accuracy.

## Описание файла с данными

Использован файл:\
network_traffic_data.csv - датасет размером 79*539 616, состоит из 78 фичей и таргета.

*в репозиторий не выложен



