---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "pass_password Resource - terraform-provider-pass"
subcategory: ""
description: |-
  
---

# pass_password (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **path** (String) Full path where the pass data will be written

### Optional

- **data** (Map of String, Sensitive) Additional key-value data
- **id** (String) The ID of this resource.
- **password** (String, Sensitive) Secret password
- **yaml** (String, Sensitive) YAML encoded data

### Read-Only

- **body** (String) Body of the secret
- **full** (String) Entire secret contents


