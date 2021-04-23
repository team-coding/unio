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
   "participants":[
      {
         "user_id":"String",
         "is_admin":"Boolean"
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