# Ежедневник

### Приложение для отслеживания задач

Данное приложение поможет Вам не забыть выполнить необходимые задачи.

Имеет следующий функционал:

* Создать задачу для выполнения
* Изменить поставленную задачу
* Удалить задачу
* Изменять статус поставленных задач
* Показать все поставленные задачи
* Задачи выделяются цветом в зависимости от их состояния

### Эндпоинты приложения

* Get("/") - домашняя страница приложения;
* Get("/tasks/add") - добавление новой задачи;
* Post("/tasks/add") - сохранение новой задачи;
* Get("/tasks/complete/{id}") - задача выполнена;
* Get("/tasks/delete/{id}") - удаление задачи;
* Get("/tasks/update/{id}") - обновление задачи;
* Post("/tasks/update") - сохранение обновленной задачи;
* Get("/tasks/{id}") - получение конкретной задачи;

Разработал Малютин Е.В.
