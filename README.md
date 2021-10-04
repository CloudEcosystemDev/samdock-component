# <p align="center" width="100%"> <img src="./logo.png" width="250" height="250"> </p>

# <p align="center" width="100%"> contacts OIH Connector </p>

## Description

A generated OIH connector for the contacts API (version 0.1.0).

Generated from: https://samdock.app/api/contacts/docs-json<br/>
Generated at: 2021-10-04T11:03:22+02:00

## API Description

contacts Microservice<br/>

## Authorization

Supported authorization schemes:

- Bearer Token

## Actions

### Add lastSeen

> Add single lastSeen<br/>

#### Input Parameters

- `id` - _required_

### Bulk Delete Persons

> Delete a list of persons<br/>

_Tags:_ `persons`

### Add Person

> Create a single person<br/>

_Tags:_ `persons`

### Read Person

> Get a single person<br/>

_Tags:_ `persons`

#### Input Parameters

- `id` - _required_

### Edit Persons

> Edit single person<br/>

_Tags:_ `persons`

#### Input Parameters

- `id` - _required_

### Delete Person

> Delete a single person<br/>

_Tags:_ `persons`

#### Input Parameters

- `id` - _required_

### Add Organization

> Create an organization<br/>

_Tags:_ `organizations`

### Bulk delete organizations

> Delete a list of organizations<br/>

_Tags:_ `organizations`

### Read Organization

> Get an organization by id<br/>

_Tags:_ `organizations`

#### Input Parameters

- `id` - _required_

### Edit Organization

> Edit an organization<br/>

_Tags:_ `organizations`

#### Input Parameters

- `id` - _required_

### Delete Organization

> Delete an organization<br/>

_Tags:_ `organizations`

#### Input Parameters

- `id` - _required_

### Change Tenant logo

> Change the logo of a tenant<br/>

_Tags:_ `organizations`

#### Input Parameters

- `id` - _required_

### Delete Tenant logo

> Delete the logo of a tenant<br/>

_Tags:_ `organizations`

#### Input Parameters

- `id` - _required_

### OrganizationBranchController_addBranchToOrganization

_Tags:_ `organizations branches`

#### Input Parameters

- `organizationID` - _required_

### OrganizationBranchController_editBranchOfOrganization

_Tags:_ `organizations branches`

#### Input Parameters

- `branchID` - _required_
- `organizationID` - _required_

### OrganizationBranchController_deleteBranchOfOrganization

_Tags:_ `organizations branches`

#### Input Parameters

- `branchID` - _required_
- `organizationID` - _required_

### OrganizationContactController_relatePersonToOrganization

_Tags:_ `organizations contacts`

#### Input Parameters

- `organizationID` - _required_

### OrganizationContactController_unrelatePersonToOrganization

_Tags:_ `organizations contacts`

#### Input Parameters

- `organizationID` - _required_
- `employeeID` - _required_

### OrganizationContactController_assignContactPerson

_Tags:_ `organizations contacts`

#### Input Parameters

- `personID` - _required_
- `organizationID` - _required_

### OrganizationContactController_changeRoleOfEmployee

_Tags:_ `organizations contacts`

#### Input Parameters

- `employeeID` - _required_
- `organizationID` - _required_

### Add Draft

> Create a single draft<br/>

_Tags:_ `drafts`

#### Input Parameters

- `source` - _required_

### Read a contact draft

> Get a single contact draft<br/>

_Tags:_ `drafts`

#### Input Parameters

- `id` - _required_

### Delete a draft

> Delete a single draft<br/>

_Tags:_ `drafts`

#### Input Parameters

- `id` - _required_

### Verify a draft

_Tags:_ `drafts`

#### Input Parameters

- `id` - _required_

### Add InboundSource

> Create an organization<br/>

_Tags:_ `inbound sources`

### Read an inbound source

> Get an inbound source by id<br/>

_Tags:_ `inbound sources`

#### Input Parameters

- `id` - _required_

### Edit Inbound Source

> Edit an Inbound Source, id is not required in the body<br/>

_Tags:_ `inbound sources`

#### Input Parameters

- `id` - _required_

### Delete an inbound source

_Tags:_ `inbound sources`

#### Input Parameters

- `id` - _required_

### Add a Custom Field

> Create a custom field<br/>

_Tags:_ `custom fields`

### Browse Custom fields by entity

> Get custom fields by entity<br/>

_Tags:_ `custom fields`

#### Input Parameters

- `entity` - _required_
  Possible values: person, organization.

### Set value of Custom Field

_Tags:_ `custom fields`

#### Input Parameters

- `id` - _required_
- `entity` - _required_
  Possible values: person, organization.

### Edit Custom Field

> Edit an Custom Field, id is not required in the body<br/>

_Tags:_ `custom fields`

#### Input Parameters

- `id` - _required_
- `entity` - _required_
  Possible values: person, organization.

### Delete a custom field

_Tags:_ `custom fields`

#### Input Parameters

- `id` - _required_
- `key` - _required_
- `entity` - _required_
  Possible values: person, organization.

### Add a Contact View

> Create a contact view<br/>

_Tags:_ `contact views`

### Read an contact view

> Get an contact view by id<br/>

_Tags:_ `contact views`

#### Input Parameters

- `id` - _required_

### Edit contact view

> Edit an contact view, id is not required in the body<br/>

_Tags:_ `contact views`

#### Input Parameters

- `id` - _required_

### Delete a contact view

_Tags:_ `contact views`

#### Input Parameters

- `id` - _required_

### Get xlsx file with all persons with that import ID

> Get all persons with that import ID<br/>

_Tags:_ `import`

#### Input Parameters

- `importID` - _required_
- `lang` - _required_

### Get xlsx file with all organizations + ready for import organizations

> Get all organizations<br/>

_Tags:_ `import`

#### Input Parameters

- `lang` - _required_
- `importID` - _required_

### Upload organizations file for current import

_Tags:_ `import`

#### Input Parameters

- `importID` - _required_

### Upload persons file for current import

_Tags:_ `import`

#### Input Parameters

- `importID` - _required_

### Cancel import

_Tags:_ `import`

#### Input Parameters

- `importID` - _required_

## License

: samdock-component<br/>
<br/>

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
