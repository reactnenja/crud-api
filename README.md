# A Collaborative Todo Sample - ZenStack + Next.js

This project is a collaborative todo app built with [Next.js](https://nextjs.org), [Next-Auth](nextauth.org), and [ZenStack](https://zenstack.dev).

In this fictitious app, users can be invited to workspaces where they can collaborate on todos. Public todo lists are visible to all members in the workspace.

See a live deployment at: https://zenstack-todo.vercel.app/.

## Features:

-   User signup/signin
-   Creating workspaces and inviting members
-   Data segregation and permission control

## Running the sample:

1. Setup a new PostgreSQL database

    You can launch a PostgreSQL instance locally, or create one from a hoster like [Supabase](https://supabase.com). Create a new database for this app, and set the connection string in .env file.

1. Install dependencies

    ```bash
    npm install
    ```

1. Generate server and client-side code from model

    ```bash
    npm run generate
    ```

1. Synchronize database schema

    ```bash
    npm run db:push
    ```

1. Start dev server

    ```bash
    npm run dev
    ```

For more information on using ZenStack, visit [https://zenstack.dev](https://zenstack.dev).
