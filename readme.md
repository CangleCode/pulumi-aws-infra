# Pulumi AWS Infrastructure

This is the accompanying repository to the video ["Get started with Pulumi & AWS Serverless for Jamstack Apps / Infrastructure as Code [PART 1]"](https://youtu.be/DHAqeE8zu9c).

## Required Pulumi Config

```
originDomain // example: https://www.origin-domain.com
apiDomain // example: api.domain.com
mailDomain // example: domain.com
contactEmail // example: contact@domain.com
```

## To deploy run

```bash
yarn deploy:development
// or npm run deploy:development
```

or

```bash
yarn deploy:production
// or npm run deploy:production
```

> Those package.json scripts are convenience helpers and configure Pulumi to use Yarn, set NODE_ENV and select the right Pulumi stack.
