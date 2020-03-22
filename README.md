# Angular News: API

An API for the Angular News news [webapp](https://github.com/steven-martin/angular-news-webapp) and iOS app.

## Features

* The latest Angular news from the very best Tech Journalists.
* Powered by the [Twitter-Headlines](https://www.npmjs.com/package/twitter-headlines) engine.
* A single JSON endpoint, updated every 15 minutes.

## Quick Start

Download this repo locally, update the .env file values with your own twitter account values, and ... 

```
npm i
npm run start
```

> This will start the API on local host (port:3000).

## API Reference

### Get Headlines

To view the latest headlines (in JSON) simply visit:

`http://localhost:3000/`

> A cron job updates this list every 15 minutes.

