# Отчёт о тестировании функциональности по определению валидности номера банковской карты
## Краткое описание

02.12.2021 - 02.12.2021 было проведено тестирование приложения "Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты: 
* Номера банковских карт, состоящие из 13, 15, 18, 19 цифр, не проходят валидацию (см. [bug-report](https://github.com/by4enkova/hw_validator/issues/1#issue-1069930980)).

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* IntelliJ IDEA;
* Тестовые данные;
* [credit card number generator](https://www.freeformatter.com/credit-card-number-generator-validator.html).

В качестве тестовых данных использовались данные [источника](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md).

Тестирование производилось в следующем окружении:
* Windows [Version 10.0.19044.1288]
* openjdk version "11.0.13" 2021-10-19
