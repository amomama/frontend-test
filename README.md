# Макет

https://www.figma.com/file/ghOdAgy7jEzv7wqU2VVhwK/Test_task_frontend?node-id=0%3A1

# Задание
1. Не использовать классы - только функциональные компоненты
2. Сделать валидацию email - красная рамка, если неправльно введен email (сразу при вводе)
3. Получить данные от сервера (используйте этот ресурс для генерации json и их сервер, куда вы можете сохранить свой json - https://www.json-generator.com/ ):
    - отобразить загрузку, если ошибка - ошибку (не нужно создавать отдельные компоненты, просто выведите строкой)
    - структура данных: 
    {
        columns: [''],
        rows: [''],
        cell: [{id: 0, text: ''}]
    }
4. Нужно отрендорить таблицу (можете использовать div и css grid) так, чтобы ее отображение зависело только от тех данных, которые получает компонент, то есть
    колличество колонок будет напрямую зависеть от того, сколько элементов находится в массиве columns, а количество строк от того, сколько элементов находится
    в массиве rows и количества объектов в массиве cell. Таким образом, количество колонок не будет больше или меньше, чем элементов в массиве columns и количество
    строк не будет больше, чем элементов в массиве rows, но может быть меньше, если объектов в массиве cell не достаточно для количества элементов в массиве rows
5. Именование классов должно быть по БЭМ методологии
6. Сделать нужно только desktop версию, без кликабельности ячеек и селекта недель

# Результат
Результат выполнения залить на bitbucket/github/gitlab
