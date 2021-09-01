# Отчёт о тестировании Money Transfer

## Краткое описание

01.09.2021 - 01.09.2021 было проведено функциональное тестирование приложения Money Transfer.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
* [ссылка на гит](https://github.com/Nef1lim23/-1.2/issues/2)

## Описание процесса тестирования

В качестве тестовых данных использовались [данные из задания](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)

В целях продвижения компании было решено внедрить дополнительный бонус новым клиентам.

Код программы:

    public class zadanie1_2 {

        public static void zadanie1_2 (String[] args) {
            double regularBonus = 0.3;
            double specialBonus = 0.6;
            double totalBonus = regularBonus + specialBonus;
            System.out.println(totalBonus);
        }
    }






Тестирование производилось в следующем окружении:
* Win 10, x64
* версия Java 11.0.12
* IntelliJ IDEA Community Edition 2020.3.2 x64
