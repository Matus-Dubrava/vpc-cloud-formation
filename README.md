## instantiate template

aws cloudformation create-stack --stack-name NetworkStack --template-body file://template.yaml

## update stack

aws cloudformation update-stack --stack-name NetworkStack --template-body file://template.yaml

## describe stack

aws cloudformation describe-stacks --stack-name NetworkStack
