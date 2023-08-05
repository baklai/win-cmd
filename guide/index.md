---
title: Вступ
description: 'Інтерпретатор командної строки для операційних систем OS/2, Windows CE'
prev: false
next: false
---

<script setup>
import { useData } from 'vitepress'

const  {isDark}  = useData();
</script>

<img src="/img/preview-dark.png" width="1280" height="640" alt="Preview image" v-if="isDark"/>
<img src="/img/preview-light.png" width="1280" height="640" alt="Preview image" v-else/>

<div style="text-align: justify"> 
<b>CMD (англ. command line interpreter)</b> - це інтерпретатор командної строки для операційних систем OS/2, Windows CE і для сімейства операційних систем, що базуються на Windows NT. cmd.exe є аналогом COMMAND.COM, який використовується в сімействах MS-DOS і Windows 9x. 
</div>

::: info ℹ️ Документація
Посилання на повну документацію від [Microsoft Docs for cmd](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/cmd 'Microsoft Dosc').
:::

## Параметри

- `/c` виконує команду, задану рядком, а потім зупиняється.
- `/k` виконує команду, вказану рядком, і продовжує роботу.
- `/s` змінює обробку рядка після `/c` або `/k.`
- `/q` вимикає ехо.
- `/d` вимикає виконання команд AutoRun.
- `/a` форматує вихідні дані внутрішніх команд у канал або файл у форматі Американського інституту національних стандартів (ANSI).
- `/u` форматує внутрішні вихідні дані команди в каналі або файлі у форматі Юнікод.
- `/t:bf` встановлює кольори фону (`b`) та переднього плану (`f`).
- `/e:on` увімкнює розширення команд.
- `/e:off` вимикає розширення команд.
- `/f:on` увімкнює завершення імені файлу та каталогу.
- `/f:off` вимикає завершення імені файлу та каталогу.
- `/v:on` увімкнює відкладене розширення змінної середовища.
- `/v:off` вимикає відкладене розширення змінної середовища.
- `string` вказує команду, яку потрібно виконати.
- `/?` відображення довідки в командному рядку.