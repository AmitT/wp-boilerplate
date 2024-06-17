WP Boilerplate
===
A simple and helpful template for developing a new WordPress project. Git & Docker support.

Tested on:
---
- [Docker >= 26.1](https://www.docker.com).
- [Git >= 2.45](https://www.git-scm.com).

Features
---
- All files ignored exept those you actually should change in your theme.
- Docker containers configured and ready to use with WP latest version & MySQL.

Installation
---
1. Copy `.env.example` file to `.env` file.
Using your terminal, from your project root directory just run: `cp .env.example .env`
2. Change the values in this file to fit your project needs.
3. Using your terminal, from your project root directory `docker compose up`
4. Your project is ready to use.
