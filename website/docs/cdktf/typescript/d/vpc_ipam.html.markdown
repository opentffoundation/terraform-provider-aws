---
subcategory: "VPC IPAM (IP Address Manager)"
layout: "aws"
page_title: "AWS: aws_vpc_ipam"
description: |-
  Terraform data source for managing a VPC IPAM.
---


<!-- Please do not edit this file, it is generated. -->
# Data Source: aws_vpc_ipam

Terraform data source for managing a VPC IPAM.

## Example Usage

### Basic Usage

```typescript
// DO NOT EDIT. Code generated by 'cdktf convert' - Please report bugs at https://cdk.tf/bug
import { Construct } from "constructs";
import { TerraformStack } from "cdktf";
/*
 * Provider bindings are generated by running `cdktf get`.
 * See https://cdk.tf/provider-generation for more details.
 */
import { DataAwsVpcIpam } from "./.gen/providers/aws/";
class MyConvertedCode extends TerraformStack {
  constructor(scope: Construct, name: string) {
    super(scope, name);
    new DataAwsVpcIpam(this, "example", {
      id: "ipam-abcd1234",
    });
  }
}

```

## Argument Reference

The following arguments are required:

* `id` - (Required) ID of the IPAM.

## Attribute Reference

This data source exports the following attributes in addition to the arguments above:

* `arn` - ARN of the IPAM.
* `defaultResourceDiscoveryAssociationId` - The default resource discovery association ID.
* `defaultResourceDiscoveryId` - The default resource discovery ID.
* `description` - Description for the IPAM.
* `enablePrivateGua` - If private GUA is enabled.
* `id` - ID of the IPAM resource.
* `ipamRegion` - Region that the IPAM exists in.
* `operatingRegions` - Regions that the IPAM is configured to operate in.
* `ownerId` - ID of the account that owns this IPAM.
* `privateDefaultScopeId` - ID of the default private scope.
* `publicDefaultScopeId` - ID of the default public scope.
* `resource_discovery_association_count` - Number of resource discovery associations.
* `scopeCount` - Number of scopes on this IPAM.
* `state` - Current state of the IPAM.
* `state_message` - State message of the IPAM.
* `tier` - IPAM Tier.
* `tags` - Tags of the IPAM resource.

<!-- cache-key: cdktf-0.20.8 input-2391be081c268ab813e6066936844d6abad7f49a8601921d1ce76c5dc91f9434 -->