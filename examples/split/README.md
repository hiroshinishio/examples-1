# A/B Testing with Split

[Split](https://www.split.io/) is a feature delivery platform that powers feature flag management, software experimentation, and continuous delivery. In this demo you'll be able to do A/B testing at the edge.

## Demo

https://ab-testing-split.vercel.app/

### One-Click Deploy

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=customer-success-example):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fvercel-customer-feedback%2Fedge-functions%2Ftree%2Fmain%2Fexamples%2Fsplit&env=SPLIT_ADMIN_API_KEY,SPLIT_WORKSPACE_ID,SPLIT_ENVIRONMENT_ID,NEXT_PUBLIC_SPLIT_SDK_CLIENT_API_KEY&project-name=split&repo-name=split)

## Getting Started

You'll need to have an account with [Split](https://www.split.io/signup/). Once that's done, copy the `.env.example` file in this directory to `.env.local` (which will be ignored by Git):

```bash
cp .env.example .env.local
```

Then open `.env.local` and set the environment variables to match the ones in your Split dashboard. Your keys should be available under Workspace settings - API Keys, in the admin settings of your organization.

Next, run Next.js in development mode:

```bash
npm install
npm run dev

# or

yarn
yarn dev
```