importance: 5

---

# Область видимости для документа

Напишите функцию `getDocumentScroll()`, которая возвращает объект с информацией о текущей прокрутке и области видимости.

Свойства объекта-результата:

- `top` -- координата верхней границы видимой части (относительно документа).
- `bottom` -- координата нижней границы видимой части (относительно документа).
- `height` -- полная высота документа, включая прокрутку.

В этой задаче учитываем только вертикальную прокрутку: горизонтальная делается аналогично, а нужна сильно реже.