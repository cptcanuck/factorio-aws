
## Deploy

```aws cloudformation create-stack --template-body file://factorio.template --stack-name factorio-server --parameters ParameterKey=SaveGameBucketName,ParameterValue=toddfactorio ParameterKey=SSHCidrBlock,ParameterValue=194.59.251.4/32```
