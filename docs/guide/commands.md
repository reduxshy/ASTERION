---
title: Команды
---

<div class="asterion-hero" markdown>

<p class="asterion-eyebrow">СПРАВОЧНИК · КОМАНДЫ</p>

# Команды игрока

Все команды, которые нужны в обычной игре на ASTERION. Для них не требуются права оператора.

<div class="asterion-hero-actions">
  <a class="asterion-button asterion-button-primary" href="../">Справочник <span>→</span></a>
  <a class="asterion-button asterion-button-secondary" href="../crafts/">Новые крафты <span>→</span></a>
</div>

</div>

!!! note "О доступности команд"

    Список составлен по документации плагинов, установленных на сервере. Права на команды настраивает администрация, поэтому, если какая-то команда пишет «нет прав», обратитесь в [Discord](https://discord.gg/FGb8aVEJQ).

    Обозначения: `<так>` обязательный параметр, `[так]` необязательный.

## Вход на сервер

<div class="asterion-info-panel" markdown>

<div class="asterion-info-heading" markdown>

:material-lock: **Регистрация и вход**

<span>Плагин AuthMe. При первом входе нужно зарегистрироваться, при следующих войти с паролем</span>

</div>

| Команда | Что делает |
|:--|:--|
| `/register <пароль> <пароль>` | Регистрация: пароль вводится дважды |
| `/login <пароль>` | Вход в аккаунт |
| `/changepassword <старый> <новый>` | Смена пароля |
| `/logout` | Выход из аккаунта без отключения от сервера |
| `/unregister <пароль>` | Удаление регистрации |

</div>

## Позы и движение

<div class="asterion-info-panel" markdown>

<div class="asterion-info-heading" markdown>

:material-seat: **Сидеть, лежать, ползать**

<span>Плагин GSit</span>

</div>

| Команда | Что делает |
|:--|:--|
| `/sit` | Сесть на блок под собой |
| `/lay` | Лечь |
| `/bellyflop` | Лечь лицом вниз |
| `/spin` | Вращаться на месте |
| `/crawl` | Ползти по земле (проходит в пространство высотой в 1 блок) |
| `/sit toggle` | Включить или выключить посадку по ПКМ на блоки |
| `/sit playertoggle` | Включить или выключить посадку на игроков по ПКМ |

</div>

## Статус AFK

<div class="asterion-info-panel" markdown>

<div class="asterion-info-heading" markdown>

:material-sleep: **Отошёл от игры**

<span>Плагин AFKControl</span>

</div>

| Команда | Что делает |
|:--|:--|
| `/afk` | Включить или выключить статус AFK вручную |

</div>

## Голосовой чат

<div class="asterion-info-panel" markdown>

<div class="asterion-info-heading" markdown>

:material-microphone: **Простой голосовой чат**

<span>Нужен мод Simple Voice Chat на клиенте</span>

</div>

| Действие | Что делает |
|:--|:--|
| Клавиша `V` | Открывает меню голосового чата: настройки, группы, отключение микрофона |
| `/voicechat invite <игрок>` | Приглашает игрока в вашу голосовую группу |

</div>

## Напитки

<div class="asterion-info-panel" markdown>

<div class="asterion-info-heading" markdown>

:material-glass-mug-variant: **Варка напитков**

<span>Плагин BreweryX</span>

</div>

| Команда | Что делает |
|:--|:--|
| `/brew help` | Справка по плагину |
| `/brew info` | Показывает ваше состояние опьянения |

</div>

## Имена игроков

<div class="asterion-info-panel" markdown>

<div class="asterion-info-heading" markdown>

:material-account-eye: **Скрытые ники**

<span>Плагин ClickToSeeNames</span>

</div>

Ники над головами игроков скрыты. Чтобы узнать имя, подойдите к игроку и нажмите на него **правой кнопкой мыши**: имя появится над панелью предметов.

| Команда | Что делает |
|:--|:--|
| `/ctsn gui` | Открывает меню настроек отображения имени |

</div>

## Информация о сервере

<div class="asterion-info-panel" markdown>

<div class="asterion-info-heading" markdown>

:material-speedometer: **TPS, пинг и отображение в табе**

<span>Плагин TabTPS</span>

</div>

| Команда | Что делает |
|:--|:--|
| `/tps` | Показывает TPS сервера |
| `/mspt` | Показывает время обработки тика |
| `/ping` | Показывает ваш пинг |
| `/tabtps toggle tab` | Включить или выключить информацию в списке игроков |
| `/tabtps toggle actionbar` | Включить или выключить информацию над панелью предметов |
| `/tabtps toggle bossbar` | Включить или выключить информацию в верхней полосе |

</div>

## Общие команды

<div class="asterion-info-panel" markdown>

<div class="asterion-info-heading" markdown>

:material-console: **Стандартные команды игры**

<span>Работают без дополнительных плагинов</span>

</div>

| Команда | Что делает |
|:--|:--|
| `/help` | Список доступных команд |
| `/list` | Список игроков онлайн |
| `/msg <игрок> <текст>` | Личное сообщение (также `/tell` и `/w`) |
| `/me <действие>` | Сообщение о действии от третьего лица |

</div>

<div class="asterion-bottom-note" markdown>

*Нашли неточность или хотите добавить команду? Напишите в [Discord](https://discord.gg/FGb8aVEJQ).*

</div>
