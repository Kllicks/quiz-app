# Description

- a quiz has quesitons
- questions have correct answers
- students can take quizzes
- when they do, they hand in submissions

## Quizzes

- id
- name

## Questions

- id
- text
- answer
- quiz_id (A Question has a Quiz, a Quiz has many Questions)

## Students

- id
- name

## Submissions 

- id
- student_id

## Answers

- id
- text
- student_id
- question_id
- submission_id