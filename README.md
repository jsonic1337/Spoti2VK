# Spoti2VK

Скрипт транслирующий музыку играющую у вас в Spotify в ваш статус ВКонтакте в формате проигрываемой аудиозаписи.

Скрипт написан на **builtin-only** библиотеках GoLang => 1.10.
Для получения текущего статуса в Spotify, в ваших настройках приватности аккаунта должна быть включена данная возможность.

Сейчас период обновления статуса составляет 10 секунд, что является тестовым вариантом и не принимается в качестве баг-репорта.

Также корректность передачи NP в статус не принимается без конкретизации и шагов воспроизведения.

### Подготовка к работе

Для работы необходимо получить AuthCode от Spotify со Scope = user-read-currently-playing и **токен VK с доступом к API audio методам.**

Заполняются в `const SpotiAuthCode` и `const VKToken` соотвественно.



## О найденных багах сообщать в раздел Issue:
https://github.com/P2LOVE/Spoti2VK/issues
