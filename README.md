# Jira local

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)

## About <a name = "about"></a>

Создает композитный докер контейнер с Джирой и БД постгрес для нее

## Getting Started <a name = "getting_started"></a>

### Prerequisites

Вам нужен установленный докер и гит.

### Installing

A step by step series of examples that tell you how to get a development env running.

```
git clone https://github.com/maxikoro/jira.git
cd jira
docker compose up -d
```

## Usage <a name = "usage"></a>

Джира будет доступна по адресу http://localhost:8080. Возможно, вместо localhost надо будет написать IP вашей машины.

Если запросит параметры подключения в бд
```
хост: jira_postgres
порт: 5432
имя БД=jiradb
юзер=jirauser
пароль=jirapassword
```
Контейнер жрет много ресурсов. Больше 3Гб оперативки. Развлечение не для слабых компуктеров. В процессе установки нужно получить ключ в Атлассиан. Возможно для этого потребуется впн.