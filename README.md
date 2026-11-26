
# Марина Балакина

![Backend Developer](https://img.shields.io/badge/Backend%20Developer-70263D?style=flat-square)
![ITMO University](https://img.shields.io/badge/ITMO%20University-70263D?style=flat-square)

## Обо мне

Студентка 3 курса Университета ИТМО, факультет информационных технологий и программирования, направление «Разработка программного обеспечения».

Развиваюсь в backend-разработке на Java и C#/.NET. Интересуюсь микросервисной архитектурой, распределёнными системами, проектированием приложений и работой с базами данных.

Практический опыт получила в рамках учебных, командных и самостоятельных проектов. Сейчас ищу возможность применить полученные знания в коммерческой разработке.

В одном из командных проектов на C# выполняла роль руководителя команды: участвовала в планировании, распределяла задачи и координировала совместную разработку.

---

## Технологический стек

![C#](https://img.shields.io/badge/C%23-70263D?style=flat-square)
![.NET](https://img.shields.io/badge/.NET-70263D?style=flat-square)
![Java](https://img.shields.io/badge/Java-70263D?style=flat-square)
![SQL](https://img.shields.io/badge/SQL-70263D?style=flat-square)

| Направление | Технологии и навыки |
| --- | --- |
| Backend | .NET, ASP.NET Core, Spring Boot, Spring Web, Spring Security |
| Базы данных | PostgreSQL, MongoDB, Redis |
| Работа с данными | Dapper, Hibernate, Spring Data JPA |
| Взаимодействие | REST API, gRPC, Apache Kafka |
| Архитектура | Microservices, Hexagonal Architecture |
| Проектирование | ООП, SOLID, GRASP, Design Patterns |
| Разработка | Dependency Injection, асинхронное программирование, потокобезопасность |
| Тестирование | Unit Testing, Integration Testing, Mocking |
| Инструменты | Docker, Git, Bash, Gradle |

---

## Проекты

### [![01. RequestFlow](https://img.shields.io/badge/01.%20RequestFlow-70263D?style=for-the-badge)](https://github.com/MarinaBalakina/RequestFlow)

**Микросервисная система контроля частоты запросов к API**

Система позволяет управлять пользователями, настраивать допустимое количество запросов к отдельным методам API и временно блокировать пользователей при превышении лимитов.

В проекте реализованы:

- управление пользователями через gRPC API;
- хранение пользовательских данных в PostgreSQL;
- асинхронная обработка событий через Apache Kafka;
- потокобезопасный подсчёт количества запросов;
- динамическое обновление ограничений через MongoDB Change Streams;
- временные блокировки через Redis с TTL;
- проверка запросов через gRPC Interceptors.

Командный проект, в рамках которого я также занималась планированием, распределением задач и координацией разработки.

**Стек:** C# · .NET · PostgreSQL · MongoDB · Redis · Kafka · gRPC · Dapper · Docker

[![Подробнее о проекте](https://img.shields.io/badge/Подробнее%20о%20проекте%20%E2%86%92-70263D?style=flat-square)](https://github.com/MarinaBalakina/RequestFlow)

---

### [![02. Car Management System](https://img.shields.io/badge/02.%20Car%20Management%20System-70263D?style=for-the-badge)](https://github.com/MarinaBalakina/drive-flow-backend)

**Backend-система управления автосалоном**

Система автоматизирует процессы выбора автомобиля, создания индивидуальной комплектации, оформления заказа и подготовки автомобиля к выдаче.

В проекте реализованы:

- конфигуратор автомобилей с проверкой совместимости комплектующих;
- управление заказами и тест-драйвами;
- REST API и работа с PostgreSQL;
- аутентификация и ролевое разграничение доступа;
- микросервисная архитектура;
- асинхронное взаимодействие через брокер сообщений;
- надёжная отправка событий через Transactional Outbox;
- межсервисное взаимодействие через gRPC.

**Стек:** Java · Spring Boot · Spring Data JPA · Hibernate · Spring Security · PostgreSQL · gRPC · Docker

[![Подробнее о проекте](https://img.shields.io/badge/Подробнее%20о%20проекте%20%E2%86%92-70263D?style=flat-square)](https://github.com/MarinaBalakina/drive-flow-backend)

---

### [![03. C# OOP Projects](https://img.shields.io/badge/03.%20C%23%20OOP%20Projects-70263D?style=for-the-badge)](https://github.com/MarinaBalakina/csharp-oop-projects)

**Коллекция проектов по объектно-ориентированному программированию и проектированию приложений на C#**

Серия из пяти проектов, направленных на практическое изучение принципов ООП, SOLID, GRASP, паттернов проектирования, тестирования и архитектуры приложений.

Каждый проект посвящён отдельной предметной области и подходам к организации кода.

| Проект | Функциональность | Основные навыки |
| --- | --- | --- |
| ![Симулятор поездов](https://img.shields.io/badge/Симулятор%20поездов-70263D?style=flat-square) | Моделирование движения поездов, прохождения маршрутов и проверки ограничений скорости | ООП, инкапсуляция, полиморфизм, композиция |
| ![Система сообщений](https://img.shields.io/badge/Система%20сообщений-70263D?style=flat-square) | Распределение сообщений между адресатами, фильтрация, логирование, архивирование и уведомления | SOLID, GRASP, структурные паттерны, mocking |
| ![Симулятор сражений](https://img.shields.io/badge/Симулятор%20сражений-70263D?style=flat-square) | Создание игровых существ, применение модификаторов и заклинаний, моделирование боёв | Порождающие и структурные паттерны, расширяемость кода |
| ![Файловый менеджер](https://img.shields.io/badge/Файловый%20менеджер-70263D?style=flat-square) | Навигация по файловой системе, обработка консольных команд и управление файлами | Поведенческие паттерны, SOLID, парсинг команд, ленивая загрузка |
| ![Система банкомата](https://img.shields.io/badge/Система%20банкомата-70263D?style=flat-square) | Управление счетами, пользовательскими сессиями, балансом и историей финансовых операций | ASP.NET Web API, гексагональная архитектура, DI, Repository |

Отдельное внимание уделено разделению ответственности между классами, снижению связанности компонентов, возможности расширения функциональности и тестированию бизнес-логики.

В проекте банкомата бизнес-логика отделена от слоя представления и хранения данных. Для взаимодействия с приложением используется ASP.NET Web API, для управления зависимостями — Dependency Injection.

**Стек:** C# · .NET · ASP.NET Core · ООП · SOLID · GRASP · Design Patterns · Hexagonal Architecture · Unit Testing · Mocking

[![Подробнее о проектах](https://img.shields.io/badge/Подробнее%20о%20проектах%20%E2%86%92-70263D?style=flat-square)](https://github.com/MarinaBalakina/csharp-oop-projects)

---

## Контакты

[![Telegram](https://img.shields.io/badge/Telegram-70263D?style=flat-square&logo=telegram&logoColor=white)](https://t.me/Dealer7920)
[![Email](https://img.shields.io/badge/Email-70263D?style=flat-square&logo=gmail&logoColor=white)](mailto:marinabalakina132@gmail.com)
