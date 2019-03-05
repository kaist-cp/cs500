# KAIST CS500: Design and Analysis of Algorithm (2019 Spring)


## Logistics

- Instructor: [Jeehoon Kang](https://sf.snu.ac.kr/jeehoon.kang)
- Teaching assistants: Jihoon Ko
- Time & Place: Mon & Wed 09:00am-10:15am, Rm 403, Bldg E11
- Office hour: TBA
- Website: https://github.com/kaist-cp/cs500-2019s


## Announcements

See the [issue tracker](https://github.com/kaist-cp/cs500-2019s/issues?q=is%3Aissue+is%3Aopen+label%3Aannouncement).


## Course Description

### Why algorithms?

Why computer science students should learn algorithms?  Many friends of mine in the IT industry say
algorithm is just intellectual play and is no longer relevant to the real-world practice.  Indeed,
many algorithms you learned or will learn in undergraduate algorithm (CS300) and this course (CS500)
are unlikely to be directly mobilized in your future research and development projects.  Then why
you should take this course?  Isn't it more efficient to google algorithms whenever necessary in the
future than to learn them upfront?

When the motivation of a course is challenged, it is necessary to ask the identity of the subject:
what is algorithm?  I think **algorithm is an efficient representation of computation**: (1) once an
algorithm is given, you can theoretically reproduce the corresponding computation in any computing
devices on your own; and (2) an algorithm contains no (or only a few) unnecessary details irrelevant
to computation itself.  In other words, algorithm is the essence of computation.  Learning
algorithms, therefore, helps you to be a better engineer or scientist in the following ways.

First, learning algorithms helps you understand great ideas in computer science.  These ideas are
great because they can be applied to multiple subfields of computer science, but in different veils.
These ideas are usually deep buried in the technical details, so you will not be able to clearly
recognize them unless you understand their essence, or in other words, their algorithms.  This
course will teach you the great ideas with algorithms, thereby facilitating you to adequately apply
them to your future projects, and hopefully to develop your own great idea as well.

Second, learning algorithms helps you efficiently communicate computational phenomena.  Nowadays
computation is very complex phenomena: even a hand-held mobile device (i.e. smartphone) contains
billions of transistors and, with huge number of computations, is capable of understanding images
and sounds.  Thus it is almost always impossible to explain those computations in every details.
This course will teach you how to efficiently explain and understand any kinds of computations by
representing them in efficient forms, or in other words, in algorithms.

Warning: even though algorithm is the essence of computation, learning algorithms only does not make
you a mature computer scientist or engineer.  Without hands-on experience on computing devices---in
other words, programming---you will likely suffer from <i>zǒu​huǒ​rù​mó</i> (走火入魔).  Be cautious.


### Focus on parallelism

Algorithm courses usually assume sequential model of computation, in which each unit of computation
is sequentially executed one-by-one.  However, from day one, this course assumes parallel model of
computation, in which multiple independent units of computation may be executed in parallel.  In
particular, we will learn only parallel algorithms implemented in parallel programming languages,
not sequential ones.  But don't be scared!  Fortunately, parallel algorithms are not that different
from sequential ones.

We focus on parallelism because it is the normal, ordinary mode of computation in modern computing
devices.  (In this view, sequential computation is just a special case of parallel computation.)
Parallelism has long been an important concepts in computer science, but nowadays it is becoming
fundamentally essential since the advent of multi-core systems in the early 2000s.  Unfortunately,
parallel programming is notoriously difficult and is often regarded as an esoteric wizardrous magic.
I believe one of the reasons is the lack of a good theory that demystifies the subject of parallel
computation.  This course aims to introduce such a good theory, thereby making parallelism more
accessible to the students.


## Prerequisites

This course assumes basic understanding of:

- Advanced high-school mathematics, ranging from algebra to calculus
- At least one programming language
- A few data structures and algorithms

For example, if you already took courses on programming (e.g. CS101), calculus (MAS101 and MAS102),
discrete mathematics (CS204), data structures (CS206), and algorithm (CS300), you are good to go.


## Textbook

- [Algorithm Design: Parallel and Sequential](https://sites.google.com/view/algorithms-book/), Umut
  A. Acar and Guy E. Blelloch.
- TBA


## Grading

- Attendance (including quiz): 10%
- Homework: 20%
- Midterm & final exam: 70%

Please note that the grading scheme is subject to change a little bit.


## Honor Code

The instructor has no tolerance on cheating because it harms the integrity and identity of the
individual, other students, the teaching staffs, and the institute.  Do not ever try to cheat on the
exam, quiz, assignment, and any other kinds of activities of this course.  A failure to do so will
result in F and/or the convening of disciplinary committee.

In this course, cheating means "private communication among individuals on the evaluation materials
such as exam, quiz, and assignment."  For example, if three students are discussing homework, it is
cheating.  If a student is showing the answer to the exam to another, it is cheating.  If you have
any doubts about what is allowed, ask the instructor.

For your information, the teaching staffs will do their best to detect cheating.


## Communication

- Course-related announcements and information will be posted on the
  [website](https://github.com/kaist-cp/cs500-2019s) as well as on the [GitHub issue
  tracker](https://github.com/kaist-cp/cs500-2019s/issues).  You are expected to read all
  announcements within 24 hours of their being posted.  It is highly recommended to watch the
  repository so that new announcements will automatically be delivered to you email address.

- Any technical and administrative questions, unless they are confidential or personal, should be
  asked in the [GitHub issue tracker](https://github.com/kaist-cp/cs500-2019s/issues).  Any
  questions failing to do so (e.g. email questions on course materials) will not be answered.

- Emails to the instructor or TAs should begin with "CS500:" in the subject line, followed by a
  brief description of the purpose of your email.  The content should at least contain your name and
  student number.  Any emails failing to do so (e.g. emails without student number) will not be
  answered.
