---
title: "`<em>`"
description: "Придаёт особый смысл отдельным словам или фразам в тексте."
authors:
  - xpleesid
keywords:
  - ударение
  - семантический акцент
related:
  - html/strong
  - html/i
  - a11y/screenreaders
tags:
  - doka
---

## Кратко

Тег `<em>` добавляет тексту внутри смысловой акцент.

## Пример

Текст внутри `<em>` по умолчанию выделяется курсивом при помощи `font-style: italic`.

```html
<p>Коты <em>обожают</em> кошачью мяту</p>
```

<iframe title="Базовый пример" src="demos/basic/" height="100"></iframe>

## Как пишется

Используйте `<em>` для смыслового выделения куска текста и не используйте его для просто курсива — для этого нужен тег [`<i>`](/html/i/). При этом `<em>` также не задуман для придания важности тексту — для этого подойдёт [`<strong>`](/html/strong/).

Можно вкладывать `<em>` друг в друга — семантическое ударение будет усиливаться с каждым уровнем вложенности (например, будет постепенно нарастать интонация у [скринридеров](/a11y/screenreaders/)).

```html
<p>
  <em>
    Этого не ожидал никто,
    <em>даже известный своим природным чутьём Джимми</em>
  </em>
</p>
```

<iframe title="Базовый пример" src="demos/nested/" height="150"></iframe>
