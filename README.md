# Домашнее задание к занятию «Введение в Java»

## Решение
  * <a href="https://github.com/Nephedov/2.Java/issues/1">Баг-репорт</a> - Неверный результат расчета при вычислении количества куриных бедер.

## Что было сделано
  * Установлена IntelliJ IDEA.
  * Создан проект на базе Java 11.
  * Создан класс <a href="https://github.com/Nephedov/2.Java/blob/main/src/Main.java">Main.java</a>.
  * Сделан коммит и пуш проекта на Github.
  * Заведен <a href="https://github.com/Nephedov/2.Java/issues/1">баг-репорт</a>. 

## Задание. Рецепт 

Ваша задача — проанализировать программу расчёта распределения ингредиентов на порцию. Программе на вход даётся рецепт со всеми граммовками каждого ингредиента, а также количество человек, которые будут в одинаковых порциях его есть. На выходе программа указывает без округлений, какое точное количество каждого ингредиента пришлось на одну порцию еды.

```java
public class Main {
    public static void main(String[] args) {

        int eaters = 5; // сколько людей будут есть

        int water = 3000; // миллилитров воды
        int potatoes = 5; // картофелин
        int chicken = 6; // куриных бёдер
        int spices = 10; // ложек специй

        System.out.println("Сварили суп. На одного человека вышло:");
        System.out.println((water / eaters) + " миллилитров воды");
        System.out.println((potatoes / eaters) + " картофелин(а)");
        System.out.println((chicken / eaters) + " куриных(ое) бёдер(ро)");
        System.out.println((spices / eaters) + " ложек(ка) специй");

    }
}
```

Для анализа этой программы

1. Установите бесплатную версию идеи (**Community version**) с [официальной страницы](https://www.jetbrains.com/idea/download).
2. Создайте новый проект на основе **Java 11**, идея может скачать её сама, если вы в меню выбора Java выберите `Download JDK`. Обратите внимание, что в левой части меню следует выбирать `New Project`, а не что-либо другое.
3. Создайте класс `Main` с содержимым из кода выше.
4. Нажмите на кнопку запуска программы. Она должна запуститься, вывести информацию на экран и завершиться.
5. Закоммитьте и запушьте ваш проект в публичный репозиторий на GitHub.
6. Проанализируйте код и вывод программы. Найдите в них дефекты. Менять код программы не нужно.
7. Оформите баг-репорт с помощью GitHub Issues, описывающий найденный дефект.
