# Домашнее задание к занятию "Поиск и исправление ошибок приложения. Отладка - рефакторинг"

* Любые вопросы по решению задач задавайте в чате учебной группы (ссылку вы найдете в письме на вашей эл. почте).
* При сдаче домашнего задания укажите ссылку на код проекта.


## Задание 1
1. Найти в вашем приложении места, где есть возможность неблагоприятного исхода и требуется сообщить пользователю об этом. 
2. Создайте собственный домен ошибок (перечисление). 
3. Добавьте в него случаи, которые могут быть. 
4. Покажите пользователю Alert, уведомив его об ошибке.

## Задание 2
Примените тип `Result` для асинхронного вызова, обработайте результат через `switch`.

## Задание 3
Переделайте один из методов, который возвращает `nil` в неблагоприятном исходе, используя функцию, которая выбрасывает исключение в этом случае (`throws`).

## Задание 4*
Найдите место в вашей программе, где дальнейшее ее выполнение не имеет смысла, если определенное условие не выполнено, воспользуйтесь `preconditionFailure` и `guard`.
