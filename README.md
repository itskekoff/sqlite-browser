SQLite Viewer
============


Браузер для sqlite3 файлов. За основу взят [SQLite Viewer](https://github.com/inloop/sqlite-viewer) от inloop

*Использует [sql.js](https://github.com/sql-js/sql.js/) для парсинга sqlite файлов.*


Можно добавлять файлы с сервера (используя ajax JS, удаленный сервер должен отправить `Access-Control-Allow-Origin:*`):
`http://itskekoff.github.io/sqlite-browser/?url=http://example.com/data.sqlite`


![](/img/preview.png?raw=true "Example sqlite")


### Лицензия
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
    http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
