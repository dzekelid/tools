{
  "info": {
    "name": "Akamai API List Locations",
    "_postman_id": "44784d65-7ad9-4a9b-981e-6ff4d4409683",
    "description": "List Locations",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Galaxy",
      "item": [
        {
          "id": "d48d9cc5-1332-4565-a9d7-2ad07240649c",
          "name": "galaxyv1customersincludedeleteddebug",
          "request": {
            "url": "http://developer.akamai.com/galaxy/v1/customers?debug=debug&includeDeleted=includeDeleted",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Customers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "775b0ff3-c4c5-4f8b-8bdd-963c0c534215"
            }
          ]
        },
        {
          "id": "98aa0796-111a-4028-bb95-c3d44224125c",
          "name": "galaxyv1customers",
          "request": {
            "url": "http://developer.akamai.com/galaxy/v1/customers?akamaiCustomerId=akamaiCustomerId&debug=debug",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add a Customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "88cbfd11-d364-4cc3-bf88-1097bca69902"
            }
          ]
        },
        {
          "id": "d3d71983-143e-4295-accc-2e75ad6d867a",
          "name": "galaxyv1customersakamaicustomerid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/customers/:akamaiCustomerId"
              ],
              "variable": [
                {
                  "id": "akamaiCustomerId",
                  "value": "akamaiCustomerId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a Customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30559594-2228-42f0-9749-ed63614d9e05"
            }
          ]
        },
        {
          "id": "27f108b6-4479-4aec-8912-f66be080fbac",
          "name": "galaxyv1customersakamaicustomerid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/customers/:akamaiCustomerId"
              ],
              "variable": [
                {
                  "id": "akamaiCustomerId",
                  "value": "akamaiCustomerId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8346a385-8453-4c10-9644-1be66fd5d031"
            }
          ]
        },
        {
          "id": "57339818-70df-4f20-acab-ed0acb284931",
          "name": "galaxyv1customersakamaicustomeridopdeactivate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/customers/:akamaiCustomerId/op/deactivate"
              ],
              "variable": [
                {
                  "id": "akamaiCustomerId",
                  "value": "akamaiCustomerId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Deactivate a Customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "44a5157e-dc6b-4c56-8541-e60292c79169"
            }
          ]
        },
        {
          "id": "d96668be-85e7-477d-9af7-aa7118b4b6b6",
          "name": "galaxyv1customersakamaicustomeridopreactivate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/customers/:akamaiCustomerId/op/reactivate"
              ],
              "variable": [
                {
                  "id": "akamaiCustomerId",
                  "value": "akamaiCustomerId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Reactivate a Customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a33aff34-3e9b-41fc-b7af-4a3d65ddbb19"
            }
          ]
        },
        {
          "id": "bcb63170-c44c-4a24-ae96-bfa0fa5ab13f",
          "name": "galaxyv1clientsincludedeleteddebugself",
          "request": {
            "url": "http://developer.akamai.com/galaxy/v1/clients?debug=debug&includeDeleted=includeDeleted&self=self",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Clients"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "efe7634b-025f-44ac-8803-e858e542b524"
            }
          ]
        },
        {
          "id": "433a4f84-1dc5-4464-8fbf-f6800bbd2e99",
          "name": "galaxyv1clients",
          "request": {
            "url": "http://developer.akamai.com/galaxy/v1/clients?clientId=clientId&debug=debug",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add a Client"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ad208ec7-38ae-4bd1-9851-41e3675e6375"
            }
          ]
        },
        {
          "id": "f852970e-2a7f-42f3-a970-8c4bf7630ed5",
          "name": "galaxyv1clientsclientid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/clients/:clientId"
              ],
              "variable": [
                {
                  "id": "clientId",
                  "value": "clientId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a Client"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1f44e2d-af79-40e3-94ef-14240e724db9"
            }
          ]
        },
        {
          "id": "9acd9465-9bc8-41d6-afd9-1e5e8c3fe50b",
          "name": "galaxyv1clientsclientid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/clients/:clientId"
              ],
              "variable": [
                {
                  "id": "clientId",
                  "value": "clientId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Client"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b0326919-0983-4665-9af4-4a142c2966b1"
            }
          ]
        },
        {
          "id": "70821c42-a167-42c7-a7e5-ffa89e4f74de",
          "name": "galaxyv1customersclientidopdeactivate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/customers/:clientId/op/deactivate"
              ],
              "variable": [
                {
                  "id": "clientId",
                  "value": "clientId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Deactivate a Client"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "16f5146a-4ba3-4888-bce7-732779b76318"
            }
          ]
        },
        {
          "id": "5b1d1e95-9da3-474a-b155-266cfc4a8410",
          "name": "galaxyv1customersclientidopreactivate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/customers/:clientId/op/reactivate"
              ],
              "variable": [
                {
                  "id": "clientId",
                  "value": "clientId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Reactivate a Client"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4e2b900e-429e-4aed-b139-326005a78191"
            }
          ]
        },
        {
          "id": "bab3690e-8ee5-4bae-bb35-7e93e73d6989",
          "name": "galaxyv1client-groupsincludedeleteddebugself",
          "request": {
            "url": "http://developer.akamai.com/galaxy/v1/client_groups?debug=debug&includeDeleted=includeDeleted",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Client Groups"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0e2e81ef-1cb5-4d11-8bc9-50bdc6b599e1"
            }
          ]
        },
        {
          "id": "fdd22565-07bc-413c-9040-5a612a708784",
          "name": "galaxyv1client-groups",
          "request": {
            "url": "http://developer.akamai.com/galaxy/v1/client_groups?debug=debug&includeDeleted=includeDeleted",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Associate Multiple Activation Files for a DPC"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e9e74033-5806-4a97-8dfa-de5bf2a45c5e"
            }
          ]
        },
        {
          "id": "9670d0a3-4690-46ca-9052-db62feb79db4",
          "name": "galaxyv1devicesdeviceiddebug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/devices/:deviceId"
              ],
              "query": [
                {
                  "key": "debug",
                  "value": "debug",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "deviceId",
                  "value": "deviceId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Device"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "97df682a-6e1c-46e4-9166-b77d2e95fdde"
            }
          ]
        },
        {
          "id": "6d95adba-8062-4e79-8d1c-70099495edae",
          "name": "galaxyv1devicesdeviceid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/devices/:deviceId"
              ],
              "variable": [
                {
                  "id": "deviceId",
                  "value": "deviceId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a Device"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f7f58f10-f1aa-4b51-beea-dba6cdef292e"
            }
          ]
        },
        {
          "id": "4d5bf444-2dd8-467c-9ad0-83eb08222c3a",
          "name": "galaxyv1devicesdeviceid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/devices/:deviceId"
              ],
              "variable": [
                {
                  "id": "deviceId",
                  "value": "deviceId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add a Device"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea75d5dc-7384-4775-9b33-3534b4ff059a"
            }
          ]
        },
        {
          "id": "1a9db5a0-6ea5-4cb8-a57c-eab9cde142ab",
          "name": "galaxyv1devicesdeviceid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/devices/:deviceId"
              ],
              "variable": [
                {
                  "id": "deviceId",
                  "value": "deviceId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Device"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d8819ae0-cd68-4678-bbc0-788d53077468"
            }
          ]
        },
        {
          "id": "75d31b7d-c17c-4d68-8eba-c7bba40dbcdc",
          "name": "galaxyv1devicesdeviceidopdeactivate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/devices/:deviceId/op/deactivate"
              ],
              "variable": [
                {
                  "id": "deviceId",
                  "value": "deviceId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Deactivate a Device"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7e9fe038-3d6f-478b-b758-a71489cff848"
            }
          ]
        },
        {
          "id": "afee2ba1-5859-4a36-84fe-24a552c19451",
          "name": "galaxyv1devicesdeviceidopreactivate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/devices/:deviceId/op/reactivate"
              ],
              "variable": [
                {
                  "id": "deviceId",
                  "value": "deviceId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Reactivate a Device"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "067af1a0-0322-4a3d-a713-bebe5b6a3038"
            }
          ]
        },
        {
          "id": "0b88bdd5-c600-4ddb-a4ed-063c4bc0b4df",
          "name": "galaxyv1build",
          "request": {
            "url": "http://developer.akamai.com/galaxy/v1/build",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Build Information"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ac83f1a-6a02-4930-a831-7bca642f3c31"
            }
          ]
        }
      ]
    },
    {
      "name": "Billing",
      "item": [
        {
          "id": "a11eb1a5-8d76-4611-9665-4d0a9443fdb1",
          "name": "billingcenterapiv2contractscontractidproductsproductidstatisticsyearmonthfromyearfrommonthtoyeartomo",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "billing-center-api/v2/contracts/:contractId/products/:productId/statistics"
              ],
              "query": [
                {
                  "key": "fromMonth",
                  "value": "fromMonth",
                  "disabled": false
                },
                {
                  "key": "fromYear",
                  "value": "fromYear",
                  "disabled": false
                },
                {
                  "key": "month",
                  "value": "month",
                  "disabled": false
                },
                {
                  "key": "toMonth",
                  "value": "toMonth",
                  "disabled": false
                },
                {
                  "key": "toYear",
                  "value": "toYear",
                  "disabled": false
                },
                {
                  "key": "year",
                  "value": "year",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "contractId",
                  "value": "contractId",
                  "type": "string"
                },
                {
                  "id": "productId",
                  "value": "productId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Statistics per Contract"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bcc9275d-75db-4995-863a-3e18fe39bbb4"
            }
          ]
        },
        {
          "id": "f51c735f-2ba6-4e84-abc7-50f302c90e48",
          "name": "billingcenterapiv2contractscontractidproductsproductidmeasuresyearmonthfromyearfrommonthtoyeartomont",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "billing-center-api/v2/contracts/:contractId/products/:productId/measures"
              ],
              "query": [
                {
                  "key": "billingDayOnly",
                  "value": "billingDayOnly",
                  "disabled": false
                },
                {
                  "key": "fromMonth",
                  "value": "fromMonth",
                  "disabled": false
                },
                {
                  "key": "fromYear",
                  "value": "fromYear",
                  "disabled": false
                },
                {
                  "key": "month",
                  "value": "month",
                  "disabled": false
                },
                {
                  "key": "statisticName",
                  "value": "statisticName",
                  "disabled": false
                },
                {
                  "key": "toMonth",
                  "value": "toMonth",
                  "disabled": false
                },
                {
                  "key": "toYear",
                  "value": "toYear",
                  "disabled": false
                },
                {
                  "key": "year",
                  "value": "year",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "contractId",
                  "value": "contractId",
                  "type": "string"
                },
                {
                  "id": "productId",
                  "value": "productId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Usage per Contract"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae62c474-18a7-40a1-877b-b1406bdb2ebf"
            }
          ]
        },
        {
          "id": "f0738d23-19a7-423e-ac02-2e6befa8cd2c",
          "name": "billingcenterapiv2reportinggroupsreportinggroupidproductsproductidstatisticsyearmonthfromyearfrommon",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "billing-center-api/v2/reporting-groups/:reportingGroupId/products/:productId/statistics"
              ],
              "query": [
                {
                  "key": "fromMonth",
                  "value": "fromMonth",
                  "disabled": false
                },
                {
                  "key": "fromYear",
                  "value": "fromYear",
                  "disabled": false
                },
                {
                  "key": "month",
                  "value": "month",
                  "disabled": false
                },
                {
                  "key": "toMonth",
                  "value": "toMonth",
                  "disabled": false
                },
                {
                  "key": "toYear",
                  "value": "toYear",
                  "disabled": false
                },
                {
                  "key": "year",
                  "value": "year",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "productId",
                  "value": "productId",
                  "type": "string"
                },
                {
                  "id": "reportingGroupId",
                  "value": "reportingGroupId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Statistics per Reporting Group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "807370b1-8bbf-4528-a41d-7117a8bff7f3"
            }
          ]
        },
        {
          "id": "95c42c25-6548-42e7-9448-ed64971be047",
          "name": "billingcenterapiv2reportinggroupsreportinggroupidproductsproductidmeasuresyearmonthfromyearfrommonth",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "billing-center-api/v2/reporting-groups/:reportingGroupId/products/:productId/measures"
              ],
              "query": [
                {
                  "key": "billingDayOnly",
                  "value": "billingDayOnly",
                  "disabled": false
                },
                {
                  "key": "fromMonth",
                  "value": "fromMonth",
                  "disabled": false
                },
                {
                  "key": "fromYear",
                  "value": "fromYear",
                  "disabled": false
                },
                {
                  "key": "month",
                  "value": "month",
                  "disabled": false
                },
                {
                  "key": "statisticName",
                  "value": "statisticName",
                  "disabled": false
                },
                {
                  "key": "toMonth",
                  "value": "toMonth",
                  "disabled": false
                },
                {
                  "key": "toYear",
                  "value": "toYear",
                  "disabled": false
                },
                {
                  "key": "year",
                  "value": "year",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "productId",
                  "value": "productId",
                  "type": "string"
                },
                {
                  "id": "reportingGroupId",
                  "value": "reportingGroupId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Usage per Reporting Group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c35c1a4b-8e5d-44d9-b3d2-25f30c2a194f"
            }
          ]
        }
      ]
    },
    {
      "name": "Cases",
      "item": [
        {
          "id": "39f03285-ca7f-4a31-9c9a-dcd947a7715d",
          "name": "casesv1category",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cases/v1/:category"
              ],
              "variable": [
                {
                  "id": "category",
                  "value": "category",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Cases per Category"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "026caeaa-56a7-4cf0-b8a4-2a9f01e6ada3"
            }
          ]
        },
        {
          "id": "f76ad88a-e232-49d1-b73d-45d5de09178f",
          "name": "casesv1category",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cases/v1/:category"
              ],
              "variable": [
                {
                  "id": "category",
                  "value": "category",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Case"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aea7edc4-e751-4218-bb7c-9039713ab3f8"
            }
          ]
        },
        {
          "id": "ad81a37b-c1fc-4bf1-88d7-9aef0ededef9",
          "name": "casesv1ps",
          "request": {
            "url": "http://developer.akamai.com/cases/v1/PS",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Professional Services Cases"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6a635ba1-01dd-4111-a1a5-7949cf497fb8"
            }
          ]
        },
        {
          "id": "21718c54-2a22-4ae1-b962-799364380c85",
          "name": "casesv1ps",
          "request": {
            "url": "http://developer.akamai.com/cases/v1/PS",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Professional Services Case"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "476b0e8c-daad-4300-aec8-a3d3efb5960d"
            }
          ]
        },
        {
          "id": "0b724443-4f0c-4b41-88c6-1c91744fb235",
          "name": "casesv1portaluserstatustypecategory",
          "request": {
            "url": "http://developer.akamai.com/cases/v1/portal-user?category=category&status=status&type=type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Cases"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eef5e3e4-0df1-4381-ab84-e4217098b8d7"
            }
          ]
        },
        {
          "id": "7d09f63d-8730-4e68-8738-affe1a59187c",
          "name": "casesv1portalusercasecaseid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cases/v1/portal-user/case/:caseId"
              ],
              "variable": [
                {
                  "id": "caseId",
                  "value": "caseId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Case"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7882554a-8c35-4b91-9755-bddf418b592b"
            }
          ]
        },
        {
          "id": "c19c0219-950b-46d3-a80f-67147eefd12d",
          "name": "casesv1portalusercasecaseidnotes",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cases/v1/portal-user/case/:caseId/notes"
              ],
              "variable": [
                {
                  "id": "caseId",
                  "value": "caseId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Comment on a Case"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3e880469-7811-4f2c-9d56-f4f429162f29"
            }
          ]
        },
        {
          "id": "5c55fc9c-676b-42ad-b312-894d22404f42",
          "name": "casesv1portalusercasecaseidfiles",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cases/v1/portal-user/case/:caseId/files"
              ],
              "variable": [
                {
                  "id": "caseId",
                  "value": "caseId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Upload a File Attachment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b592164b-12eb-48ec-87d9-e5a4a74948cd"
            }
          ]
        },
        {
          "id": "42d72c08-a792-45f5-948e-b3a6b4fd8f75",
          "name": "casesv1portalusercasecaseidrequestclose",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cases/v1/portal-user/case/:caseId/request-close"
              ],
              "variable": [
                {
                  "id": "caseId",
                  "value": "caseId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Close a Request"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "95b3b60b-5612-4095-a308-86e33f077723"
            }
          ]
        }
      ]
    },
    {
      "name": "Ccu",
      "item": [
        {
          "id": "2f0a7e4d-5f2b-41da-a418-3f1eae7035bc",
          "name": "ccuv3invalidateurlnetwork",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "ccu/v3/invalidate/url/:network"
              ],
              "variable": [
                {
                  "id": "network",
                  "value": "network",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Invalidate by URL"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ccfb26f0-e074-40c8-bbfd-2dab8e8fa771"
            }
          ]
        },
        {
          "id": "b38e7b07-b268-47fb-8f60-71e93ba53078",
          "name": "ccuv3deleteurlnetwork",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "ccu/v3/delete/url/:network"
              ],
              "variable": [
                {
                  "id": "network",
                  "value": "network",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Delete by URL"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4203d4d9-9c46-4c9d-83dd-f0a0abeaf91b"
            }
          ]
        },
        {
          "id": "3d884892-d241-46f6-8f20-2cc255455a3c",
          "name": "ccuv2queuesqueuename",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "ccu/v2/queues/:queueName"
              ],
              "variable": [
                {
                  "id": "queueName",
                  "value": "queueName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Current Queue Size"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4270f832-500a-40c5-9909-c11440146ecc"
            }
          ]
        },
        {
          "id": "d5e259f3-bf8b-48a0-8ccb-ab749d1fdbf2",
          "name": "ccuv2queuesqueuename",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "ccu/v2/queues/:queueName"
              ],
              "variable": [
                {
                  "id": "queueName",
                  "value": "queueName",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add a Request"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f8c01f9d-83b4-4547-9231-366375af8d15"
            }
          ]
        },
        {
          "id": "e97bab91-1325-43cf-95e0-6a7c55d0a4e7",
          "name": "ccuv2purgespurgeid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "ccu/v2/purges/:purgeId"
              ],
              "variable": [
                {
                  "id": "purgeId",
                  "value": "purgeId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Purge Status"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6807f295-d518-41c5-bb22-d88fdef17c02"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudlet",
      "item": [
        {
          "id": "f35fb889-428a-45bf-975e-3f8fa86081fc",
          "name": "cloudletid",
          "request": {
            "url": "http://developer.akamai.com/cloudletId?cloudletId=cloudletId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Cloudlets"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1035816c-da5b-4754-9542-4c11b241a380"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudlets",
      "item": [
        {
          "id": "0a33c3fe-fa13-4905-a4df-ef12d9b5e7ae",
          "name": "cloudletsapiv2groupinfo",
          "request": {
            "url": "http://developer.akamai.com/cloudlets/api/v2/group-info",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Groups"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5189a053-af8f-43f2-b656-6071ddcf116a"
            }
          ]
        },
        {
          "id": "7f33cc70-e282-41a1-a19d-21930c7439a2",
          "name": "cloudletsapiv2groupinfogroupid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/group-info/:groupId"
              ],
              "variable": [
                {
                  "id": "groupId",
                  "value": "groupId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae341052-057f-4ef2-b592-3c978011f767"
            }
          ]
        },
        {
          "id": "a011ec26-3317-4980-9c62-ec319be857c3",
          "name": "cloudletsapiv2policiesgidincludedeletedcloudletid",
          "request": {
            "url": "http://developer.akamai.com/cloudlets/api/v2/policies?cloudletId=cloudletId&gid=gid&includeDeleted=includeDeleted",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Policies"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "788ddebc-96ff-4fbb-8301-6ad7c5592340"
            }
          ]
        },
        {
          "id": "4fd52bf0-c644-4222-b481-4f7bee7a8c46",
          "name": "cloudletsapiv2policiesclonepolicyidversion",
          "request": {
            "url": "http://developer.akamai.com/cloudlets/api/v2/policies?clonePolicyId=clonePolicyId&version=version",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a4e31f9c-95f7-4e70-94b1-820cbfd42098"
            }
          ]
        },
        {
          "id": "7c29a801-3d2f-4da3-ac82-0825a166a4b4",
          "name": "cloudletsapiv2policiespolicyid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId"
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8acd8e9d-2615-4741-9867-d291a08ea7cc"
            }
          ]
        },
        {
          "id": "7104810f-a74e-4e4d-aff7-7120a0f88fa9",
          "name": "cloudletsapiv2policiespolicyid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId"
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5acc8ad8-7d36-47dc-8015-bfb8eca343a3"
            }
          ]
        },
        {
          "id": "b3d96c1a-1bf7-47c2-b906-b07039fd86e7",
          "name": "cloudletsapiv2policiespolicyid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId"
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2024655b-8237-478e-9465-c82735351726"
            }
          ]
        },
        {
          "id": "0ad7c1e6-f4d7-42f1-8140-215f7c464e04",
          "name": "cloudletsapiv2policiespolicyidversionsincluderulesmatchruleformat",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions"
              ],
              "query": [
                {
                  "key": "includeRules",
                  "value": "includeRules",
                  "disabled": false
                },
                {
                  "key": "matchRuleFormat",
                  "value": "matchRuleFormat",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Policy Versions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a14830cc-ecbd-463c-8d63-72e9d954a6be"
            }
          ]
        },
        {
          "id": "8dbac49c-5449-451f-a975-225644edc1f5",
          "name": "cloudletsapiv2policiespolicyidversionsmatchruleformatcloneversion",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions"
              ],
              "query": [
                {
                  "key": "cloneVersion",
                  "value": "cloneVersion",
                  "disabled": false
                },
                {
                  "key": "matchRuleFormat",
                  "value": "matchRuleFormat",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a New Policy Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "23b4e70e-97cf-4b0a-8a6a-a6f05c301ed1"
            }
          ]
        },
        {
          "id": "71dd08be-e448-4203-9a36-770707e18acd",
          "name": "cloudletsapiv2policiespolicyidversionsversionomitrulesmatchruleformat",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions/:version"
              ],
              "query": [
                {
                  "key": "matchRuleFormat",
                  "value": "matchRuleFormat",
                  "disabled": false
                },
                {
                  "key": "omitRules",
                  "value": "omitRules",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "version",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Policy Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f829802-31a0-48b9-8f93-843bf6455efa"
            }
          ]
        },
        {
          "id": "56d1850a-70b7-4c93-8e5f-29deae5b252e",
          "name": "cloudletsapiv2policiespolicyidversionsversionmatchruleformat",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions/:version"
              ],
              "query": [
                {
                  "key": "matchRuleFormat",
                  "value": "matchRuleFormat",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "version",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update a Policy Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e3c6c486-1205-4d35-a079-746bfc4f1fe3"
            }
          ]
        },
        {
          "id": "9e2bb9ea-a73e-4562-a326-bd9166380537",
          "name": "cloudletsapiv2policiespolicyidversionsversionomitrulesmatchruleformat",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions/:version"
              ],
              "query": [
                {
                  "key": "matchRuleFormat",
                  "value": "matchRuleFormat",
                  "disabled": false
                },
                {
                  "key": "omitRules",
                  "value": "omitRules",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "version",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Policy Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d1197df0-c9f8-4578-ba26-8a965ee05a9d"
            }
          ]
        },
        {
          "id": "3b9116c0-8e9a-49a4-b715-a62a1f0ff401",
          "name": "cloudletsapiv2policiespolicyidversionsversionrulesindex",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions/:version/rules"
              ],
              "query": [
                {
                  "key": "index",
                  "value": "index",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "version",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add a Version Rule"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "46ac213a-428f-48eb-be0b-a83fcf021171"
            }
          ]
        },
        {
          "id": "68aaa85a-d393-4d49-bcf5-542526c7909f",
          "name": "cloudletsapiv2policiespolicyidversionsversionrulesakaruleid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions/:version/rules/:akaRuleId"
              ],
              "variable": [
                {
                  "id": "akaRuleId",
                  "value": "akaRuleId",
                  "type": "string"
                },
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "version",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Version Rule"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0e1ba82f-3f7b-4ae4-aac9-58443bace6dc"
            }
          ]
        },
        {
          "id": "e5c42455-4122-4476-8a3d-f4ff42b0fff4",
          "name": "cloudletsapiv2policiespolicyidversionsversionrulesakaruleid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions/:version/rules/:akaRuleId"
              ],
              "variable": [
                {
                  "id": "akaRuleId",
                  "value": "akaRuleId",
                  "type": "string"
                },
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "version",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update a Version Rule"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9517f194-c44c-405d-ad53-d43c176cee42"
            }
          ]
        },
        {
          "id": "cf7aa111-4724-49e2-9c30-74b9e03ec4b5",
          "name": "cloudletsapiv2properties",
          "request": {
            "url": "http://developer.akamai.com/cloudlets/api/v2/properties",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Associated Properties"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4cf2b88f-30c5-41c2-b523-9108fda8a06a"
            }
          ]
        },
        {
          "id": "9f3e078a-2438-4413-b212-ab6a16ece6b7",
          "name": "cloudletsapiv2policyidproperties",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/:policyId/properties"
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Associated Properties for a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c59151b1-1e72-4953-85ff-127f6893932c"
            }
          ]
        },
        {
          "id": "a18b07c2-60af-43b0-af87-b53d7dc4c051",
          "name": "cloudletsapiv2originstype",
          "request": {
            "url": "http://developer.akamai.com/cloudlets/api/v2/origins?type=type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Cloudlets Origins"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b9d04b0e-a6e6-4d52-8474-3a20a460c69b"
            }
          ]
        },
        {
          "id": "e24e1cff-3d69-4a9d-b07d-e6044baa7c56",
          "name": "cloudletsapiv2originsoriginid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/origins/:originId"
              ],
              "variable": [
                {
                  "id": "originId",
                  "value": "originId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Cloudlets Origin"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f383ffa-c472-4cb2-9f66-99f184d6e171"
            }
          ]
        },
        {
          "id": "85587f7b-9841-4e94-85cf-0a947243d183",
          "name": "cloudletsapiv2originsoriginid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/origins/:originId"
              ],
              "variable": [
                {
                  "id": "originId",
                  "value": "originId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update a Cloudlets Origin"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "107a2d8b-513a-4b40-bcd6-c88ca8d47531"
            }
          ]
        },
        {
          "id": "72b6ce0f-49e5-43f4-a9d7-b3c0034e7989",
          "name": "cloudletsapiv2originsoriginidversions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/origins/:originId/versions"
              ],
              "variable": [
                {
                  "id": "originId",
                  "value": "originId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Cloudlets Origin Versions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e57fd6f-b379-49d7-8f64-afcd3dde666e"
            }
          ]
        },
        {
          "id": "d06cc325-41a1-4560-b9f8-6f854c607113",
          "name": "cloudletsapiv2originsoriginidversions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/origins/:originId/versions"
              ],
              "variable": [
                {
                  "id": "originId",
                  "value": "originId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Cloudlets Origin Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "46f2957e-e45e-4e30-8036-78674666e17e"
            }
          ]
        },
        {
          "id": "5d046636-d078-459b-83b9-02cb32c6f401",
          "name": "cloudletsapiv2originsoriginidversionsversionvalidate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/origins/:originId/versions/:version"
              ],
              "query": [
                {
                  "key": "validate",
                  "value": "validate",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "originId",
                  "value": "originId",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "version",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Cloudlets Origin Version"
          },
          "response": [
            {
              "status": "OK",