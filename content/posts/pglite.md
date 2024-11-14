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

### When will I need this

This module will be useful to me in situations where I need quick, reliable data handling without the overhead of a remote database.
**But**, as this is only in the innovative stage, I will keep an eye on it and test it when it is more mature.

## Ressources

-   [PGlite - run Postgres everywhere](https://buttondown.com/entbit/archive/pglite-run-postgres-everywhere/)
-   [PGlite.dev](https://pglite.dev/)
-   [PGlite GitHub Repository](https://github.com/electric-sql/pglite)
