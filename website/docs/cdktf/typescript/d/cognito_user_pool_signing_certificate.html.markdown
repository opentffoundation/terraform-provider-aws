---
subcategory: "Cognito IDP (Identity Provider)"
layout: "aws"
page_title: "AWS: aws_cognito_user_pool_signing_certificate"
description: |-
  Get signing certificate of user pool
---


<!-- Please do not edit this file, it is generated. -->
# Data Source: aws_cognito_user_pool_signing_certificate

Use this data source to get the signing certificate for a Cognito IdP user pool.

## Example Usage

```typescript
// DO NOT EDIT. Code generated by 'cdktf convert' - Please report bugs at https://cdk.tf/bug
import { Construct } from "constructs";
import { TerraformStack } from "cdktf";
/*
 * Provider bindings are generated by running `cdktf get`.
 * See https://cdk.tf/provider-generation for more details.
 */
import { DataAwsCognitoUserPoolSigningCertificate } from "./.gen/providers/aws/data-aws-cognito-user-pool-signing-certificate";
class MyConvertedCode extends TerraformStack {
  constructor(scope: Construct, name: string) {
    super(scope, name);
    new DataAwsCognitoUserPoolSigningCertificate(this, "sc", {
      userPoolId: myPool.id,
    });
  }
}

```

## Argument Reference

* `userPoolId` - (Required) Cognito user pool ID.

## Attribute Reference

This data source exports the following attributes in addition to the arguments above:

* `certificate` - Certificate string

<!-- cache-key: cdktf-0.20.8 input-841008061a82572c40fa11d3c10bc7dfd40e9bb58c679fe5f8e62188a7dcffb2 -->