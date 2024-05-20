### Пояснение к коду:

1.HTML:
    Создаем поле для ввода (`input`) с ID `priceInput` и контейнер для сообщений об ошибках и результатов.
    Добавляем стили для рамки поля ввода и сообщения об ошибках.

2.JavaScript:
    При загрузке страницы добавляем обработчики событий для поля ввода.
    При фокусе (`focus`) добавляем зеленую рамку.
    При потере фокуса (`blur`) проверяем значение:
        Если значение не является числом или меньше нуля, добавляем красную рамку и выводим сообщение об ошибке.
        В противном случае создаем `span` с текущей ценой и кнопкой `X`.
    При нажатии на кнопку `X` удаляем результат и очищаем поле ввода.
    Обработчик событий — это функция, которая выполняется в ответ на определенное событие, например, щелчок мышью, нажатие клавиши или изменение значения в поле ввода.