# Glipbot Bootstrap

## Overview

This is a simple tool to help you get your team's Glip bot off the ground.

Right now this supports creating a webhook subscription if you have the following:

1. Configured bot app in [RingCentral Developer Portal](https://developer.ringcentral.com)
1. A bot access token
1. A running bot that response on the webhook URL with the `Validation-Token` header

## Usage

### As-is

Go to: [https://grokify.github.io/glipbot-bootstrap](https://grokify.github.io/glipbot-bootstrap)

### Customize

You can customize this yourself by cloning the repo and running this locally:

```
$ git clone https://grokify.github.io/glipbot-bootstrap
```

Then you can start a local http server, such as [`http-server` on NPM](https://www.npmjs.com/package/http-server):

```bash
$ npm install http-server -g
$ http-server glipbot-bootstrap
```

The go to https://localhost:8080 in your browser, assuming `http-server` is running on port 8080.

## More Reading

Additional information and reading is available here:

1. [Glip Bot Developer Guide](http://ringcentral-api-docs.readthedocs.io/en/latest/glip_bots/)
1. [Deploy a Glip chatbot to AWS Lambda](https://medium.com/ringcentral-developers/deploy-a-glip-bot-to-aws-lambda-60a2a09ddcd4)
1. [Latest Glip bot provision flow](https://medium.com/ringcentral-developers/latest-glip-bot-provision-flow-a626a8dd0d98)