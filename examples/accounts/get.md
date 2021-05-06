# Show Accessible Accounts

Show all Accounts the active User can access and with what permission level.
Includes their own Account if they have one.

**URL** : `/api/generate/`

**Method** : `POST`

**Auth required** : YES

**Permissions required** : None

**Parameters** : `{"parameters":["one","two"],"values":["123","3243"], "base64PDF":"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"}`

## Success Responses

**Condition** : User can not see any Accounts.

**Code** : `200 OK`

**Content** : `{[]}`

### OR

**Condition** : User can see one or more Accounts.

**Code** : `200 OK`

**Content** : In this example, the User can see three Accounts as AccountAdmin
`AA`, Viewer `VV`, and Owner `OO` - in that order:

```json
[
    {
        "account": {
            "id": 123,
            "name": "Lots of Admins Project",
            "enterprise": false,
            "url": "http://testserver/api/accounts/123/"
        },
        "permission": "AA"
    },
    {
        "account": {
            "id": 234,
            "name": "Feel free to View this",
            "enterprise": false,
            "url": "http://testserver/api/accounts/234/"
        },
        "permission": "VV"
    },
    {
        "account": {
            "id": 345,
            "name": "Mr Owner Project",
            "enterprise": false,
            "url": "http://testserver/api/accounts/345/"
        },
        "permission": "OO"
    }
]
```
