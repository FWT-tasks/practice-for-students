Привет!
Это тестовое задание для получения практики в нашей компании.

Твоя задача реализовать 2 функции на JavaScript(используй TypeScript, если умеешь)
+
небольшое задание на вёрстку.
___

### Задачи

#### Функция sum

Реализуйте функцию sum, которая принимает **произвольное** количество аргументов и возвращает их сумму.

Ошибки, которые должны быть обработаны:

Не переданы хотя бы два аргумента. Код ошибки INVALID_ARGUMENTS_COUNT.
Хотя бы один из аргументов не типа number. Код ошибки INVALID_ARGUMENT.

Примеры использования:
sum(1, 2, 3);        // 6
sum();               // ошибка с кодом INVALID_ARGUMENTS_COUNT
sum(0, 1, '1', 2); // ошибка с кодом INVALID_ARGUMENT

---
#### Функция intersection
Реализуйте функцию intersection, которая принимает два массива чисел и возвращает массив чисел, присутствующих в первом и во втором массивах.

Ошибки, которые должны быть обработаны:

Не переданы два аргумента. Код ошибки INVALID_ARGUMENTS_COUNT.
Хотя бы один из аргументов функции не массив. Код ошибки INVALID_ARGUMENT.
Хотя бы один из элементов массива не типа number. Код ошибки INVALID_ELEMENT_IN_ARRAY.

Примеры использования:
intersection([1], [2]);            // []
intersection([1, 2], [3, 2, 1]);   // [1, 2]

intersection([1, 1], [1, 1]);      // [1]

intersection([1, 2, 1], [1]);      // [1]

intersection([], []);              // []

intersection()                     // ошибка с кодом INVALID_ARGUMENTS_COUNT

intersection([], '[]')             // ошибка с кодом INVALID_ARGUMENT

intersection([], [1, '2'])         // ошибка с кодом INVALID_ELEMENT_IN_ARRAY


___
### Вёрстка:

Сделать вёрстку по макету представленному в ссылке ниже =>
[Figma](https://www.figma.com/file/Mvl8oAQm96G2DAg7VGnkVd/template?type=design&node-id=0-1&mode=design&t=SAgSQ1Xce3FaRnMg-0)

Задание:
Сверстать 1 экран(страницу), согласно макету.

Требования:
1) Вся вёрстка вмещается в 1 экран(нет скролла), меню пребито к нижней границе экрана. Блок с картинкой использует всё оставшееся пространство. Ширина экрана от 1440px - о мобилке не думаем.
2) Hero заголовок - находится строго по центру блока с картинкой.
3) Меню - это ссылки, при наведении меняют цвет - показано на кнопке - "About", ссылки ведут по "/".
4) При клике на картинку, и сверху, и снизу происходит редирект на "/".
5) Шрифт - Roboto mono для текста, подключен в html
6) Стили пишем в соседнем файле, и подключаем в html

Примечание:
Логотип компании - есть во вкладке Symbols.
Картинку для фона экспортируем из самого макета.


___
### Итог

Готовое решение должно состоять из 2 папок:
1) functions - js/ts файлы с функциями
2) html - html и css файлы

Его необходимо поместить в архив .zip - именем которого является твоё имя и группа.

Своё решение нужно отправить ***до 20:00 07/02/2024***

