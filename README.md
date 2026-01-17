# NotPixel SDK — Issues & Feedback

[![npm version](https://img.shields.io/npm/v/notpixel.svg)](https://www.npmjs.com/package/notpixel)
[![npm downloads](https://img.shields.io/npm/dm/notpixel.svg)](https://www.npmjs.com/package/notpixel)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue.svg)](https://www.typescriptlang.org/)

**Contextual ads SDK for LLMs.** Simple, provider-agnostic, privacy-first.

---

> 📌 **This repository is for bug reports and feature requests only.**  
> The SDK source code is private.

| Resource | Link |
|----------|------|
| 📦 **npm package** | [npmjs.com/package/notpixel](https://www.npmjs.com/package/notpixel) |
| 📖 **Documentation** | [docs.notpixel.ai](https://docs.notpixel.ai) |
| 🌐 **Website** | [notpixel.ai](https://notpixel.ai) |

---

## ✨ Features

- 🔌 **Provider Agnostic** — Works with OpenAI, Anthropic, Google, xAI, Mistral, and 200+ models via OpenRouter
- 🔒 **Privacy-First** — Client-side embeddings option ensures user queries never leave the device
- ⚡ **Streaming Support** — Native streaming with ads injected at the end of responses
- ⚛️ **React Components** — Ready-to-use React components with proper disclosure
- 🌐 **Browser SDK** — Lightweight tracking for click and conversion events
- 📊 **Full Analytics** — Track impressions, clicks, and conversions

---

## 📦 Installation

```bash
npm install notpixel
```

See full installation instructions at [docs.notpixel.ai/getting-started](https://docs.notpixel.ai/getting-started).

---

## 🚀 Quick Start

```typescript
import Ads from "notpixel";

const ads = new Ads({
  publisherId: "pub_xxxxx",
  model: "openai/gpt-4o",
  input: "What are the best practices for React performance?",
});

const response = await ads.offer();

console.log(response.text);
// → Your LLM response with contextually relevant sponsored content
```

For more examples, visit [docs.notpixel.ai](https://docs.notpixel.ai).

---

## 🔧 Supported Providers

| Provider | Model Examples |
|----------|----------------|
| **OpenAI** | `openai/gpt-4o`, `openai/gpt-4o-mini` |
| **Anthropic** | `anthropic/claude-3-opus`, `anthropic/claude-3-sonnet` |
| **Google** | `google/gemini-pro`, `google/gemini-1.5-flash` |
| **xAI** | `xai/grok-2` |
| **Mistral** | `mistral/mistral-large`, `mistral/mixtral-8x7b` |
| **200+ more** | Via [OpenRouter](https://openrouter.ai) |

---

## 🐛 Issues & Feature Requests

Found a bug or have a feature request for the SDK?

- 🐛 [Report a Bug](https://github.com/notpixel-ai/sdk/issues/new?template=bug_report.md)
- 💡 [Request a Feature](https://github.com/notpixel-ai/sdk/issues/new?template=feature_request.md)
- 🔐 Security issues: [security@notpixel.ai](mailto:security@notpixel.ai)

Please read our [Contributing Guidelines](./CONTRIBUTING.md) before opening an issue.

---

## 📖 Documentation

Full documentation is available at **[docs.notpixel.ai](https://docs.notpixel.ai)**:

- [Getting Started](https://docs.notpixel.ai/getting-started)
- [React Integration](https://docs.notpixel.ai/react)
- [Browser Tracking](https://docs.notpixel.ai/browser)
- [Privacy Modes](https://docs.notpixel.ai/privacy)
- [API Reference](https://docs.notpixel.ai/api)

---

## 🤝 For Publishers

Want to monetize your AI platform?

1. Sign up at [notpixel.ai/publisher](https://notpixel.ai/publisher)
2. Get your Publisher ID
3. Integrate the SDK
4. Start earning

---

## 📄 License

MIT © [NotPixel](https://notpixel.ai)

---

<p align="center">
  <a href="https://www.npmjs.com/package/notpixel">npm</a> •
  <a href="https://docs.notpixel.ai">Docs</a> •
  <a href="https://notpixel.ai">Website</a> •
  <a href="mailto:hello@notpixel.ai">Contact</a>
</p>