# Работа с примечаниями AmoCrm через API

### Задание:

#### Работа производится в аккаунте AmoCrm, который был создан в [задании № 2](https://github.com/gt4u/tasks/tree/master/task_2), используя данные из отправленной формы [задания № 1](https://github.com/gt4u/tasks/tree/master/task_1) и авторизацию из [задания № 3](https://github.com/gt4u/tasks/tree/master/task_3), с использованием ID контакта полученного из [задания № 4](https://github.com/gt4u/tasks/tree/master/task_4) и ID сделки из [задания № 5](https://github.com/gt4u/tasks/tree/master/task_5).

Конечная цель задания - добавить новое примечание в сделку AmoCrm.

[Документация по работе с примечаниями в AmoCrm](https://www.amocrm.ru/developers/content/api/notes).

### План выполнения:

1. После успешно созданной задачи в сделке необходимо создать примечание с параметрами:
    - **Тип примечания** = *Обычное примечание*;
    - **Сущность** = *сделка;*
    - **ID сущности** = *ID созданной сделки;*
    - **Текст примечания** = *Полная информация о заявке с сайта*, [пример.](https://yadi.sk/i/LgJhGZX9jIa2lw)
