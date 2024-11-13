---
date: 2024-11-01
draft: false
params:
    author: Jérémie
title: Run Postgres everywhere
tags:
    - Postgres
    - Database
weight: 10
---

> TL;DR :
>
> PGlite is an in-browser Postgres database (WASM-based) that’s perfect for full-stack devs needing local-first data handling, offline support, or fast prototyping without external databases. It runs in JavaScript runtimes like NodeJS and Deno, supports Postgres extensions, and even offers live query updates. Great for caching, testing, and fast data access in client-side apps.

## Run Postgres everywhere

As full-stack developers, we often find ourselves juggling databases across different environments and use cases, especially when building offline-friendly, data-intensive apps. Enter PGlite—a WASM-based, in-browser Postgres database that runs in environments like NodeJS, Deno, BUN, and even directly in the browser. PGlite offers the flexibility to run a local Postgres instance right where the user is, and it includes powerful extensions like PostGIS and pgvector for spatial and vector-based data.

### Why Use PGlite ?

**Local First Apps**: PGlite is perfect for "Local First" applications, providing near-instant data access and syncing with remote databases in the background. This makes it ideal for apps that require offline support or fast response times.

**Prototyping and Testing**: Quickly prototype with SQL directly in TypeScript, skipping the setup of external databases. For testing in CI pipelines, PGlite can serve as an embedded database, eliminating the need for containerized setups.

**Local Data Caching**: For data-heavy applications, PGlite can act as a local cache, reducing the need for frequent remote API calls and minimizing latency.

### Getting Started

Using PGlite is as simple as installing the `@electric-sql/pglite` package, and you’re ready to execute SQL commands right in your JavaScript runtime. Need live updates? You can even subscribe to "live queries" for real-time data monitoring.

For a quick test, check out the [pglite.dev playground](https://pglite.dev/repl/), which lets you play with a PGlite database right in your browser.

If you’re looking for a flexible, easy-to-use solution for local data handling in your projects, PGlite is definitely worth exploring!

## Ressources

-   [PGlite - run Postgres everywhere](https://buttondown.com/entbit/archive/pglite-run-postgres-everywhere/)
-   [PGlite.dev](https://pglite.dev/)
-   [PGlite GitHub Repository](https://github.com/electric-sql/pglite)
