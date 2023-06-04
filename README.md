# java-what-year
## Приложения для определения високосности года.

Приложение умеет определять високосность года для праздника "День программиста", а также выводить получившийся результат пользователю в консоль.

----
Приложение написано на Java. Пример кода:
```java
public static boolean isLeapYear(int year) {
            if (year % 400 == 0) {
                return true;
            } else if (year % 100 == 0) {
                return false;
            } else if (year % 4 == 0) {
                return true;
            } else {
                return false;
            }
        }
```
----
Приложение создано в рамках прохождения курса Java-разработчик от [Яндекс Практикум](https://practicum.yandex.ru/java-developer/ "Тут учат Java!") 
