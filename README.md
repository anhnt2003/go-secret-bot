TeleVault is a personal password manager built as a learning project around secure secret storage and modern infrastructure tools.

It uses:
- **Golang** for the backend services and Telegram bot
- **HashiCorp Vault** to store and encrypt secrets
- **Consul** for service discovery / storage backend for Vault (optional)
- **PostgreSQL / SQLite** for user and metadata management
- **Telegram Bot** as the main user interface

With TeleVault you can:
- Securely store passwords and notes per service/account
- Add, retrieve, list, and delete secrets directly from Telegram commands
- Isolate access via Vault policies and tokens
- Enable basic safety features like PIN verification and audit logging

