# A CloudFormation custom resource example, using Lambda, for CodeDeploy
The `stack.yaml` in this repository contains everything to set use a CloudFormation custom resource. It includes everything required to set up a CodeDeploy application. With the custom resource, we add functionality for a CodeDeploy feature that is currently missing in CloudFormation.

Keep in mind that it also spins up an EC2 instance, to it might cost a few cents to spin up this stack (though the instance is eligible for the free tier).

The full stack is explained in my blog post: [A custom CloudFormation resource example for CodeDeploy](https://sanderknape.com/2017/08/custom-cloudformation-resource-example-codedeploy).
