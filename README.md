# ![LOGO](logo.png) groov Public **flow**ground Connector

## Description

A generated **flow**ground connector for the groov Public API (version R3.3a).

Generated from: https://api.apis.guru/v2/specs/opto22.com/groov/R3.3a/swagger.json<br/>
Generated at: 2019-05-07T17:43:28+03:00

## API Description

#### Revised: 2016-09-29

### Overview
groov Public API revision 1.


## Authorization

Supported authorization schemes:
- API Key
## Actions

### Get information about groov. No authorization required.

*Tags:* `info`

### List devices available in the data store. Authorized for admins and editors.

*Tags:* `data-store`

### List tags of the given device. Authorized for admins and editors.

*Tags:* `data-store`

#### Input Parameters
* `id` - _required_ - ID of the device to use.

### Read selected tags from the data store. Authorized for admins and editors.

*Tags:* `data-store`

### Read the current value of a single tag. Authorized for admins and editors.

*Tags:* `data-store`

#### Input Parameters
* `id` - _required_ - ID of the tag to read.
* `index` - _optional_ - Table index to start reading at.
* `count` - _optional_ - Number of elements to read from a table.

### List all data store tags defined in the project. Authorized for admins and editors.

*Tags:* `data-store`

### Writes a new value to the given tag. Authorized for admins and editors.

*Tags:* `data-store`

#### Input Parameters
* `id` - _required_ - ID of the tag to write.
* `value` - _required_ - Value to write to the tag. Must be a string, number, or boolean.
* `index` - _optional_ - For array tags, the index to write the value to.

### Get information about the user you are authenticated as. Authorized for admins, editors, operators, and kiosk.

*Tags:* `whoami`

## License

**flow**ground :- Telekom iPaaS / opto-22-com-groov-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
