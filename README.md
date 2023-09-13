# Complete passkeys integration example for plain Javascript with Corbado

This is a sample implementation of the Corbado web component being integrated into a web application built with Javascript.

## File structure

- `src/index.html`: The login page
- `src/profile.html`: The profile page that is only accessible after a successful login
- `.env`: add Corbado project id as environment variables that you can obtain
  from [Corbado developer panel](https://app.corbado.com/signin#register)


## Prerequisites

Please follow the steps in [Getting started](https://docs.corbado.com/overview/getting-started) to create and configure
a project in the [Corbado developer panel](https://app.corbado.com/signin#register).

## Usage
We need a local webserver like [this](https://www.npmjs.com/package/http-server) to run the project locally.
Run

```bash
npm install --global http-server
```

to install the mentioned local webserver.

Finally, you can run the project locally with

```bash
npx http-server ./
```
