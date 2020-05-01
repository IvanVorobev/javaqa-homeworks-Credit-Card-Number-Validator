# Отчёт о тестировании программы Credit Card Number Validator

## Краткое описание

01.05.2020 было проведено тестирование программы Credit Card Number Validator

На тестирование затрачено: 1,5 часа

1. В результате тестирования работы программы Credit Card Number Validator выявлены следующие дефекты:
* [Ошибка FAIL в Credit Card Number Validator при проверке номеров карт из 19 знаков](https://github.com/IvanVorobev/javaqa-homeworks-Credit-Card-Number-Validator/issues/1)
* [Ошибка FAIL в Credit Card Number Validator при проверке номера карты из 14 знаков](https://github.com/IvanVorobev/javaqa-homeworks-Credit-Card-Number-Validator/issues/2)
* [Ошибка FAIL в Credit Card Number Validator при проверке номера карты из 15 знаков](https://github.com/IvanVorobev/javaqa-homeworks-Credit-Card-Number-Validator/issues/3)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Отчет о тестировании
* Баг-репорты в Issues
* Руководство по установке IntelliJ IDEA

В качестве тестовых данных при проверке программы Credit Card Number Validator использовались номера кредитных карт из [Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html):

* 4539202836562680 Visa

* 4556142198775827 Visa

* 4916772761181314846 Visa

* 6011340692520196084 Discover 

* 5420208869673194 MasterCard

* 3533763399318147352 JCB

* 36048136703052 Diners Club - International

* 6386993981679241 InstaPayment

* 347187764042112 American Express (AMEX)

* 5583861385896690 Diners Club - North America

* 6761390585347520 Maestro

Ожидаемый результат:

отображение в нижней части программы IntelliJ IDEA
```
Result is OK
Process finished with exit code 0

```
Тестирование производилось в следующем окружении:
* Windows 10
* IntelliJ IDEA COMMUNITY 2020.1
* openjdk version "11.0.7" 2020-04-14
* git version 2.26.0.windows.1