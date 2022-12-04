HW docker
Рассмотрена работа докера
Рассмотрен вопрос хранения состояния в докере
Рассмотрен вопрос сетевого взаимодействия в докер
Рассмотрены основные команды для создания образа
Создание локальных образов. Написание Dockerfile
Запуск контейнеров из докера
Получение образов  из hub.docker.comСоздание локального образа и отправка образа в hub.docker.com
Использование команд для входа внутрь контейнера
Использование команд inspect, logs и др.
Использование docker-compose
Установка docker-desktop и использование docker-machine локально и с yandex-cloud

Monitoring-1

Сделаны базовые задания согласно руководству
Задание со *
1.Добавьте в Prometheus мониторинг MongoDB с использованием необходимого экспортера.
2.Добавьте в Prometheus мониторинг сервисов comment, post, ui с помощью blackbox exporter.

Сделано:
Добавлен контейнер gpuliyar/mongo-exporter, метрики с БД приходят все работает отлично.
Добавлен контейнер blackbox он проверяет отклик с ip:9292 конфиг его лежит в monitoring/blackbox.

https://hub.docker.com/repository/docker/supercat89/post
https://hub.docker.com/repository/docker/supercat89/comment
https://hub.docker.com/repository/docker/supercat89/ui
https://hub.docker.com/repository/docker/supercat89/prometheus
https://hub.docker.com/repository/docker/supercat89/blackbox
