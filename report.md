# Отчёт о тестировании валидации номеров карт

## Краткое описание

24.11.2021 - 24.11.2021 было проведено функциональное тестирование приложения Money Transfer.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* https://github.com/Sormat59/Java-DZ-1/issues/1#issue-1062668882


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Тест план из [задания № 1](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-1---money-transfer)


В качестве тестовых данных использовались данные [задания № 1](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-1---money-transfer):
* При сложении переменных [кода](https://github.com/Sormat59/Java-DZ-1/blob/4519e8df82bf4f5e557d6c4cfb21294db444bfdf/src/Main.java#L1-L9) :balance 2 000 000 000 + transfer 500 000 000, ожидаемый результат суммы значений равен 2 500 000 000


Тестирование производилось в следующем окружении:
* Windows 10 Pro x64
* версия Java "11.0.12"
* IDEA Community 2021.2.3.