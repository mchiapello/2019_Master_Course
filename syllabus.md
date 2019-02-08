---
layout: page
title: Syllabus
credits: 3
semester: Summer 2019
professor: Dr. Marco Chiapello
office: Istituto per la Protezione Sostenibile delle Piante, Strada delle cacce 73
email: chiapello.m@gmail.com
schedule: ['Fridays, 14:00-18:00']
location: Via P.Giuria
office_hours: Monday 14-17
office_hours_location: Istituto per la Protezione Sostenibile delle Piante, Strada delle cacce 73
TA: Silvia Perotto
TA_email: silvia.perotto@unito.it
---

## Course

{{ site.title }}

{{ page.catalog }}, {{ page.credits }} Credits, {{ page.semester }}

### Instructor

{{ page.professor }}

Office: {{ page.office }}

Email (best way to contact us):
[{{ page.email }}](mailto:{{ page.email }})


### Location

{{location}}


### Times

{% for class in page.schedule %}
  {{ class }}
{% endfor %}


### Office Hours

Times: {{ page.office_hours }}

Location: {{ page.office_hours_location }}

Or by appointment. *Note: my schedule gets very busy during the semester so
please try to schedule appointments as far in advance as possible. In general it
will be very difficult to set up appointments less than 24 hours in advance.*


### Course Coordinator

{{ page.TA }}

Email: [{{ page.TA_email }}](mailto:{{ page.TA_email }})


### Website

The syllabus and other relevant class information and resources will be posted
at [{{ site.url}}]({{ site.baseurl }}/).
Changes to the schedule will be posted to this site so please try to check it
periodically for updates.


### Course Communications

Email: [{{ page.email }}](mailto:{{ page.email }})


### Required Texts

There is no required text book for this class.

All needed material is openly available on the course website. If you are
interested in additional reading on the topics we are covering I highly
recommend [R for Data Science](https://r4ds.had.co.nz/), which is freely
available on the web.


### Course Description

Computers are increasingly essential to the study of all aspects of
biology. Data management skills are needed for entering data without errors,
storing it in a usable way, and extracting key aspects of the data for
analysis. Basic programming is required for everything from accessing and
managing data, to statistical analysis, to modeling. This course will provide an
introduction to data management, manipulation, and analysis, with an emphasis on
biological problems. Class will typically consist of short introductions or
question & answer sessions, followed by hands on computing exercises. The course
will be taught using R and SQLite, but the concepts learned will easily apply to
all programming languages and database management systems. No background in
programming or databases is required.


### Prerequisite Knowledge and Skills

Knowledge of basic biology.


### Purpose of Course

In this course you will learn all of the fundamental aspects of computer
programming that are necessary for conducting biological research. By the end of
the course you will be able to use these tools to import data into R, perform
analysis on that data, and export the results to graphs, text files, and
databases. By learning how to get the computer to do your work for you, you will
be able to do more science faster.


### Course Objectives and Goals

Students completing this course will be able to:

* Create well structured databases
* Extract information from databases
* Write simple computer programs in R
* Automate data analysis
* Apply these tools to address biological questions
* Apply general data management and analysis concepts to other programming
  languages and database management systems


### Teaching Philosophy

This class is taught using a flipped, learner-centered, approach, because
learning to program and work with data requires actively working on
computers. Flipped classes work well for all kinds of content, but I think they
work particularly well for computer oriented classes. 

### Instructional Methods

As a flipped classroom, students are provided with either reading or video
material that they are expected to view/read prior to class. Classes will
involve brief refreshers on new concepts followed by working on exercises in
class that cover that concept. While students are working on exercises the
instructor will actively engage with students to help them understand material
they find confusing, explain misunderstandings and help identify mistakes that
are preventing students from completing the exercises, and discuss novel
applications and alternative approaches to the data analysis challenges students
are attempting to solve.


## Course Policies


### Attendance Policy

Attendance will taken and is a factor into the grades for this class. 

### Quiz/Exam Policy

There will be an exam in this course.


### Make-up policy

Life happens and therefore there is an automatic grace period of 48 hours for
the submission of late assignments with no need to request an extension.
However, it is highly recommended that you submit assignments on time when
possible because assignments build on one another and it can be hard to catch up
if you fall behind. Reasonable requests for longer extensions will also be granted.
Assignments turned in after the 48 hour grace period without an extension will be
be graded with a 20% penalty.


### Assignment policy

Assignments are due Wednesday night by 11:59 pm. Assignments should be
submitted via email.

### Course Technology

Students are required to provide their own laptops and to install free and open
source software on those laptops (see [Setup]({{ site.baseurl }}/computer-setup)
for installation instructions). Support will be provided by the instructor in
the installation of required software. If you don't have access to a laptop
please contact the instructor and they will do their best to provide you with
one.


## Grading Policies

Grading for this course is based on assignments and final exam.

Exercises in assignments will be graded as follows:

* Produces the correct answer using the requested approach: 100%
* Generally uses the right approach, but a minor mistake results in an incorrect
    answer: 90%
* Attempts to solve the problem and makes some progress using the core concept:
    50%
* Answer demonstrates a lack of understanding of the core concept: 0%

## Course Schedule

The details course schedule is available on the course website at:
[{{ site.url }}/schedule]({{ site.baseurl }}/schedule).

