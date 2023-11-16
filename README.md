# Портфолио: аналитик данных

## Обо мне 
Привет! Меня зовут Ольга, я начинающий аналитик данных. 
В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>


## Навыки и технологии
- Инструменты анализа данных: ``SQL``, ``Excel``: 
- Языки программирования и библиотеки: --
- Системы управления базами данных: ``PostgreSQL``
- Средства визуализации данных: --
- Инструменты для машинного обучения: --


## Проекты

<p> Проект 1: Калькулятор юнит-экономики онлайн-кинотеатра</p>

<p> Инструмент - Excel.</p>

<p>Что нужно было сделать:<p>
<ol>
  <li>Задача №1. Посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25%-ную маржинальность.</li>
  <li>Задача №2. Собрать визуализации основных бизнес-показателей.</li>
   <li>Задача №3. Собрать калькулятор юнит-экономики продукта.</li>
</ol>

<p>Как решала(-а): Определила, что является юнитом в нашей бизнес-модели. Посчитала юнит-экономику продукта и предложила сценарий по настройке параметров для выхода на 25%-ную маржинальность. Выбрала оптимальный вариант расчета Retention. Собрала визуализации основных бизнес-показателей. Исследовала данные о пользователях и их поведении.<p>

> <a href="https://github.com/Olga-Gud/data-analytics-projects/blob/main/%D0%AE%D0%BD%D0%B8%D1%82-%D1%8D%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B8%D0%BA%D0%B0%20%D0%BE%D0%BD%D0%BB%D0%B0%D0%B9%D0%BD-%D0%BA%D0%B8%D0%BD%D0%BE%D1%82%D0%B5%D0%B0%D1%82%D1%80%D0%B0.xlsx">Ссылка на проект</a>
  
<p>Выводы (итоги):<p>
<ol>
  <li>Затраты на привлечение одного пользователя (CAC) оказались больше, чем выручка, которую он нам приносит (LTR).</li>
  <li>Наиболее активно пользователи просматривают фильмы в вечернее время. С 6 до 8 вечера – наиболее активный временной промежуток.</li>
  <li>На выходные дни недели – субботу и воскресенье – приходится больше всего просмотров среди недели. Но количество всех просмотров в будние дни превышает общее количество просмотров в выходные дни. </li>
  <li>Также больше чем в два раза просмотров в летний период, чем в весенний.</li>
  <li>Чтобы покрыть половину всех просмотров, нужно взять 73 самых популярных фильма.</li>
</ol>
<br> 

<br> 

<p>Проект 2: Моделирование изменения балансов студентов</p> 

<p>Инструмент - SQL.</p> 

<p>Что нужно было сделать:<p>
<ol>
  <li>Задача №1. Смоделировать изменение балансов студентов. Получить запрос, который собирает данные о балансах студентов за каждый "прожитый" ими на платформе день.</li>
  <li>Задача №2. Собрать визуализацию и сделать выводы из получившегося результата.</li>
   <li>Задача №3. Проверить, всё ли в порядке с данными, составить список гипотез и вопросов к дата-инженерам. </li>
</ol>

<p>Как решала(-а): Узнала, когда была первая транзакция для каждого студента. Узнала, за какие даты имеет смысл собирать баланс для каждого студента, то есть все даты жизни студента после того, как произошла его первая транзакция. Нашла все изменения балансов, связанные с успешными транзакциями – сколько уроков было начислено или списано в этот день. Нашла баланс студентов, который сформирован только приобретением уроков. Нашла баланс студентов, который сформирован только прохождением уроков. Создала запрос с вычисленными балансами для каждого студента. Посмотрела, как менялось общее количество уроков на балансах студентов.<p>

> <a href="https://github.com/Olga-Gud/data-analytics-projects/blob/main/%D0%9C%D0%BE%D0%B4%D0%B5%D0%BB%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B1%D0%B0%D0%BB%D0%B0%D0%BD%D1%81%D0%BE%D0%B2%20%D1%81%D1%82%D1%83%D0%B4%D0%B5%D0%BD%D1%82%D0%BE%D0%B2.xlsx">Ссылка на проект</a>
 
 <p>Выводы (итоги):<p>
<ol>
  <li>Общая тенденция развития бизнесса положительная, т. е. бизнесс прогрессирует. К концу года по сравнению с началом года наблюдается планомерный рост, уроков покупают все больше.</li>
  <li>Уроки чаще покупают в будние дни, чем в выходные. В 2016 году больше всего покупок приходилось на начало недели, в особенности на понедельник. Часто покупка уроков приходится на начало или конец месяца.</li>
 <li>Чаще пользователи смотрят уроки также по будням, по выходным это число в два раза меньше. Активнее уроки начинают смотреть со второй половины месяца. К концу месяца это число только растет.</li>
 <li>На последний день года баланс по всем пользователям составил 4534 непройденных урока. Почему так могло произойти? Возможно не хватает учителей, и уроки копятся быстрее, чем проводятся. Возможно темы уроков сложные/неитересные, или плохо подан материал, поэтому у пользователей есть трудности с просмотром и выполнением заданий, например. Возможно слишком короткие дедлайны, и студенты не успевают выполнять задания в срок. Вероятно многие пользователи совмещают учебу с работой, это также может быть причиной накапливания уроков.</li>
 <li>А может быть проводилась какая-то акция, распродажа, и часть уроков была приобретена в этот период, поэтому студенты не спешат смотреть такие уроки.</li>
 

  
</ol>

## Контактная информация
- Email: aloha.010997@gmail.com
