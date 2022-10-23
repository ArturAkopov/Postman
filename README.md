# Примеры запросов в Postman к https://dummyapi.io/:
POST-для создания нового пользователя
![](https://github.com/ArturAkopov/Postman/blob/c379273ddd6d048c630cc20eea0fda6626050f03/POST%201.png)
GET-для получения полных данных пользователя по идентификатору пользователя
![](https://github.com/ArturAkopov/Postman/blob/f8619201e4d6201e62e8eea814108d7ba5fa0ad1/GET%201.png)
DELETE-удалить пользователя по идентификатору, вернуть идентификатор удаленного пользователя
![](https://github.com/ArturAkopov/Postman/blob/4ec6c115b644515a5004767a0ebbb49d73685902/DELETE.png)
PUT-для обновления пользователя по идентификатору, вернуть обновленные пользовательские данные
![](https://github.com/ArturAkopov/Postman/blob/4ec6c115b644515a5004767a0ebbb49d73685902/PUT+BAG.png)
Как мы видим, из запроса PUT, обновление фамилии прошло успешно, что противоречит требованиям из скриншота ниже
![](https://github.com/ArturAkopov/Postman/blob/0c13cfa71486dd6d64f5c0bf72a6e7841d13c43e/Bag%201.png)
Следовательно оформляем баг-репорт, в нашем случае в Redmine
![](https://github.com/ArturAkopov/Postman/blob/0c13cfa71486dd6d64f5c0bf72a6e7841d13c43e/BAG%202.png)
