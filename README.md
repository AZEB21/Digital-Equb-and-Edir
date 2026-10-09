# Digital Equb and Edir Manager

A TypeScript backend for managing equb (rotating savings) and edir (community support funds) groups, which are often run on paper or Telegram chats, where missed payments and unclear payout order cause disputes.

## Features
- Create equb and edir groups with custom contribution rules
- Manage members and record contributions (paid, unpaid, late)
- Equb payout rounds with random draw or manual order
- Edir claim submission and approval
- Group summaries and per-member statements

## Tech Stack
TypeScript (strict mode), Node.js, Express, Zod, JSON storage (SQLite/Postgres planned)

## Highlights
- Discriminated unions for typed API responses and group types
- Generic `Repository<T>` data layer
- Zod schemas as the single source of truth for validation and types

## Getting Started
    git clone https://github.com/<your-username>/equb-edir-manager.git
    cd equb-edir-manager
    npm install
    npm run dev

## Roadmap
Telebirr integration, SMS reminders, Ethiopian calendar support, Amharic localization

## Author
Azeb Yirga
