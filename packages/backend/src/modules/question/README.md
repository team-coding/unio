# Aggregate Question

```json

{
   "id":"String",
   "title":"String",
   "description":"String",
   "author_id":"String",
   "is_public":"Boolean",
   "comments_id":["String"],
   "options":[
      {
         "id":"String",
         "description":"String",
         "position":"Number",
         "is_right_option":"Boolean",
      },
      {
         "id":"String",
         "description":"String",
         "position":"Number",
         "is_right_option":"Boolean",
      }
   ],
   "created_at":"Date",
   "updated_at":"Date",
}

```

### Methods 

- Create question 
- Copy question 
- Import question 
- Export question
- Remove option from question  
- Change title 
- Change description
- Comment on question 
- Define a question as rigth question 
- Change questions position (ordernation)