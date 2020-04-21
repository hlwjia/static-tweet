# Static Tweet

Completely customizable static tweet for Next.js applications.

## Demo

https://static-tweet.now.sh/1238918791947522049

## How to use

To have a working copy of this project, run the following command:

```bash
yarn create next-app static-tweet --example https://github.com/lfades/static-tweet/tree/master
```

To have full access to all Twitter elements, like videos and polls, you'll need a Twitter API Token, once you have it, copy the [`.env.example`](.env.example) file in the root directory to `.env` (which will be ignored by Git):

```bash
cp .env.example .env
```

Once you add your API token to `.env`, it should look like this:

```bash
TWITTER_API_TOKEN=...
```

For polls, make sure that you have **Tweets and Users** from **Twitter Labs** enabled for your app. It's required to get access to polls metadata.

## Add Static Tweets to Your Project

TODO