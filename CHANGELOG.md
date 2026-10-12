# Изменения

## 0.1.0 — 2026-10-12

- HTTP-сервис `bilem`: `GET /whoami` (токен в заголовке `X-Bilem-Token`), `POST /mcp/{token}` — MCP (JSON-RPC 2.0, Streamable HTTP без SSE).
- Инструмент MCP `whoami`: пользователь 1С, организация, версии конфигурации, платформы и расширения.
- Роль `Bilem_Агент`, константа `BilemТокен`.
