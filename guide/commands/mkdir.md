---
title: Створення каталогів
description: mkdir • cтворення каталогів
---

# Створення каталогів

Команда **[mkdir](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/mkdir 'Microsoft Dosc')** створює каталог або підкаталог. Розширення команд, які за замовчуванням увімкнені, дозволяють використовувати одну команду `mkdir` для створення проміжних каталогів у вказаному шляху.

::: info Примітка

Ця команда така ж, як і команда **[md](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/md 'Microsoft Dosc')**.

:::

## Синтаксис

```cmd
mkdir [<диск>:]<шлях>
```

## Параметри

- `<диск>` вказує диск, на якому ви хочете створити новий каталог.
- `<шлях>` вказує назву та розташування нового каталогу. Максимальна довжина будь-якого шляху обмежена файловою системою. Це обов'язковий параметр.
- `/?` відображає довідку стосовно команди.

## Приклади

1. Створити новий каталог

```cmd
mkdir NewFolder
```