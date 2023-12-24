# Описание:

Протестировано приложение покупки туров и при оплате дебетовой и кредитной картами.

## Тест-кейсы:

Всего составлено 56 тест-кейсов. Процент успешных тестов: 92.85%

В проекте есть следующие тестовые классы:

* NegativeScenariosTest - негативные сценарии
* PositiveScenariosTest - позитивные сценарии

![Screenshot1.png](https://github.com/AnastasiaBorisovna/Diplom/tree/main/documents/screenshots/Screenshot1.png)
![Screenshot2.png](https://github.com/AnastasiaBorisovna/Diplom/tree/main/documents/screenshots/Screenshot2.png)


## Список упавших тестов:

![Screenshot3.png](https://github.com/AnastasiaBorisovna/Diplom/tree/main/documents/screenshots/Screenshot3.png)

### Итог:

|                       | Кол-во тестов | Пройдено | Упало | Процент, % |
|:----------------------|:-------------:|:--------:|:-----:|-----------:|
| PositiveScenariosTest |       2       |    0     |   2   |         0% |
| NegativeScenariosTest |      54       |    52    |   2   |      96.3% |
| Всего                 |      56       |    52    |   4   |     92.85% |

Были найдены баги и составлены баг-репорты [Баги](https://github.com/AnastasiaBorisovna/Diplom/issues)

## Комментарии

* Приложение работает, в целом, не так, как задумано. Есть баги, которые надо исправлять.
* Были проблемы с поиском локаторов, но данная проблема была решена успешно. 
Требуются исправления от разработчиков фронта.
* Один из багов был найден при проверке портала вручную (когда выходят два сообщения об успешности). Не удалось найти его автотестом, т.к. в нём не было проверки наличия обоих сообщений, а только одного, что, в принципе, логично.