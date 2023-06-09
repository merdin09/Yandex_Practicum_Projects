# Создание дашборда  взаимодействия пользователей с карточками ЯндексДзен

[**Презентация**](https://github.com/merdin09/Yandex_Practicum_Projects/blob/main/09%20%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%B4%D0%B0%D1%88%D0%B1%D0%BE%D1%80%D0%B4%D0%B0%20%20%D0%B2%D0%B7%D0%B0%D0%B8%D0%BC%D0%BE%D0%B4%D0%B5%D0%B9%D1%81%D1%82%D0%B2%D0%B8%D1%8F%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9%20%D1%81%20%D0%BA%D0%B0%D1%80%D1%82%D0%BE%D1%87%D0%BA%D0%B0%D0%BC%D0%B8%20%D0%AF%D0%BD%D0%B4%D0%B5%D0%BA%D1%81%D0%94%D0%B7%D0%B5%D0%BD/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B2%D0%B7%D0%B0%D0%B8%D0%BC%D0%BE%D0%B4%D0%B5%D0%B9%D1%81%D1%82%D0%B2%D0%B8%D1%8F%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9%20%D1%81%20%D0%BA%D0%B0%D1%80%D1%82%D0%BE%D1%87%D0%BA%D0%B0%D0%BC%D0%B8%20%D0%AF.pdf)

[**Дашборд**](https://public.tableau.com/app/profile/sergei.pakhar/viz/yandex_dzen_16812258327940/Dashboard1?publish=yes)

**Задачи:** Анализ взаимодействия пользователей с карточками Яндекс.Дзен

**Описание проекта:** 

Состав данных для дашборда:

- история событий по темам карточек (два графика - абсолютные числа и процентное соотношение);
- разбивка событий по темам источников;
- таблица соответствия тем источников темам карточек;

По каким параметрам данные должны группироваться:
- дата и время;
- тема карточки;
- тема источника;
- возрастная группа;

Характер данных:
- история событий по темам карточек — абсолютные величины с разбивкой по минутам;
- разбивка событий по темам источников — относительные величины (% событий);
- соответствие тем источников темам карточек - абсолютные величины;

**Используемый стек**: pandas, sqlalchemy, Tablue

## Выводы: ##
- Основная активность в ЯндексДзен с 18:52 до 19:00; 
- Топ-3 тем по карточкам: отношения, интересные факты, наука; 
- Топ-3 событий по темам источников: семейные отношения, Россия, полезные сове
