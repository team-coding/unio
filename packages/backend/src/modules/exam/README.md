# Aggregate Exam

```json

{
   "id":"String",
   "title":"String",
   "header": {"logo" : "String",
              "institution": "String",
              "department": "String",
              "grade": "String",
              "teacher": "String",
              "subject": "String",
              "class": "String",
              "exam_marks": "Number",
              "questions_qty": "Number",
              "date": "String",
              "time": "String",
              "location": "String"
              },
   "candidate": {"name": "String",
                 "registration_number": "String",
                 "signature": "String"},
   "instructions": "String",
   "maximum_mark":"Number",
   "owner_id":"String",
   "timeout_to_completion":{
      "duration":"Time",
      "start_time":"Time",
      "end_time": "Time",
      "start_date":"Date",
      "end_date":"Date"
   },
   "shared_with_user_id":["String"],
   "shared_by":"String",
   "shared_in_group":["String"],
   "questions":[
      {
         "id":"String",
         "value":"Number",
         "position":"Number"
      }
   ],
   "created_at":"Date",
   "updated_at":"Date",
   "archived": "Boolean"
}

```

### Methods

- Create Exam
- Update Exam
- Delete Exam
- List Exam *?
- Import Exam
- Export Exam
- Archive Exam

Observation:

The exams can be shared with students or groups, but it will always reference the user.
Options can be ordered.
Each option has an individual mark, but cannot exceed the total marks of the exam.
The exam can have a custom header.
The test should only be available within the defined date range.
