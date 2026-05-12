# GT Sysadmin Test Assignment

Практическое тестовое задание на позицию дежурного системного администратора.

## Цель

Развернуть тестовую инфраструктуру на виртуальных машинах с использованием Linux, Docker, Nginx, MongoDB, HTTPS, логирования, анализа ресурсов и firewall.

## Окружение

- Host OS: Windows 11
- Virtualization: Oracle VirtualBox
- Guest OS: Ubuntu Server 22.04 LTS
- Repository: gt-sysadmin-test

## Виртуальные машины

| VM | Назначение | ОС | IP |
|---|---|---|---|
| VM-app | Приложение, Docker, Reaction Commerce | Ubuntu Server 22.04 LTS | TBD |
| VM-www-db | Nginx reverse proxy, MongoDB container | Ubuntu Server 22.04 LTS | TBD |
| VM-mongodb | MongoDB replica set member | Ubuntu Server 22.04 LTS | TBD |

## Структура репозитория

```text
gt-sysadmin-test/
├── README.md
├── screenshots/
├── configs/
│   ├── nginx/
│   ├── docker/
│   ├── firewall/
│   └── mongodb/
├── notes/
│   └── commands.md
└── report/
    └── summary.md