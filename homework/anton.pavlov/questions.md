1. user-service.ts - line: 31 - при отправке подобного запроса я получаю: POST http://test-api.javascript.ru/v1/tonyp/users 400 (Bad Request)
2. user-card-list.component.ts - line: 33 - выдаётся ошибка следующего содержания: ERROR HttpErrorResponse {headers: HttpHeaders, status: 200, statusText: "OK", url: "http://test-api.javascript.ru/v1/tonyp/users/59f1cae6adc7813304e7683b", ok: false, …} - при этом запись из базы удаляется, но subscribe не срабатывает и страница не обновляется