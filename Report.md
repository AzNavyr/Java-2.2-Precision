# Отчёт о тестировании Precision

## Тестирование части JAVA кода 

12.09.2021 12:07 - 12.09.2021 12:40 было проведено в приложении IntelliJ IDEA.

На тестирование затрачено: 33 минуты

В результате тестирования выявлены следующие дефекты:
* [Некорректное отображение значения переменной double total в java коде](https://github.com/AzNavyr/Java-2.2-Precision/issues/1#issue-994715359)


В качестве тестовых данных использовались следующие данные:

* Часть JAVA кода :
```
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
* PC, Windows 7 64-bit
* Java v.11
* IntelliJ IDEA v2021.2.1