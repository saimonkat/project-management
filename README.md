# Project management

## Развертка нового проекта

1. Зарегать проект в хабе, добавить всех разрабов и начать трекать
2. Создать папку проекта в закладках браузера для всех ссылок
3. Добавить туда макеты и drafts-копию
4. Создать [новый](https://bitbucket.org/repo/create) гит пеозиторий, добавить всех причастных
5. Зарегистрирвать [домен](https://cp.beget.com/domains) и создать [FTP-доступы](https://cp.beget.com/ftp), проверить их
6. Создать чат в телеграм **Проект "ProjectName" / DEV** со всеми причастными, создать иконку чата, добавить чат в папку проектов, включить реакции, дать админ-права кому нужно
  
    ![image](https://user-images.githubusercontent.com/22715126/140881250-318ef022-872f-4e4a-96c0-47a13fb6fbf0.png)
 
7. Собрать все ссылки в папке закладок браузера, все доступы в txt-файле и в закрепе в чате:  
    **ДОСТУПЫ**  
    Домен  
    onepix  
    close_index
  
    ТЗ и оценка:
  
    Макеты:
  
    FTP/SFTP:
  
    GIT:
8. Создать папку проекта в папке "Проекты" и сохранить ярлык на рабочем столе
9. Скачать нулевую версию WP из [регламента по бэку](https://github.com/dev-kick/wp-theme-rules)
10. Выбрать один из сборщиков из [регламента по фронту](https://github.com/saimon322/frontend-builder-rules) и добавить его в папку assets
11. Установить в папке фронтенда модули и собрать проект
12. Создать новый сайт в FileZilla Site Manager, подключиться и загрузить файлы папки dist фронтенда
13. Запушить собранный проект в гит
14. Закрыть сайт от индексации
  - папка libs/close_index
  - обновить домен в .httacess
15. Добавить сайт в [таблицу серверов](https://docs.google.com/spreadsheets/d/1pjO0auYLbv7Voc-9YABIZUMxmMVH9hXv67iHFQfluS4/edit#gid=0)

## Отчет заказчику

Добрый день, Thomas!
Собрали промежуточный отчет за прошедшую неделю (подскажите, будет ли удобно дальше также получать отчеты по понедельникам?)

Закончили верстку двух страниц с адаптивом: 
Главную и О мясе. Также с сегодняшнего дня уже начали параллельно интеграцию на WordPress.. Все ссылки и доступы отправляю сообщением ниже, чтобы закрепить.

Хотел бы сразу уточнить что верстка еще не протестирована до конца, где-то возможны баги или отклонения от макетов. Полное тестирование проводим по завершению всего этапа фронтенда обычно.

---

Тестовый домен (WordPress):  
https://tomaso.one-pix.ru/

Верстка с навигацией по страницам:  
https://tomaso.one-pix.ru/wp-content/themes/tomaso/assets/dist/index.html

Авторизация для доступа к сайту:  
onepix  
close_index

WP админ-панель:  
https://tomaso.one-pix.ru/wp-login  
admin  
1234554321
