# Отчёт о тестировании функционала валидации номеров банковских карт

## Краткое описание

09/09/2021 было проведено фунциональное тестирование валидации номеров банковских карт.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* ["Result is FAIL" при использовании номера карты меньше или больше 16 цифр](https://github.com/FiruzKholmatov/CC_Number_Validator/issues/1#issue-994275235)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Баг репорт](https://github.com/FiruzKholmatov/CC_Number_Validator/issues/1#issue-994275235)
* [Исходный код](https://github.com/FiruzKholmatov/CC_Number_Validator/blob/aaa3f22d63082b1c03191361463ab33abd66d220/src/Main.java)


В качестве тестовых данных использовались данные 
* данные валидных карт с сайта [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)

Тестирование производилось в следующем окружении:
* Windows 10, 64x
*  Версия Java, Amazon Coretto version 11.0.12