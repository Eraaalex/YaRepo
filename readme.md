# Сайт-визитка
Для реализации проекта я использовала HTML, CSS и JavaScript.
## Header
В верхней части сайта присутсвует навигационная панель, для удобства перехождения к информационной части. Она выполнена в виде списка.
Для расположения большинства блоков использована технология **Flexbox**, так как она имеет достаточно удобные свойства расположения в контейнере.
## Body
Для не однообразного последовательного расположения посредством технологии **Grid**, я расположила информационное видео параллельно блоку описания.
Также были использованы id для некоторых блоков с целью удобной ссылки на них в навигационной панели.
Добавлена адаптация под маленькие экраны мобильных устройств с использованием **медиавыражений**. В некоторых параграфах использованы неразрывные дефисы, для устранения возможного неправильного автоматического деления текста.
### JS
Я не стала создавать отдельный js файл, включив script в html-документ, так как строчек кода достаточно немного. JavaScript был использован для обработки события нажатия на кнопку для появления навигационной панели. А также для печатания одного из сообщений документа только при попадании в зону видимости окна для большей интерактивности сайта (с помощью setTimeout для медленного набора символов).
### CSS
Оформление ссылки на репозиторий было выполнено посредством кнопки, которая меняет форму при наведении с помощью **transform** и **animation**, чтобы избавиться от статичности и однообразности сайта.
## Footer
В данном проекте сайта-визитки нет информации, подходящей под расположение в данном блоке, потому там только указание автора, отделенное элементом ```<hr>``` от остальных частей сайта.
