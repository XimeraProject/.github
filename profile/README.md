# Welcome to the Ximera Project <!-- omit in toc -->

Ximera, pronounced "chimera," (**X**imera: **I**nteractive,
**M**athematics, **E**ducation, **R**esources, for **A**ll) is an
open-source platform that provides tools for authoring and publishing
(PDF and Online), open-source, interactive educational content, such
as textbooks, assessments, and online courses.  
The Ximera Project is
funded 2024-2026 with (no other external funding) by a $2,125,000
[Open Textbooks Pilot
Program](https://www2.ed.gov/programs/otp/index.html) grant. In the
past, the Ximera Project has also recieved support from NSF Grant
DUE-1245433, the Shuttleworth Foundation, the Ohio State University
Department of Mathematics, and the Affordable Learning Exchange at
OSU.  

**The ultimate goal of this project is to promote sustained
student success and savings.**



Ximera is built with authors, instructors, and students in mind. We
seek to provide an optimal work environment for all three types of
users.


- [Authors](#authors)
  - [Online Deployment](#online-deployment)
- [Instructors](#instructors)
  - [Courses in Ximera](#courses-in-ximera)
  - [Support](#support)
  - [Use in the classroom](#use-in-the-classroom)
    - [Online Materials with LMS Integration](#online-materials-with-lms-integration)
    - [Online Materials without LMS Integration](#online-materials-without-lms-integration)
    - [PDF Materials](#pdf-materials)
- [Students](#students)
- [Current Development](#current-development)
- [Disclaimer](#disclaimer)



## Authors

With Ximera, authors use LaTeX to create their content. With this
single source code, we generate different types of output:

![Ximera generates a PDF worksheet, an online interactive worksheet, and a PDF solution manual.](https://github.com/XimeraProject/.github/blob/main/profile/SimultaneousOutput.jpg "Single source code generates three different outputs.")

To get started as an author in Ximera, all you need is the XimeraLaTeX
LaTeX Package, which is available on CTAN. 
Please feel free to contact `ximera@math.osu.edu` with questions. 

### Demo

A simple demo course showing the main Ximera features can be found at 

* [Short Demo Course](https://set.kuleuven.be/voorkennis/ximerademo/demo/demo/theorie) at a KU Leuven server
* [Short Demo Course](https://ximera.osu.edu/wimdemo/demo/demo/theorie) at the OSU server (the same content with different styling and some functions not yet supported)
  
Both links show the same content, but with different styling. 
This functionality is currently (summer 2024) being worked on, and is in constant evolution. More unified and better documented Ximera releases will become available in the next weeks and months.
As of July 2024, there remain some incompabibilities between the official OSU server and the KU Leuven server.
But, both OSU, KU Leuven and some other institutions provide courses that have been running for several years.

### Online Deployment

Once you have some content, you will probably want to see how it works
online. Currently, deployment is most conveniently done from our deployment server.
In the near future a cloud based CI/CD infrastucture will be set up. Until then, we advise you contact the Ximera developers at `ximera@math.osu.edu` 

## Instructors

Instructors (who are not authors) can freely use any Ximera materials,
**without permission**, simply by using the URL of the
course. Here is an incomplete list of Ximera courses that have been
deployed online (authors, please feel free to add your course!)

### Courses in Ximera

- [Calculus 1 at OSU](https://ximera.osu.edu/mooculus/calculus1), [PDF](https://github.com/mooculus/calculus/releases/tag/v1.0.0), and [source](https://github.com/mooculus/calculus)
- [Calculus 2 at OSU](https://ximera.osu.edu/mooculus/calculus2), [PDF](https://github.com/mooculus/calculus/releases/tag/v1.0.0), and [source](https://github.com/mooculus/calculus)
- [Calculus 3 at OSU](https://ximera.osu.edu/mooculus/calculus3), [PDF](https://github.com/mooculus/calculus/releases/tag/v1.0.0), and [source](https://github.com/mooculus/calculus)
- [Linear Algebra: An Interactive Introduction](https://ximera.osu.edu/oerlinalg/LinearAlgebra) and [source](https://github.com/annadavismath/LinearAlgebraV2)
- [Linear Algebra and Ordinary Differential Equations](https://ximera.osu.edu/laode) and [source](https://github.com/mooculus/laode)
- [This is Linear Algebra](https://ximera.osu.edu/linearAlgebra) and [source](https://github.com/mooculus/linearAlgebra)
- [Quality Control Topics for Introductory Statistics and Manufacturing Courses (funded by Intel)](https://ximera.osu.edu/qcstats/QC_stats) and [source](https://github.com/annadavismath/QC_stats)

### Support

If an instructor experiences issues with the content or performance of the materials, there are simple ways to report these issues.

![Buttons that link to GitHub issues.](https://github.com/XimeraProject/.github/blob/main/profile/getHelp.png "Buttons for help.")

Morever, here is a list of [common solutions for student issues](https://github.com/XimeraProject/.github/blob/main/profile/commonSolutions.md).

For other technical support, contact the developers at `ximera@math.osu.edu`.

### Use in the classroom

The instructor experience falls into three basic categories:

#### Online Materials with LMS Integration

At OSU, UF, and KU Leuven instructors have Ximera assignments directly integrated into the Learning Management
System (LMS). For these instructors, Ximera works seamlessly and invisibly.

#### Online Materials without LMS Integration

At other institutions using Ximera, instructors can use Ximera
materials, and have their students complete various Ximera
assignments. However, data access prohibitively difficult for most
instructors in this category. **We are currently working on finding a
solution that will provide grade data for all Ximera instructors.**

#### PDF Materials

There are a number of Ximera courses that are not yet deployed online. Their materials are currently used only in PDF form.
Instructors in this category are usually in a development phase of their Ximera
course. The PDFs produced by the [Ximera document class](https://ctan.org/pkg/ximera) allow for incremental development of
materials while still being used and tested in the classroom (not all of these repos will have fully developed PDFs). It does this by:

- Allowing individual LaTeX activites to compile on their own while also being included as sections/chapters in book.
- Facilitating the "hiding" of environments, this can be used to make "instuctor editions" or "solution manuals"
- Allows numbering of the document to be set as an option in the preamble.


For examples see:


* [Abstract Algebra I](https://github.com/bartsnapp/abstractAlgebraI) and [PDF](https://github.com/bartsnapp/abstractAlgebraI/releases/tag/v1.0.0)
* [Advanced Geometry](https://github.com/mooculus/advancedGeometry)
* [Math for Architects](https://github.com/mooculus/mathForArchitects)
* [Math for Teachers](https://github.com/mooculus/mathForTeachers)
* [History of Mathematics](https://github.com/mooculus/historyOfMathematics)
* [Business Calculus](https://github.com/mooculus/business)
* [Linear Algebra and Ordinary Differential Equations](https://github.com/mooculus/laode)

Moreover, PDF materials are not limited to textbooks/worksheets. Exams can we be written in Ximera, and then their content can be used to create online interactive practice exams. *
For and example see:

* [Practice Exam](https://ximera.osu.edu/testing/exam/practiceExam) and [PDF](https://github.com/XimeraProject/examples/releases/tag/v1.0.0)


## Students

Ximera materials are free. Students can use any of the materials they
find, even if the student is not enrolled in a course. We hope that
authors can use our materials to make the very best possible learning
experience for students.

## Current Development

Ximera is maintained by a community of people. In particular:

- [Bart Snapp](https://people.math.osu.edu/snapp.14/) (Project Manager and LaTeX Development)
- [Jim Fowler](https://kisonecat.com/) (Frontend/Backend Development)
- [Jason Nowell](https://www.jasonnowell.com/home) (Answer-type/LaTeX Development)
- [Wim Obbels](https://www.kuleuven.be/wieiswie/en/person/00045050) (Frontend/LaTeX/Deployment Development)

In May 2024, the Ximera Document Class was submitted to CTAN.
Currently, we are working on Docker containers for both Ximera deployment and the Ximera server.

## Disclaimer

_The contents of this repository were developed under a grant from the
Department of Education. However, those contents do not necessarily
represent the policy of the Department of Education, and you should
not assume endorsement by the Federal Government._
