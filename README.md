# Hightower
Hightower is planned as an application for managing multiple AWS orgs.

This repo is under construction. It currently contains some starter resources:
  * A DynamoDB Table, codified using the [AWS Cloud Development Kit (CDK)](https://docs.aws.amazon.com/cdk/api/latest/docs/aws-construct-library.html);
  * CI code to deploy it to a test and prod account;
  * CI code to deploy development instances of it to forks of this repo on development branches;
  * Code to configure the CDK stack by reading [SSM parameters](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html) from the accounts where it's deployed.

