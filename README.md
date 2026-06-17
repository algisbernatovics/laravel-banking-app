# Laravel Banking App

An educational Laravel internet banking demo with authentication, accounts, currencies, transactions, and screenshots of the user flow.

## Overview

Laravel Banking App is a full-stack demo built to practice Laravel application structure, authenticated user flows, account balances, currency conversion, cryptocurrency interactions, and transaction-oriented workflows.

## Features

- User authentication and protected banking flows.
- Account and transaction-oriented Laravel structure.
- Currency conversion using the [Latvijas Banka API](https://www.latvijasbanka.lv/vk/ecb.xml).
- Cryptocurrency-related data using the [CoinMarketCap API](https://pro-api.coinmarketcap.com/v1/).
- Tailwind/Laravel Mix/Vite-era frontend assets.
- Multiple screenshots for quick review.

## Tech Stack

- PHP
- Laravel
- Composer
- Laravel Fortify
- Laravel Sanctum
- Tailwind CSS
- MySQL/PostgreSQL-compatible Laravel database layer
- External currency and crypto APIs

## Getting Started

Install dependencies and configure the app:

```bash
composer install
npm install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm run dev
php artisan serve
```

Configure database credentials and API keys in `.env`, including any required CoinMarketCap values.

Open the app locally at the URL shown by Laravel, commonly `http://localhost:8000`.

## Project Structure

- `app/` - Laravel application logic
- `routes/` - web routes
- `resources/` - Blade views and frontend assets
- `database/` - migrations/seeders
- `1.png ... 13.png` - portfolio screenshots

## Portfolio Notes

- One of the stronger full-stack portfolio projects in the account.
- Shows authentication, domain modeling, external API usage, and transaction-oriented workflows in Laravel.
- Screenshots make it easier to review without running the project locally.

## Status

Portfolio-ready Laravel application.

## License

MIT License. See [LICENSE](./LICENSE).
