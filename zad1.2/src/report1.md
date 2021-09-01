# Отчёт о тестировании Money Transfer

## Краткое описание

01.09.2021 - 01.09.2021 было проведено функциональное тестирование приложения Money Transfer.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
* [ссылка на гит](https://github.com/Nef1lim23/-1.2.git)

## Описание процесса тестирования

В качестве тестовых данных использовались [данные из задания](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)

**Текущий баланс счёта клиента - переменная типа int, значение - 2_000_000_000 (два миллиарда рублей)**
**Сумма перевода - переменная типа int, значение - 500_000_000 (пятьсот миллионов рублей)**

Код программы:

    public class Main {
    public static void main(String[] args) {
    int balance = 2_000_000_000;
    int transfer = 500_000_000;
    int total = balance + transfer;
    System.out.println(total);
    }
    }




Тестирование производилось в следующем окружении:
* Win 10, x64
* версия Java 11.0.12
* IntelliJ IDEA Community Edition 2020.3.2 x64
