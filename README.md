# chatbot-AWS-CFN
chatbot using AWS CloudFormation

# To deploy-
aws cloudformation deploy \
  --template-file template.yml \
  --stack-name my-chatbot \
  --capabilities CAPABILITY_IAM