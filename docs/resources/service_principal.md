---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "adldap_service_principal Resource - terraform-provider-adldap"
subcategory: ""
description: |-
  adldap_service_principal manages an SPN attached to a user in Active Directory.
---

# adldap_service_principal (Resource)

`adldap_service_principal` manages an SPN attached to a user in Active Directory.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **samaccountname** (String) The account on which to attach the service principal.
- **spn** (String) The service principal name, usually in `{service}/{fqdn}` format

### Read-Only

- **id** (String) The ID of the SPN in {spn}---{samaccountname} format.


