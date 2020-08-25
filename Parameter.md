{
    "$schema": "https://schema.management.azure.com/schemas/2015-01-01/deploymentParameters.json#",
    "contentVersion": "1.0.0.0",
    "parameters": {
        "name": {
            "value": "testchandnan"
        },
        "location": {
            "value": "eastus"
        },
        "sku": {
            "value": "Standard"
        },
        "accessPolicies": {
            "value": [
                {
                    "objectId": "c08520cd-a380-4c54-9629-3c68e1d79cbe",
                    "tenantId": "d29ae78b-4c99-47f7-b3a4-bc050911c7e2",
                    "permissions": {
                        "keys": [
                            "Get",
                            "List",
                            "Update",
                            "Create",
                            "Import",
                            "Delete",
                            "Recover",
                            "Backup",
                            "Restore"
                        ],
                        "secrets": [
                            "Get",
                            "List",
                            "Set",
                            "Delete",
                            "Recover",
                            "Backup",
                            "Restore"
                        ],
                        "certificates": [
                            "Get",
                            "List",
                            "Update",
                            "Create",
                            "Import",
                            "Delete",
                            "Recover",
                            "Backup",
                            "Restore",
                            "ManageContacts",
                            "ManageIssuers",
                            "GetIssuers",
                            "ListIssuers",
                            "SetIssuers",
                            "DeleteIssuers"
                        ]
                    }
                }
            ]
        },
        "tenant": {
            "value": "d29ae78b-4c99-47f7-b3a4-bc050911c7e2"
        },
        "enabledForDeployment": {
            "value": true
        },
        "enabledForTemplateDeployment": {
            "value": false
        },
        "enabledForDiskEncryption": {
            "value": false
        },
        "enableRbacAuthorization": {
            "value": false
        },
        "enableSoftDelete": {
            "value": true
        },
        "softDeleteRetentionInDays": {
            "value": 90
        },
        "networkAcls": {
            "value": {
                "defaultAction": "allow",
                "bypass": "AzureServices",
                "ipRules": [],
                "virtualNetworkRules": []
            }
        }
    }
}
