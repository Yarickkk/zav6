# Завдання 6
## Кравченко Ярослав
### Загальне завдання
Продемонструвати можливість паралельної обробки елементів колекції
(пошук мінімуму, максимуму, обчислення середнього значення, відбір за
критерієм, статистична обробка тощо).
Управління чергою завдань (команд) реалізувати за допомогою
шаблону Worker Thread.
Забезпечити діалоговий інтерфейс з користувачем.
Розробити клас для тестування функціональності програми.
Використовувати коментарі для автоматичного створення документації
засобами javadoc.

#### Скріншоти завдання

AppMain - Головний клас, діалоговий інтерфейс

![Код](https://github.com/Yarickkk/zav6/blob/main/AppM1.png)
![Код](https://github.com/Yarickkk/zav6/blob/main/AppM2.png)
![Код](https://github.com/Yarickkk/zav6/blob/main/AppM3.png)
![Код](https://github.com/Yarickkk/zav6/blob/main/AppM4.png)
![Код](https://github.com/Yarickkk/zav6/blob/main/AppM5.png)

WorkerThreadPool - Менеджер який керує чергою та потоками

![Код](https://github.com/Yarickkk/zav6/blob/main/WThread1.png)
![Код](https://github.com/Yarickkk/zav6/blob/main/WThread2.png)
![Код](https://github.com/Yarickkk/zav6/blob/main/WThread3.png)

StatTasks - Завдання, які будуть виконуватися паралельно.

![Код](https://github.com/Yarickkk/zav6/blob/main/Stat1.png)
![Код](https://github.com/Yarickkk/zav6/blob/main/Stat2.png)
![Код](https://github.com/Yarickkk/zav6/blob/main/Stat3.png)
![Код](https://github.com/Yarickkk/zav6/blob/main/Stat4.png)

ParallelTest - Тестувення

![Код](https://github.com/Yarickkk/zav6/blob/main/Test.png)

Приклад роботи програми

![Приклад](https://github.com/Yarickkk/zav6/blob/main/TestP.png)

Приклад роботи класу тестування

![Приклад](https://github.com/Yarickkk/zav6/blob/main/ParallelTest.png)
