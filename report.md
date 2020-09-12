
# Отчёт о тестировании Precision

## Краткое описание

12.09.2020 - 12.09.2020 было проведено модульное тестирование Precision.

На тестирование затрачено: 20 мин

В результате тестирования выявлены дефекты:
* [https://github.com/mymoskvina/java1.4/issues/1](https://github.com/mymoskvina/java1.4/issues/1)

## Описание процесса тестирования

В качестве тестовых данных использовались данные:

Исходный код:

```java
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```


Тестирование производилось в следующем окружении:
* MAC OS 10.15.6 2,6 GHz 2‑ядерный процессор Intel Core i5
* версия Java 11.0.8
* IntelliJ IDEA CE 2020.2.1