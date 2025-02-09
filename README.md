# Pinger

Как и сказано в задании, есть 3 сервиса: Frontend, Backend, Pinger.

## Запуск

```
docker-compose up
```

Затем, страница будет доступна по адресу `http://localhost/pings`

## Networking

Все 3 сервиса объединены внутренней сетью. Только ко Frontend есть доступ извне. Этим и достигается хоть какой-то уровень безопасности.
Возможности человека, не имеющего доступа к внутренней сети, ограничиваются теми, которые ему предоставляет Frontend.
Было бы, безусловно, неплохо также реализовать авторизацию, но у меня, к сожалению, уже не хватило на это времени.

## Сервисы
[backend](https://github.com/VK-backend-test-task/backend)<br>
[frontend](https://github.com/VK-backend-test-task/frontend)<br>
[pinger](https://github.com/VK-backend-test-task/pinger)
