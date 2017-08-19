# lambda-webpack-starter
***
This a starter pack for lambda that uses webpack built with the serverless framework.

## Setup
---

* You'll need to install serverless,

`npm install -g serverless`

* and the node dependencies.

`npm install`

* Next create a serverless project with a nodejs template for lambda.

`serverless create -t aws-nodejs`

* A serverless.yml will be created in your directory. The template is pretty straight forward and includes links to serverless's documenation. 

* You'll also need to set up the [aws cli](https://aws.amazon.com/cli/) tool too, if you haven't already done so.

## Development

To run locally use:

`serverless invoke local --function <function-name>`

## Deployment

To deploy to your lambda simply type:

'serverless deploy'