Основное решение для стилизации конкретного участка страницы — использование классов. Они помогают задать нужный нам стиль не разом для всех элементов на странице, а только для тех элементов, у которых указан необходимый класс.

Чтобы задать стиль для класса в CSS используется селектор `.название-класса`. Обратите внимание на точку — именно так браузер понимает, что данный стиль указывается для класса.

```html
<p class="paragraph">
  Текст нашего параграфа.
  Именно с помощью класса paragraph в CSS
  будут устанавливаться свойства для этого блока текста
</p>
```

```css
.paragraph {
  color: #333333;
  /*
    Правило color устанавливает цвет текста.
    В данном случае — это серый цвет со значением #333333
  */
}
```

Так как классов с одинаковым именем на странице может быть много, то это правило сработает для всех элементов, у которых атрибут класс равен `paragraph`.