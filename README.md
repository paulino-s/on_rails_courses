# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

## Building app

- An aplication to manage courses

- Courses will have one or more lessons, lessons will have one or more questions.

- We will have students and teachers

### Optional

- Teachers can create courses and lessons.

- Students can create questions in lessons.

We will need a homepage that will show the available courses and from there users will be able to loook at the course contents and sign up. 

## Models
* Course
    * title
    * description
* Lesson
    * course_id
    * title
    * content
* Question
    * lesson_id
    * content
* Users
    * teacher
        * last_name
        * first_name
    * students
        * first_name
        * last_name
