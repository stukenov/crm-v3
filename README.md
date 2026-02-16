# CRM System - Version 3

A refined Customer Relationship Management system maintaining the full-featured architecture of V2 with stability improvements and optimizations.

## Description

Version 3 continues the mature CRM architecture introduced in V2, focusing on stability, performance optimizations, and refinement of the Contact-Deal-Interaction model. This version maintains the same feature set while improving code quality and user experience.

## Tech Stack

- **Backend**: Laravel 11.9 (PHP 8.2+)
- **Frontend**: Livewire 3.0
- **UI**: Tailwind CSS
- **Authentication**: Laravel Jetstream 5.1 with Livewire
- **API**: Laravel Sanctum 4.0 for API authentication
- **Database**: SQLite/MySQL/PostgreSQL support
- **Build Tool**: Vite 5

## Key Features

- **Contact Management**: Complete CRUD operations for customer contacts
- **Deal Pipeline**: Track deals through various stages with amount tracking
- **Deal Stages**: Multi-stage deal progression system
- **Interactions**: Record and track all customer interactions
- **Contact Groups**: Organize contacts into groups with relationship management
- **User Assignment**: Assign deals and contacts to team members
- **Team Management**: Multi-user support with Jetstream teams
- **API Authentication**: Secure API access with Sanctum tokens
- **Real-time Updates**: Livewire-powered reactive UI

## Installation

1. Clone the repository:
```bash
git clone https://github.com/stukenov/crm-v3.git
cd crm-v3
```

2. Install dependencies:
```bash
composer install
npm install
```

3. Setup environment:
```bash
cp .env.example .env
php artisan key:generate
touch database/database.sqlite
```

4. Initialize database:
```bash
php artisan migrate
```

5. Build and serve:
```bash
npm run build
php artisan serve
```

## Development

```bash
npm run dev
```

In a separate terminal:
```bash
php artisan serve
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Copyright (c) 2025 Saken Tukenov

## Development Timeline

This is Version 3 (August 2024) - Stability and optimization release maintaining V2 architecture.
