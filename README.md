**Задание [ссылка](https://github.com/netology-code/loadqa-homeworks/blob/main/3.Load%20web/homework_lecture3.md)**

# Проведение нагрузочного веб-тестирования сайта кинотеатра

Репозиторий с сайтом кинотеатра https://github.com/mshegolev/congenial-potato.git
## Тестирование покупки билета в кинотеатр и получения QR кода

**Cценарий тестирования**
1. Открыть страницу в Chrome по url - http://localhost:8000. Ожидание: 2000-4000 мс
2. Выбрать следующий день. Ожидание: 2000-4000 мс
3. Выбрать Зал 1 - Фильм 3 - Сеанс на 11:10. Ожидание: 2000-4000 мс
4. Выбрать место. Ожидание: 2000-4000 мс. 
5. Клик по кнопке "Забронировать". Ожидание: 2000-4000 мс
6. Клик по кнопке "Получить код бронирования".

# BlazeMeter
**LOAD TEST REPORT в системе BlazeMeter: [ссылка](https://a.blazemeter.com/app/executive-summary/index.html?master_id=67319227&selectedTimeMeasure=milliseconds#/)**

**Cкриншоты нагрузки в системе BlazeMeter**

![2023-04-07_12-59-29](https://user-images.githubusercontent.com/105548819/230682040-77717de6-9058-4f01-afdb-a218764dd4e5.png)
![2023-04-07_12-59-53](https://user-images.githubusercontent.com/105548819/230682043-06a3f169-6437-4494-8e56-c2552ac2662e.png)
![2023-04-07_13-00-15](https://user-images.githubusercontent.com/105548819/230682046-30e4f86a-b6f8-49be-ab6f-11dc53451492.png)
![2023-04-07_13-00-32](https://user-images.githubusercontent.com/105548819/230682047-3a60aff6-53b3-4189-baa2-b63f39c4b426.png)
![2023-04-07_13-01-35](https://user-images.githubusercontent.com/105548819/230682048-97c2e946-20ce-4209-93a5-edc6ae8032db.png)
![2023-04-07_13-01-57](https://user-images.githubusercontent.com/105548819/230682050-460ad523-52e7-4c5d-aa2f-81958501c82f.png)
![2023-04-07_13-02-23](https://user-images.githubusercontent.com/105548819/230682051-361f133d-7c4a-4ed4-9358-d98ca5ae5bcc.png)

# JMeter

**Записанный сценарий JMeter в формате jmx: [ссылка](https://github.com/VisYar/HW3-websiteCinema/blob/master/Cinema%2004-07-23.jmx)**

**Графики в influx**

![2023-04-07_22-10-08](https://user-images.githubusercontent.com/105548819/230682183-3441cae6-a687-493d-bd89-bed9fd713a41.png)

**Cкриншоты сценария в JMeter**

![2023-04-07_22-11-51](https://user-images.githubusercontent.com/105548819/230682184-3dcfe9db-cd31-4833-8d65-809463ef86d3.png)
![2023-04-07_22-12-19](https://user-images.githubusercontent.com/105548819/230682185-417c6ca6-1010-411e-8c77-cecb8cad4286.png)
![2023-04-07_22-12-41](https://user-images.githubusercontent.com/105548819/230682188-a74cbab4-9160-49fc-bc21-fc7986dff5df.png)
![2023-04-07_22-13-09](https://user-images.githubusercontent.com/105548819/230682189-34e95aed-4c96-4c8c-8e5f-ebfd8a2d6d97.png)
![2023-04-07_22-13-28](https://user-images.githubusercontent.com/105548819/230682191-48f9fe22-073a-4651-ab1b-95c03582bace.png)
![2023-04-07_22-13-37](https://user-images.githubusercontent.com/105548819/230682192-d5809d84-c44c-42a9-acb3-565cacbb9cd0.png)
![2023-04-07_22-13-47](https://user-images.githubusercontent.com/105548819/230682194-956bb85b-3b90-442e-b1e3-b83bdfc19dad.png)
![2023-04-07_22-13-57](https://user-images.githubusercontent.com/105548819/230682196-fbdbfeca-1afa-4c09-88b4-990ab9a795ab.png)
![2023-04-07_22-14-36](https://user-images.githubusercontent.com/105548819/230682198-1c5cef69-0ee3-4486-8330-b0e1f6efc071.png)

