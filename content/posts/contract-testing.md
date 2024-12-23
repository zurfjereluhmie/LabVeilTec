---
date: 2024-11-14
draft: false
params:
    author: Jérémie
title: Simple approach to contract testing
cover:
    image: https://blog.appsignal.com/_next/image?url=%2Fimages%2Fblog%2F2024-11%2Fstreamlining-contract-testing.jpg&w=1920&q=50
tags:
    - Testing
    - Web development
    - Back-end
    - Robustness
weight: 10
---

> TL;DR :
>
> Contract testing is a simple way to ensure that your services communicate correctly with each other. By defining and testing the contracts between services, you can catch integration issues early and avoid costly bugs in production.

### Why contract testing is important

Contract testing is ensure seamless communication between different parts of an application. It involves verifying that interactions between services adhere to predefined agreements, or "contracts," which specify the expected inputs and outputs. This approach is particularly beneficial in complex systems where multiple services interact, as it helps identify integration issues early in the development process.

#### Simple approach to contract testing

The author presents a simplified method that doesn't require extensive infrastructure changes, making it accessible for individual developers to adopt. By utilizing tools like Jest for testing and Axios for HTTP requests, developers can set up contract tests that validate API interactions against predefined JSON schemas.

### When will I need this

I will need this when I start working on a new project that involves multiple services communicating with each other. By implementing contract testing early in the development process, I can ensure that my services are compatible and that any changes to one service do not break the contract with another.

## Ressources

-   [Streamlined Contract Testing in Node.js: A Simple and Achievable Approach](https://blog.appsignal.com/2024/11/13/streamlined-contract-testing-in-nodejs-a-simple-and-achievable-approach.html)
