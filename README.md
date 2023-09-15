# Complete passkeys integration example for plain JavaScript with Corbado

This is a sample implementation of the Corbado web component being integrated into a web application built with JavaScript.

## File structure

- `index.html`: The login page
- `profile.html`: The profile page that is only accessible after a successful login

## Prerequisites

Please follow the steps in [Getting started](https://docs.corbado.com/overview/getting-started) to create and configure
a project in the [Corbado developer panel](https://app.corbado.com/signin#register). Most importantly, you need to
obtain a `project ID` and insert it in the code for the placeholder `<project ID>`.

## Usage
We need a local webserver to start our application. We chose the [http-server](https://www.npmjs.com/package/http-server) package for this.
Install it with

```bash
npm install --global http-server
```

Then you can run the project locally with

```bash
http-server ./
```
