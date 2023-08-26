<div align="center">

[![Discord Auth Banner](https://i.imgur.com/mnqbOIl.png)](https://github.com/slekup/passport-discord-auth)

---

<a target="\_blank">Documentation (soon)</a> • <a href="https://discord.gg/p5rxxQN7DT" target="_blank">Discord</a> • <a href="https://github.com/slekup/passport-discord-auth" target="_blank">GitHub</a>

---

An updated passport authentication strategy for Discord.

[![Discord Server](https://img.shields.io/discord/1028009131073880104?color=5865F2&logo=discord&logoColor=white)](https://discord.gg/p5rxxQN7DT)
![NPM Version](https://img.shields.io/npm/v/passport-discord-auth.svg) ![NPM Downloads](https://img.shields.io/npm/dt/passport-discord-auth) ![Test Status](https://github.com/slekup/passport-discord-auth/actions/workflows/tests.yml/badge.svg) ![NPM Size](https://img.shields.io/bundlephobia/min/passport-discord-auth)

</div>

---

Passport strategy for authenticating with Discord using the OAuth 2.0 API. This library lets you authenticate using Discord in your Node.js applications. By plugging into Passport, Discord authentication can be easily and unobtrusively integrated into any application or framework that supports Connect-style middleware, including Express.

> **Warning:** This library is still in development and is not ready for production use. There may be breaking changes in the future.

## Installation

```bash
# Using npm
> npm install passport-discord-auth
# Using yarn or pnpm
> yarn/pnpm add passport-discord-auth
```

## Usage

### Importing

This library supports both typescript and javascript, with ES6 modules and CommonJS.

```ts
// ES6 modules
import { Strategy } from 'passport-discord-auth';
// CommonJS
const { Strategy } = require('passport-discord-auth');
```