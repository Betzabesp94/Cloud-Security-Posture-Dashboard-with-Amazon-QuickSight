# This public repository is for a follow along of the workshop 


As in the section [Infrastructure Deployment](https://catalog.workshops.aws/securitydashboard/en-US/build/infrastructure-deployment)

- cfn.yaml to deploy the complete workshop.
- S3AthenaWorkshopTemplate.yaml to deploy the workshop with the services already active.


```bash
chmod u+x cloudformation_templates/deploy
```

```bash
aws securityhub get-findings --region us-east-1 > findings.json
```