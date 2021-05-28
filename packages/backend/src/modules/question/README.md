# Aggregate Question

```json

{
   "id":"String",
   "keywords":"String",
   "statement":"String",
   "author_id":"String",
   "is_public":"Boolean",
   "comments_id":["String"],
   "tags": ["String"],
   "keywords": ["string"],
   "alternatives":[
      {
         "id":"String",
         "number_of_alternatives": "Number",
         "statement":"String",
         "position":"Number",
         "comments": "String",
         "correct_alt":"Boolean",
         "position_fixed": "Boolean"
      }
   ],
   "created_at":"Date",
   "updated_at":"Date",
   "archived": "Boolean"
}

```

### Methods 

- Create question 
- Update question (Delete alternative from question, Change title (?), Change statement, Comment on question, Define right alternative, Change fixed alternative position)
- Copy question 
- Archive question
- Import question 
- Export question
- Make public
