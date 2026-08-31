# AI Image Generator

An AI image generation app: authenticated users spend credits to generate images, with usage tracked server-side and synced via Clerk webhooks.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

## Stack

Next.js · Clerk (auth, via Svix-verified webhooks) · MongoDB/Mongoose · Tailwind CSS

## Running locally

```bash
npm install
npm run dev
```

Needs Clerk and MongoDB connection details in `.env`.
