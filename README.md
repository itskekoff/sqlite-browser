SQLite Viewer
============


Браузер для sqlite3 файлов. За основу взят [SQLite Viewer](https://github.com/inloop/sqlite-viewer) от inloop
*Использует [sql.js](https://github.com/sql-js/sql.js/) для парсинга sqlite файлов.*
Можно добавлять файлы с сервера (используя ajax JS, удаленный сервер должен отправить `Access-Control-Allow-Origin:*`):
`http://itskekoff.github.io/sqlite-browser/?url=http://example.com/data.sqlite`

