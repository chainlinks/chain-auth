# Identity

Official chainlinks implementation/gateway for the ***Identity*** user-verification protocol

_Know your customer, skip in-house identity verification, all while following financial regulations and not having to worry about fraud._

## How it works

### Start validating user identities in a few steps


**1. Add a user**

   Seamlessly add users with Chainlink’s credential-based flow and post-identity requests to the API
   
    
**2. Retrieve Identity data**

   Once a user has been added, the account holder’s info can be retrieved and used at any time
   
   

```Javascript
{
  "identity": {
    "addresses": [
        {
          "accounts": [
              "Bank Checking 1234",
          ],
          "data": {
            "zip": "94117",
            "state": "CA",
            "city": "San Francisco",
            "street": "128 Block ln"
          },
          "primary": true
        }
    ],
    "emails": [
      {
        "primary": true,
        "type": "personal",
        "data": "jane.doe@example.com"
      }
    ],
    "names": [
        "Jane Doe"
    ],
    "phone_numbers": [
      {
        "primary": true,
        "type": "home",
        "data": "415-555-5555"
      }
    ]
  }
  
```
