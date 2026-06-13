# Awesome Deno [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

[<img src="deno-logo.png" align="right" width="100">](https://deno.land)

Deno is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 and is built in Rust.

This list is a collection of the best Deno modules and resources.

## Contents

* [Docs](#docs)
  * [Official Docs](#official-docs)
  * [External Docs](#external-docs)
* [Modules](#modules)
  * [Automation](#automation)
  * [CLI utils](#cli-utils)
  * [Cloud APIs](#cloud-apis)
  * [Database](#database)
  * [Editor framework](#editor-framework)
  * [Frontend framework](#frontend-framework)
  * [Game engine](#game-engine)
  * [Logging](#logging)
  * [Machine Learning](#machine-learning)
  * [Mail](#mail)
  * [Markdown](#markdown)
  * [Math](#math)
  * [Static site generator](#static-site-generator)
  * [String utils](#string-utils)
  * [Social Platform APIs](#social-platform-apis)
  * [Template engine](#template-engine)
  * [Testing](#testing)
  * [Utils](#utils)
  * [Web framework](#web-framework)
  * [WebSocket](#websocket)
  * [Web utils](#web-utils)
  * [Webview](#webview)
  * [XML](#xml)
* [Registries](#registries)
* [Showcases](#showcases)
* [Tools](#tools)
* [Integrations](#integrations)
* [Articles](#articles)
* [Blogs/Newsletters](#blogsnewsletters)
* [Presentations](#presentations)
* [Resources](#resources)
  * [Books](#books)
* [Resources in Other Languages](#resources-in-other-languages)
  * [Chinese](#chinese)
  * [Hebrew](#hebrew)
  * [Indonesian](#indonesian)
  * [Italian](#italian)
  * [Japanese](#japanese)
  * [Korean](#korean)
  * [Russian](#russian)
  * [Spanish](#spanish)
  * [Darija (Arabe marocain)](#darija)
  * [Kurdish (Central)](#kurdish-central)

## Docs

### Official Docs

* [Deno API Reference](https://docs.deno.com/api)
* [Deno Manual](https://docs.deno.com)
* [Deno Standard Library](https://jsr.io/@std)
* [Official Site](https://deno.com)

### External Docs

* [V8 Docs for Deno](https://denolib.github.io/v8-docs/)

## Modules

### Automation

* [swissknife](https://github.com/fakoua/SwissKnife) ⭐ 10 | 🐛 1 | 🌐 TypeScript | 📅 2023-12-23 - SwissKnife - Deno Swiss Knife tools for Windows.

### CLI utils

* [yargs](https://github.com/yargs/yargs) ⭐ 11,489 | 🐛 321 | 🌐 JavaScript | 📅 2026-06-12 - The modern, pirate-themed successor to optimist.
* [cac](https://github.com/cacjs/cac) ⭐ 3,091 | 🐛 34 | 🌐 TypeScript | 📅 2026-05-22 - Simple yet powerful framework for building command-line apps.
* [cliffy](https://github.com/c4spar/cliffy) ⭐ 1,159 | 🐛 44 | 🌐 TypeScript | 📅 2026-06-12 - The complete solution for building interactive command-line tools.
* [tui](https://github.com/Im-Beast/deno_tui) ⭐ 303 | 🐛 5 | 🌐 TypeScript | 📅 2024-11-19 - Module which allows easy creation of Terminal User Interfaces.
* [charmd](https://github.com/littletof/charmd) ⭐ 65 | 🐛 1 | 🌐 JavaScript | 📅 2025-08-04 - A simple, extendable markdown renderer for your terminal.
* [cli-spinner](https://github.com/ameerthehacker/deno-cli-spinners) ⭐ 57 | 🐛 2 | 🌐 TypeScript | 📅 2025-03-18 - Show spinners in the terminal while running long tasks.
* [commit-sage-cli](https://github.com/AhmedOsman101/commit-sage-cli) ⭐ 47 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-08 - Generates Conventional Commit messages with AI based on Git repository changes.
* [clite](https://github.com/jersou/clite-parser) ⭐ 10 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-08 - Automatic CLI generation from a class.

### Cloud APIs

* [aws-api](https://aws-api.deno.dev/) - From-scratch Typescript AWS API client built for Deno.
* [googleapis](https://googleapis.deno.dev/) - Auto-generated Google API clients for Deno.

### Database

* [denodb](https://github.com/eveningkid/denodb) ⭐ 1,926 | 🐛 105 | 🌐 TypeScript | 📅 2023-10-28 - MySQL, SQLite, MariaDB, PostgreSQL and MongoDB ORM for Deno.
* [postgres](https://github.com/denodrivers/postgres) ⭐ 654 | 🐛 38 | 🌐 TypeScript | 📅 2025-04-24 - Driver for PostgreSQL database.
* [nessie](https://github.com/halvardssm/deno-nessie) ⭐ 520 | 🐛 8 | 🌐 TypeScript | 📅 2024-04-10 - Create, migrate and rollback migrations for PostgreSQL, MySQL and SQLite.
* [deno\_mongo](https://github.com/denodrivers/mongo) ⭐ 513 | 🐛 48 | 🌐 TypeScript | 📅 2025-03-14 - MongoDB database driver.
* [redis](https://github.com/denodrivers/redis) ⭐ 467 | 🐛 42 | 🌐 TypeScript | 📅 2026-06-08 - An experimental implementation of redis client for deno.
* [deno\_mysql](https://github.com/denodrivers/mysql) ⭐ 264 | 🐛 23 | 🌐 TypeScript | 📅 2024-06-26 - MySQL database driver.
* [aloedb](https://github.com/Kirlovon/aloedb) ⭐ 143 | 🐛 4 | 🌐 TypeScript | 📅 2024-07-30 - Light, Embeddable, NoSQL database for Deno without dependencies.
* [dongoose](https://github.com/roonie007/dongoose) ⭐ 27 | 🐛 2 | 🌐 TypeScript | 📅 2023-07-10 - A simple and easy to use ORM for Deno KV.
* [maxminddb](https://github.com/josh-hemphill/maxminddb-wasm) ⭐ 17 | 🐛 7 | 🌐 TypeScript | 📅 2026-06-08 - A library that enables the usage of MaxmindDB geoIP database files
* [yongo](https://github.com/yooneskh/yongo) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2024-07-08 - Subset of Mongoose api in deno (like populate) but will not fully copy mongoose
* [@iuioiua/redis](https://jsr.io/@iuioiua/redis) - Fast, lightweight Redis client built upon the Web Streams API.

### Editor framework

* [Denops](https://github.com/vim-denops/denops.vim) ⭐ 787 | 🐛 9 | 🌐 TypeScript | 📅 2026-05-15 - 🐜 An ecosystem to write Vim/Neovim plugins with Deno.

### Frontend framework

* [fresh](https://github.com/denoland/fresh) ⭐ 13,761 | 🐛 119 | 🌐 TypeScript | 📅 2026-06-03 - The next-gen web framework.
* [ultra](https://github.com/exhibitionist-digital/ultra) ⭐ 2,954 | 🐛 28 | 🌐 TypeScript | 📅 2024-10-28 - 💎 Modern Streaming React Framework in Deno.
* [packup](https://github.com/kt3k/packup) ⭐ 337 | 🐛 12 | 🌐 TypeScript | 📅 2024-06-02 - Zero-config web application packager for Deno.

### Game engine

* [sdl2](https://github.com/littledivy/deno_sdl2) ⭐ 185 | 🐛 15 | 🌐 TypeScript | 📅 2025-10-18 - SDL2 module for Deno
* [caviar](https://github.com/load1n9/caviar) ⭐ 171 | 🐛 4 | 🌐 TypeScript | 📅 2025-09-03 - ⚡ Blazing fast, modern, Game Engine powered by WebGPU for Deno and the browser

### Image

* [ImageScript](https://github.com/matmen/ImageScript) ⭐ 675 | 🐛 21 | 🌐 JavaScript | 📅 2025-06-14 - Image processing in JavaScript, utilizing WebAssembly for performance.
* [monke](https://github.com/retraigo/monke) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2023-07-29 - Color quantization and dithering library with extra image filters (blur, invert, etc).

### Logging

* [LogTape](https://github.com/dahlia/logtape) ⭐ 1,825 | 🐛 12 | 🌐 TypeScript | 📅 2026-06-13 - Simple logging library with zero dependencies for Deno/Node.js/Bun/browsers.

### Machine learning

* [netsaur](https://github.com/denosaurs/netsaur) ⭐ 256 | 🐛 7 | 🌐 Rust | 📅 2024-10-02 - Powerful machine learning, accelerated by WebGPU
* [appraisal](https://github.com/retraigo/appraisal) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2024-03-05 - Feature extraction and conversion.
* [classy-lala](https://github.com/retraigo/la-classy) ⭐ 5 | 🐛 2 | 🌐 Rust | 📅 2024-04-01 - Single-layer perceptrons for supervised learning tasks.

### Mail

* [deno-smtp](https://github.com/manyuanrong/deno-smtp) ⭐ 83 | 🐛 18 | 🌐 TypeScript | 📅 2024-05-29 - A smtp mail sender for deno.

### Markdown

* [LiteMarkup](https://github.com/tuures/LiteMarkup) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-13 - AST-first parser. Under 3 KB gzipped, zero dependencies.

### Math

* [neo](https://github.com/denosaurs/neo/) ⭐ 71 | 🐛 15 | 🌐 TypeScript | 📅 2023-08-02 - Matrix and other math, accelerated by WebGPU

### Static site generator

* [lume](https://github.com/lumeland/lume) ⭐ 2,260 | 🐛 43 | 🌐 TypeScript | 📅 2026-06-12 - A static site generator similar to Jekyll or Eleventy with support for multiple file formats.
* [pagic](https://github.com/xcatliu/pagic) ⭐ 1,654 | 🐛 12 | 🌐 JavaScript | 📅 2023-09-19 - The easiest way to generate static html page from markdown, built with Deno.

### String utils

* [written](https://github.com/vixalien/written) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2024-09-04 - A provides a set of utilities for manipulating text, with a focus on providing typographic tools rather than pure string manipulation.

### Social Platform APIs

* [grammY](https://github.com/grammyjs/grammY) ⭐ 3,629 | 🐛 17 | 🌐 TypeScript | 📅 2026-05-16 - Telegram Bot API framework for Deno.
* [discordeno](https://github.com/discordeno/discordeno) ⭐ 939 | 🐛 99 | 🌐 TypeScript | 📅 2026-06-13 - Discord API library for Deno
* [MTKruto](https://github.com/MTKruto/MTKruto) ⭐ 162 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-12 - Deno-first, cross-runtime client library for Telegram's MTProto API.

### Template engine

* [eta](https://github.com/bgub/eta) ⭐ 1,727 | 🐛 6 | 🌐 TypeScript | 📅 2026-04-25 - Fast, lightweight, and configurable embedded template engine.
* [dejs](https://github.com/syumai/dejs) ⭐ 146 | 🐛 4 | 🌐 TypeScript | 📅 2023-05-30 - Ejs template engine for deno.
* [handlebars](https://github.com/alosaur/handlebars) ⭐ 31 | 🐛 4 | 🌐 TypeScript | 📅 2024-07-17 - Handlebars template engine for deno

### Testing

* [deno-puppeteer](https://github.com/lucacasonato/deno-puppeteer) ⭐ 458 | 🐛 43 | 🌐 TypeScript | 📅 2023-12-01 - A library which provides a high-level API to control Chromium or Chrome over the DevTools Protocol.
* [unexpected](https://github.com/unexpectedjs/unexpected) ⭐ 366 | 🐛 51 | 🌐 JavaScript | 📅 2026-04-14 - Extensible BDD assertion toolkit.
* [superdeno](https://github.com/cmorten/superdeno) ⭐ 124 | 🐛 1 | 🌐 TypeScript | 📅 2025-05-18 - Super-agent driven library for testing Deno HTTP servers.
* [superoak](https://github.com/cmorten/superoak) ⭐ 120 | 🐛 1 | 🌐 TypeScript | 📅 2025-11-15 - HTTP assertions for Oak made easy via SuperDeno.
* [rhum](https://github.com/drashland/rhum) ⭐ 91 | 🐛 8 | 🌐 TypeScript | 📅 2024-05-31 - A lightweight testing framework for Deno.
* [qunitx](https://github.com/izelnakri/qunitx) ⭐ 34 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-08 - Zero dependency, fully customizable, mature, universal test API that can run interchangably in node.js, Deno & browser, using default runtime test runners.
* [tepi](https://deno.land/x/tepi) - A .http Test Runner

### Utils

* [croner](https://github.com/Hexagon/croner) ⭐ 2,559 | 🐛 6 | 🌐 TypeScript | 📅 2026-06-12 - Cron library with advanced scheduling features, well-documented API, and zero dependencies.
* [fastest-validator](https://github.com/icebob/fastest-validator) ⭐ 1,464 | 🐛 42 | 🌐 JavaScript | 📅 2026-04-09 - Schema validator for all javascript platforms
* [denon](https://github.com/denosaurs/denon/blob/master/mod.ts) ⭐ 1,109 | 🐛 27 | 🌐 TypeScript | 📅 2024-03-21 - A file watcher with a for-await generator.
* [evt](https://github.com/garronej/evt) ⭐ 463 | 🐛 7 | 🌐 TypeScript | 📅 2025-10-01 - Type safe replacement for EventEmitter.
* [computed\_types](https://github.com/neuledge/computed-types) ⭐ 360 | 🐛 7 | 🌐 TypeScript | 📅 2026-01-29 - Joi like validators for Typescript and Deno.
* [rubico](https://github.com/a-synchronous/rubico) ⭐ 283 | 🐛 52 | 🌐 JavaScript | 📅 2026-05-27 - 🏞 \[a]synchronous function composition; it just works.
* [optionals](https://github.com/OliverBrotchie/optionals) ⭐ 193 | 🐛 5 | 🌐 TypeScript | 📅 2024-09-09 - Rust-like error handling and options with exhaustive pattern matching.
* [solc](https://github.com/deno-web3/solc) ⭐ 72 | 🐛 2 | 🌐 TypeScript | 📅 2025-02-27 - 💎 Solidity bindings for Deno.
* [qrcode](https://github.com/denorg/qrcode) ⭐ 45 | 🐛 9 | 🌐 JavaScript | 📅 2026-05-21 - QR code image generator for Deno.
* [garn-validator](https://github.com/jupegarnica/garn-validator) ⭐ 42 | 🐛 7 | 🌐 JavaScript | 📅 2024-04-23 - Create validations with ease.
* [buckets](https://github.com/jacoborus/deno-buckets) ⭐ 24 | 🐛 0 | 🌐 TypeScript | 📅 2024-03-01 - Bundle assets and scripts in a single executable file.
* [durationjs](https://github.com/retraigo/duration.js) ⭐ 21 | 🐛 0 | 🌐 TypeScript | 📅 2025-06-15 - Get formatted time duration from a timestamp or a human-readable string.
* [fortuna](https://github.com/retraigo/fortuna) ⭐ 20 | 🐛 0 | 🌐 TypeScript | 📅 2025-06-04 - Weighted gacha system.
* [wu-diff-js](https://github.com/bokuweb/wu-diff-js) ⭐ 19 | 🐛 13 | 🌐 TypeScript | 📅 2026-05-12 - A diff library to compute differences between two slices using wu(the O(NP)) algorithm.
* [deno\_kv\_fs](https://github.com/hviana/deno_kv_fs) ⭐ 17 | 🐛 0 | 🌐 TypeScript | 📅 2025-06-20 Deno KV file system, compatible with Deno deploy. Makes use of Web Streams API.
* [PLS](https://github.com/xorgram/pls) ⭐ 9 | 🐛 0 | 🌐 TypeScript | 📅 2025-07-22 - Use 2 lines to persist localStorage in any database, including, but not limited to, MongoDB, PostgreSQL and Redis.
* [colors](https://github.com/retraigo/colors) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2024-09-14 - Color conversions and operations in TypeScript.
* [deno-config](https://github.com/yooneskh/deno-unified-config) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2024-10-03 - Utility to streamline deno app configuration management through cli, .env and json files
* [locale-kit](https://deno.land/x/localekit) ([GitHub](https://github.com/locale-kit/locale-kit) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2024-03-17) - A internationalisation/localisation/translation (i18n/l10n/t9n) library with a wrapper for Fresh and support for plurals and dynamic replacement.
* [esm-itter](https://github.com/tillsanders/esm-itter) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-10 – A strongly typed fork of the popular EventEmitter3 with a focus on EcmaScript module syntax, TypeScript and modern tooling.
* [switcher4deno](https://github.com/switcherapi/switcher-client-deno) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-28 - Feature Flag Deno SDK client for Switcher-API.
* [dinoenv](https://deno.land/x/dinoenv) - tiny library to manage environment variables with deno.

### Validation

* [zod](https://github.com/colinhacks/zod) ⭐ 42,954 | 🐛 201 | 🌐 TypeScript | 📅 2026-06-13 - TypeScript-first schema validation with static type inference.

### Web framework

* [hono](https://github.com/honojs/hono) ⭐ 30,942 | 🐛 372 | 🌐 TypeScript | 📅 2026-06-09 - Ultrafast web framework for Cloudflare Workers, Deno, and Bun. Fast, but not only fast.
* [oak](https://github.com/oakserver/oak) ⭐ 5,406 | 🐛 52 | 🌐 TypeScript | 📅 2026-02-22 - A middleware framework for Deno's net server.
  * [oak-http-proxy](https://github.com/cmorten/oak-http-proxy) ⭐ 42 | 🐛 1 | 🌐 TypeScript | 📅 2024-01-28 - Proxy middleware for Deno Oak HTTP servers.
  * [oak-routing-ctrl](https://github.com/Thesephi/oak-routing-ctrl) ⭐ 10 | 🐛 2 | 🌐 TypeScript | 📅 2026-03-30 - TypeScript Decorators for easy scaffolding API services with the oak framework.
* [drash](https://github.com/drashland/drash) ⭐ 1,067 | 🐛 15 | 🌐 TypeScript | 📅 2026-05-30 - A REST microframework for Deno's HTTP server with zero dependencies.
* [opine](https://github.com/cmorten/opine) ⭐ 849 | 🐛 2 | 🌐 TypeScript | 📅 2024-01-28 - Fast, minimalist web framework ported from ExpressJS.
  * [opine-http-proxy](https://github.com/cmorten/opine-http-proxy) ⭐ 17 | 🐛 1 | 🌐 TypeScript | 📅 2025-11-15 - Proxy middleware for Deno Opine HTTP servers.
* [alosaur](https://github.com/alosaur/alosaur) ⭐ 817 | 🐛 25 | 🌐 TypeScript | 📅 2024-11-05 - Alosaur - Deno web framework with many ES Decorators.
* [danet](https://github.com/Savory/Danet) ⭐ 519 | 🐛 4 | 🌐 TypeScript | 📅 2026-06-13 - A Savory web framework for Deno heavily inspired by [Nest.js](https://nestjs.com).
* [aqua](https://github.com/predetermined/aqua) ⭐ 216 | 🐛 5 | 🌐 TypeScript | 📅 2023-12-13 - A minimal and fast web framework for Deno.
* [faster\_react](https://github.com/hviana/faster_react) ⭐ 99 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-06 - Full Stack web framework with React + Faster. Fully compatible with Deno Deploy.
* [faster](https://github.com/hviana/faster) ⭐ 58 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-01 - A fast and optimized middleware server with a set of useful middlwares.

### WebSocket

* [wocket](https://github.com/drashland/wocket) ⭐ 102 | 🐛 2 | 🌐 TypeScript | 📅 2024-05-02 - A WebSocket library for Deno.
* [dropper](https://github.com/denyncrawford/dropper-deno) ⭐ 27 | 🐛 1 | 🌐 TypeScript | 📅 2023-07-06 - Custom event-based WebSockets framework for building real-time apps on Deno 🦕

### Web utils

* [obsidian](https://github.com/open-source-labs/obsidian) ⭐ 763 | 🐛 4 | 🌐 TypeScript | 📅 2024-05-17 - A native GraphQL caching client and server module.
* [djwt](https://github.com/Zaubrik/djwt) ⭐ 235 | 🐛 3 | 🌐 TypeScript | 📅 2024-08-09 - Make JSON Web Tokens (JWT) on Deno based on JWT and JWS specifications.
* [gql](https://github.com/deno-libs/gql) ⭐ 203 | 🐛 0 | 🌐 TypeScript | 📅 2026-01-20 - Universal GraphQL HTTP middleware.
* [nats](https://github.com/nats-io/nats.deno) ⭐ 179 | 🐛 10 | 🌐 TypeScript | 📅 2025-12-15 - A Deno client for the [NATS messaging system](https://nats.io/).
* [fresh\_chart](https://github.com/denoland/fresh_charts) ⭐ 153 | 🐛 9 | 🌐 TypeScript | 📅 2024-04-17 - A server-side-rendered charting library for Fresh.
* [router](https://github.com/zhmushan/router) ⭐ 55 | 🐛 2 | 🌐 TypeScript | 📅 2026-03-02 - A high-performance basic router works anywhere.
* [gentleRpc](https://github.com/timonson/gentle_rpc) ⭐ 45 | 🐛 2 | 🌐 TypeScript | 📅 2024-05-18 - A JSON-RPC 2.0 TypeScript library for Deno and the browser.
* [ts-prometheus](https://github.com/marcopacini/ts_prometheus) ⭐ 31 | 🐛 1 | 🌐 TypeScript | 📅 2023-11-14 - A prometheus client.
* [rpc](https://github.com/deno-libs/rpc) ⭐ 23 | 🐛 1 | 🌐 TypeScript | 📅 2026-02-28 - JSONRPC server implementation for Deno.
* [forwarded](https://github.com/deno-libs/forwarded) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-26 - Deno port of `forwarded` library.
* [graphql-tag](https://github.com/deno-libs/graphql_tag) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-01 - GraphQL schema AST from template literal.
* [react-icons](https://react-icons.deno.dev/) - React Icons converted to preact for deno fresh.

### Webview

* [webview](https://github.com/webview/webview_deno) ⭐ 1,595 | 🐛 42 | 🌐 TypeScript | 📅 2025-02-25 - Deno bindings for webview, a tiny library for creating web-based desktop GUIs.

### XML

* [sax-ts](https://github.com/Maxim-Mazurok/sax-ts) ⭐ 20 | 🐛 0 | 🌐 JavaScript | 📅 2024-03-17 - SAX-style XML parser ported from [sax-js](https://github.com/isaacs/sax-js) ⭐ 1,156 | 🐛 96 | 🌐 JavaScript | 📅 2026-03-17.

## Registries

* [crux.land](https://crux.land/) - A free registry service meant for hosting small ( < 10kB) single deno scripts.
* [Deno PKG](https://denopkg.com/) - An easier way to use code from GitHub in your Deno project.
* [deno.land/x/](https://deno.land/x/) - The official 3rd party module registry.
* [nest.land](https://nest.land) - An immutable, blockchain powered Deno package registry. 🥚

## Showcases

* [GitHub Profile Trophy](https://github.com/ryo-ma/github-profile-trophy) ⭐ 6,568 | 🐛 23 | 🌐 TypeScript | 📅 2026-05-30 - 🏆 Add dynamically generated GitHub Trophy on your readme
* [Edrys](https://github.com/edrys-org/edrys) ⭐ 332 | 🐛 8 | 🌐 Vue | 📅 2024-08-12 - Remote Teaching Software
* [Deno Rest](https://github.com/Prolifode/deno_rest) ⭐ 162 | 🐛 3 | 🌐 TypeScript | 📅 2025-02-09 - A Boilerplate for deno RESTful apis.
* [ShopSavvy Deno Deploy](https://github.com/shopsavvy/deno-deploy-shopsavvy) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-01 - Deno Deploy router with Hono for product search, real-time pricing, and price history.
* [The Official Showcase](https://deno.land/showcase) - The official showcase of Deno.
* [UsingDeno](https://usingdeno.com) - Curated list of Web Applications & Projects using Deno 🦕.

## Tools

* [vscode-deno](https://github.com/denoland/vscode_deno) ⭐ 1,548 | 🐛 121 | 🌐 TypeScript | 📅 2026-06-13 - VS Code extension that provides Deno support using the `TypeScript Deno language service plugin`.
* [dnt](https://github.com/denoland/dnt) ⭐ 1,325 | 🐛 113 | 🌐 Rust | 📅 2025-07-17 - Deno to npm package build tool.
* [denon](https://github.com/denosaurs/denon) ⭐ 1,109 | 🐛 27 | 🌐 TypeScript | 📅 2024-03-21 - A daemon script runner, like nodemon. Built in and for Deno.
* [deno\_docker](https://github.com/denoland/deno_docker) ⭐ 1,014 | 🐛 16 | 🌐 Dockerfile | 📅 2026-06-11 - Latest dockerfiles and images for Deno - alpine, centos, debian, ubuntu.
* [denoify](https://github.com/garronej/denoify) ⭐ 949 | 🐛 14 | 🌐 TypeScript | 📅 2025-10-01 - For NPM module authors that would like to support Deno but do not want to write and maintain a port.
* [trex](https://github.com/crewdevio/Trex) ⭐ 730 | 🐛 7 | 🌐 TypeScript | 📅 2023-08-18 - Package management like npm for deno.
* dvm
  * [justjavac/dvm](https://github.com/justjavac/dvm) ⭐ 705 | 🐛 12 | 🌐 Rust | 📅 2026-05-29 - Deno Version Manager: manage multiple active Deno versions.
  * [axetroy/dvm](https://github.com/axetroy/dvm) ⭐ 165 | 🐛 14 | 🌐 Go | 📅 2024-08-27 - Version manger for Deno without runtime dependencies.
  * [asdf-community/asdf-deno](https://github.com/asdf-community/asdf-deno) ⭐ 132 | 🐛 8 | 🌐 Shell | 📅 2026-06-02 - Deno plugin for [asdf](https://asdf-vm.com/)
  * [ghosind/dvm](https://github.com/ghosind/dvm) ⭐ 53 | 🐛 4 | 🌐 Shell | 📅 2025-09-16 - A lightweight Deno Version Manager for Linux/MacOS.
* [udd](https://github.com/hayd/deno-udd) ⭐ 327 | 🐛 36 | 🌐 TypeScript | 📅 2024-04-25 - Update Deno dependencies: updates import statements to their latest published version.
* [denoflow](https://github.com/denoflow/denoflow) ⭐ 286 | 🐛 0 | 🌐 TypeScript | 📅 2023-10-04 - Configuration as code, use YAML to write automated workflows that run on Deno, with any Deno modules, Typescript/Javascript codes
* [denopkg](https://github.com/egoist-labs/denopkg.com) ⭐ 239 | 🐛 9 | 🌐 TypeScript | 📅 2025-08-14 - An easier way to use code from GitHub in your Deno project.
* [pup](https://github.com/Hexagon/pup) ⭐ 194 | 🐛 14 | 🌐 TypeScript | 📅 2026-02-20 - Advanced process manager for Deno. With autorestart, fs watch, cron start, process telemetry, ipc, clustering, load balancer and more.
* [denomander](https://github.com/siokas/denomander) ⭐ 151 | 🐛 3 | 🌐 TypeScript | 📅 2025-02-20 - Deno command-line interfaces inspired from commander.js.
* [studio-pack-generator](https://github.com/jersou/studio-pack-generator) ⭐ 121 | 🐛 2 | 🌐 TypeScript | 📅 2025-01-04 - Convert a folder or a RSS URL to Studio pack for Lunii device
* [denoliver](https://github.com/joakimunge/denoliver) ⭐ 104 | 🐛 5 | 🌐 TypeScript | 📅 2025-07-24 - A simple, dependency free file server with live reload.
* [dmm](https://github.com/drashland/dmm) ⭐ 58 | 🐛 2 | 🌐 TypeScript | 📅 2025-08-25 - Lightweight Deno Module Manager
* [make-deno-edition](https://github.com/bevry/make-deno-edition) ⭐ 43 | 🐛 5 | 🌐 TypeScript | 📅 2026-03-26 - Automatically makes package.json projects (such as npm packages and node.js modules) compatible with Deno.
* [dpm](https://github.com/dpmland/dpm) ⭐ 40 | 🐛 0 | 🌐 TypeScript | 📅 2024-11-18 - Deno Package Manager, a NPM | Yarn Experience for Deno
* [kopo-cli](https://github.com/littletof/kopo-cli) ⭐ 16 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-03 - A Deno registry browser in the terminal.
* [clone](https://github.com/ekaragodin/clone) ⭐ 4 | 🐛 1 | 🌐 TypeScript | 📅 2026-03-30 - A simple utility for the convenient clone.
* [entype](https://github.com/bcheidemann/entype) ⭐ 4 | 🐛 1 | 🌐 TypeScript | 📅 2023-08-23 - A CLI tool used to generate type definitions for serialised data, currently supporting JSON to Rust and TypeScript.
* [Deno Dig](https://github.com/theGEBIRGE/DenoDig) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2024-10-29 - A tool for extracting application code and npm packages from stand-alone Deno executables.
* [denopendabot](https://github.com/apps/denopendabot) - Dependabot for Deno projects.

## Integrations

* [Netlify Edge Functions](https://docs.netlify.com/edge-functions/overview/) - Edge Functions connect the Netlify platform and workflow.
* [Slack Custom Functions](https://api.slack.com/future/functions/custom) - Build custom Run On Slack functions using Deno.
* [Smallweb](https://www.smallweb.run/) - A personal cloud contained in a single directory. You can customize the server behavior using Deno.
* [Supabase Edge Functions](https://supabase.com/docs/guides/functions) - Edge Functions are server-side TypeScript functions, distributed globally at the edge.
* [Astro](https://docs.astro.build/en/guides/deploy/deno/) - Deploy a server-side rendered Astro site to Deno Deploy.

## Blogs/Newsletters

* [Craig's Deno Diary](https://deno-blog.com) - A blog focussing on Deno tech & lib howtos.
* [Deno Blog](https://deno.com/blog) - The official blog of the Deno Company.
* [Deno News](https://deno.news) - A newsletter of Deno articles, news and cool projects.

## Articles

* [Develop with Deno and Visual Studio Code](https://medium.com/@kitsonk/develop-with-deno-and-visual-studio-code-225ce7c5b1ba)
* [First thoughts on Deno, the JavaScript/TypeScript run-time](https://43081j.com/2019/01/first-look-at-deno)
* [Getting started with Deno](https://dev.to/wuz/getting-started-with-deno-e1m)
* [What's Deno, and how is it different from Node.js?](https://dev.to/bnevilleoneill/what-s-deno-and-how-is-it-different-from-node-js-366g)
* [Write a small API using Deno](https://dev.to/kryz/write-a-small-api-using-deno-1cl0)
* [Deno on Cloud Run](https://medium.com/google-cloud/deno-on-cloud-run-89ae64d1664d)
* [Learn Deno: Chat app](https://aralroca.com/blog/learn-deno-chat-app)
* [From Node to Deno](https://dev.to/aralroca/from-node-to-deno-5gpn)
* [Create a simple Note-taking app with Deno](https://dev.to/jeferson_sb/create-a-simple-note-taking-app-with-deno-3k7g)
* [Building API's using Deno, Oak and MYSQL](https://codeforgeek.com/building-api-server-using-deno-and-mysql/)
* [Create your first News CLI app using Deno](https://medium.com/javascript-in-plain-english/creating-your-first-news-cli-app-using-deno-e1470398c627)
* [Continuous Integration with Deno](https://semaphoreci.com/blog/continuous-integration-with-deno)
* [The Hidden Superpower of Deno: xeval](https://stefanbuck.com/blog/hidden-superpower-deno-xeval)
* Deno REST API with Oak Tutorial Series [0](https://www.robinwieruch.de/deno-tutorial), [1](https://www.robinwieruch.de/deno-oak), [2](https://www.robinwieruch.de/deno-oak-rest-api)
* [Getting Started with Deno](https://sabe.io/tutorials/getting-started-with-deno)
* [How to deploy a Deno app using Docker](https://sabe.io/tutorials/how-to-deploy-deno-app-docker)

## Presentations

* [10 Things I Regret About Node.js - Ryan Dahl - JSConf EU 2018](https://www.youtube.com/watch?v=M3BM9TB-8yA)
  * [Slides](https://tinyclouds.org/jsconf2018.pdf)
* [JSDC 2018#A01 - Deno, A New Server-Side Runtime By Ryan Dahl](https://www.youtube.com/watch?v=FlTG0UXRAkE)
* [Ryan Dahl. Deno, a new way to JavaScript. JS Fest 2019 Spring](https://www.youtube.com/watch?v=z6JRlx5NC9E)
  * [Slides](https://www.slideshare.net/JSFestUA/js-fest-2019-ryan-dahl-deno-a-new-way-to-javascript)
* [Rafał Pocztarski — From Node.js to Deno - JavaScript/TypeScript runtime built with V8 and Rust \[EN\]](https://www.youtube.com/watch?v=Aib1OZLy0_c)
* [Ryan Dahl: A secure runtime for JavaScript and TypeScript | js.la April 2019](https://www.youtube.com/watch?v=RAmqgbv247s)
  * [Slides](https://docs.google.com/presentation/d/1CSQVTeH5tFzE4AZVXIpx9Xwew5YS-gxJZ03eRFtNeIc/edit)
* [Ryan Dahl: Deno, a new way to JavaScript - HolyJS 2019 Piter](https://www.youtube.com/watch?v=HjdJzNoT_qg)
  * [Slides](https://docs.google.com/presentation/d/1BjvZx5S8noVfFINptH4jfKfqh9jB9nXlFC0I3oIDtg4/edit)
* [Rafał Pocztarski - What is Deno? A new runtime for modern JavaScript and TypeScript backends for 2020s - Deno Warsaw](https://www.youtube.com/watch?v=aI5A9zvYSjk)
* [Michał Sabiniarz - How to contribute to Deno? - Deno Warsaw](https://www.youtube.com/watch?v=LAtjnKLbPpw)
* [Bartek Iwańczuk - Deno internals, how modern runtime is built - Deno Warsaw](https://www.youtube.com/watch?v=qt7fbmypAFk)
  * [Slides](https://docs.google.com/presentation/d/1LYNGpyjx9PemL-P__7hVC8mSqkX-jL8VQLMhCRehy00/edit?usp=sharing)
* [Ryan Dahl & Kitson Kelly: Deno is a New Way to JavaScript - TSConf 2019](https://www.youtube.com/watch?v=1gIiZfSbEAE)
* [Bert Belder - Deno - dotJS 2019](https://www.youtube.com/watch?v=puXyo1jGQys)
* [Kitson P. Kelly - Deno, and The Future of JavaScript Runtimes - CityJS Conf 2020](https://www.youtube.com/watch?v=2eRyZpX4qvI)
* [Matías Insaurralde - Deno: an experimental approach on V8 interoperability \[EN subtitles\] - NodeConf Argentina 2019](https://www.youtube.com/watch?v=N0BRE-0n2cU)
  * [Slides](https://speakerdeck.com/matiasinsaurralde/deno-an-experimental-approach-on-v8-interoperability)

## Resources

### Books

* [Modern Web Development with Deno](https://bpbonline.com/products/modern-web-development-with-deno)

## Resources in Other Languages

### Chinese

* [Deno 并不是下一代 Node.js](https://juejin.im/post/5b14a390e51d4506c1300bbc)
* [玩 Deno 遇到问题的解决方案](https://juejin.im/post/5b1245b3f265da6e4c6cf249)
* [让我们一起来学习别人学不动的 Deno](https://segmentfault.com/a/1190000015151287)
* [Design Mistakes in Node zh-CN](https://zhuanlan.zhihu.com/p/37637923)
* [Node之父ry：Node中的设计错误](https://mp.weixin.qq.com/s/7XAiYw18c8YZc-fXk0-wrw)
* [Node之父 - Deno，一个新的JS运行时](https://www.bilibili.com/video/av52038617)

### Hebrew

* [Deno intro in Hebrew (slides in English)](https://www.youtube.com/watch?v=9tJ_LkI6_qw)

### Indonesian

* [Berkenalan dengan Deno](https://medium.com/@redhajuanda/berkenalan-dengan-dengan-deno-c48cdf3aa31e)
* [Perkenalan Deno dan Instalasi](https://youtu.be/V_kpUTJSd9c)
* [Deno Land Indonesia Telegram group](https://t.me/deno_id)

### Italian

* [Deno - L'anagramma di Node](https://www.slideshare.net/FrancescoSciuti/deno-lanagramma-di-node)

### Japanese

* [deno-ja](https://deno-ja.deno.dev/) - Deno Japanese User Group.
* [Node.js における設計ミス By Ryan Dahl](https://yosuke-furukawa.hatenablog.com/entry/2018/06/07/080335)
* [mizchi/deno\_code\_reading.md](https://gist.github.com/mizchi/31e5628751330b624a0e8ada9e739b1e)
* [Design Mistakes in Node & Deno #kng5 / deno](https://speakerdeck.com/masashi/deno)
* [Dive into Deno：プロセス起動からTypeScriptが実行されるまで](https://blog.leko.jp/post/code-reading-of-deno-boot-process/)

### Korean

* [Deno Korea](https://deno.kr/) - Deno Korean User Group.

### Russian

* [Telegram channel](https://t.me/denoland_ru)
* [Telegram chat](https://t.me/denoland)

### Spanish

* [Hola Deno! . 🦕](https://medium.com/javascript-espa%C3%B1ol/hola-deno-f31f9f6f2c84)
* [Así puedes crear tu primera API REST con Deno](https://medium.com/@mpampols/as%C3%AD-puedes-crear-tu-primera-api-rest-con-deno-a9094ee5c0b2)
* [Primeros pasos con Deno 🦕 El sucesor de NodeJS desarrollado con Rust y TypeScript](https://medium.com/@manurua/primeros-pasos-con-deno-el-nuevo-nodejs-desarrollado-con-rust-y-typescript-b9ac14f7d0c7)
* [Primer vistazo con deno](https://dev.to/buttercubz/first-look-with-deno-spanish-30dh)

### Darija

* [A first look at Deno | BlaBlaConf 2021 🇲🇦](https://www.youtube.com/watch?v=Y_etUvzAa4s)

### Kurdish (Central)

* [A short introduction to Deno](https://devs.krd/about-deno)
