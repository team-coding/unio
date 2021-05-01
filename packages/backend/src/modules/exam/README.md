# Aggregate Exam

```json

{
   "id":"String",
   "title":"String",
   "header":"JSON",
   "value":"Number",
   "owner_id":"String",
   "timeout_to_respond":{
      "start_at":"Date",
      "ends_at":"Date"
   },
   "shared_with_user_id":["String"],
   "shared_by":"String",
   "shared_in_group":["String"],
   "questions":[
      {
         "id":"String",
         "value":"Number",
         "position":"Number"
      },
      {
         "id":"String",
         "value":"Number",
         "position":"Number"
      }
   ],
   "created_at":"Date",
   "updated_at":"Date",
}

```

### Methods

- Create Exam
- Update Exam
- Delete Exam
- List Exam
- Import Exam
- Import Questions
- Export Questions
- Export Exam

Observation:

The exams can be shared with students or groups, but it will always reference the user.
Options can be ordered.
Each option has an individual grade, but cannot exceed the total of the exam.
The exam can have a custom header.
The test should only be available within the defined date range.