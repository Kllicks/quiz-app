# Description

- a quiz has questions
- questions have correct answers
- students can take quizzes
- when they do, they hand in submissions

## Quizzes

- id
- name

## Questions

- id
- question_text
- correct_answer
- quiz_id (A Question has a Quiz, a Quiz has many Questions)

## Students

- id
- name

## Answers

- id
- answer_text
- question_id
- student_id

# future Enhancements:

## Add solumn to Answers:

- correct (boolean)

## Or Add Table: Grades
- id
- score
- student_id
- quiz_id

# What are some example queries?

- what are all the quiz scores for a particular student?
- what are all the scores for a quiz?
- how do I know if an answer is correct?
- what questions did no one get right?
