<p align="center">
  <img src="https://raw.githubusercontent.com/SMART-DATING/.github/main/profile/assets/nexus-hero.svg" alt="Nexus — знакомства на одной волне" width="100%">
</p>

<p align="center">
  <strong>Люди, с которыми есть о чём поговорить.</strong><br>
  Знакомства через общие интересы, личные истории и взаимную симпатию.
</p>

<p align="center">
  <a href="https://github.com/SMART-DATING/nexus-docs">Документация</a> ·
  <a href="https://github.com/SMART-DATING/nexus-docs/blob/main/RUNBOOK.md">Запуск</a> ·
  <a href="https://github.com/SMART-DATING/nexus-docs/blob/main/diagrams/README.md">Архитектура и схемы</a>
</p>

## От интереса к разговору

Выбрать «музыка» — только начало. За этим могут стоять любимая группа, первый концерт или песни, которые помогают пережить сложный день. Nexus предлагает рассказать немного больше и искать людей по смыслу этих историй.

| Расскажи о себе | Найди общее | Начни разговор |
| --- | --- | --- |
| Выбери темы и ответь на вопросы Некса либо напиши свободный текст. Проверь рассказ перед сохранением | Смотри анкеты сначала из своего города, затем из других; внутри групп — по близости рассказов | Выражай симпатию. Если она взаимна, открывается чат |

Подробные истории остаются доступны только автору. Их обрабатывает локальная модель на сервере; другим участникам видны публичная анкета и разрешённые фотографии. Число своих фото определяет число открытых чужих — до шести у каждого.

## Устройство проекта

| Репозиторий | Что внутри | Начать |
| --- | --- | --- |
| [nexus-frontend](https://github.com/SMART-DATING/nexus-frontend) | React / TypeScript, интерфейс знакомства, фотографии, анкеты и чаты | [README](https://github.com/SMART-DATING/nexus-frontend#readme) |
| [nexus-backend](https://github.com/SMART-DATING/nexus-backend) | Java / Spring Boot, REST API, PostgreSQL / H2, локальная RuBERT-tiny2 | [README](https://github.com/SMART-DATING/nexus-backend#readme) |
| [nexus-docs](https://github.com/SMART-DATING/nexus-docs) | Цели продукта, требования, сценарии, архитектура, API и инструкции | [Навигация](https://github.com/SMART-DATING/nexus-docs#readme) |

## Посмотреть приложение

Самый короткий путь из исходников — расположить три репозитория рядом и запустить общий Docker Compose из nexus-docs. Сайт откроется на `http://127.0.0.1:8088/`. Также доступны раздельная разработка и единый JAR. [Пошаговый запуск](https://github.com/SMART-DATING/nexus-docs/blob/main/RUNBOOK.md).

Nexus — работающий веб-прототип для совершеннолетних участников. Некс задаёт подготовленные вопросы; процент сходства описывает тексты, а не обещает успешные отношения. Постоянное публичное размещение и продуктовые исследования остаются отдельными задачами.

[Текущее состояние](https://github.com/SMART-DATING/nexus-docs/blob/main/STATUS.md) · [Бизнес-требования](https://github.com/SMART-DATING/nexus-docs/blob/main/requirements/business-requirements.md) · [Данные и приватность](https://github.com/SMART-DATING/nexus-docs/blob/main/privacy/data-handling.md) · [Команда](https://github.com/SMART-DATING/nexus-docs/blob/main/team/roles.md)
