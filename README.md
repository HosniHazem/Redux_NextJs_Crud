# Employee Directory — Next.js CRUD

An employee records application: list, create, edit and delete staff, with
state handled through Redux and side effects through Redux-Saga.

## What it does

- Paginated employee table
- Add and edit through a modal form, validated with React Hook Form
- Delete with confirmation
- Records persisted in MongoDB through Next.js API routes
- Redux-Saga mediates every API call, so loading and error state is handled in one place

## Stack

Next.js · Redux with Redux-Saga · next-redux-wrapper · Mongoose · React Hook Form · Sass

## Running locally

```bash
yarn install
yarn dev
```

Set `MONGO_URI` in `.env.local` to a MongoDB connection string.
