
# Марина Балакина

![Backend Developer](https://img.shields.io/badge/Backend-Developer-722F37?style=flat-square)
![ITMO University](https://img.shields.io/badge/ITMO-University-722F37?style=flat-square)

## Обо мне

Студентка 3 курса Университета ИТМО, факультет информационных технологий и программирования, направление «Разработка программного обеспечения».

Развиваюсь в backend-разработке на Java и C#/.NET. Интересуюсь микросервисной архитектурой, распределёнными системами, проектированием приложений и работой с базами данных.

Практический опыт получила в рамках учебных, командных и самостоятельных проектов. Сейчас ищу возможность применить полученные знания в коммерческой разработке.

В одном из командных проектов на C# выполняла роль руководителя команды: участвовала в планировании, распределяла задачи и координировала совместную разработку.

---

## Технологический стек

![C#](https://img.shields.io/badge/C%23-722F37?style=flat-square)
![.NET](https://img.shields.io/badge/.NET-722F37?style=flat-square)
![Java](https://img.shields.io/badge/Java-722F37?style=flat-square)
![SQL](https://img.shields.io/badge/SQL-722F37?style=flat-square)

| Направление | Технологии и навыки |
| --- | --- |
| Backend | .NET, ASP.NET Core, Spring Boot, Spring Web, Spring Security |
| Базы данных | PostgreSQL, MongoDB, Redis |
| Работа с данными | Dapper, Hibernate, Spring Data JPA |
| Взаимодействие | REST API, gRPC, Apache Kafka |
| Архитектура | Microservices, Hexagonal Architecture, SOLID, ООП, Design Patterns |
| Разработка | Dependency Injection, асинхронное программирование, тестирование |
| Инструменты | Docker, Git, Bash, Gradle |

---

## Проекты

### 01. [RequestFlow](https://github.com/MarinaBalakina/RequestFlow)

**Микросервисная система контроля частоты запросов к API**

Система позволяет управлять пользователями, настраивать допустимое количество запросов к отдельным методам API и временно блокировать пользователей при превышении лимитов.

В проекте реализованы:

- управление пользователями через gRPC API;
- асинхронная обработка событий через Apache Kafka;
- потокобезопасный подсчёт количества запросов;
- динамическое обновление ограничений через MongoDB Change Streams;
- временные блокировки через Redis с TTL;
- проверка запросов через gRPC Interceptors.

Командный проект, в рамках которого я также занималась планированием и координацией разработки.

**Стек:** C# · .NET · PostgreSQL · MongoDB · Redis · Kafka · gRPC · Docker

[Подробнее о проекте →](https://github.com/MarinaBalakina/RequestFlow)

---

### 02. [Car Management System](https://github.com/MarinaBalakina/drive-flow-backend)

**Backend-система управления автосалоном**

Система автоматизирует процессы выбора автомобиля, создания индивидуальной комплектации, оформления заказа и подготовки автомобиля к выдаче.

В проекте реализованы:

- конфигуратор автомобилей с проверкой совместимости комплектующих;
- управление заказами и тест-драйвами;
- REST API и работа с PostgreSQL;
- аутентификация и ролевое разграничение доступа;
- микросервисная архитектура;
- асинхронное взаимодействие через брокер сообщений;
- Transactional Outbox и межсервисное взаимодействие через gRPC.

**Стек:** Java · Spring Boot · Spring Data JPA · Hibernate · Spring Security · PostgreSQL · gRPC · Docker

[Подробнее о проекте →](https://github.com/MarinaBalakina/drive-flow-backend)

---

### 03. ATM System

**Backend-система банкомата**

Система для управления банковскими счетами, пользовательскими сессиями и финансовыми операциями.

В проекте реализованы:

- Web API для работы с банковскими счетами;
- управление пользовательскими сессиями;
- выполнение финансовых операций;
- гексагональная архитектура;
- внедрение зависимостей через Dependency Injection;
- модульное тестирование бизнес-логики с использованием моков.

**Стек:** C# · ASP.NET Core · Web API · Dependency Injection · Hexagonal Architecture

<!-- Здесь будет ссылка на репозиторий -->

---

## Контакты

[![Telegram](https://img.shields.io/badge/Telegram-722F37?style=flat-square)](https://t.me/Dealer7920)
[![Email](https://img.shields.io/badge/Email-722F37?style=flat-square)](mailto:marinabalakina132@gmail.com)
