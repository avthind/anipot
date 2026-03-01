# anipot
> Intelligent Anime Discovery Platform

A full-stack anime discovery and review platform where users can find new shows, track what they're watching, and get AI-powered recommendations tailored to their taste.

## What is this?

anipot is built around the idea that finding your next favourite anime shouldn't require scrolling through Reddit threads. It uses OpenAI embeddings and vector similarity search to understand what a user actually enjoys — based on their watchlist and ratings — and surfaces genuinely relevant recommendations, not just "most popular this season."

Beyond discovery, it's a complete platform: user profiles, watchlists, reviews, and a trending analytics dashboard. Redis caching keeps the experience fast, and the infrastructure is deployed cloud-native on AWS.

## Core Features

- [ ] User auth, profiles, and watchlists
- [ ] Anime catalog with search and filters
- [ ] AI recommendation engine (embeddings + vector similarity)
- [ ] Review and rating system
- [ ] Trending analytics dashboard
- [ ] Redis caching layer
- [ ] Cloud deployment on AWS S3 and EC2

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js 14, TypeScript, Tailwind CSS |
| Backend | Node.js, Express, Prisma |
| AI | OpenAI embeddings, pgvector |
| Database | PostgreSQL |
| Caching | Redis |
| Infra | AWS S3, EC2, Docker, GitHub Actions |
