---
template: sidebyside
endpoint: dcp_services
endpoint_prefix: /dcp_services/
type: POST
title: Create DCP Service
anchor: create-dcpservice
request:
  name: "My DCP Service"
response: |
  {
    "id": 567,
    "account_id": 123456,
    "archived": false,
    "aws_access_key": "123423asfakedf12vh451234",
    "aws_secret_key": "1234fake12341asdfas234zc",
    "created": "2015-08-01T11:50:37.864010Z",
    "last_modified": "2015-08-18T21:38:55.927670Z",
    "name": "My DCP Service",
    "s3_path": "dcp/567"
  }
---

Create a new DCP Service under your account.

#### Required Fields
- `name`

<div class="attention attention--warning push--bottom">
*NOTE:* The DCP Service is not yet linked to any projects. After creating a DCP Service, be sure to link a
project to the DCP Service using [update project](#update-project).  
*NOTE:* Currently, each Optimizely Account can have a maximum of one DCP Service. Please submit a support ticket if you think you have a need for multiple DCP Services.
</div>
