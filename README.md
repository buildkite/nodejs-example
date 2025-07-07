# Buildkite Node.js Example

[![Build status](https://badge.buildkite.com/e21216a03d600c23dbc8329539efc088264fae90e5a81940f2.svg?branch=main)](https://buildkite.com/buildkite/nodejs-example/builds/latest?branch=main)
[![Add to Buildkite](https://img.shields.io/badge/Add%20to%20Buildkite-14CC80)](https://buildkite.com/new)

This repository is an example [Buildkite](https://buildkite.com/) pipeline that runs tests for a [Node.js](https://nodejs.org/) project.

👉 **See this example in action:** [buildkite/nodejs-example](https://buildkite.com/buildkite/nodejs-example/builds/latest?branch=main)

[![Add to Buildkite](https://buildkite.com/button.svg)](https://buildkite.com/new)

<a href="https://buildkite.com/buildkite/nodejs-example/builds/latest?branch=main">
  <img width="1491" alt="Screenshot of Buildkite Node.js example pipeline" src=".buildkite/screenshot.png" />
</a>

<!-- docs:start -->

## How it works

This example:
- Runs `npm install` and `npm test` using Node.js
- Assumes Node.js is already available on the agent machine

> 💡 If you prefer to use Docker instead of installing Node.js directly, check out the [Node.js Docker Example](https://github.com/buildkite/nodejs-docker-example).

<!-- docs:end -->

## License

See [LICENSE.md](LICENSE.md) (MIT)
