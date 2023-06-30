# Портфолио: аналитик данных

## Обо мне 

Привет! Меня зовут Александр Борисенко, я начинающий аналитик данных. 
Около 10 лет я работал юристом, но решил попробовать себя в чем-то новом и интересном для меня. 
Недолго подумав я решил, что больше всего меня беспокоит вопрос о том как понять окружающий мир.
Ответом на него я решил искать, используя аналитику данных. Я надеюсь, что это именно тот инструмент, который поможет мне смотреть на мир объективно и понимать его лучше.
В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>

## Навыки и технологии
- Инструменты анализа данных: ``SQL``, ``Excel``: 
- Системы управления базами данных: ``PostgreSQL``; ``Metabase``



## Проекты
<p> Проект 1: Калькулятор юнит-экономики онлайн-школы</p>
<p>Что нужно было сделать:
Цель проекта - на основании данных по костам и количестве учителей, работающих в онлайн школе, за 2021 год сделать правдоподобный калькулятор юнит-экономики, позволяющий менять параметры основных метрик таким образом, чтобы было ясно какие действия нужно будет предпринять и затраты понести, чтобы достить целевых показателей в 2022 году.
Исходя из этих показателей также нужно было подготовить реалистичный прогноз найма учителей, выполнимый для HR.
<p>
<ol>
  <li>Задача №1 - подготовить прогнозный калькулятор юнит-экономики</li>
  <li>Задача №2 - подготовить план найма преподавателей</li>
</ol>

<p>Как решала(-а):<p>
<p>1.1) На основании данных за 2021 год произвел расчет основных метрик (Средний Retention за период,Lifetime (месяцы), Средняя интенсивность, Lifetime (уроки), Средняя цена урока, LTR, 
CAC, ЗП Учителя на 1 урок, Fixed costs на 1 урок )<p>
<p>1.2) Добавил столбец "Изменение", позволяющий вписывать параметры на период 05.21-04.22, установив расчет значений таблицы с основными данными на основании установленных показателей.<p>
<p>1.3) Установил показатель "Поправочный коэф-т на привлечение" с возможностью изменять этот показатель для расчётного периода 05.21-04.22 по аналогии с другими - через столбец "Изменение" и привязал расчет количества новых студентов за период 05.21-04.22 с поправкой на этот коэффициент. <p>
<p>1.4) Добавил в калькулятор Найма преподавателей возможность изменять входныепараметры: Пропускную способность П и Retention П - с помощью дополнительного столбца с процентными изменениями.<p>
<p>2.1) Сделал поправку в расчёте общей пропускной способности так, чтобы отразить, что новые преподаватели в первый месяц своей работы могут проводить только половину уроков от средней пропускной способности преподавателя, задаваемой параметром.<p>
<p>2.2) Обновите прогнозное количество уроков, добавив новые значения из 1 части (полученные после поправки на планы маркетинга)<p>
<p>2.3) Просчитал сценарий, при котором Пропускная способность П увеличится на 15 процентов, а Retention П упадёт на 2 процента<p>
<p>2.4) С помощью Поиска решений составил новый план найма с ограничением: за месяц нельзя нанять более 70 преподавателей<p>
<p>

<p>Выводы (итоги):<p>
<ol>
  <li>Калькулятор работает исправно. Его можно использовать для построения прогноза по привлечению новых студентов.</li>
</ol>
<br> 

<p> Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Задача №1</li>
  <li>Задача №2.</li>
</ol>

<p>Как решала(-а): краткое описание решения (автореферат)<p>

> <a href="https://drive.google.com/drive/folders/11HcEeqniyrCMjuwHZ0GLysX0A2SEv-_x">Ссылка на проект</a>
 (ссылка должна содержать демонстративные материалы: скриншоты, таблички, запросы, код. Работодатель должен иметь возможность быстро посмотреть результаты работы)
 
<p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  <li>Итог №2</li>
</ol>
<br> 

<br> 
<p> Проект 3: Когортный анализ онлайн-кинотеатра с помощью SQL</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Задача №1</li>
  <li>Задача №2.</li>
</ol>

<p>Как решала(-а): краткое описание решения (автореферат)<p>
  
> <a href="https://drive.google.com/drive/folders/1wdD-mfSeIsHWgrMLJz8Tv_ClAuP_EAOQ?usp=sharing">Ссылка на проект</a>
(ссылка должна содержать демонстративные материалы: скриншоты, таблички, запросы, код. Работодатель должен иметь возможность быстро посмотреть результаты работы)

  <p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  <li>Итог №2</li>
</ol>

<br> 
<p>Проект 4: Построение витрины для модели машинного обучения в банке </p> 
<p>Что нужно было сделать: задача №1.<p>
  
<p>Как решала(-а): краткое описание решения (автореферат)<p>

> <a href="https://drive.google.com/drive/folders/1QOk5AAh6x7jK_yHgfKI2sUFYR7AWUi5u">Ссылка на проект</a>
(ссылка должна содержать демонстративные материалы: скриншоты, таблички, запросы, код. Работодатель должен иметь возможность быстро посмотреть результаты работы)
  
 <p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  <li>Итог №2</li>
</ol>
<br> 


<p>Проект 5: Моделирование изменения балансов студентов</p> 
<p>Что нужно было сделать:<p>
<ol>
  <li>Задача №1</li>
  <li>Задача №2.</li>
</ol>

<p>Как решала(-а): краткое описание решения (автореферат)<p>
<li>Итоги:</li>
Запрос, который собирает данные о балансах студентов за каждый "прожитый" ими день и визуализация балансов.
<li>Выводы по 1 визуализации (из первых 1000 строк):</li>
1.	Ученики занимаются без оплат. В балансе иногда появляются отрицательные числа. Почему?
2.	Почему 3 мая и 18 октября была оплата ровно 64 уроков у двух разных учеников?
<li>Выводы по 2 визуализации (изменение балансов всех учеников):</li>
1. Пройденные уроки и покупки показывают планомерный рост, причем транзакции растут большими темпами, что положительно сказывается на балансе (синяя шкала), который также планомерно растет. 
2. Из этого следует вывод об успешности кампаний либо по привлечению учеников, либо по их удержанию (возможно и той и той)
3. На графике видны всплески активности (баланса) учеников – это весна и осень. В течение лета хоть и наблюдается рост, но менее выраженный. По-видимому, это связано с сезонностью учебного года.
4. п. 3. также может говорить о том, что основные ученики - школьники и студенты, что проверяется по данным учеников. Соответственно, возможно расширение клиентской базы за счет других групп людей.
5. Касательно прохождения уроков (CL_SUM) мы явно видим, что в выходные и праздничные дни ученики занимаются менее активно, что особенно заметно в мае - 1-го и 8-го числа (праздничные дни)
6. При этом транзакции в выходные и праздничные дни также происходят значительно реже (например 30-го января, 7, 8-го мая оплат вообще не было)
7. К концу года на балансе студентов осталось 4534 урок, т.е. студентам было начислено больше уроков, чем было пройдено. Что может говорить о том, что много учеников к концу года забросило обучение.


<ol>


</ol>

## Контактная информация
- Email: analysis.legalis@gmail.com
- LinkedIn: https://www.linkedin.com/in/%D0%B0%D0%BB%D0%B5%D0%BA%D1%81%D0%B0%D0%BD%D0%B4%D1%80-%D0%B1%D0%BE%D1%80%D0%B8%D1%81%D0%B5%D0%BD%D0%BA%D0%BE-b97386275/

