# Отчёт о тестировании функциональности валидации номера банковской карты

## Краткое описание

28.06.2020 было проведено функциональное тестирование валидации номера банковской карты.

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:
* https://github.com/mgilmanova/-2---Credit-Card-Number-Validator/issues/2
* https://github.com/mgilmanova/-2---Credit-Card-Number-Validator/issues/3
* https://github.com/mgilmanova/-2---Credit-Card-Number-Validator/issues/4

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Баг-репорт в системе GitHub.

В качестве тестовых данных использовался код из предыдущих наработок программиста, реализовывающего данную функциональность, а также сгенерированные с помощью сервиса freeformatter.com валидные номера карт VISA, MasterCard, American Express (AMEX), Discover, JCB, Diners Club - North America, Diners Club - Carte Blanche, Diners Club - International, Maestro, Visa Electron, InstaPayment.

Тестирование производилось в следующем окружении:
* Windows 10, 64-разрядная ОС
* JDK11