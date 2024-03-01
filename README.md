# DevOps Engineer

## Обо мне
Являюсь `DevOps` инженером с опытом `SRE/Support`. 
Работал с различными технологиями автоматизации, контейнеризации, прикладными инструментами и системами мониторинга. 

### Развёртывание проектов на:
- PHP, Node.js, Ruby, Python, Go
### Работа с базами данных:
- MySQL, PostgreSQL, MongoDB (в связке с Redis, Memcached)
### Конфигурирование:
- Nginx, Apache, Lighthttpd, Traefik, PHP-FPM
### Работа с системами хранения и обработки данных
- MinIO, ELK, Graylog
### Построение CI/CD в связке:
- Gitea/GitLab + Drone CI/Gitlab CI
### Описание конфигурации серверов посредством:
- Ansible, с интеграцией Molecule + Testinfra
### Реализация изолированных стендов в связке:
- LXС + Docker
### Работа и взаимодействие с ДЦ:
- AWS, GCE, Azure, DigitalOcean, Linode, Vultr, OVH, Hetzner, Selectel и др.
### Реализация мониторинга в связках:
- Monit + *exporter/Netdata + Prometheus + Grafana + Loki + Alertmanager + Alerta
- Zabbix + Zabbix agent

# Опыт работы

## Киберпротект
_с Октябрь 2023 — по настоящее время (5 месяцев) г. Москва, `cyberprotect.ru`_

### **Программный инженер (DevOps/Observability Engineer)**

Работа с инструментами:
### Jenkins:
- Создание и поддержка пайплайнов CI/CD для интеграции и доставки кода в тестовое
окружение.
### Ansible:
- Настройка и обслуживание конфигураций для инструментов и приложений, включая
Kubernetes (k8s).
### Bitbucket:
- Управление репозиториями.
### ovirt:
- Для развертывания, настройки и управления виртуальными машинами, используемыми в
тестовых средах.
Развёртывание/поддержка инструментов:
### Zabbix, Prometheus и Grafana:
- Поддержка и доработка в рамках мониторинга состояния инфраструктуры и приложений.
- Настройка правил алертинга и дашбордов.
### Opensearch:
- Интеграция и поддержка системы логирования для агрегации и анализа логов.
### Sentry:
- Для отслеживания и управления ошибками приложений в реальном времени.

## OSSHelp
_с Апрель 2021 — по Октябрь 2023 (2 года 7 месяцев), г. Ростов-на-Дону, `osshelp.io`_

### **Специалист технической поддержки (DevOps/SRE/Support Engineer)**

### Администрирование серверов Linux:
- Переустановка ОС (CentOS/Ubuntu/Arch)
- Первичная конфигурация (RAID, net, sysctl, systemd/sysV/Upstart, etc.)
- Настройка локального мониторинга (monit, *exporter, pushgateway, smartmontools)
- Нагрузочное и контрольное тестирование сервера (sysbench, smartd)
- Работы по обновлению ядра ОС, пакетов и прочая поддержка софтовой части в актуальном
состоянии
- Обслуживание и замена комплектующих (SSD/HDD, CPU, RAM)
- Работа с системами виртуализации VMware/VirtualBox/Proxmox

### Ansible:
- Написание ansible playbook'ов для автоматизации первичного конфигурирования парка
серверов
- Работы по обновлению/развёртыванию стека PHP, JAVA и NodeJS приложений
- Написание ansible ролей разной сложности (на основе словарей, кортежей, декартовых
произведений и т.д.)
- Доработка существующих ansible ролей до достижения идемпотентности
- Тестирование playbook в molecule
- Написание python тестов (pytest testinfra) для post-деплой проверок на сервере

### Контейнеризация:
- Подготовка LXC/Docker контейнеров под типовые или клиентские сценарии
- Подготовка и развёртывание Docker Compose стека микросервисных приложений
- Развёртывание bitrix в LXC-среде
- Создание кастомных Docker образов и их выгрузка в registry
- Поддержание LXC/Docker образов в актуальном состоянии

### CI/CD:
- Написание pipeline в Drone Ci, Gitlab CI, Jenkins
- Сборка, развертывание, обновление ПО из CI
- Тестирование и деплой LXC/Docker контейнеров из CI
- Применение ansible playbook из CI
- Интеграция CI/CD с системами мониторинга, алертингом и мессенджерами
- Интеграция и работа с линтерами

### Мониторинг:
- Настройка сбора метрик (netdata, node-exporter, sql-exporter, consul)
- Развёртывание и настройка стека мониторинга (Prometheus/Grafana/Alertmanager/Alerta и
Zabbix)
- Подготовка и доработка дашбордов (Grafana)
- Внедрение сбора, экспорта и визуализации логов (Promtail/Loki/Grafana, ELK, Graylog)
- Работы по обновлению инфраструктуры мониторинга

### Другое:
- Настройка интеграции с anti-DDoS сервисами (CloudFlare, Qrator, DDoS Guard)
- Настройка резервного копирования посредством кастомных sh-библиотек и последующей
выгрузкой в удалённое хранилище
- Написание кастомных sh-скриптов при выполнении определённых сценариев с
последующим экспортом метрик посредством pushgateway
- Взаимодействие с клиентами для информирования о предстоящих работах или планах по
интеграции/модернизации инфраструктуры проекта
- Ведение и актуализация тех. документации как клиентской так и внутренней
- Реагирование на алерты в течение рабочей смены, их разбор и подготовка отчёта в тикет
системе по каждому инциденту
- Трекинг времени и контроль 'рабочей' очереди задач
- Наставничество и менторство

## ООО "Сеть"
_с Ноябрь 2018 — по Апрель 2022 (3 года 6 месяцев), г. Ставрополь_

### **Инженер технической поддержки (Support Engineer)**

- Конфигурирование L2, L3 и L4 коммутаторов: D-Link, Alcatel, Eltex, Cisco, Zyxel.
- Диагностика и устранение проблем сетевого характера на уровнях агрегации и сети доступа.
- Наставничество и работа в команде.
- Ведение и актуализация тех. документации.
- Ночные дежурства.
- Тестирование ПО и функционала, а также перепрошивка L2 коммутаторов.


## ООО "Восточные сети"
_с Июль 2015 — по Октябрь 2017 (2 года 4 месяца), г. Улан-Удэ_

### **Сетевой инженер-монтажник (Field Network Technician)**

- Монтаж и конфигурирование комплектов спутникового оборудования для реализации ШПД
- Монтаж и конфигурирование Wi-Fi антенн, Wi-Fi точек доступа для реализации радиоканала и
БШПД (Ubiquiti, MikroTik)
- Конфигурирование маршрутизаторов MikroTik
- Прокладка ЛВС
- Конфигурирование клиентского оборудования (ПК, маршрутизаторы и пр. локальные
устройства)


## Образование:
```text
Среднее специальное профессиональное
2017 Бурятский филиал Сибирского государственного университета телекоммуникаций и информатики,
Многоканальные телекоммуникационные системы
```

```text
Повышение квалификации, курсы
2017 Cisco Networking Academy Cisco, 
CCNA Routing and Switching
```

## Ключевые навыки:
```yaml
Английский язык — B2, Наставничество
TCP/IP, Nginx, CCNA, HTTP
Linux, Bash, Ansible, Git, Docker, Docker Compose, DroneCI, GitLab, Jenkins, Kubernetes
HTML, Python, RabbitMQ, MongoDB, Apache, SQL
Grafana, Prometheus, Zabbix, ELK
```
