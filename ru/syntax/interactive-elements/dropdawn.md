# Дропдаун

Используйте дропдаун, чтобы получить удобный выпадающий список, если элементов со скрытым контентом слишком много.

```markdown
{% list tabs dropdown %}

- Название пункта 1

  Контент для пункта 1.

- Название пункта 2

  Контент для пункта 2.

{% endlist %}
```

**Результат:**

{% list tabs dropdown %}

- Название пункта 1

  Контент для пункта 1.

- Название пункта 2

  Контент для пункта 2.

{% endlist %}

## Элемент по умолчанию

Если нужно, чтобы элемент был раскрыт по умолчанию, добавьте к нему атрибут `{selected}`.

```markdown
{% list tabs dropdown %}

- Название пункта 1

  Контент для пункта 1.

- Название пункта 2 {selected}

  Пункт будет открыт по умолчанию.

- Название пункта 3

  Контент для пункта 3.

{% endlist %}
```

**Результат:**

{% list tabs dropdown %}

- Название пункта 1

  Контент для пункта 1.

- Название пункта 2 {selected}

  Пункт будет открыт по умолчанию.

- Название пункта 3

  Контент для пункта 3.

{% endlist %}