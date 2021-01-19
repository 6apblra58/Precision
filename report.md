# Отчёт о тестировании приложения "Precision"
## Краткое описание
Начало тестирования 19.01.2021 - 19.01.2021

На тестирование затрачено: 5 минут

Проводилось функциональное тестирование методом черного ящика

В результате тестирования выявлены следующие дефекты:

[Неверный подсчет бонусов в приложении Precisions](https://github.com/6apblra58/Precision/issues/1#issue-789026025)


## Описание процесса тестирования
В качестве тестовых данных использовался код Java-приложения:

public class Main {

    public static void main(String[] args) {
    
        double regularBonus = 0.3;
        
        double specialBonus = 0.6;
        
        double totalBonus = regularBonus + specialBonus;
        
        System.out.println(totalBonus);
        
    }
    
}


## Тестирование проводилось в следующем окружении

Windows 10 Home Edition x64

java version "11.0.9.1" 2020-11-04

Google Chrome Версия 87.0.4280.141 (Официальная сборка), (64 бит)

IntelliJ IDEA 2020.2.3 (Community Edition)
