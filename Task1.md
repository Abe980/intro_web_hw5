# Задача №1: проверить XML на Well formed:

## Оригинал

<req>

        <surname>Иванов</surname>

        <name>Иван</name>

        <patronymic>Иванович</patronymic>

        <birthdate>01.01.1990</birthdate>

        <birthplace>Москва</birthplace>

        <phone>8 926 766 48 48</phone>

</req               

#### Ошибки
- Не хватает объявления xml
- Не хватает угловой скобки в самом конце

## Исправленный

<?xml version="1.1" encoding="UTF-8" ?>

<req>

        <surname>Иванов</surname>

        <name>Иван</name>

        <patronymic>Иванович</patronymic>

        <birthdate>01.01.1990</birthdate>

        <birthplace>Москва</birthplace>

        <phone>8 926 766 48 48</phone>

</req>




