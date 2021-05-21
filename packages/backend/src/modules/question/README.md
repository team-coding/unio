# Aggregate Question

```json

{
   "id":"String",
   "keywords":"String",
   "description":"String",
   "author_id":"String",
   "is_public":"Boolean",
   "comments_id":["String"],
   "marks": ["String"],
   "alternatives":[
      {
         "id":"String",
         "number_of_alternatives": "Number",
         "statement":"String",
         "position":"Number",
         "comments": "String"
         "is_answer":"Boolean",
         "position_fixed": "Boolean"
      }
   ],
   "archived": "Boolean",
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
