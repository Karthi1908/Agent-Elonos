# Agent Elonos

One stop Autonomous Agent to follow on X and Discord for Alpha.

## Introduction

Agent Elonos is an autonomous agent who interacts with other users via X and Discord platforms. He can help users perform copy trading from expert traders in decentralized exchanges. Agent Elonos is a Based agent who monitors the base chain for pump and dump activities to alert and publish the trades to his followers. He will also perform some of the users requests for onchain activity such as deploying a ERC20 Token or NFT token.  He will also try to mimic some of the trades by buying them in  for himself and will wholeheartedly airdrop some of the tokens to his loyal followers. Agent Elonos is real Alpha Agent.

## Requirements

- Node.js 18+
- [CDP API Key](https://portal.cdp.coinbase.com/access/api)
- [OpenAI API Key](https://platform.openai.com/docs/quickstart#create-and-export-an-api-key)
- [AWS API Key] (https://ap-south-1.console.aws.amazon.com/bedrock/home?region=ap-south-1#/)
- [Discord API key]
- [Twitter API Key]

### Checking Node Version

Before using the example, ensure that you have the correct version of Node.js installed. The example requires Node.js 18 or higher. You can check your Node version by running:

```bash
node --version
npm --version
```

## Installation

```bash
npm install
```

## Run the Chatbot

### Set ENV Vars

- Ensure the following ENV Vars are set:
  - "CDP_API_KEY_NAME"
  - "CDP_API_KEY_PRIVATE_KEY"
  - "OPENAI_API_KEY"
  - "NETWORK_ID" (Defaults to `base-sepolia`)
  - "DISCORD_BOT_TOKEN"
  - "DISCORD_CHANNEL_ID"
  - "TWITTER_ACCESS_TOKEN"
  - "TWITTER_ACCESS_TOKEN_SECRET"
  - "TWITTER_API_KEY"
  - "TWITTER_API_SECRET"
  - "TWITTER_BEARER_TOKEN"
  - "BEDROCK_AWS_ACCESS_KEY_ID"
  - "BEDROCK_AWS_SECRET_ACCESS_KEY"
  - "BEDROCK_AWS_REGION="ap-south-1"

```bash
npm start
```

## License

MIT
