# Real-Money Gambling MVP

Compliance-first starter architecture for a licensed gambling operator.

This is a development scaffold, not a licensed gambling product. Before accepting real wagers, connect approved KYC, payment, geolocation, AML, responsible-gambling, and game-certification providers appropriate to the jurisdiction.

## Stack
- Next.js + React + TypeScript
- Fastify + Node.js + TypeScript
- Prisma + PostgreSQL
- Redis-ready architecture
- Docker Compose

## Run
1. Copy `.env.example` to `.env`.
2. Run `docker compose up -d postgres redis`.
3. Install dependencies with `npm install`.
4. Run Prisma migration/generate.
5. Start the API and web apps.

The included roulette engine is a non-production demonstration. Do not use it for real-money play without the testing/certification and controls required by the applicable regulator.
