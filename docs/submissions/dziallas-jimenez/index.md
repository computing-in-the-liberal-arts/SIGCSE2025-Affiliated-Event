# _Challenges and Opportunities in Collaborating on Instructional Materials_

## _University of the Pacific_
Contributed by _Sebastian Dziallas_, _sdziallas@pacific.edu_
Contributed by _Osvaldo Jiménez_, _ojimenez@pacific.edu_

## Institutional and departmental context

- Location: Stockton, CA
- Undergraduate student body size: _~3300_ students
- Degree(s) offered: Computer Science
- Department/major name: Department of Computer Science
- Number of contributing faculty: _11_ FTE
- Number of majors annually: _65_ undergraduate majors in 2023 (up from _36_ in 2019), as well as a growing number of graduate students
- Does the department offer any graduate programs? Yes
- Other context: At the University of the Pacific, the Department of Computer Science is part of the School of Engineering and Computer Science.
  The school has a diverse student population, with a significant number of transfer students.
  The university has obtained Asian American and Native American Pacific Islander-Serving Institution (AANAPISI) status and has applied for Hispanic-Serving Institution (HSI) status.
  All students at the university complete two core courses, as well as seven breadth requirements as part of the general education program.

## Description of Opportunity or Challenge

Instructors often share course materials with each other, such as when a new faculty member joins a new department,
takes over an existing course and makes modifications to adapt existing materials to their own teaching practices,
or is part of a group of instructors teaching the same course.
In these cases, it can be challenging for faculty to keep track of and share current and future changes with others.
This challenge is further exacerbated in the liberal arts community, as small department sizes frequently translate to different instructors teaching the same course across semesters.
With the rapid evolution of computing knowledge, the idea of sharing changing materials becomes even more important.

Currently, most faculty have used one of the following methods to share instructional materials:

- [ ] Via a folder/zip
- [ ] Real-time share of a folder (e.g. google drive/dropbox/onedrive)
- [ ] Canvas/Moodle/Blackboard copy course
- [ ] Offline material transfer (physical copies)
- [ ] Meeting/Conversation

While each one of these has benefits, they have drawbacks as well.
For instance, we have found it difficult to:

- keep track of new changes introduced into existing material,
- report changes back to an original author of the material,
- review suggestions to new material and decide whether to apply it to our particular course offering,
- eradicate errata (or "bugs") in our course materials that propagate out to future course offerings.

In this session, we propose to discuss the challenges we have faced at Pacific around sharing pedagogical materials, such as instructional labs.
We also propose to discuss one approach that we have used in our own courses that may address some of these challenges.

We hope that by having this session we can foster increased collaboration on instructional materials across the liberal arts computing community.

## Recommendation or Contribution

We hope to use this session as an opportunity for the liberal arts computing community to reflect on how they share materials and the challenges they face.
To address some of the limitations around sharing course materials,
we propose to discuss how we have leveraged version control systems, such as git and GitHub,
to collaborate on course materials and what we have learned in our review of the existing literature.

The use of git and GitHub in the computing classroom has exploded in popularity in [the last 10 years](https://education.github.com/classroom-report).
Much of the existing educational computing literature on version control revolves around course management (Clifton et al., 2007), specifically around hosting assignments.
Scholars have also examined the use of version control in education,
such as how to leverage git, GitHub, GitHub Classroom in Computer & Data Science courses (Zagalsky et al., 2015, Hicks & Irizarry, 2018, Fiksel et al., 2019).
For instance, Hicks and Irizarry not only introduced their students to using git,
but also used GitHub to organize their course materials and setup GitHub Pages to host their course websites (2018).
Other scholars, like Rodriguez et al., have reported setting up private GitLab servers to host an entire department's curriculum (2018).
Finally, Feliciano et al. also reported on how git democratizes shared knowledge, as students can suggest changes to existing pedagogical materials.
They write:
> "educators leverage GitHub’s collaboration and transparency features to create, reuse and remix course materials,
> and to encourage student contributions and monitor student activity on assignments and projects." (2016)

We believe that there exists an opportunity for educators to leverage some of these practices to share course materials and keep track of changes.
Rodriguez et al. referred to this as **courseware as code** (2018, 2020).
We aim to discuss this opportunity and how we can adapt its use at liberal arts colleges.

This approach to collaboration resembles the knowledge sharing approach used for this event, with its use of GitHub Pages to host materials and pull requests to incorporate changes.
However, there are also differences, as instructional materials are fluid and ever-changing, whereas conference materials tend to be hosted in a final "production-ready" state.

With this in mind, we would like to highlight a few practices that we have used ourselves and that could help faculty in sharing instructional materials.
For example, we:

- used existing tools to convert legacy documents to more version control friendly formats (such as markdown),
- leverage continuous integration pipelines to retain stylistic differences by instructors,
- focus on the onboarding of instructors to promote their "buy-in" and to lessen the amount of changes to their existing workflows.

We believe that by following similar practices, faculty in the liberal arts community could benefit by:

- avoiding some of the aforementioned problems around sharing pedagogical materials,
- being able to share revisions with other instructors of the same course automatically,
- allowing faculty to share their course materials more broadly,
  which would allow colleagues at other institutions to draw on, change, and contribute to these materials.
  This mechanism is important at liberal arts institutions, where the author may be the sole "expert" in their particular field.

Ultimately, we hope that this session will encourage attendees to reflect on their own practices and to collaborate on instructional materials more effectively.
