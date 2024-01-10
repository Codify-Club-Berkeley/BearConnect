# Bear Connect

A platform for discovering student organizations at UC Berkeley.

# Setup

## Install dependencies:

```bash
pnpm install
```

If you don't have pnpm installed, check the [documentation](https://pnpm.io/installation)

## Set up the environment variables

Make a file called `.env` in the root directory of the project. Copy the contents of `.env.example` into it. Fill in the values for the environment variables (get them from Discord).

## Generate the Prisma client

```bash
pnpx prisma generate
```

## Start the development server

```bash
pnpm dev
```

# Tech Stack

This project uses the [T3 Stack](https://create.t3.gg/), which is a full-stack TypeScript framework for building web apps. It uses the following primary technologies:

- [Next.js](https://nextjs.org)
- [NextAuth.js](https://next-auth.js.org)
- [Prisma](https://prisma.io)
- [Tailwind CSS](https://tailwindcss.com)
- [tRPC](https://trpc.io)

We also use [shadcn ui](https://ui.shadcn.com/) for the UI components and tRPC's built in adapter for [React Query](https://react-query.tanstack.com/) for data fetching. The shadcn cli is already configured to work with this project, so it can be used to install new components instead of copy and pasting.

# Extensions

The recommended extensions for this project are bundled into the [Codify Extension Pack](https://marketplace.visualstudio.com/items?itemName=CodifyBerkeley.codify-extensions&ssr=false#overview). Install them in the marketplace to have the best developer experience.
