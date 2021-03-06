CompSci 404.1
-------------
This repository houses the code and scaffolding that UC Berkeley Extension students taking CS 404.1
use when completing their assignments.

Starter Code
------------
This repository contains various pieces of starter code that provide a skeleton and will help you
get started on your assignments. When working with this starter code, please remember that you may
not change or delete:

- Any of the code or tests already present
- Any of the interfaces, APIs, or methods already present

Supported Languages
-------------------
Quite a bit of work goes into preparing the course and the repository to use a particular language
(e.g. starter code, unit tests, solutions, etc). Currently, this course is offered in the following
languages. Other languages may be offered in the future.

- Java

Student Setup
-------------
In order to set up your environment, follow the setup instructions in the [Student
Setup](https://github.com/fsareshwala/cs404.1/blob/master/student-setup.md) guide.

Use of the Standard Library
---------------------------
This course focuses on data structures, algorithms, and their implementations. As such, in order for
you to learn about their internals, you must first implement them yourself. Therefore, in this
course, you may not use or import any standard library data structures or algorithms, unless
expressly permitted. If you need access to a particular data structure or algorithm, you must
implement it.

In order to ensure that you are not accidentally using a part of the standard library, run
`tools/nostdlib.sh` from the top level repository root. This script will scan your code and report
where invalid uses of the standard library are occurring. It's a good idea to run this script before
submitting your code for grading.

Code Style and Code Formatting
------------------------------
As a general rule, it is very important to keep source code in a consistent format. Most companies
have an established coding style for each language that they develop in. For this course, we will be
using Google's style guides for each language:

- Java: [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)

While it is useful to read the style guide and understand why the decisions were made as they were,
no one can expect to remember every detail every time. Therefore, we have tooling to help in
formatting the code in adherence to the style guide.

In order to format your code, run `tools/format.sh` from the top level repository root. This script
formats all supported languages within the repository.

Pulling In New Changes
----------------------
From time to time, I make changes in the upstream repository. You should pull these down into your
fork of the upstream repository. To do so, run `tools/update.sh` from the top level repository root.
This script will issue a series of `git` commands and merge the upstream changes with your local
changes. Remember to push the newly added changes to your GitHub fork as well. If you prefer, you
may use a GUI `git` client to simply fetch from the remote repository and merge automatically.

Submitting Your Work
--------------------
Submit your work by committing your changes and pushing them upstream before the due date.

Grading
-------
Each program description will include a command that will be used to run tests for the code you
write in each assignment. The percentage of tests that pass will be your final grade for the
assignment.

Contributing
------------
If you find any issues within this repository while completing your assignments, please [open an
issue](https://github.com/fsareshwala/cs404.1/issues/new) in the issue tracker. Better yet, please
open a pull request against the repository and I will be happy to merge it in.
