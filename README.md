Backend for Posterr (https://github.com/Kasmadei/Postter)
Author (https://github.com/maxfarseer)

## First start
1. Clone this repo
  ```
  git clone https://github.com/Kasmadei/Postter_backend.git
  ```
2. Add clientID.

_backend/config/env/common.js_

```
...
google: {
  clientID: "ВАШ_ID_ЗДЕСЬ" // остальные поля конфига не трогайте
}
...
```

## Start with Docker


1. [Download and install docker](https://store.docker.com/).
2. Comand line:
   ```
   cd backend-tz3 
   docker-compose up
   ```

## Swagger UI

After Docker start, you can use swagger to see endpoints.
```
go: localhost
```
