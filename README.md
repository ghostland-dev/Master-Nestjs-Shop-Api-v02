# NestJS Shop API (v2)

Second version of the e-commerce REST API: authentication, roles and a full order flow.

## Features

- JWT authentication with role-based guards
- Products, users and orders (commandes) modules
- Auth middleware and DTO validation
- Prisma data layer

## Tech Stack

- NestJS (TypeScript)
- Prisma ORM
- PostgreSQL
- Passport / JWT
- Jest for unit and e2e tests

## Getting Started

```bash
git clone https://github.com/ghostland-dev/nestjs-shop-api-v2.git
cd nestjs-shop-api-v2
npm install
cp .env.example .env   # then fill in your own values
npm run start:dev
```

Run the tests with `npm run test` and `npm run test:e2e`.

## Author

**Ismail.M**, Software Engineer & DevOps

- GitHub: [@ghostland-dev](https://github.com/ghostland-dev)
- Website: [ismail-mouyahada.com](https://www.ismail-mouyahada.com)
