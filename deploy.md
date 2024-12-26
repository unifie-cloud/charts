# Deploy

```bash
cd ./helm/
helm package evershop
aws ecr-public get-login-password \
 --region us-east-1 | helm registry login \
 --username AWS \
 --password-stdin public.ecr.aws

helm push evershop-1.tgz oci://public.ecr.aws/n2j0t2f9/helm/evershop
```
