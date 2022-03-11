---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "cloudngfwaws_instances Data Source - cloudngfwaws"
subcategory: ""
description: |-
  Data source get a list of instances.
---

# cloudngfwaws_instances (Data Source)

Data source get a list of instances.

## Example Usage

```terraform
data "cloudngfwaws_instances" "example" {}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- **id** (String) The ID of this resource.
- **max_results** (Number) Max number of results. Defaults to `100`.
- **vpc_ids** (List of String) List of vpc ids.

### Read-Only

- **instances** (List of Object) List of instances. (see [below for nested schema](#nestedatt--instances))
- **next_token** (String) Token for the next page of results.

<a id="nestedatt--instances"></a>
### Nested Schema for `instances`

Read-Only:

- **account_id** (String)
- **name** (String)

