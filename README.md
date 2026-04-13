# db-portal

Docker MySQL + phpMyAdmin para hospedagem dedicada Locaweb.

## Servicos

- **MySQL 8.0** - Banco de dados (porta 3306)
- **phpMyAdmin** - Interface web de gerenciamento (porta 8080)

## Configuracao

1. Copie o `.env.example` para `.env` no servidor
2. Ajuste as variaveis de ambiente no `.env`
3. Execute `docker compose up -d`

## Acesso phpMyAdmin

Acesse via `http://SEU_IP:8080`
