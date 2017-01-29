# Всегда используйте шаблоны проектирования. #

> У меня просто аллергия на башни из слоновой кости и на шаблоны проектирования. Когда Питер Норвиг был в Harlequin Inc, он написал статью о том, что шаблоны проектирования на самом деле лишь прикрывают дефекты в вашем языке программирования, вам надо выбрать язык программирования получше. И он абсолютно прав. Поклоняясь паттернам, можно думать только категориями: «Так, сейчас я буду использовать шаблон X»
>
> -- Брендан Айк в ["Кодеры за работой - Размышления о ремесле программирования"](http://codersatwork.com/)

В программной инженерии шаблон проектирования представляет собой многоразовое решение для проблем, с которыми обычно сталкиваются при разработке программного обеспечения. Шаблон проектирования - не окончательная конструкция, её можно преобразовать непосредственно в программный код. Это описание решения проблемы, которое может быть использовано в различных ситуациях. В объектно-ориентированных языках шаблоны проектирования, как правило, показывают отношения и взаимодействия между классами или объектами без указания классов и объектов конечного приложения.
PHP поддерживает императивную, функциональную, объектно-ориентированную, процедурную и рефлексивную парадигмы. PHP это набор из огромного количества различных инструментов, которые дают возможность решить многие проблемы многими различными путями – не только одним способом.
Суть PHP это свобода, быстрые и масштабируемые решения, наличие множества различных способов справиться с проблемами.
Когда мы пытаемся совершенствоваться, а в данном случае речь идет об улучшении кода, мы иногда так зацикливаемся на философии конкретного паттерна или идеи, что перестаём думать практично.

> Когда я вижу в своей программе шаблоны, я расцениваю это как тревожный знак. Модель программы должна отражать только ту проблему, которую должна решить. Любая другая закономерность в коде, по крайней мере для меня, является признаком того, что я использую недостаточно мощные абстракции. Например, что я вручную генерирую расширения макросов, которые нужно написать.
>
> -- [Пол Грэм](http://c2.com/cgi/wiki?AreDesignPatternsMissingLanguageFeatures)

Мы не должны быть втянуты в философию или идею конкретного шаблона или решения. Наша главная задача – сохранить код максимально понятным и простым для навигации, насколько это вообще возможно. И в результате будет легко поддерживать этот код и легко обеспечивать его безопасность.
Мы также должны помнить, что существует такая вещь, как анти-паттерн. Это тоже шаблон, который обычно используется, но на практике оказывается неэффективным и/или контрпродуктивным.

> Я думаю, что шаблоны начинали как общепризнанные лучшие решения для общих проблем. Но теперь, после того, как какое-то время паттерны были в ходу, мы имеем приложения, которые в десятки раз сложнее, чем это необходимо. И это только потому, что люди пытаются впихнуть в них все шаблоны, о которых когда-либо читали («мое приложение хорошо спроектировано, потому что до краев напичкано разными паттернами»). Так что мое впечатление об их ценности немного изменилось.
>
> -- Пол Уитон в ["Зло шаблонов проектирования"](http://www.javaranch.com/patterns/)

Всегда используйте практический подход:

> Действие или стратегия должны быть продиктованы скорее соображениями достижения качества немедленных практических результатов, чем теориями или догмами.
>
> -- Collins English Dictionary, Complete and Unabridged, 12th Edition 2014

**Неправильный путь**: Искать шаблон, чтобы решить проблему. ![Thumbs down](/img/thumbs-down.png)