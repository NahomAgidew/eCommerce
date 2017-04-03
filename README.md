# Reaction

[![bitHound Overall Score](https://www.bithound.io/github/reactioncommerce/reaction/badges/score.svg)](https://www.bithound.io/github/reactioncommerce/reaction) [![bitHound Dev Dependencies](https://www.bithound.io/github/reactioncommerce/reaction/badges/devDependencies.svg)](https://www.bithound.io/github/reactioncommerce/reaction/9a858eb459d7260d5ae59124c2b364bc791a3e70/dependencies/npm) [![bitHound Code](https://www.bithound.io/github/reactioncommerce/reaction/badges/code.svg)](https://www.bithound.io/github/reactioncommerce/reaction) [![Circle CI](https://circleci.com/gh/reactioncommerce/reaction.svg?style=svg)](https://circleci.com/gh/reactioncommerce/reaction) [![Gitter](https://badges.gitter.im/JoinChat.svg)](https://gitter.im/reactioncommerce/reaction?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This is a completely generic eCommerce website built with Node.js on top of the Reaction framework. 

![Reaction v.1.0.0](https://raw.githubusercontent.com/reactioncommerce/reaction-docs/master/assets/rc-desktop.png)

## Features

Reaction’s out-of-the-box core features include:

* Drag-and-drop merchandising
* Order processing
* Payments
* Shipping
* Taxes
* Discounts
* Analytics
* Integration with dozens of third-party apps

And, since anything in our codebase can be extended, overwritten, or installed as a package, you may also develop, scale, and customize anything on our platform.

## Installation

**_reaction-cli installation_**

```bash
npm install -g reaction-cli
reaction init
cd reaction
reaction
```

For more information on setup and configuration, check out the [installation](https://docs.reactioncommerce.com/reaction-docs/development/installation) and [configuration](https://docs.reactioncommerce.com/reaction-docs/development/configuration) docs.


### Testing

Testing is another great way to contribute. If you do discover a bug, [create an issue](https://github.com/reactioncommerce/reaction/issues/new) to report it.

Integration tests can be run at the command line with `reaction test`. Use `npm run-script test-local` to run local tests.
