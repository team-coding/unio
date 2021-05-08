# Aggregate User

```json

{
   "id":"String",
   "name":"String",
   "avatar":"String",
   "email":["String"], 
   "password":"String",
   "mobile_phone":["String"],
   "cpf":"String",
   "created_at":"Date",
   "updated_at":"Date",
   "account_verified": "String",
   "owner_of": [
      { "group": "String",
        "status": "String",
        "creation_date": "Date",
        "end_date": "Date",
        "cession_date": "Date",
        "ceased_to": "String",
        "member": [
          { "id": "String",
            "status": "String",
            "join_date": "Date",
            "leave_date": "Date",
          }
        ]
      }  
   ], 
   "member": [
      { "group": "String",
        "status": "String",
        "join_date": "Date",
        "leave_date": "Date"
      } 
   ],
   "admin_of": [
      { "group": "String",
        "status": "String",
        "join_date": "Date",
        "leave_date": "Date",
        "invited_admins": [{"id": "String"}],
        "members": [
          { "id": "String",
            "status": "String",
            "join_date": "Date",
            "leave_date": "Date",
          }
        ]
      } 
   ],
   "author_of_questions":["Questions"],
   "author_of_exams": ["Exams"],
   "payment_plan": [
      { 
      "plan": "String",
      "status": "String",
      "payment_date": "Date",
      "payment_means": "String",
      "payment_status": "String",
      "receipt": "String",
      "start_date": "Date",
      "end_date": "Date",
      "renewal_date": "Date"
      }
   ],    
   "terms_accepted":[
      {
      "ip": "String",
      "accepted_at": "Date",
      "term_version":"String",
      "user_agent": {
        "name": "String",
        "version": "String",
        "os": "String",
        "type": "String"
      }
    }
   ]
}

```


### Methods 

- Signin 
- Signup
- Request data 
- Accept Terms
- Request reset password 
- Confirm emails and mobile phones  
- Change avatar
- Change plan
