# Dashboard-by-user-events
*Создание дашборда по пользовательским событиям для агрегатора новостей*   
Основные задачи:   
1. Подключение к удаленной базе данных;
2. Выгрузка данных из таблицы;
3. Передача данных для загрузки в Tableau;
4. Построение графиков и дашборда в Tableau;
5. Оформление результатов в презентации.   

Ссылка на дашборд: 
https://public.tableau.com/app/profile/guzal3734/viz/project_automation_ChukhlebovaGR/project_automation_ChukhlebovaGR?publish=yes

## Описание проекта
| **Название проекта** | **Описание** | **Используемые библиотеки** |
| :-------------------- | :-------------------- |:--------------------|
|Создание дашборда по пользовательским событиям для агрегатора новостей|Работу над этим проектом я провела на удаленной машине в сервисе Yandex.Cloud. Мной был установлен PostgreSQL, развернута база данных. Затем я написала скрипт пайплайна, который позволил собирать данные за определенный временной период, и настроила его автономную работу через crontab. Для визуализации собранных данных я написала скрипт дашборда с несколькими фильтрами и также запустил его на удаленной машине. По результатам была подготовлена презентация с полученными графиками. | *SQLAlchemy PostgreSQL dash Tableau* |

