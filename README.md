# FaunaDB GraphQL Editor

**Quickly build your GraphQL schema for FaunaDB, directly from your browser!**

The default GraphQL schema uses FaunaDB internal GraphQL definitions. (`@collection, '@relation', etc.`).

## Online demo

[Demo](https://faunadb-graphql-editor.vercel.app/) (automatically updated from the `master` branch).


## Deploy your own

Fork this template using [Vercel](https://vercel.com):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/Vadorequest/faunadbgraphql-editor&project-name=faunadbgraphql-editor&repository-name=faunadbgraphql-editor)

## A word of caution

The editor uses **the browser Local Storage** to store the GraphQL Editor schema metadata.

> **There is no way to restore lost versions**, and everything you do in your browser can be lost definitively if the local storage is cleared.

It is recommended to keep a copy of your schema somewhere (GitHub, etc.).
This way, you can quickly restore it using copy/paste right into the editor. 

## Fork

This is a fork of [personal-graphql-editor](https://github.com/Vadorequest/personal-graphql-editor).
