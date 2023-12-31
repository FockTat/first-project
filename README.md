# Шпаргалка markdown

## Выделение текста

Вы можете выделять тескт в markdown с помощью '_' или '*'. Например: 

Пример _курсива_ и **жирного** текста.

## Заголовки 

Заголовок можно создать с помощью символа '##'. Чем больше '#', тем меньше заголовок. Например:

# Заголовок первого уровня

## Заголовок второго уровня 

### Заголовок третьего уровня

---

## Выделение кода

Чтобы выделить текст как код, поместите его в тройные кавычки ``.

```
mkdir my_project

cd my_project

git init

```
---

Можно добавить черту под заголовком или абзацем "---". Например:

### Title

Text above the line

'---'

Underline text

---

## Чтобы сделать разрыв строки, нужно поставить два пробела (в примере ниже они обозначены точками ⋅⋅) или сочетание символов "<br>".

Text 1  
Text 2 '<br>'
Text 3

## Чтобы начать новый параграф, в конце предыдущей строки должно стоять два символа переноса. Для этого нужно нажать **Enter** два раза.

Line

another line


### Если сделать один перенос строки, как в примере ниже, и не поставить два пробела, текст сольётся в одну строку.

Line
another line

---

**Чтобы выделить текст:**

Курсивом - ** или _ _ (*курсив*)

Полужирный - ** ** (**Текст**)

Зачеркнутый - ~~ ~~ (~~Текст~~)

---

## Для оформления нумерованного списка достаточно поставить в начало строки цифры с точкой.

1. Первый пункт нумеровоного списка

2. Второй пункт

### Ненумерованный список создаётся звёздочкой с пробелом в начале строки либо дефисом с пробелом.

* первый пункт ненумеровонного списка
* второй пункт ненумеровонного списка

- первый пункт ненумированного списка 
- второй пункт ненумерованного списка

---

## Чтобы сделать ссылкой часть текста, его заключают в квадратные скобки, а затем указывают нужный адрес в круглых скобках. Например:

[Яндекс](https://www.yandex.ru)

### Также можно добавить ссылке тайтл (от англ title — «название», «заголовок»). Тайтл — это всплывающая подсказка, которая появляется при наведении мыши на ссылку. Тайтл нужно заключить в кавычки и указать внутри скобок после адреса.

[Яндекс](https://www.yandex.ru "Я Yandex")


```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "???"     --> tracked/comitted;

%% стрелка без текста для примера: 
  A --> B;
``` 

