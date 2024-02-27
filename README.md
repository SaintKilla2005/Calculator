# Calculator
<h2 align = 'center'>Онлайн калькулятор на микросервисной архитектуре</h2>
<p align = 'center'>Данный проект написан на языке Java, фреймворк Spring. Ниже будут показаны постепенные шаги создания</p>
1)Установил и настроил среду разработки:
<img align = 'center' src = "screen1.jpg">

2)Собрал проект на сайте start.spring.io:
<img align = 'center' src = "screen3.jpg">

3)Извлек из данной папки все в созданный мною проект:
<img align = 'center' src = "screen4.jpg">

4)В папке "practice" создал папку "controller":
<img align = 'center' src = "screen6.jpg">

5)Создал файл CalcController.java и написал в нем два метода для моего калькулятора, а также создал аннотации к ним:
<img align = 'center' src = "screen9.jpg">

6)Отладка без ошибок:
<img align = 'center' src = "screen10.jpg">

7)Перехожу на localhost и передаю в запрос метод, которым хочу воспользоваться и 2 аргумента, соответсвенно получаю результат:
<img align = 'center' src = "screen11.jpg">

8)Подключаю веб-интерфейс для моей программы при помощи Swagger, для этого  в xml файле пишу нужные зависимости:
<img align = 'center' src = "screen12.jpg">

9)Дабы проверить интерфейс , ввожу новую ссылку в браузере - http://localhost:8080/swagger-ui/index.html. Результат:
<img align = 'center' src = "screen13.jpg">
