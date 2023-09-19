---
content_type: page
description: This syllabus section provides a course overview and information on meeting
  times, course highlights, grading, the target student population, and the calendar
  of lecture topics and lecturers.
learning_resource_types: []
ocw_type: CourseSection
title: Syllabus
uid: 86b89111-2d4f-73a9-d987-11245987bcd3
---

Course Meeting Times
--------------------

Lectures: Three sessions / week, 2 hours / session

Recitations: Two sessions / week, 1 hour / session

Course Overview
---------------

The era of Moore's law induced performance gains of sequential programs is over. In the future, the primary method of increasing program performance will require the utilization of multicore parallelism. The processing platforms of the future will have hundreds or even thousands of processor cores that are tightly integrated for parallel processing. Unfortunately, very few programmers know how to program these multicore systems. This pain will be felt in all tiers of the market because of the increasing reliance on computing power for scientific discovery and day-to-day activities. There will be a deep impact on academic institutions as well because they have done little to train the programmers of the future with the right concepts and tools so that they can harness the computing power of multicores and massively parallel systems.

Some leading vendors are already offering parallel processors on a chip. Today, most general purpose processors in the market are multicores. The Cell processor from IBM, Sony, and Toshiba is a 9-core heterogeneous processor that powers the [Sony PLAYSTATION®3](http://www.us.playstation.com/PS3) and also appears in various broadband markets. At their Developer Forum a few months ago, Intel announced an [80-core homogeneous processor](http://techfreep.com/intel-80-cores-by-2011.htm) slated for fabrication in just a few years. These new architectures offer the unique opportunity to have parallel systems on a chip available to the masses in gaming consoles, mobile devices, personal computers, and embedded platforms. The ubiquitous presence of parallelism will make it necessary to train a new breed of programmers so that parallel programming is as easy and tractable as the conventional sequential programming that millions of programmers are accustomed to today.

Course Highlights
-----------------

The course serves as an introductory course in parallel programming. It offers a series of lectures on parallel programming concepts as well as a group project that provides hands-on experience with parallel programming. Students will have the unique opportunity to use the cutting-edge [PLAYSTATION 3](http://www.us.playstation.com/PS3) development platform, as they learn how to design and implement exciting applications for multicore architectures. At the end of the course, students will have an understanding of:

*   Fundamental design philosophies that multicore architectures address.
*   Parallel programming philosophies and emerging best practices.

Course Description
------------------

The course briefly covers the history of the microprocessor evolution and discusses the reasons for the recent shift in architecture design toward multicores. Students will become familiar with the Cell processor that powers the [PLAYSTATION 3](http://www.us.playstation.com/PS3) and how its design choices compare to other emerging architectures.

Students will also learn about the various programming models currently used for programming parallel architectures. The course combines lectures with hands-on labs so that students can experiment with the different models of computation and learn about the pros and cons of the different programming models. Students will also learn [StreamIt](http://cag.csail.mit.edu/streamit/), a new, simple, and natural to understand programming language for stream computing. The course will explore broader implications of the stream programming model to various kinds of traditional parallelization technology.

Students will participate in a course long project drawn from any of several exciting domains that include gaming engines, media applications, algorithms for molecular dynamics, and protein folding challenge problems. Students are expected to participate in small project teams. Course projects are evaluated based on their performance, complexity, and completeness. Students will compete for exciting prizes to be awarded to the best project as selected by a panel of judges.

Grading
-------

Grades will be determined using the following weights:

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
ACTIVITIES
{{< thclose >}}
{{< thopen >}}
PERCENTAGES
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
Mini-quizzes
{{< tdclose >}}
{{< tdopen >}}
16%
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Exercises and labs
{{< tdclose >}}
{{< tdopen >}}
24%
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Final group project
{{< tdclose >}}
{{< tdopen >}}
60%
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

Target Student Population
-------------------------

The course is open to all students (undergraduates and graduates). Students who are interested in the course are strongly encouraged to discuss project ideas with the instructors before enlisting in the course. We have several projects that we can suggest and discuss with you, or we can discuss some of your own project ideas. We strongly encourage small teams of students per project. Teams of 4-5 students are likely to work best, but smaller teams are also plausible. We can help you assemble a team as necessary, although it is best if you know someone that will want to work on the same project with you. Each team will have dedicated access to a PLAYSTATION 3 console, along with programming and debugging tools, tutorials, and hands-on help.

Calendar
--------

The calendar below provides information on the course's lecture (L) and recitation (R) sessions.

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
SES #
{{< thclose >}}
{{< thopen >}}
TOPICS
{{< thclose >}}
{{< thopen >}}
LECTURERS
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen colspan="3" >}}
**Week 1**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L1
{{< tdclose >}}
{{< tdopen >}}
Course introduction
{{< tdclose >}}
{{< tdopen >}}
Saman Amarasinghe
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L2
{{< tdclose >}}
{{< tdopen >}}
Introduction to Cell processor
{{< tdclose >}}
{{< tdopen >}}
Michael Perrone, IBM
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
R1
{{< tdclose >}}
{{< tdopen >}}
Getting to know Cell
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L3
{{< tdclose >}}
{{< tdopen >}}
Introduction to parallel architectures
{{< tdclose >}}
{{< tdopen >}}
Saman Amarasinghe
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
Quiz 1
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L4
{{< tdclose >}}
{{< tdopen >}}
Introduction to concurrent programming
{{< tdclose >}}
{{< tdopen >}}
Saman Amarasinghe
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
Project reviews
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L5
{{< tdclose >}}
{{< tdopen >}}
Parallel programming concepts
{{< tdclose >}}
{{< tdopen >}}
Rodric Rabbah, IBM
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
Quiz 2
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L6
{{< tdclose >}}
{{< tdopen >}}
Design patterns for parallel programming I
{{< tdclose >}}
{{< tdopen >}}
Rodric Rabbah, IBM
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen colspan="3" >}}
**Week 2**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
R2-R3
{{< tdclose >}}
{{< tdopen >}}
Cell programming hands-on
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L7
{{< tdclose >}}
{{< tdopen >}}
Design patterns for parallel programming II
{{< tdclose >}}
{{< tdopen >}}
Rodric Rabbah, IBM
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
Quiz 3
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L8
{{< tdclose >}}
{{< tdopen >}}
StreamIt language
{{< tdclose >}}
{{< tdopen >}}
Bill Thies
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
R4
{{< tdclose >}}
{{< tdopen >}}
Cell debugging tools
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L9
{{< tdclose >}}
{{< tdopen >}}
Debugging parallel programs
{{< tdclose >}}
{{< tdopen >}}
Rodric Rabbah, IBM
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
Quiz 4
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L10
{{< tdclose >}}
{{< tdopen >}}
Performance monitoring and optimizations
{{< tdclose >}}
{{< tdopen >}}
Rodric Rabbah, IBM
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen colspan="3" >}}
**Week 3**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L11
{{< tdclose >}}
{{< tdopen >}}
Parallelizing compilers
{{< tdclose >}}
{{< tdopen >}}
Saman Amarasinghe
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
Quiz 5
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L12
{{< tdclose >}}
{{< tdopen >}}
StreamIt parallelizing compiler
{{< tdclose >}}
{{< tdopen >}}
Saman Amarasinghe
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
R5
{{< tdclose >}}
{{< tdopen >}}
Cell profiling tools
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
R6
{{< tdclose >}}
{{< tdopen >}}
SIMD programming on Cell
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L13
{{< tdclose >}}
{{< tdopen >}}
Star-P
{{< tdclose >}}
{{< tdopen >}}
Alan Edelman
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
Quiz 6
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L14
{{< tdclose >}}
{{< tdopen >}}
Synthesizing parallel programs
{{< tdclose >}}
{{< tdopen >}}
Arvind
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L15
{{< tdclose >}}
{{< tdopen >}}
Cilk
{{< tdclose >}}
{{< tdopen >}}
Bradley Kuszmaul
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L16
{{< tdclose >}}
{{< tdopen >}}
Introduction to game development
{{< tdclose >}}
{{< tdopen >}}
Mike Acton, Insomiac Games
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen colspan="3" >}}
**Week 4**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L17
{{< tdclose >}}
{{< tdopen >}}
The Raw experience
{{< tdclose >}}
{{< tdopen >}}
Rodric Rabbah, IBM
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L18
{{< tdclose >}}
{{< tdopen >}}
The future
{{< tdclose >}}
{{< tdopen >}}
Saman Amarasinghe
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
Student project competition
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
Award ceremony
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}