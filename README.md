# Доска мемов (Meme Board) - Лабораторная работа №35

## Выполнение работы

**Студент:** Алексеев Григорий  
**Группа:** ИСП-232  
**Дата выполнения:** 31.03.226

## Описание проекта

Веб-приложение "Доска мемов" — это полнофункциональное SPA (Single Page Application), состоящее из:
- **Backend** на ASP.NET Core Web API
- **Frontend** на HTML + CSS + Vanilla JavaScript

Приложение позволяет просматривать, добавлять и удалять мемы с оценкой по категориям.


## Инструкция по запуску

### Требования

- [.NET SDK](https://dotnet.microsoft.com/download) (версия 6.0 или выше)
- [VS Code](https://code.visualstudio.com/) или другой редактор кода
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) (расширение для VS Code)

### Запуск Backend

1. Откройте терминал
2. Перейдите в папку с API:
 ```bash
   cd MemesApi
   dotnet run
```

### что изучили: 

| Концепция | Где используется |
|-----------|------------------|
| `fetch(url)` | GET-запрос к API |
| `fetch(url, { method, headers, body })` | POST и DELETE запросы |
| `response.ok` | Проверка успешности ответа |
| `response.json()` | Чтение JSON из ответа |
| `JSON.stringify(...)` | Объект JS → JSON-строка для отправки |
| `async / await` | Ожидание ответа от сервера |
| `try / catch / finally` | Обработка ошибок при fetch |
| `CORS` | Разрешение запросов между разными портами |
| `AddCors + UseCors` | Включение CORS в ASP.NET Core — два шага |