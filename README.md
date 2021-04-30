# aws-ec2

[pres](https://github.githistory.xyz/balazs4/aws-ec2/commits/master/cloudformation.yml)

## deploy

```bash
aws cloudformation deploy --template-file cloudformation.yml --stack-name <STACK-NAME> --parameter-overrides MyKeyPair=<KEY-PAIR>
```
