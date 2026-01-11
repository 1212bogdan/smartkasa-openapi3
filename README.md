# SmartKasa OpenAPI Specification

[![OpenAPI Version](https://img.shields.io/badge/OpenAPI-3.1.0-green.svg)](https://spec.openapis.org/oas/v3.1.0)
[![License](https://img.shields.io/badge/License-Proprietary-blue.svg)](https://www.smartkasa.ua/wp-content/uploads/2025/03/ukrtrimeks-api-integracziya.pdf)

[English](#english) | [Українська](#ukrainian)

---

## <a name="english"></a>English

This repository contains the **OpenAPI 3.1.0** specification for the [SmartKasa API](https://smartkasa.docs.apiary.io/) - a Ukrainian fiscal cash register and point-of-sale management system.

### 📋 About SmartKasa API

SmartKasa provides a comprehensive REST API for managing:
- **Authentication** - User sessions and authorization
- **Terminals** - POS terminal configuration and management
- **Shops** - Retail location management
- **Employees** - Staff and permissions management
- **Units of Measure** - Reference data for product units
- **Categories** - Product catalog categories
- **Products** - Product catalog and pricing
- **Inventory Cards** - Stock tracking and management
- **Product Subgroups** - Product classification
- **Import** - Batch operations for products and categories
- **Shifts** - Fiscal and trade shifts management
- **POS Operations** - Receipts, payments, and transactions
- **Reports** - Sales reports, X-reports, and Z-reports

### 🔗 Base URL

```
https://core.smartkasa.ua
```

### 🔐 Authentication

The API uses API Key authentication:
- **API Key** (`X-API-KEY` header) - Required for all requests

For requests that require user authorization, an additional `Authorization` header must be present (obtained via `/api/v1/auth/sessions`).

### 📄 API Specification Files

- **JSON**: [`openapi.json`](./openapi.json)
- **YAML**: [`openapi.yaml`](./openapi.yaml)

### 📖 Documentation

- **Total Endpoints**: 56
- **API Version**: 1.0.18
- **OpenAPI Version**: 3.1.0

### 📦 Original Format

This specification is also available in [API Blueprint](https://smartkasa.docs.apiary.io/api-description-document) format.

### 📄 License

This OpenAPI specification is provided for integration and development purposes. Please refer to [SmartKasa API Integration Rules](https://www.smartkasa.ua/wp-content/uploads/2025/03/ukrtrimeks-api-integracziya.pdf) for API usage policies.

---

## <a name="ukrainian"></a>Українська

Цей репозиторій містить **OpenAPI 3.1.0** специфікацію для [SmartKasa API](https://smartkasa.docs.apiary.io/) - української системи управління фіскальними касовими апаратами та точками продажу.

### 📋 Про SmartKasa API

SmartKasa надає комплексний REST API для управління:
- **Авторизація** - Сесії користувачів та авторизація
- **Термінали** - Налаштування та управління POS терміналами
- **Торгові точки** - Управління локаціями роздрібної торгівлі
- **Працівники** - Управління персоналом та правами доступу
- **Одиниці виміру** - Довідник одиниць виміру товарів
- **Каталоги** - Категорії товарів
- **Товари** - Каталог товарів та ціни
- **Облік товарів** - Облік та управління запасами
- **Товарні підгрупи** - Класифікація товарів
- **Імпорт** - Масові операції з товарами та категоріями
- **Зміни** - Управління фіскальними та торговими змінами
- **POS операції** - Чеки, платежі та транзакції
- **Звіти** - Звіти про продажі, X-звіти та Z-звіти

### 🔗 Базова URL

```
https://core.smartkasa.ua
```

### 🔐 Аутентифікація

API використовує аутентифікацію через API Key:
- **API Key** (заголовок `X-API-KEY`) - Обов'язковий для всіх запитів

Для запитів які потребують авторизації користувача повинен бути наявним додатково заголовок `Authorization` (отримується через `/api/v1/auth/sessions`).

### 📄 Файли специфікації API

- **JSON**: [`openapi.json`](./openapi.json)
- **YAML**: [`openapi.yaml`](./openapi.yaml)

### 📖 Документація

- **Всього Endpoints**: 56
- **Версія API**: 1.0.18
- **Версія OpenAPI**: 3.1.0

### 📦 Оригінальний формат

Також ця специфікація доступна в форматі [API Blueprint](https://smartkasa.docs.apiary.io/api-description-document).

### 📄 Ліцензія

Ця OpenAPI специфікація надається для цілей інтеграції та розробки. Будь ласка, зверніться до [Правил інтеграції SmartKasa API](https://www.smartkasa.ua/wp-content/uploads/2025/03/ukrtrimeks-api-integracziya.pdf) щодо політики використання API.
