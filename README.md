# Skipper NDT's web application

## Pre-commit setup

```bash
python3.11 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
pre-commit install
```


This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.


# AdonisJS Slim Starter Kit

This repo contains the smallest possible AdonisJS application with the framework core and the Japa test runner. You can clone this repo to start from a clean state and configure new packages as needed.

## What's included

- TypeScript setup with commands to run the development server using `ts-node + swc` and create a production build.
- ESLint and Prettier setup extending the [AdonisJS tooling config](https://github.com/adonisjs/tooling-config) presets.
- Ace command line framework
- Everything else you get with the core of AdonisJS.

## Usage

By executing the following command, you can create a new app using the `slim` starter kit. The command will perform the following steps.

- Download the repo
- Install dependencies
- Copy `.env.example` to `.env`
- Set the app key using the `node ace generate:key` command.

```sh
npm init adonisjs@latest hello-world -- -K=slim
```


# boilerplate_next_adonis_traefik
# sveltekit-adonis
