![Header](https://raw.githubusercontent.com/yuhangch/openai-proxy/master/.github/img/header.png)

:rocket:  The template to deploy an openai api proxy to [Cloudflare Workers](https://developers.cloudflare.com/workers/). The `src/index.ts` file contains the route definitions of Reflare. The documentation of Reflare can be found [here](https://github.com/xiaoyang-sde/reflare).

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/yuhangch/openai-proxy)

## Installation

[Install `wrangler` CLI](https://github.com/cloudflare/wrangler#installation) and authorize `wrangler` with Cloudflare account.

```console
npm install -g wrangler

wrangler login
```
- Run `npm run dev` (need `npm run build` at first time) to preview openai-proxy with local development server provided by [Miniflare](https://miniflare.dev).
- Run `npm run deploy` to publish Reflare on Cloudflare Workers.
