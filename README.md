# Passkey-First Authentication with plain JavaScript and Corbado

This is a sample implementation of the Corbado Vanilla JavaScript component being integrated into a plain HTML, CSS &
JavaScript web application.

Please see the [full blog post](https://www.corbado.com/blog/passkeys-javascript) to understand the detailed steps
needed to integrate passkeys into JavaScript apps.

## File structure

- `index.html`: The login page
- `profile.html`: The profile page that is only accessible after a successful login

## Prerequisites

Please follow the steps in [Getting started](https://docs.corbado.com/overview/getting-started) to create and configure
a project in the [Corbado developer panel](https://app.corbado.com/signin#register). Most importantly, you need to
obtain a `project ID` and insert it in the code for the placeholder `<PROJECT_ID>`.

## Usage

We need a local webserver to start our application. We chose
the [http-server](https://www.npmjs.com/package/http-server) package for this.
Install it with

```bash
npm install --global http-server
```

Then you can run the project locally with

```bash
http-server ./
```
