# Aggregate User

```json

{
   "id":"String",
   "name":"String",
   "avatar":"String",
   "email":["String"], *
   "password":"String",
   "mobile_phone":["String"], *
   "cpf":"String",
   "created_at":"Date",
   "updated_at":"Date",
   "account_verified": "String",
   "owner_of": ["Groups"], *
   "member_of": ["Groups"], *
   "admin_of": ["Groups"], *
   "author_of_questions":["Questions"], *
   "author_of_exams": ["Exams"], *
   "user_plan": "String", *
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
- Confirm emails and mobile phones * 
- Change avatar
- Change plan *
