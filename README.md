# Домашнее задание к занятию «2.2. Testability, автотесты, введение в ООП: объекты и методы»

## Задача №1 - Мили (модернизация)

### Легенда

Поскольку вы уже научились создавать классы и методы, вам необходимо модернизировать приложение для рассчёта миль.

Что для этого нужно:
1. Создайте класс `BonusMilesService`
1. Определите в нём метод `calculate`, который:
    1. Принимает на вход один параметр: `cost` типа `int`
    1. Возвращает рассчитанное количество миль (тип - `int`)
    
Разместите следующий код в классе `Main`:

```java
public class Main {
    public static void main(String[] args) {
        BonusMilesService service = new BonusMilesService();
        int price = 10_000;
        int miles = service.calculate(price);
        System.out.println(miles);
    }
}
```