# Amazon Affiliate Platform - Supabase

Amazon Affiliate Marketing Platform migrated to Supabase with Docker deployment.

## Overview

This project is a modern affiliate marketing platform built with Supabase as the backend. It enables users to manage Amazon affiliate links, track conversions, and optimize marketing campaigns.

## Tech Stack

- **Backend**: Supabase (PostgreSQL + Authentication + Storage + Edge Functions)
- **Deployment**: Docker
- **Repository**: [GitHub](https://github.com/Gustavoov22/amazon-affiliate-platform-supabase)

## Prerequisites

- Node.js (v18+ recommended)
- Docker and Docker Compose
- A Supabase account and project

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Gustavoov22/amazon-affiliate-platform-supabase.git
cd amazon-affiliate-platform-supabase
```

### 2. Environment Variables

Create a `.env` file in the root directory with the following variables:

```env
PUBLIC_KEY=your_supabase_publishable_key
URL=your_supabase_url
```

> **Note**: Never commit your `.env` file to version control. It's already included in `.gitignore`.

### 3. Install Dependencies

```bash
npm install
```

### 4. Run Locally

```bash
npm run dev
```

## Project Structure

```
amazon-affiliate-platform-supabase/
├── src/           # Application source code
├── docs/          # Documentation
├── .env           # Environment variables (not committed)
├── .gitignore     # Git ignore rules
└── README.md      # This file
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is private and proprietary.

## Contact

For questions or support, please open an issue on GitHub.
