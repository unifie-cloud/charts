# EverShop helm chart

[Evershop](https://evershop.io) - NodeJS E-commerce Platform

# Usage

```bash
helm repo add unifie https://unifie-cloud.github.io/charts/helm
```

## Globals variables

| Name                            | Description       |
| ------------------------------- | ----------------- |
| global.postgresql.auth.database | Database name     |
| global.postgresql.auth.username | Database username |
| global.postgresql.auth.password | Database password |
| global.postgresql.auth.port     | Database port     |
| global.postgresql.auth.host     | Database host     |

## Variables

| Name           | Description                                |
| -------------- | ------------------------------------------ |
| evershop.image | Image (default `evershop/evershop:latest`) |

## Tip

Add extension [Amazon S3 Storage](https://evershop.io/extensions) or [Azure Blob Storage](https://evershop.io/extensions) for storing media files separately from deployment.
It will allow to use stateless deployment instead of Stateful.

## Source code

[Source code](https://github.com/unifie-cloud/charts/tree/main/helm/evershop)

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/unifie)](https://artifacthub.io/packages/search?repo=unifie)
