## Отчёт о тестировании Credit Card Number Validator
### Краткое описание

3.05.2020 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:

 * [Ошибка при введении валидного номера карты VISA](https://github.com/UlyanaErmoshina/Credit-Card-Number-Validator/issues/2)
* [Ошибка при введении валидного номера карты AMEX](https://github.com/UlyanaErmoshina/Credit-Card-Number-Validator/issues/3)
* [Ошибка при введении валидного номера карты Diners Club - International](https://github.com/UlyanaErmoshina/Credit-Card-Number-Validator/issues/7)
 * [Ошибка при введении валидного номера карты JCB](https://github.com/UlyanaErmoshina/Credit-Card-Number-Validator/issues/6)
* [Ошибка при введении валидных номеров карт Diners Club - Carte Blanche](https://github.com/UlyanaErmoshina/Credit-Card-Number-Validator/issues/5)
* [Ошибка при введении валидных номеров карт Discover](https://github.com/UlyanaErmoshina/Credit-Card-Number-Validator/issues/4)


## Описание процесса тестирования

В качестве тестовых данных использовались данные с сайта [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html):

Visa
* 4916010855812750 
Ожидаемый результат ОК
* 4929770640347949155
Ожидаемый результат ОК

Discover
* 6011361504174723
Ожидаемый результат ОК
* 6011377407181011
Ожидаемый результат ОК

Diners Club - Carte Blanche
* 30172059331406
Ожидаемый результат ОК
* 30157544201272
Ожидаемый результат ОК

Visa Electron
* 4026983979097614
Ожидаемый результат ОК

MasterCard
* 5581689876803970
Ожидаемый результат ОК

JCB
* 3542168015263324
Ожидаемый результат ОК

Diners Club - International
* 36399445833837
Ожидаемый результат ОК
* 36419274083302
Ожидаемый результат ОК

InstaPayment
* 6391216963042300
Ожидаемый результат ОК
* 6395968794729945
Ожидаемый результат ОК

American Express (AMEX)
* 341199942105022
Ожидаемый результат ОК

Maestro
* 5020541395999327
Ожидаемый результат ОК


Тестирование производилось в следующем окружении:
* Windows 10, x64
* IntelliJ IDEA 2020.1.1
