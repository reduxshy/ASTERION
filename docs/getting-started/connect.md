---
title: Подключение
---

<div class="asterion-hero" markdown>

<p class="asterion-eyebrow">НАЧАЛО ИГРЫ</p>

# Как подключиться

Пошаговая инструкция: от добавления сервера до первого входа и решения частых проблем.

<div class="asterion-hero-actions">
  <a class="asterion-button asterion-button-primary" href="../../rules/">Правила сервера <span>→</span></a>
  <a class="asterion-button asterion-button-secondary" href="../../guide/commands/">Команды игрока <span>→</span></a>
</div>

<div class="asterion-server-status">
  <span class="asterion-status-dot"></span>
  <span>Адрес сервера</span>
  <span class="asterion-status-divider">/</span>
  <code>asterion.20tps.ru</code>
</div>

</div>

## Данные сервера

<div class="asterion-info-panel" markdown>

<div class="asterion-info-heading" markdown>

:material-server-network: **Параметры ASTERION**

<span>Всё, что нужно знать перед входом</span>

</div>

| Параметр | Значение |
|:--|:--|
| **Игра** | Minecraft: Java Edition |
| **Адрес** | `asterion.20tps.ru` |
| **Ядро** | Purpur |
| **Версия** | `26.2` |
| **Вход** | По паролю: регистрация при первом заходе |

</div>

## Быстрый старт

<div class="grid cards asterion-cards" markdown>

-   :material-numeric-1-circle:{ .asterion-icon }

    **Запустите Minecraft**

    ---

    Нужна Java Edition. Если игра не пускает из-за версии, уточните актуальную в [Discord](https://discord.gg/FGb8aVEJQ).

-   :material-numeric-2-circle:{ .asterion-icon }

    **Добавьте сервер**

    ---

    «Сетевая игра» → «Добавить сервер». В поле адреса введите `asterion.20tps.ru` без пробелов.

-   :material-numeric-3-circle:{ .asterion-icon }

    **Зарегистрируйтесь**

    ---

    После входа введите `/register <пароль> <пароль>`. Пароль вводится дважды.

-   :material-numeric-4-circle:{ .asterion-icon }

    **Проверьте свою сборку**

    ---

    Убедитесь, что среди ваших модов нет [запрещённых](../rules/forbidden-mods.md).

</div>

## Первый и последующие входы

<div class="asterion-info-panel" markdown>

<div class="asterion-info-heading" markdown>

:material-lock: **Регистрация и вход**

<span>Работает через плагин AuthMe</span>

</div>

| Когда | Команда |
|:--|:--|
| Первый вход | `/register <пароль> <пароль>` |
| Каждый следующий вход | `/login <пароль>` |
| Смена пароля | `/changepassword <старый> <новый>` |

</div>

!!! warning "О пароле"

    Придумайте пароль, который вы больше нигде не используете, и никому его не сообщайте. Администрация никогда не просит пароль. Если забыли его, напишите в [Discord](https://discord.gg/FGb8aVEJQ).

## Полезные моды для клиента

Эти моды необязательны, но делают игру удобнее.

<div class="grid cards asterion-cards" markdown>

-   :material-microphone:{ .asterion-icon }

    **Simple Voice Chat**

    ---

    Голосовой чат по расстоянию. Меню открывается клавишей `V`.

-   :material-map:{ .asterion-icon }

    **Xaero's Minimap и World Map**

    ---

    Единственные разрешённые мини-карта и карта мира. Подробности в [правилах по модам](../rules/forbidden-mods.md).

</div>

## Если не получается подключиться

<div class="asterion-info-panel" markdown>

<div class="asterion-info-heading" markdown>

:material-lifebuoy: **Частые проблемы**

<span>Проверьте по порядку</span>

</div>

| Проблема | Что сделать |
|:--|:--|
| Сервер не найден или превышено время ожидания | Проверьте адрес `asterion.20tps.ru`: без пробелов и лишних символов. Затем проверьте интернет и попробуйте ещё раз |
| Пишет о несовместимой версии | Запустите нужную версию Java Edition. Если не уверены в ней, спросите в [Discord](https://discord.gg/FGb8aVEJQ) |
| Вас кикает после входа | Вы не зарегистрировались или ввели неверный пароль: используйте `/register` или `/login` |
| Не работает голосовой чат | Установите мод Simple Voice Chat и проверьте настройки микрофона в меню `V` |
| Отключает или блокирует за моды | Сверьте сборку со списком [запрещённых модов](../rules/forbidden-mods.md) |

</div>

!!! tip "Ничего не помогло?"

    Сохраните текст ошибки или сделайте скриншот и напишите в [поддержку](../community/index.md). Так администрации будет проще разобраться.

<div class="asterion-bottom-note" markdown>

*Все команды игрока собраны в разделе [«Команды»](../guide/commands.md).*

</div>
