---
name: Add new institutional tenant
about: Add a tenant for a Dryad member institution
title: 'Add Tenant: [InstitutionName]'
labels: ''
assignees: ''

---

**Tenant name:** 

**Logo location:** 

**Contacts to receive submission notices:** 

**RORs that are considered part of the tenant (including medical centers, alternate campuses, etc.)**

**Shibboleth info, if not in [InCommon](https://incommon.org/community-organizations/):**

**Membership model:**

Tasks:
- [ ] add config to `config/tenants`
- [ ] add logo to `app/assets/images/tenants`
- [ ] deploy and test on stage (institution should log in to verify working as expected)
- [ ] update `tenant_id` for users in the database who have emails with the institutional domain name
