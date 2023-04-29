# Детекция повреждений дорожного покрытия
## Аннотация
Результат выполнения задания World Skills. Выделяет повреждения дорожного покрытия с помощью генерируемой битовой маски
## Особенности
- Использует модель Unet
- [Dataset](https://www.researchgate.net/publication/282807920_Dataset_of_images_used_for_pothole_detection)
## Как использовать
В репозитории лежат два файла формата Jupyter Notebook.
Один из них анализирует содержимое датасета, другой собирает данные и использует их для обучения. 
Вы можете запустить это на платформе Jupyter Notebook или Google Colab, изменив конфиг в заголовке файла.
Внутри файлов находится документация
## Предупреждение
Модель не обучена. Чтобы пользоваться ею, вам нужно будет ее обучить. Модель UNET требовательна к железу, поэтому рекомендуется обучение с помощью GPU
## Ссылки
[1] S. Nienaber, M.J. Booysen, R.S. Kroon, “Detecting potholes using simple image processing techniques and real-world footage”, SATC, July 2015, Pretoria, South Africa.
[2] S. Nienaber, R.S. Kroon, M.J. Booysen , “A Comparison of Low-Cost Monocular Vision Techniques for Pothole Distance Estimation”, IEEE CIVTS, December 2015, Cape Town, South Africa.
