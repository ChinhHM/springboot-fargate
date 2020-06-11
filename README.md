## Get Started

1. Create a Cloud9 environment
2. Run commands

```bash
cd springboot-fargate-cdk

npm install -g aws-cdk

npm install

cdk bootstrap aws://<account ID>/<region>

npm run build

cdk synth > infra.yaml
cdk deploy 

```
