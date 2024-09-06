# Analysis-of-Micromobile-Taxi-Service-Operation-in-India_python

![Uploading image.png…]()

# Description of the business task and data set

The "Yulu" dataset contains information on demand for shared e-bikes in India, provided by India's leading micromobility provider Yulu. This company offers unique vehicles for daily commutes with the aim of eliminating traffic congestion in India and providing a safe, convenient and affordable solution to mobility. Yulu zones are located in optimal locations, including metro stations, bus stops, office spaces, residential areas and corporate offices, to facilitate the first and last kilometers of travel.

Recently, Yulu has faced significant declines in revenue, so the company turned to a consulting firm to understand what factors are driving demand for these shared e-bikes, especially in the Indian market.

The dataset used in this project is publicly available: dataset link yulu_rental.csv https://drive.google.com/file/d/1f3zTW-hRHo1DQrtjjxsA2yTErjQNSvb5/view?usp=sharing

List of data set columns:

datetime: The date and time are collected hourly
season: season (1: spring, 2: summer, 3: autumn, 4: winter)
holiday: whether the day is a holiday (retrieved from http://dchr.dc.gov/page/holiday-schedule)
workingday: if the day is not a weekend or holiday, it is marked as 1, otherwise - 0.
weather:
1 - Clear, Partly cloudy, partly cloudy
2 - Fog + Cloudy, Fog + Broken clouds, Fog + Partly cloudy, Fog
3 - Light snow, Light rain + Thunderstorm + Scattered clouds, Light rain + Scattered clouds
4 - Heavy Rain + Ice Balls + Thunderstorm + Fog, Snow + Fog
temp: temperature in degrees Celsius
atemp: how the temperature feels in degrees Celsius
humidity: humidity
windspeed: wind speed
casual: number of informal users
registered: number of registered users
count: total number of bikes rented, including informal and registered users

The main task of the analysis:

* Study the dynamics of changes in registered users by period.
* Seasonal analysis.
* Analysis of the impact of weather conditions on business.
* Study of changes in the daily number of registered users.
* Comparison of the number of users on weekdays and weekends.
  
# Опис бізнес задачі та набору даних

Набір даних "Yulu" містить інформацію про попит на спільні електровелосипеди в Індії, що надаються провідним індійським постачальником мікромобільності Yulu. Ця компанія пропонує унікальні транспортні засоби для щоденних поїздок з метою усунення транспортних заторів в Індії та забезпечення безпечного, зручного та доступного рішення для пересування. Зони Yulu розташовані в оптимальних місцях, включаючи станції метро, автобусні зупинки, офісні простори, житлові райони та корпоративні офіси, щоб полегшити поїздки на перші та останні кілометри.

Останнім часом Yulu зіткнулася зі значними зниженнями доходів, тому компанія звернулася до консалтингової фірми з метою зрозуміти, від яких факторів залежить попит на ці спільні електровелосипеди, особливо на індійському ринку.

Набір даних, який використовується в цьому проекті, є загальнодоступним: посилання на набір даних yulu_rental.csv https://drive.google.com/file/d/1f3zTW-hRHo1DQrtjjxsA2yTErjQNSvb5/view?usp=sharing

Перелік колонок набору даних:

datetime: дата та час зібрані погодинно
season: сезон (1: весна, 2: літо, 3: осінь, 4: зима)
holiday: чи є день святковим (витягнуто з http://dchr.dc.gov/page/holiday-schedule)
workingday: якщо день не є вихідним або святковим, то позначається як 1, в іншому випадку – 0.
weather:
1 - Ясно, Мало хмарно, частково хмарно
2 - Туман + Хмарно, Туман + Розірвані хмари, Туман + Мало хмарно, Туман
3 - Легкий сніг, Легкий дощ + Гроза + Розсіяні хмари, Легкий дощ + Розсіяні хмари
4 - Сильний дощ + Крижані кулі + Гроза + Туман, Сніг + Туман
temp: температура в градусах Цельсія
atemp: як відчувається температура в градусах Цельсія
humidity: вологість
windspeed: швидкість вітру
casual: кількість неформальних користувачів
registered: кількість зареєстрованих користувачів
count: загальна кількість велосипедів, взятих в оренду, включаючи неформальних та зареєстрованих користувачів

Основна задача аналізу:

* Дослідити динаміку зміни зареєстрованих користувачів по періодам.
* Сезонний аналіз.
* Аналіз впливу погодних умов на бізнес.
* Дослідження зміни поденної кількості зареєстрованих користувачів.
* Порівняння кількості користувачів у будні та вихідні дні.



