# WordPress Blog Telegram Bot

Автоматизированная система уведомлений для блога на WordPress с интеграцией Telegram-бота для управления подписками.

## 📸 Скриншоты

![start](start_subscribe.jpg)

Демонстрирует начальный этап работы с ботом:
- Первый запуск бота командой `/start`
- Проверка статуса подписки до оформления подписки
- Интерфейс команды `/status` для неподписанного пользователя
- Процесс подписки через команду `/subscribe`

![subscribe](status_message.jpg)

Показывает полный цикл взаимодействия подписанного пользователя:
- Успешное оформление подписки
- Получение уведомления о новой публикации в блоге
- Формат сообщения с названием статьи, кратким содержанием и ссылкой
- Проверка статуса для подписанного пользователя

![workflow](Workflow.jpg)

Архитектура рабочего процесса системы

![workflow-messages](Workflow_messages.jpg)

Добавление в workflow автопубликаций для рассылки сообщений.

--- 

Все скриншоты находятся в папке `/img` в корне проекта.
