<div align="center">

<img src="https://raw.githubusercontent.com/gxdlxss/gxdlxss/main/logo.png" alt="Godless logo" width="120"/>

# Godless

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=440&lines=no+gods+%C2%B7+no+masters;i've+lost+my+god;Middle+Golang+Developer" alt="Typing SVG" />

</div>

---

### О себе

```go
type Godless struct {
    Name              string
    Languages         []string
    FavouriteLang     string
    CurrentlyLearning string
    CurrentCompany    string
    Age               int
    StudyAt           string
    Site              string
}

func NewGodless() *Godless {
    return &Godless{
        Name:              "Godless",
        Languages:         []string{"C#", "C++", "C", "Go"},
        FavouriteLang:     "Go",
        CurrentlyLearning: "Go",
        CurrentCompany:    "Recovery Toolbox Inc.",
        Age:               19,
        StudyAt:           "CU'28",
        Site:              "gxdlxsss.ru",
    }
}
```

<div align="center">

| Компания | Учёба | Возраст | Сайт |
|:---:|:---:|:---:|:---:|
| Recovery Toolbox Inc. | CU'28 | 19 | [gxdlxsss.ru](https://gxdlxsss.ru) |

</div>

---

### Стек

<div align="center">

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=for-the-badge&logo=google&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

</div>

Любимый язык: Go

---

### Опыт работы

**Junior Golang разработчик** - Recovery Toolbox Inc.
Ноябрь 2024 - настоящее время

Разрабатываю и развиваю Go-сервисы для управления и мониторинга серверов компании.

- Ускорил тяжёлые эндпоинты с 800 до 150 мс: переписал SQL-запросы, добавил составные индексы в PostgreSQL и Redis-кэш на горячие данные
- Сократил время выката новой версии с 15 до 8 минут: GitLab CI, multi-stage Docker-образы, деплой в Kubernetes
- Вынес межсервисное взаимодействие в Kafka - 150 тыс. событий/сутки: развязал продюсеров и консьюмеров, сервисы держат пиковые нагрузки без деградации
- Спроектировал и вывел в прод REST- и gRPC-сервисы (Protobuf) на Go, стабильно 800 запросов/сек: валидация входящих данных, единая обработка ошибок, аккуратный проброс context.Context между слоями
- Поднял покрытие бизнес-логики unit-тестами до 70% - регрессии перестали доезжать до продакшена
- Разработал фоновые обработчики на горутинах и каналах с sync-примитивами и graceful shutdown - ноль потерь данных при перезапуске и деплое

---

### Проекты

<img src="https://raw.githubusercontent.com/gxdlxss/gxdlxss/main/%D0%A4%D0%B0%D0%B9%D0%BB_2-1.png" alt="Karma logo" width="40" align="left"/>&nbsp;**[Karma](https://karma-verdict.com)**
<br>Мультитенант SaaS: Go control plane, клиентский JS-тег, кабинет на React + TypeScript. Антибот-защита сайтов, вердикты по сессиям на клиентской телеметрии, общий блеклист известных ботов, увод на зеркало, TOTP MFA, RBAC, биллинг (PayPro / YooKassa / Cryptomus).

<img src="https://raw.githubusercontent.com/gxdlxss/gxdlxss/main/%D0%A4%D0%B0%D0%B9%D0%BB_2.png" alt="RDP Protector logo" width="40" align="left"/>&nbsp;**[RDP Protector](https://rdpprotector.com)**
<br>Мультитенант SaaS: Go control plane, Windows-агент, кабинет на React + TypeScript. mTLS-энроллмент, TOTP MFA, RBAC, биллинг (PayPro / YooKassa / Cryptomus).

<img src="https://raw.githubusercontent.com/gxdlxss/gxdlxss/main/%D0%A4%D0%B0%D0%B9%D0%BB_2-2.png" alt="SSH Protector logo" width="40" align="left"/>&nbsp;**[SSH Protector](https://sshprotector.com)**
<br>Мультитенант SaaS: Go control plane, Linux-агент, кабинет на React + TypeScript. Защита SSH и FTP от брутфорса, баны подсетей, общая база угроз, mTLS-энроллмент, TOTP MFA, RBAC, биллинг (PayPro / YooKassa / Cryptomus).

<img src="https://raw.githubusercontent.com/gxdlxss/gxdlxss/main/%D0%A4%D0%B0%D0%B9%D0%BB_2-11.png" alt="Sentinel logo" width="40" align="left"/>&nbsp;**[Sentinel](https://servers-sentinel.com)**
<br>Мультитенант SaaS для мониторинга серверов: Go control plane, агенты для Linux и Windows, кабинет на React + TypeScript. Метрики и их история, uptime- и API-проверки с SLA, алерты в email / Telegram / Slack / webhook, статус-страницы, биллинг (PayPro / YooKassa / Cryptomus).

<img src="https://raw.githubusercontent.com/gxdlxss/gxdlxss/main/%D0%A4%D0%B0%D0%B9%D0%BB_1.png" alt="Majestic Bots logo" width="40" align="left"/>&nbsp;**[Majestic Bots](https://majestic-bots.ru)**
<br>Экосистема ботов и сайтов для Majestic RP (бренды [majestic-bots.ru](https://majestic-bots.ru) и [russia-online-bots.ru](https://russia-online-bots.ru)). Discord-бот семьи на Go (discordgo) + MongoDB: рекрут, дни рождения, сборы, розыгрыши, тир-ап, temp-войсы, видеоуведомления, статус серверов, статистика — с админ-панелью (Go + Next.js). Статистика в стиле HLTV ([maj-hltv.ru](https://maj-hltv.ru), [russia-online-hltv.ru](https://russia-online-hltv.ru)): Go-парсер официального API в Mongo (арена, войны семей, капты, рейтинги) и веб на Vite + React 19 с SSR-пререндером. Мониторинг жалоб на [forum.majestic-rp.ru](https://forum.majestic-rp.ru): три Go-сервиса, обход антибота ReAct через headless Chromium (go-rod), уведомления в Discord и Telegram. Лендинги на Next.js 15 + React 19.

---

### Контакты

<div align="center">

[![Website](https://img.shields.io/badge/gxdlxsss.ru-black?style=for-the-badge&logo=googlechrome&logoColor=white)](https://gxdlxsss.ru)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gxdlxss)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/gxdlxsss)
[![VK](https://img.shields.io/badge/VK-0077FF?style=for-the-badge&logo=vk&logoColor=white)](https://vk.com/gxdlxsss)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@gxdlxss)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/FjpCFMvaQW)

</div>

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=gxdlxss&color=blueviolet&style=flat-square)

</div>
