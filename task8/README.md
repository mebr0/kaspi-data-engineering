# Task 7

## Objectives
* Java Serialization

## Original task
> 1. реализовать вывод текстовых сообщений в поток в текстовый файл в каталоге программы.
>   каждое сообщение должно содержать дату, когда оно произошло и текст.
>   все сообщения относительно покупателей должны содержать номер покупателя
>   все сообщения относительно касс должны содержать номер кассы
> 
> 2. Добавить класс "магазин", к которому будет храниться коллекция покупателей. 
>   При создании покупателей добавлять их в коллекцию в "магазин".
> 
>   Должна получиться принадлежность - Магазин - Покупатель - Корзина - Суб-Корзина - Товары
> 
> 3. изменить логику основного метода, реализовать последовательность:
>   - создание покупателей с товарами
>   - добавление в магазин
>   - сохранение (сериализация) начиная с объекта "магазин" в файл в каталоге программы
>   - расчет покупателей
> 
> 4. добавить загрузку состояния магазина из файла, логика будет выгляыдеть:
>   - попытка загрузить магазин из сериализованного представления
> 	если нет, то
> 		- создание покупателей с товарами
> 		- добавление в магазин
>   - добавление одного покупателя с товарами
>   - сохранение (сериализация) в файл в каталоге программы
>   - расчет покупателей

Note: all typos preserved