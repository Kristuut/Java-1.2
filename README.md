# Отчёт о тестировании части кода

## Краткое описание

11.07.20 - 11.07.20 было проведено функциональное тестирование части кода.

На тестирование затрачено: 1,5 часа.

В результате тестирования выявлены следующие дефекты:
* [Ошибка при номере карты AMEX](https://github.com/Kristuut/Java-1.2/issues/1)
* [Баг, если номер карты состоит из 14 цифр](https://github.com/Kristuut/Java-1.2/issues/2)
* [Баг, если номер карты состоит из 19 цифр](https://github.com/Kristuut/Java-1.2/issues/3)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Баг-репорты в Issues 
* Отчет о тестировании
* В качестве тестовых данных использовались номера карт по [ссылке](https://www.freeformatter.com/credit-card-number-generator-validator.html) .

Тестирование производилось в следующем окружении:
* OC Windows 10, 64-bit
* Java version 11.0.7
* IntelliJ IDEA