---
description: Початковий фаайл, з якого розпочинається підключення scss
---

# style.scss

Початковий фаайл, з якого розпочинається підключення scss має 4 частини.

В першій частині ми підключаємо початкові стилі. Решта частин це основні блоки.

{% tabs %}
{% tab title="IMPORT" %}
```scss
// @use "./styles/" as *;
@use "../styles/" as *; //@use "./asm-ui/styles/" as *;
```
{% endtab %}

{% tab title="HEADER" %}
```scss
.header {
    .container {
        padding-top: 36px;
        padding-bottom: 36px;
    }
}
```
{% endtab %}

{% tab title="MAIN" %}
```scss
.main {
    .container {
        padding-top: 36px;
        padding-bottom: 36px;
    }
}
```
{% endtab %}

{% tab title="FOOTER" %}
```scss
.footer {
    .container {
        padding-top: 36px;
        padding-bottom: 36px;
    }
}
```
{% endtab %}
{% endtabs %}
