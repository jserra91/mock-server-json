# 1. Instalación

npm install -g json-server

# 2. Utilización

json-server --watch db.json

Abrir navegador web -> http://localhost:3000/

# 3. Paginación

Use `_page` and optionally `_limit` to paginate returned data.

In the `Link` header you'll get `first`, `prev`, `next` and `last` links.

```
GET /pagination?_page=7
GET /pagination?_page=7&_limit=20
```

_10 items are returned by default_

# 4. Readme Oficial

README_OFICIAL.md
