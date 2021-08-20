# hw-classes

### Темы для повторения
[Класс: базовый синтаксис](https://learn.javascript.ru/class)

[Наследование классов](https://learn.javascript.ru/class-inheritance)

### Задание 

1. Скопировать класс `User` из кода, который писали на уроке
2. Создать класс `Worker`. 
3. Наследовать его от класса `User`. 
4. Добавить в `Worker` свойствa (значение приходит из аргументов ): `speciality` (string), `openToWork` (boolean).
5. Также добавить методы `changeHiringStatus(isOpened)`, который меняет свойство `openToWork`. 
6. Создать новый instance класса `Worker`

**Дополнительно**

Создать класс `Hirer`. У класса должен быть метод, который прнимает параметром instance от Worker и добавляет его в массив, если worker открыт к предложениям (`openToWork === true`).

Создать новый instance и протестить код
