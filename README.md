# Расчетно-пояснительная записка: VK Education High-load

## 1. Тема и целевая аудитория

[Ticketmaster](https://www.ticketmaster.com/)—крупнейший сервис продажи билетов в Северной Америке, и один из крупнейших во всем мире.[^em-dash]

[^em-dash]: Здесь и далее, все тире ставил человек.

### Ключевой функционал

* Покупка билета на событие.
* Просмотр предстоящих событий.
* Поиск событий.
* Просмотр информации о конкретном событии.

### Целевая аудитория

Родительская компания Ticketmaster—Live Nation Entertainment—не публикует свои прямые метрики. Однако можно оценить масштаб по ежегодному отчету[^10k-filing], который она обязана публиковать как крупная американская компания: За 2025 год было продано 646 миллионов билетов среди 805 миллионов пользователей в 55 странах.

[^10k-filing]: т.н. [Form 10-k от LIVE NATION ENTERTAINMENT, INC.](https://investors.livenationentertainment.com/sec-filings/annual-reports/content/0001335258-26-000009/0001335258-26-000009.pdf) за 2025.

Одно мобильное приложение имеет более 30 миллионов ежемесячных пользователей.[^mobile-30mil] Сайты web-аналитики в средням делают оценку[^mau-web] в 95–100 миллионов запросов в месяц при ~3.5 страницах на пользователя (т.е., почти 30 миллионов пользователей) лишь на домен [ticketmaster.com](https://ticketmaster.com), которым в основном пользуются жители Северной Америки (>80% посетителей из США)—в то время как сервис также доступен через [ticketmaster.co.uk](https://ticketmaster.co.uk) в Англии (4.5 млн. пользователей в месяц), [ticketmaster.de](https://ticketmaster.de) в Германии (~1 млн.), и т.д.

[^mobile-30mil]: [Официальный сайт](https://business.ticketmaster.com/ticketing-straight-to-your-app/) Ticketmaster Business.
[^mau-web]: [Similarweb](https://www.similarweb.com/website/ticketmaster.com/#traffic) и [Semrush](https://www.semrush.com/website/ticketmaster.com/overview/).

Также представляет интерес пиковая активность—например, 15 Ноября 2022 года сервис получил более 3.5 миллиардов запросов (т.е., более 40,000 в секунду) при продаже двух миллионов билетов за один день после открытия регистрации на концерт певицы Тейлор Свифт.[^eras-tour]

[^eras-tour]: Официальный сайт Ticketmaster Business: [Taylor Swift | The Eras Tour Onsale Explained](https://business.ticketmaster.com/press-release/taylor-swift-the-eras-tour-onsale-explained/).

<!-- Mentioning Taylor Swift in a report... What am I doing with my life? --->
