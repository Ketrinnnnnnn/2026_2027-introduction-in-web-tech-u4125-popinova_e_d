University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [Введение в веб технологии](https://itmo-ict-faculty.github.io/introduction-in-web-tech/)
Year: 2026/2027
Group: U4125
Author: Popinova Ekaterina Dmitrievna
Lab: Lab3
Date of create: 13.09.2026
Date of finished: XX.09.2026

Цель работы
Настроить систему мониторинга с Prometheus и Grafana, собирать метрики и визуализировать их.

2. Ход работы
- Создана папка prometheus и файл prometheus.yml
- Запущен Node Exporter (скриншот Node Exporter - хост.png)
- Запущен Prometheus (скриншот Prometheus - работа.png и Prometheus статусы.png)
- Запущена Grafana (скриншот Запуск Grafana.png)
- Настройка Grafana (скриншот Настройка Grafana.png)
- Добавление дашборда CPU (скриншот Дашборд CPU.png)
- Добавление дашбордов Память, сеть, диск (скриншот Дашборд memory & network.png и Дащборд filesystem.png)
- Результат работы контейнеров (скриншот Статусы контейнеров.png)


см скриншоты работы в папке

3. Результат
Настроена система мониторинга: Prometheus собирает метрики с Node Exporter, Grafana визуализирует их в виде графиков. Всё работает в Docker-контейнерах.
