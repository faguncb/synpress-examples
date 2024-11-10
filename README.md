# synpress examples v3

This repository contains different examples of usage for [synpress](https://github.com/Synthetixio/synpress) which is e2e testing framework for web3 dapps.

For more information about the framework, please refer to the [synpress](https://github.com/Synthetixio/synpress) repository.

🔥 Synpress works out-of-the-box with other frameworks! There is no need to use it directly.

Check [examples](https://github.com/synpress-io/synpress-examples#available-examples) below to see how to use it.

## Supported frameworks

- [synpress](https://github.com/Synthetixio/synpress)
- [Playwright](https://playwright.dev/) (as a plugin)
- [Cypress](https://github.com/cypress-io/cypress) (as a plugin)

## Supported wallets

- [MetaMask](https://metamask.io/)

## Available examples

- [Synpress](https://github.com/synpress-io/synpress-examples/tree/master/synpress) => examples of how to use synpress directly.
  - [basic](https://github.com/synpress-io/synpress-examples/tree/master/synpress/basic) => example setup of Synpress using shared state meaning that each test is run on same instance of tested website. Metamask extension state is also shared all the time.
  - [with-docker](https://github.com/synpress-io/synpress-examples/tree/master/synpress/with-docker) => example setup of Synpress using shared state meaning that each test is run on same instance of tested website. Metamask extension state is also shared all the time. It has additional docker integration with many benefits like recording of videos, VNC, noVNC and ngrok.
- [Playwright](https://github.com/synpress-io/synpress-examples/tree/master/playwright) => examples of how to use synpress with Playwright.
  - [isolated-state](https://github.com/synpress-io/synpress-examples/tree/master/playwright/isolated-state) => example setup of Playwright with synpress using isolated state meaning that each test is run in a separate browser context with fresh instance of metamask extension. Test isolation is preferred way of running tests, but it takes more time for setting up metamask extension before each test.
  - [shared-state](https://github.com/synpress-io/synpress-examples/tree/master/playwright/shared-state) => example setup of Playwright with synpress using shared state meaning that each test is run in same browser context and share same instance of metamask extension.
  - [eslint](https://github.com/synpress-io/synpress-examples/tree/master/playwright/eslint) => example setup of Playwright with synpress and eslint using isolated state.
- [Cypress](https://github.com/synpress-io/synpress-examples/tree/master/cypress) => examples of how to use synpress with Cypress.
  - [isolated-state](https://github.com/synpress-io/synpress-examples/tree/master/cypress/isolated-state) => example setup of Cypress with synpress using isolated state meaning that each test is run on fresh instance of tested website, but in same browser (works differently than Playwright which uses new browser context). Metamask extension state is shared all the time. Test isolation is preferred way of running tests.
  - [shared-state](https://github.com/synpress-io/synpress-examples/tree/master/cypress/shared-state) => example setup of Cypress with synpress using shared state meaning that each test is run on same instance of tested website. Metamask extension state is also shared all the time.
