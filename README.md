{
    "protoPayload": {
      "@type": "type.googleapis.com/google.cloud.audit.AuditLog",
      "status": {},
      "authenticationInfo": {
        "principalEmail": "kaitlynmalone094@gmail.com",
        "principalSubject": "user:kaitlynmalone094@gmail.com"
      },
      "requestMetadata": {
        "callerIp": "2600:387:c:7132::6",
        "callerSuppliedUserAgent": "Mozilla/5.0 (Linux; Android 11; moto g stylus 5G) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/99.0.4844.88 Mobile Safari/537.36,gzip(gfe)",
        "requestAttributes": {
          "time": "2022-03-27T15:41:24.265075410Z",
          "auth": {}
        },
        "destinationAttributes": {}
      },
      "serviceName": "iam.googleapis.com",
      "methodName": "google.iam.admin.v1.SetIAMPolicy",
      "authorizationInfo": [
        {
          "permission": "iam.serviceAccounts.setIamPolicy",
          "granted": true,
          "resourceAttributes": {}
        }
      ],
      "resourceName": "projects/-/serviceAccounts/112650090025525899268",
      "serviceData": {
        "@type": "type.googleapis.com/google.iam.v1.logging.AuditData",
        "policyDelta": {
          "bindingDeltas": [
            {
              "action": "ADD",
              "role": "roles/owner",
              "member": "user:kaitlynpuckett739@gmail.com"
            }
          ]
        }
      },
      "request": {
        "resource": "projects/account-fa037/serviceAccounts/112650090025525899268",
        "@type": "type.googleapis.com/google.iam.v1.SetIamPolicyRequest",
        "policy": {
          "version": 3,
          "etag": "ACAB",
          "bindings": [
            {
              "role": "roles/owner",
              "members": [
                "user:kaitlynpuckett739@gmail.com"
              ]
            }
          ]
        }
      },
      "response": {
        "version": 1,
        "@type": "type.googleapis.com/google.iam.v1.Policy",
        "etag": "BwXbNQc1TTI=",
        "bindings": [
          {
            "members": [
              "user:kaitlynpuckett739@gmail.com"
            ],
            "role": "roles/owner"
          }
        ]
      }
    },
    "insertId": "vwzeucecs6qj",
    "resource": {
      "type": "service_account",
      "labels": {
        "unique_id": "112650090025525899268",
        "email_id": "account-fa037@appspot.gserviceaccount.com",
        "project_id": "account-fa037"
      }
    },
    "timestamp": "2022-03-27T15:41:24.032761606Z",
    "severity": "NOTICE",
    "logName": "projects/account-fa037/logs/cloudaudit.googleapis.com%2Factivity",
    "receiveTimestamp": "2022-03-27T15:41:25.047175420Z"
  }
]
