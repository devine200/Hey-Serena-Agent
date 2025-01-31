# SIRI For Your Business

## Objective

The Objective of this project is to create an ai interface that allows users to communicate with an application using voice interactions and getting response through audio and great ui.

### Built On Eliza

This project is built using Eliza which is an AI framework built by the ai16z team, you can check out the code base at [@ai16z/eliza](https://github.com/ai16z/eliza)

### Add clients

```diff
- clients: [],
+ clients: ["direct"],
```

## Duplicate the .env.example template

```bash
cp .env.example .env
```

\* Fill out the .env file with your own values.

### Add login credentials and keys to .env
...
-OPENAI_API_KEY=sk-*
+OPENAI_API_KEY=sk-<secret-key>

...
-USE_OPENAI_EMBEDDING=
+USE_OPENAI_EMBEDDING=TRUE
```

## Install dependencies and start your agent

```bash
pnpm i && pnpm start
```
# Hey-Serena-Agent
