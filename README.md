# lesson-logs
Домашнее задание

Настраиваем центральный сервер для сбора логов

Описание/Пошаговая инструкция выполнения домашнего задания:

Для выполнения домашнего задания используйте методичку
https://docs.google.com/document/d/16UBAMu4LYqvRv6PmCeHcmOampMrIZavH/edit?usp=share_link&ouid=104106368295333385634&rtpof=true&sd=true

Что нужно сделать?

в вагранте поднимаем 2 машины web и log

на web поднимаем nginx

на log настраиваем центральный лог сервер на любой системе на выбор
journald;
rsyslog;
elk.

настраиваем аудит, следящий за изменением конфигов нжинкса

Все критичные логи с web должны собираться и локально и удаленно.

Все логи с nginx должны уходить на удаленный сервер (локально только критичные).

Логи аудита должны также уходить на удаленную систему.

Формат сдачи ДЗ - vagrant + ansible

развернуть еще машину elk*

таким образом настроить 2 центральных лог системы elk и какую либо еще;

в elk должны уходить только логи нжинкса;

во вторую систему все остальное.

В чат ДЗ отправьте ссылку на ваш git-репозиторий . Обычно мы проверяем ДЗ в течение 48 часов.

Если возникнут вопросы, обращайтесь к студентам, преподавателям и наставникам в канал группы в Slack.

Удачи при выполнении!
