
# Create stack
aws cloudformation create-stack \
--profile xpeppers-test \
--stack-name codebuild-sample \
--template-body file://codebuild.yml \
--region eu-central-1 \
--capabilities CAPABILITY_IAM

# Note
[Immagini per codebuild](http://docs.aws.amazon.com/codebuild/latest/userguide/build-env-ref.html)