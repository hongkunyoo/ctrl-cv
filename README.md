# ctrl-cv

A personal clipboard for your AI apps, over [MCP](https://modelcontextprotocol.io). Ask one AI to copy text, then ask another to paste it.

- Website: https://ctrl-cv.io
- Docs: https://ctrl-cv.io/docs/
- MCP server: `https://app.ctrl-cv.io/mcp` (remote, Streamable HTTP, sign in with Google)
- Support: help@ctrl-cv.io

## Connect

Add `https://app.ctrl-cv.io/mcp` as a remote MCP server or custom connector in your AI app, then sign in with Google.

## Tools

| Tool | Input | Result |
|---|---|---|
| `copy` | `content`, up to 1,000,000 bytes of UTF-8 | The new clip's id |
| `paste` | `id`, optional | That clip's text, or your most recent clip |

Your first 30 copies are free, with no card needed. See [pricing](https://ctrl-cv.io/pricing/), the [privacy policy](https://ctrl-cv.io/privacy/), and the [terms](https://ctrl-cv.io/terms/).

## This repository

This is the website, built with [Astro](https://astro.build). The MCP server itself is a hosted service and isn't in this repository.

```bash
npm install
npm run dev
```
