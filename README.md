# aws-packer-skeleton
A packer skeleton used to build my AWS AMI's

## Config
This following example uses setting variables from a file but you could choose another type of [setting vars].

## Usage

```
packer build --var-file credentials.json templates/skeleton.json
```

[setting vars]: <https://www.packer.io/docs/templates/user-variables.html>

