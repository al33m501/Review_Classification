# Review Classification
Работа доступна в Jupyter Notebook: **ML_Project.ipynb**

## Постановка задачи
Классификация отзывов о банке по категориям (ипотека, дебетовые карты, обслуживание юр лиц и т.д.)

Датасет собирался с сайта Banki ru самостоятельно, ноутбук со скрапингом доступен в Jupyter Notebook: **dataset_scraping.ipynb**

Обращаю внимание, что данную функцию можно переиспользовать, выбирать любой банк, любые категории, ограничивать количество загружаемых страниц с отзывами. Для примера был выбран банк Тинькофф

## Область Применения
Модель может применяться для классификации обращений в техническую поддержку с какими-либо вопросами и сложностями клиентов. Модель может предсказать вид услуг по тексту отзыва и сразу передать обращение нужному сотруднику, повысив КПД техподдержки.

Также, по имеющимся данным можно построить модель предсказания оценки, которую поставит пользователь по тексту его отзыва. Так можно отделять негативные упоминания банка в социальных сетях и оперативно реагировать на них. В автоматическом режиме, в виде 'уточните вашу проблему в личном сообщении'. Даже такое простое применение алгоритма может повысить лояльность всех тех, кто увидит сообщение в соц. сети.
