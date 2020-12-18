# Lambda Template
## Purpose
  Lambda template

## Getting Started

Prerequisites:
 - [aws-vault gem](https://github.com/99designs/aws-vault) installed and configured with relevant profile.
 - [Serverless Framework](https://serverless.com/framework/docs/getting-started) installed

1. Clone the repo
2. `bundle install --deployment`
3. Deploy to dev:  `aws-vault exec dev-admin -- sls deploy`


Note: This was adapted from serverless team blog post https://www.serverless.com/blog/api-ruby-serverless-framework