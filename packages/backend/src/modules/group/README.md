# Aggregate Group

```json

{
   "id":"String",
   "image":"String",
   "title":"String",
   "owner_id":"String",
   "invite":{
      "qr_code":"String",
      "created_at":"String",
      "updated_at":"String",
      "expires_at":"Date"
   },
   "owner":  
            { "group_name": "String",
               "status": "String",
              "creation_date": "Date",
              "end_date": "Date",
              "cession_date": "Date",
              "ceased_to": "String",
            } , 
   "member": [
          { "user_id": "String",
            "user_name": "String",
            "status": "String",
            "is_owner": "Boolean",
            "is_admin": "Boolean",
            "join_date": "Date",
            "leave_date": "Date"
          }
        ],
    "admin: [
      { "group_name": "String",
        "status": "String",
        "join_date": "Date",
        "leave_date": "Date",
        "invited_admins": [{"user_id": "String"}],
        "members": [             * deixa ou tira?
          { "id": "String",
            "status": "String",
            "join_date": "Date",
            "leave_date": "Date",
          }
        ]
      } 
   ],
   "created_at":"Date",
   "updated_at":"Date",
}

```

# Aggregate Messages

```json
{
   "id":"String",
   "group_id":"String",
   "owner_id":"String",
   "name":"String",
   "avatar":"String",
   "message":"String",
   "created_at":"Date",
   "updated_at":"Date",
}
```

### Methods 

- Add user to group 
- Generate invite 
- Revoke invitation
- Make an user an admin
- Remove user from group
- Change image
- Change title
- Delete group
- Send message on group
- Delete message
