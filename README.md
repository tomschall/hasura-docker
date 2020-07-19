# Realtime Chat using GraphQL Subscriptions

This is the source code for a fully working group chat app that uses subscriptions in Hasura GraphQL Engine. It is built using React and Apollo.

[![Edit chat-app](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/github/hasura/graphql-engine/tree/master/community/sample-apps/realtime-chat?fontsize=14)

-   [Fully working app](https://realtime-chat.demo.hasura.app/)
-   [Backend](https://realtime-chat.demo.hasura.app/console)

For a complete tutorial about data modelling, [check out this blog](https://hasura.io/blog/building-a-realtime-chat-app-with-graphql-subscriptions-d68cd33e73f).

Use Node Version 14.5

Run yarn

```
yarn
```

Run docker containers

```
docker-compose up -d
```

Install Hasura cli

Then run migration

```
hasura migrate apply
```
