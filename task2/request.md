# Пример REST API запроса

Метод: `GET`  
Эндпоинт: `/api/v1/partners/stores`  
Заголовки (опционально): `Authorization: Bearer <token>`

Пример вызова (cURL):
```bash
curl -X GET https://api.petrushka-green.ru/api/v1/partners/stores \
  -H "Authorization: Bearer your_token_here"
