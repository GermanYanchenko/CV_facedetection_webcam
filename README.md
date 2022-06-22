# Детектирование человеческого лица при работе с webcam
## Исходные данные
С помощью библиотеки openCV происходит подключение webcam и сохранение изображений. Затем с помощью labelme производилась разметка положения лица. Полученные изображения представлены ниже.
![alt text](https://github.com/GermanYanchenko/CV_facedetection_webcam/blob/main/readme_img/base.png?raw=true)
# Данные после преобразования
С помощью библиотеки albumentation увеличиваем количество изображений, путем различных модификаций исходных изображений. Пример:
![alt text](https://github.com/GermanYanchenko/CV_facedetection_webcam/blob/main/readme_img/aug_data.png?raw=true)
# Работа модели в реальном масштабе времени
Используя за основу VGG16 обучаем модель и проверяем работу в реальном времени. Итог:
![alt text](https://github.com/GermanYanchenko/CV_facedetection_webcam/blob/main/readme_img/facedetection.gif?raw=true)
