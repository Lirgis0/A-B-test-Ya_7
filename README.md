# A-B-test-Ya_8
Проведение и исследование результатов  A/B теста

# Язык комментариев / Language
Русский / Russian

# Описание проекта:
Вы — аналитик крупного интернет-магазина. Вместе с отделом маркетинга вы подготовили список гипотез для увеличения выручки.
Приоритизируйте гипотезы, запустите A/B-тест и проанализируйте результаты. 

# Данные:
Файл /datasets/hypothesis.csv.  
Hypothesis — краткое описание гипотезы;  
Reach — охват пользователей по 10-балльной шкале;  
Impact — влияние на пользователей по 10-балльной шкале;  
Confidence — уверенность в гипотезе по 10-балльной шкале;  
Efforts — затраты ресурсов на проверку гипотезы по 10-балльной шкале. Чем больше значение Efforts, тем дороже проверка гипотезы.  
Файл /datasets/orders.csv.  
transactionId — идентификатор заказа;  
visitorId — идентификатор пользователя, совершившего заказ;  
date — дата, когда был совершён заказ;  
revenue — выручка заказа;  
group — группа A/B-теста, в которую попал заказ.  
Файл /datasets/visitors.csv.  
date — дата;  
group — группа A/B-теста;  
visitors — количество пользователей в указанную дату в указанной группе A/B-теста  

# Задача
Приоритизируйте гипотезы, запустите A/B-тест и проанализируйте результаты. 

# Используемые библиотеки
pandas
numpy
matplotlib
scipy.stats
