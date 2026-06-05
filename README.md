# Roman Monzhelesov

Junior DevOps Engineer. Специализируюсь на Kubernetes, автоматизации инфраструктуры и построении CI/CD пайплайнов. Строю production-grade инфраструктуру на Yandex Cloud с Terraform, управляемым Kubernetes и полным стеком мониторинга.

## Стек

**Linux** — Администрирование, systemd, файловые системы, управление процессами, права доступа

**Сети** — TCP/IP, DNS, HTTP/HTTPS, маршрутизация, файрволы, iptables

**Виртуализация** — KVM/QEMU, Vagrant

**Контейнеры** — Docker (multi-stage builds, non-root), Docker Compose, Yandex Container Registry

**Kubernetes** — Managed K8s, Helm, Ingress-Nginx, HPA, NetworkPolicy, RBAC

**Cloud & IaC** — Yandex Cloud, Terraform (S3 backend, модульная структура)

**Конфигурация** — Ansible, Jinja2 шаблоны

**CI/CD** — GitHub Actions (автосборка по коммиту, деплой по тегу), Trivy сканирование

**Мониторинг и логи** — Prometheus, Grafana, Alertmanager, node-exporter, кастомные метрики

**Базы данных** — PostgreSQL, SQL, администрирование БД

**Безопасность** — Информационная безопасность, сканирование образов, non-root контейнеры

**Микросервисы** — Проектирование микросервисной архитектуры

**Отказоустойчивость** — Балансировка, кластеризация, резервирование

**VCS** — Git, GitHub, GitLab

**Языки** — Bash, Python, HCL, SQL

## Проекты

### StatusBoard — DevOps Infrastructure Platform

Сквозной инфраструктурный проект: микросервисное приложение, развёрнутое в Managed Kubernetes с Terraform IaC, GitHub Actions CI/CD и полным стеком Prometheus/Grafana.

**Что внутри:**
- Terraform: VPC, 3 зоны доступности, Managed K8s кластер, Container Registry, S3 backend для state
- Kubernetes: Deployments, HPA, NetworkPolicy, RBAC, Ingress
- CI/CD: lint → test → build → push в registry (по коммиту), deploy в K8s (по тегу)
- Мониторинг: Prometheus + дашборды Grafana + Alertmanager

![Приложение](https://raw.githubusercontent.com/monzhelesov/statusboard/main/docs/images/app.png)

![Grafana](https://raw.githubusercontent.com/monzhelesov/statusboard/main/docs/images/grafana.png)

![CI/CD](https://raw.githubusercontent.com/monzhelesov/statusboard/main/docs/images/ci.png)

[Портфолио репо](https://github.com/monzhelesov/statusboard) · [Инфраструктура](https://github.com/monzhelesov/infrastructure) · [Приложение](https://github.com/monzhelesov/statusboard-app) · [K8s конфиг](https://github.com/monzhelesov/k8s-config)

## Образование

| Период | Квалификация | Детали |
|---|---|---|
| 2023–2026 | DevOps-инженер — проф. переподготовка (900+ часов) | Нетология. Linux, Docker, Kubernetes, Terraform, Ansible, CI/CD, мониторинг, безопасность, базы данных, микросервисы |
| 2023–2026 | Магистр — Реклама и связи с общественностью | АТиСО |
| 2019–2023 | Бакалавр — Менеджмент | ИМЭС |

## Контакты

- GitHub: github.com/monzhelesov
- Email: roman.monzhelesov@bk.ru
