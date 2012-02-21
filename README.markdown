# Gradebook

This is the example application for the Rails Developer position at Viget. Building this application is the primary way we will judge your skills and suitability for the position from a technical perspective. This is not an exercise to weed out the non-programmers -- if you're at this stage of the interview process, we know you can program, now show us what you've got.

We anticipate this exercise taking candidates 4 - 6 hours to complete and submit. We recognize that this is a significant investment of your time and we appreciate that investment. We will invest the same amount of care in reviewing and providing feedback on your submission.

To get started, just clone this repository.

## Exercise

We'd like you to build an application that allows for the recording and reporting of courses offered by teachers and taken by students. It should satisfy these stories:

* A Teacher can manage his course roster
* A Teacher can view the enrolled students and their grades for a given course
* A Student can see the courses he is registered for (with grades)
* A Student can see his GPA for a given semester
* An Administrator can view enrollment counts across all courses for a semester (performance is a concern)
* An Administrator can view an average grade for a given course (performance is a concern)

## Evaluation

We expect you to demonstrate proficiency with:

* Database design and normalization
* Object-Oriented design and programming
* Ruby and Rails consistent with your experience
* SQL beyond simple SELECT / INSERT / UPDATE queries
* Test-Driven Development practices

When we evaluate your submission, we will be reviewing it in the context of your professional experience. We don't expect a novice to be writing more advanced code, and we wouldn't expect an advanced programmer to be writing novice code -- keep that in mind as you do the exercise.

## Submission

Once you've completed the exercise:

1. Make sure you can run the app from scratch (e.g. `bundle && rake db:migrate && rails server`)
1. Run all tests to ensure that they are still passing
1. Document any special considerations for running / using the application

Once you're ready to send us your working application:

1. Create a bare clone of your local repository (`git clone --bare gradebook gradebook.git`)
1. Create a tarball of the repository (`tar czf gradebook.tar.gz gradebook.git`)
1. Email your submission to developers@viget.com

If you have any questions during this exercise, please feel free to email developers@viget.com with any questions.
