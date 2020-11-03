# cs302-F2020-portfolio1-starter

![](../../workflows/build/badge.svg)

## Table of Contents

* [Deadlines](#deadlines)
* [Objectives](#objectives)
* [Introduction](#introduction)
* [Continuous Learning](#continuous-learning)
* [Accessing the Assignment](#accessing-the-assignment)
* [Final Project Tasks](#final-project-tasks)
  + [Overview of the Project](#overview-of-the-project)
  + [Creating the First Draft of Your Web Site](#creating-the-first-draft-of-your-web-site)
  + [Description of the Topics for the Web Design Portfolio](#description-of-the-topics-for-the-web-design-portfolio)
  + [Transferring Your Source code and Technical Writing to GitHub](#transferring-your-source-code-and-technical-writing-to-github)
  + [Requirements for the Web Design Portfolio Project](#requirements-for-the-web-design-portfolio-project)
  + [Summary of the Deliverables for the Web Design Portfolio Project](#summary-of-the-deliverables-for-the-web-design-portfolio-project)
  + [Reminder About Due Dates for the Web Design Portfolio Project](#reminder-about-due-dates-for-the-web-design-portfolio-project)
    - [Summary of the Due Dates](#summary-of-the-due-dates)
    - [Details About Each of the Due Dates](#details-about-each-of-the-due-dates)
* [Automated Checks with GatorGrader](#automated-checks-with-gatorgrader)
* [Assignment Assessment](#assignment-assessment)
* [Advance Feedback on an Assignment](#advance-feedback-on-an-assignment)
* [Discussion of a Graded Assignment](#discussion-of-a-graded-assignment)
* [Additional Resources](#additional-resources)
  + [System Commands](#system-commands)
  + [Non-Interactive Docker Commands](#non-interactive-docker-commands)
  + [Commands for an Interactive Docker Shell](#commands-for-an-interactive-docker-shell)
  + [Upgrading the Docker Container](#upgrading-the-docker-container)
  + [Downloading Project Updates](#downloading-project-updates)
  + [Using GitHub Actions](#using-github-actions)
  + [System Requirements](#system-requirements)
  + [Reporting Problems](#reporting-problems)

## Deadlines

- **Assignment Released**: October 19, 2020
- **Project Proposal Due**: October 27, 2020
- **Status Update One Due**: November 3, 2020
- **Status Update Two Due**: November 10, 2020
- **Status Update Three Due**: November 17, 2020
- **Final Report Due**: December 7, 2020 at 11:59 pm
- **Final Web Site Due**: December 7, 2020 at 11:59 pm

## Objectives

The learning objective for the web design portfolio project is for students to
apply their knowledge of Markdown, HTML, CSS, JavaScript, and Netlify to
iteratively propose, design, implement, test, deploy, and document a functional
web site with a unified theme. Students are also invited to reflect on their web
development experience, identifying what work well and what they would try
differently the next time that they create their own web site.

## Introduction

Designed for use with [GitHub Classroom](https://classroom.github.com/) and
[GatorGrader](https://github.com/GatorEducator/gatorgrader/), this repository
contains a laboratory assignment for a web development course. The source code
and technical writing for this assignment must pass tests set by the
[GatorGrader tool](https://github.com/GatorEducator/gatorgrader). When you use
the `git commit` command to transfer your source code to your GitHub
repository, GitHub Actions will initialize a build of your assignment, checking
to see if it meets all of the requirements. If both your source code and
writing meet all of the established requirements, then you will see a green ✔
in the listing of commits in GitHub. If your submission does not meet the
requirements, a red ❌ will appear instead. Please note that, at the option of
the course instructor, some checks may be run in GitHub Actions that are not
run locally by the [GatorGrader
tool](https://github.com/GatorEducator/gatorgrader).

## Continuous Learning

If you have not done so already, please read all of the relevant [GitHub
Guides](https://guides.github.com/) that explain how to use many of the features
that GitHub provides. In particular, please make sure that you have read the
following GitHub guides: [Mastering
Markdown](https://guides.github.com/features/mastering-markdown/), [Hello
World](https://guides.github.com/activities/hello-world/), and [Documenting Your
Projects on GitHub](https://guides.github.com/features/wikis/). Each of these
guides will help you to understand how to use both [GitHub](http://github.com) and
[GitHub Classroom](https://classroom.github.com/).

Students who want to learn more about how to use
[Docker](https://www.docker.com) should review the [Docker
Documentation](https://docs.docker.com/). Students are also encouraged to
review the documentation for their text editor, which is available at [VS
Code](https://code.visualstudio.com/docs). You should also review the [Git
documentation](https://git-scm.com/doc) to learn more about how to use the Git
command-line client. In addition to talking with the instructor and technical
leader for your course, students are encouraged to search
[StackOverflow](https://stackoverflow.com/) for answers to their technical
questions.

As outlined in the course schedule in the [course planning
repository](https://github.com/Allegheny-Computer-Science-302-F2020/cs302-F2020-plans),
students should also read all of the assigned readings for up to and including
the week of the semester on which this laboratory assignment was assigned.

## Accessing the Assignment

To access this assignment, you should go into the `#announcements` channel in
our Slack workspace and find the announcement that provides a link for it. Copy
this link and paste it into your web browser. Now, you should accept the
laboratory assignment and see that GitHub Classroom created a new GitHub
repository for you to access the assignment's starting materials and to store
the completed version of your assignment. Specifically, to access your new
GitHub repository for this assignment, please click the green "Accept" button
and then click the link that is prefaced with the label "Your assignment has
been created here". If you accepted the assignment and correctly followed these
steps, you should have created a GitHub repository with a name like
`Allegheny-Computer-Science-302-Fall-2020/computer-science-302-fall-2020-portfolio-1-gkapfham`.
Unless you provide the course instructor with documentation of the extenuating
circumstances that you are facing, not accepting the assignment means that you
automatically receive a failing grade for all of its components.

Before you move to the next step of this laboratory assignment, please make sure
that you read all of the content on the web site for your new GitHub repository,
paying close attention to the technical details about the commands that you will
type and the output that your program must produce. Now you are ready to
download the starting materials to your laboratory computer. Click the "Clone or
download" button and, after ensuring that you have selected "Clone with SSH",
please copy this command to your clipboard. At this point, you can open a new
terminal window and type the command `mkdir cs302F2020`. To enter into this
directory you should now type `cd cs302F2020`. Next, you can type the either
`ls` (on either MacOS or Linux) or `dir` (on Windows 10 Pro or Windows 10
Enterprise) and see that there are no files or directories inside of this
directory. By typing `git clone` in your terminal and then pasting in the string
that you copied from the GitHub site you will "download" all of the code for
this assignment. For instance, if the course instructor ran the `git clone`
command in the terminal, it would look like:

```
git clone git@github.com:Allegheny-Computer-Science-302-F2020/computer-science-302-fall-2020-portfolio-1-gkapfham.git
```

After this command finishes, you can use `cd` to change into the new directory.
If you want to "go back" one directory from your current location, then you can
type the command `cd ..`. Finally, please continue to use the `cd` and `ls`
commands to explore the files that you automatically downloaded from GitHub. If
one of the aforementioned commands does not work correctly, then it is possible
that your terminal window is not up-to-date or not configured correctly. In this
case, please share your specific error messages with the instructor, ultimately
working to master the use of terminal commands. What files and directories do
you see? What do you think is their purpose? Spend some time exploring, telling
your discoveries to a student technical leader.

## Final Project Tasks

### Overview of the Project

Throughout the semester, you have been exploring and will continue to explore
the fundamentals of web development, learning how to design and create
mobile-ready web sites that contain, for instance, images and forms and use the
Markdown, HTML, CSS, and JavaScript programming languages. This web design
portfolio project invites you to explore, in greater detail, the challenge and
excitement of real-world web development. Specifically, you will design,
implement, test, and evaluate a mobile-ready site that, whenever possible,
engages with international and/or intercultural perspectives and technologies.
The goal of this project is for you to learn more about how to use, implement,
test, and evaluate different types of software for creating real-world web
sites. Since you will implement and deploy your web site using GitHub and
Netlify, you will also learn more about version control, specifically focusing
on the use of the "GitHub Flow" model and the creation of branches, pull
requests, and Netlify preview builds. You will create a fully documented web
site that explores a stated theme and is both publicly visible and mobile-ready.
Students are also invited to share the details about web design, implementation,
and deployment with their friends and instructors at Allegheny College.
To get started on the assignment, students should learn more about the
technologies mentioned in this paragraph:

- https://www.netlify.com/
- https://guides.github.com/introduction/flow/
- https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/github-flow
- https://githubflow.github.io/

In addition to featuring a production quality web site, your web design
portfolio will include a detailed plan for your project, three
intermediate status updates, and a final report. Written in Markdown,
the detailed plan should explain the theme for your web site and then
the steps that you will take to complete the final version of the site.
Each of the three status reports will highlight your recent
accomplishments and your next steps in light of your detailed plan. The
final report should explain all of your source code, highlighting the
key contributions of your work. This report should also include a
description of why the chosen theme is important and discuss the design,
implementation, and testing that you undertook. All of the written
material in your web design portfolio should be appropriately formatted
and both grammatically and technically correct. The source code that you
write must be carefully documented and tested. If you use existing
resources (e.g., a Flickr image or a responsive web design framework),
then the steps for installation and use should be clearly documented in
your report. Also, the report must explain both the steps that you took
to deploy your site to Netlify and to run your own local web server and
view the web site.

### Creating the First Draft of Your Web Site

To start this project, you should learn about the "JAMStack" and then
visit a listing of web site templates that are available at web sites like the
following:

- https://templates.netlify.com/
- https://jamstackthemes.dev/
- https://themes.gohugo.io/
- http://jekyllthemes.org/
- https://jekyllthemes.io/

After carefully studying each of these templates and the technologies that they
will expect you to master, please pick one and follow its instructions to create
your new GitHub repository and deploy the first version of your web site to
Netlify. Students should also take care to install the Netlify GitHub app so
that you can receive deploy summaries on your pull requests. After the deploy
finishes, check to make sure that your web site is live and working as expected.
Now, you are ready to customize your web site by giving it a project-specific
uniform resource locator (URL). At this step you should also customize the name
of your GitHub repository so that it is the same as the full name of your web
site. For instance, the address of the instructor's web site is
https://www.gregorykapfhammer.com/ and it is hosted in the GitHub repository at
https://github.com/gkapfham/www.gregorykapfhammer.com. Remember, instead of
using the default name for your web site's URL and its GitHub repository, you
should immediately pick suitable names that fit the theme for your site!

After you have appropriately changed these names, please clone your repository
so that it is available on your workstation. After the clone finishes, you can
use `cd` to change into this new directory. If you want to "go back" one
directory from your current location, then you can type the command `cd ..`. You
may continue to use the `cd` and `ls` commands to explore the files that you
automatically downloaded from GitHub. After ensuring that you fully understand
the organization of the source code that emerges from your chosen template,
please follow the "GitHub Flow" model to create a branch of your repository,
make that branch available on GitHub, update at least one file in your branch,
create a pull request, and then check the preview build created by Netlify. If
you are not sure how to take these steps in the terminal window and/or GitHub's
web-based interface, please talk with the course instructor and review the
aforementioned resources. You should continue to practice these important steps
until you can perform them with ease! Here are some extra tips to help you to
successfully complete your web design portfolio:

- If you experience difficulties in getting your chosen template to work, please
  search its GitHub repository for a work-around that you can try. Otherwise,
  please pick an alternative template.

- Spend some time learning how your chosen template uses and organizes the
  Markdown, HTML, CSS, and JavaScript files. Take time to find and understand
  the purpose and behavior of the other types of files that are also in your
  site's repository (e.g., Sassy CSS files).

- Make sure that your HTML, CSS, and JavaScript source code is organized into
  directories.

- Remember that all of your source code must meet well-established programming
  standards.

- Unless you require a customized mobile-ready layout, consider using Bootstrap
  for this task or, alternatively, adopting the responsive design framework
  associated with your chosen template.

- If you download and use images from Flickr or Instagram, give credit and the
  license details.

- Use the textbook's description of web development projects to help you when
  brainstorming.

- Recall that there are no GatorGrader checks for the source code that you
  implement for your own web site, specifically due to the fact that each
  project is different.

- In GatorGrader's absence, you should create and run correctness checks for
  your source code.

- Importantly, you should use "linting" tools to better ensure your source
  code's correctness.

- With that said, there are GatorGrader checks defined for the content that you
  upload to your GitHub repository that contains, for instance, your project
  proposal and your three status updates.

The next step for this project is to identify one aspect of the template
that you want to customize. For instance, you might want to first focus
on improving the fonts, colors, content, or header, footer, or overall
layout. Ultimately, the final version of your web site should be fully
customized and contain useful content that completely explores your
theme. At the start of the project, though, you should focus on ensuring
that you can make a change to your web site's source code and then see
it reflected in the deployed version of your site. While you are not
required to do so, students who want to purchase their own domain names
can collaborate with the instructor to ensure that their Netlify-hosted
site is available under the domain that they purchased.

At this point you have started your web design portfolio. You should now
ensure that you schedule time every week to add content (e.g., new
articles or features) and source code (e.g., CSS files for a
mobile-ready layout) to your web design portfolio, ensuring that it
demonstrates your mastery of the technical skills in the field of web
development and that you can submit it on time.

### Description of the Topics for the Web Design Portfolio

Each student is invited to pick one of the following projects. Please note that
a student selecting the student-designed project must first discuss the idea
with the course instructor, during an upcoming laboratory session, and receive
feedback and then final approval. Please remember that you are fully responsible
for ensuring the feasibility of the project that you propose.

- **International Character Reference**: This topic invites you to investigate
  the Unicode standard for the consistent encoding and display of most of the
  world's languages. Even though Unicode is documented through several sites,
  such as https://en.wikipedia.org/wiki/Unicode, this standard is lengthy and
  cumbersome to search and understand. If you pick this project, you can learn
  more about Unicode by reading Section 3.4 and then develop a site that enables
  people to, for instance, search for and learn about specific characters. This
  web site should feature a responsive layout ensuring that both Unicode
  character examples and the textual content is visible on laptops, desktops,
  and mobile devices. Whenever possible, the web site should enable user
  interactivity through, for instance, the capability to display Unicode symbols
  in different colors or in boxes with different backgrounds.

- **International Art Museum**: Develop an extension of the "art store" project
  described in Sections 3.7, 4.8, and 7.9. Your web site should feature examples
  of international art and then descriptions of both the artists who created the
  work and the art itself. Your site should feature a responsive layout displays
  both the art and the textual content on laptops, desktops, and mobile devices.
  Whenever possible, the site should support user interactivity through, for
  instance, an art discussion board or a background choice for the featured
  artwork.

- **International Travel Site**: You should create an extension of the "travel
  photographs" project described in, for example, Section 7.9. This web site
  could feature photographs taken during international travel, further
  explaining the cultural context that is documented by the photograph.
  Additionally, the site can furnish tips for successful international travel or
  publish interviews with travellers. Your web site should feature a responsive
  layout ensuring that both the photographs and the textual content is visible
  on laptops, desktops, and mobile devices. Whenever possible, the site should
  enable user interactivity through, for instance, a travel discussion board or
  a zooming display for the travel photographs.

- **International Country Site**: Selecting this project means that you will
  create an extension of the "countries database" site given in the extended
  example of Section 8.10. This site could feature the flag or some other iconic
  image for each country. Additionally, the site can furnish important facts
  about each of the chosen countries. Students who are interested in this
  project can investigate the Gapminder web site, at https://www.gapminder.org,
  for inspiration. This web site should feature a responsive layout ensuring
  that both the images and the textual content is visible on laptops,
  desktops, and mobile devices. Whenever possible, the web site should enable
  user interactivity through, for instance, a visualization of statistics
  about countries or a feature supporting the uploading of images and details
  about a new country.

- **Intercultural Perspectives Survey**: You should create a significant
  extension of the "country survey" form given in Section 5.4. This web site
  could feature a survey that asks a person to share their views on one or more
  cultural issues. This site could also present some of the results from the
  individuals who have already taken the survey. This web site should feature a
  responsive layout ensuring that both the images and the textual content is
  visible on laptops, desktops, and mobile devices. A person that picks this
  project should follow the advice in Section 5.5 to ensure that their forms and
  tables are accessible to a wide range of people (e.g., individuals who face
  visual or mobility challenges). If possible, the site should enable user
  interactivity through, for instance, a visualization of results from the
  survey.

- **Student-Designed Project**: Students will develop an idea for their own
  project that focuses on, whenever possible, both international or
  intercultural topics and the field of web development. After receiving the
  course instructor's approval for your idea, you will complete the project and
  report on it. Students who select this project must ensure that it ultimately
  meets all of the requirements outlined in the following section by furnishing,
  for instance, a mobile-ready layout.

### Transferring Your Source code and Technical Writing to GitHub

As you are working on your laboratory assignment, please make sure that you use
VSCode to regularly save your work and transfer it to the GitHub servers. For
instance, please use the `git commit` command in your terminal window or use the
similar feature in VSCode to "stage" your changes in your repository. Once you
have committed your source code to your repository, you can use the `git push`
command to transfer your work to your GitHub repository, making it available for
the course instructor to assess. Please make sure that you regularly commit your
source code and technical writing, using descriptive commit messages to explain
how each commit changes the contents of the repository. Please do not use
vacuous commit messages that do not explain how your commit changes the contents
of the repository!

### Requirements for the Web Design Portfolio Project

To ensure that you have mastered the concepts introduced in this course, your
project's source code should adhere to the following requirements. These
requirements may be modified, at the discretion of the course instructor, only
if a student receives prior permission and documents this approval in the final
report and the source code. Without prior approval, all submitted projects
should contain source code in the Markdown, HTML, CSS, and JavaScript
programming languages. While it is acceptable to reuse source code from
previous laboratory and practical assignments and your chosen template, the
origin of all your derived code must be clearly documented.

Critically, the majority of your project's source code may not be comprised of
work that you found in online sources or completed as part of a previous course
assignment. Additionally, your web site must feature a mobile-ready design that
you created with either bespoke CSS source code or through the use of a
responsive web design framework like Bootstrap. Finally, your site must feature
images that you appropriately stored inside of your GitHub repository. Unless
there is an extenuating reason that prevents you from doing so, your web site
must be publicly available in a GitHub repository and hosted on Netlify; please
see the instructor immediately if you cannot create a public site.

### Summary of the Deliverables for the Web Design Portfolio Project

This assignment invites students to submit, using GitHub, the following
deliverables. Please note that you should maintain two distinct GitHub
repositories: one for the source code and assets of your web site and another,
created by GitHub Classroom for all of the other deliverables. Here is a summary
of the deliverables that you must submit for the web design portfolio project:

- Completed, fully commented, and properly formatted versions of all the source
  code files. Please ensure that you source code adheres to all of the
  requirements mentioned in this assignment sheet (e.g., the use of all the
  required programming languages for web development).

- A one-page written proposal, saved in the file `writing/proposal.md`, with an
  informative title, an abstract, a description of the main idea, an initial
  listing of the tasks that you must complete, and a plan that you will follow
  to complete the entire web design portfolio.

- Three two-paragraph status updates, saved in the appropriate Markdown files,
  that explains what you have already implemented and the steps that you will
  take to finish your web site.

- A detailed final project report, saved in the file `writing/report.md`, that
  documents, in a project-specific fashion, how you designed, implemented,
  tested, and evaluated your web site.

- Stored in the `screenshots/` directory, a collection of five screenshots that
  showcase different aspects of your mobile-ready web site. You should produce
  screenshots that highlight how your site behaves at different viewport widths
  (e.g., wide-screen desktop, standard desktop, laptop, tablet, and phone).

### Reminder About Due Dates for the Web Design Portfolio Project

#### Summary of the Due Dates

- **Assignment Released**: October 19, 2020
- **Project Proposal Due**: October 27, 2020
- **Status Update One Due**: November 3, 2020
- **Status Update Two Due**: November 10, 2020
- **Status Update Three Due**: November 17, 2020
- **Final Report Due**: December 7, 2020 at 11:59 pm
- **Final Web Site Due**: December 7, 2020 at 11:59 pm

#### Details About Each of the Due Dates

- **Project Assigned:** October 19, 2020

    After meeting with the course instructor and discussing your ideas with
    members of your class, pick a topic for your final project. Remember, if you
    select the student-designed project, you must first have your project
    approved by the course instructor. Next, make sure that you create a public
    GitHub repository that contains source code and web resources that can be
    deployed by Netlify.

- **Project Proposal:** October 27, 2020

    Write and submit a one-page proposal for your project. While you can use the
    project descriptions on the previous pages as a starting point, your proposal
    should have an informative title, an abstract, a description of the main idea,
    an initial listing of the tasks that you must finish, a plan for completing
    the work, and, if necessary, a statement of instructor approval.

- **Intermediate Status Updates**: November 3, 10, and 17, 2020

    As you continue working on your project, please write and submit a
    two-paragraph status update through your GitHub repository created by GitHub
    Classroom. When appropriate, you should give a demonstration of your web
    site to either a member of the class, a student technical leader, or the
    course instructor. You can schedule a demonstration with the course
    instructor by picking a time during the instructor's office hours.

- **Due Date of the Web Design Portfolio**: December 7, 2020 at 11:59 pm

    You should submit the final version of your project through both your site's
    GitHub repository and the repository created by GitHub Classroom. This
    submission should include all of the relevant source code and web site
    screenshots, the final version of each written reports, the textually
    archived feedback from the people who used your web site, and any additional
    required or supplementary materials that serve to demonstrate the success of
    your project.

## Automated Checks with GatorGrader

In addition to meeting all of the requirements outlined in this assignment
sheet, your submission must pass the following checks that
[GatorGrader](https://github.com/GatorEducator/gatorgrader) automatically
assesses:

- The file proposal.md exists in the writing directory
- The file report.md exists in the writing directory
- The file screenshot_five.png exists in the screenshots directory
- The file screenshot_four.png exists in the screenshots directory
- The file screenshot_one.png exists in the screenshots directory
- The file screenshot_three.png exists in the screenshots directory
- The file screenshot_two.png exists in the screenshots directory
- The file update_one.md exists in the writing directory
- The file update_three.md exists in the writing directory
- The file update_two.md exists in the writing directory
- The proposal.md in writing has at least 100 word(s) in total
- The proposal.md in writing has exactly 0 of the `Add Your Name Here` fragment
- The proposal.md in writing has exactly 0 of the `TODO` fragment
- The proposal.md in writing has exactly 1 of the `heading` tag
- The report.md in writing has at least 100 word(s) in total
- The report.md in writing has at least 1 of the `code_block` tag
- The report.md in writing has exactly 0 of the `Add Your Name Here` fragment
- The report.md in writing has exactly 0 of the `TODO` fragment
- The report.md in writing has exactly 1 of the `heading` tag
- The repository has at least 10 commit(s)
- The update_one.md in writing has at least 50 word(s) in total
- The update_one.md in writing has exactly 0 of the `Add Your Name Here` fragment
- The update_one.md in writing has exactly 0 of the `TODO` fragment
- The update_one.md in writing has exactly 1 of the `heading` tag
- The update_three.md in writing has at least 50 word(s) in total
- The update_three.md in writing has exactly 0 of the `Add Your Name Here` fragment
- The update_three.md in writing has exactly 0 of the `TODO` fragment
- The update_three.md in writing has exactly 1 of the `heading` tag
- The update_two.md in writing has at least 50 word(s) in total
- The update_two.md in writing has exactly 0 of the `Add Your Name Here` fragment
- The update_two.md in writing has exactly 0 of the `TODO` fragment
- The update_two.md in writing has exactly 1 of the `heading` tag

```
        ┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
        ┃ Passed 32/32 (100%) of checks for cs302-F2020-portfolio1! ┃
        ┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
```

If [GatorGrader's](https://github.com/GatorEducator/gatorgrader) automated
checks pass correctly, the tool will produce the output like the following in
addition to returning a zero exit code (which you can access by typing the
command `echo $?`). You will need to run
[GatorGrader](https://github.com/GatorEducator/gatorgrader) in a Docker
container by following the steps in the [Using Docker](#using-docker) section.

## Assignment Assessment

Taking inspiration from the principles of [specification-based
grading](https://www.amazon.com/Specifications-Grading-Restoring-Motivating-Students/dp/1620362422),
the grade that a student receives on a laboratory assignment will be based on
whether or not it meets the standards for technical work in the fields of
software engineering and discrete structures. Instead of receiving a single
numerical or letter grade for this assignment, your grade will have the
following components:

- **Percentage of Correct GatorGrader Checks Ranging Between 0 and 100**: Your
  submitted Python program must pass all of GatorGrader's checks by, for
  instance, ensuring that it produces the correct output and has all of the
  required characteristics. Your technical writing must pass all of
  GatorGrader's checks about, for instance, the length of its output and its use
  of the required Markdown language features for technical writing. For this
  component of a laboratory assignment's grade, your work will receive a
  percentage, ranging from 0 to 100, that corresponds to the percentage of
  GatorGrader checks that automatically pass inside of a GitHub Actions build.

- **GitHub Actions Build Status of Either ✔  or ❌**: Since additional checks on
  the Python source code and/or technical writing are encoded in GitHub Action
  workflows and, moreover, all of the GatorGrader checks are also run in GitHub
  Actions, your work will receive a checkmark grade if the last
  before-the-deadline build in GitHub Actions passes and a ✔  appears in the
  GitHub commit log instead of an ❌. The build status reported by GitHub
  Actions will only be a ✔ if the source code and technical writing in the
  GitHub repository pass all of both the GatorGrader checks and the additional
  checks.

- **Technical Writing Mastery of Either ✔  or ❌**: Students will also receive a
  ✔ grade when the responses to the technical writing questions presented in the
  `writing/reflection.md` reveal a mastery of technical writing skills. To
  receive a checkmark grade, the submitted writing should have correct spelling,
  grammar, punctuation, and formatting in addition to following the rules of the
  Markdown language. Your work will receive a ✔ grade for this component
  if the build report from GitHub Actions reveals that there are no detected
  mistakes in the technical writing.

- **Technical Knowledge and Skill Mastery of Either ✔  or ❌**: Students will
  also receive a checkmark grade when the GitHub repository reveals that they
  have mastered all of the technical knowledge and skills developed during the
  completion of the laboratory assignment. As a part of this grade, the
  instructor will assess aspects of the project including, but not limited to,
  the use of effective Python source code comments, correct Git commit messages,
  and accurate responses to the technical writing questions.

A student will receive either a ✔  or ❌ for their proposal and then for each of
the three status updates. A student will receive all of the above grades for
their final submission of the web design portfolio. You are not expected to have
a passing build for the web design portfolio project until you have completed
your final submission no later than the final due date specified at the top of
the assignment sheet.

## Advance Feedback on an Assignment

Students who wish to receive feedback on their work for any course assignment
should first open an issue on the issue tracker for their assignment's GitHub
repository, giving an appropriate title and description for the type of feedback
that you would like the course instructor to provide. After creating this issue,
you will see that GitHub has created a unique web site that references it. To
alert the course instructor to the fact that the issue was created and that you
want feedback on your work, please send it to him by a Slack direct message at
least 24 hours in advance of the project's due date. After the instructor
responds to the issue, please resolve all of the stated concerns and participate
in the discussion until the issue is resolved and ultimately marked as closed.

## Discussion of a Graded Assignment

Students who wish to receive feedback on their work for any graded course
assignment should leave question in the same region of Github where the course
instructor submitted the assignment's grade. For example, if the instructor
submits your grade to a pull request in your repository for a laboratory
assignment, then you should ask questions about your grade in that pull request,
bearing in mind the need to @-mention the course instructor in the body of your
comment. Students can continue to discuss the graded assignment with the course
instructor until they understand all the technical topics that were the
focus of the particular assignment.

## Additional Resources

### System Commands

This project invites students to enter system commands into a terminal window.
This assignment uses [Docker](https://www.docker.com) to deliver programs, such
as `gradle` and the source code and packages needed to run
[GatorGrader](https://github.com/GatorEducator/gatorgrader), to a students'
computer, thereby eliminating the need for a programmer to install them on their
development workstation. Individuals who do not want to install Docker can
optionally install of the programs mentioned in the [Project
Requirements](#requirements) section of this document.

### Non-Interactive Docker Commands

Once you have installed [Docker
Desktop](https://www.docker.com/products/docker-desktop), with MacOS and Linux
you can use the following `docker run` command to start `gradle grade` as a
containerized application, using the
[DockaGator](https://github.com/GatorEducator/dockagator) Docker image available
on
[DockerHub](https://cloud.docker.com/u/gatoreducator/repository/docker/gatoreducator/dockagator).

```bash
docker run --rm --name dockagator \
  -v "$(pwd)":/project \
  -v "$HOME/.dockagator":/root/.local/share \
  gatoreducator/dockagator
```

The aforementioned command will use `"$(pwd)"` (i.e., the current working
directory) as the project directory and `"$HOME/.dockagator"` as the cached
GatorGrader directory. Please note that both of these directories must exist,
although only the project directory must contain something. Generally, the
project directory should contain the source code and technical writing for an
assignment, as provided to a student by the instructor through GitHub.
Additionally, the cached directory should not contain anything other than
directories and programs created by DockaGator, thus ensuring that they are not
otherwise overwritten during the completion of the assignment.

To ensure that the previous command will work correctly, you should create the
cache directory by running the command `mkdir $HOME/.dockagator` on the MacOS
and Linux operating systems. However, if you are using the Windows operating
system then you will instead need to type the command `mkdir
%HomeDrive%%HomePath%/.dockagator`. Finally, since the above `docker run`
command does not work correctly on the Windows operating system, you will need
to instead run the following command to adapt to the differences in the `cmd`
terminal window:

```bash
docker run --rm --name dockagator \
  -v "%cd%:/project" \
  -v "%HomeDrive%%HomePath%/.dockagator:/root/.local/share" \
  gatoreducator/dockagator
```

Please note that not all version of the Windows terminal window will correctly
recognize the use of the `%cd%` and `%HomeDrive%%HomePath%` variables. In this
case, you should substitute the actual directory for a specific course
assignment for the `%cd%` variable and the drive letter that contains the
`.dockagator` directory for the `%HomeDrive%%HomePath%` variable. Finally, the
Windows terminal window may not work correctly when you attempt to run a
multi-line command. In this case, you should break up the aforementioned
four-line command into separate lines, like `docker run --rm --name dockagator`
and `-v "%cd%:/project"` and then connect them into a single long line that you
separate by a single space. Here is an example of what the long command would
look like, again assuming that the Windows `cmd` terminal correctly interprets
the `%cd%` and `%HomeDrive%%HomePath%` variables:

```bash
docker run -it --rm --name dockagator -v "%cd%:/project" -v "%HomeDrive%%HomePath%/.dockagator:/root/.local/share" gatoreducator/dockagator /bin/bash
```

Here are some additional commands that you may need to run when using Docker:

* `docker info`: display information about how Docker runs on your workstation
* `docker images`: show the Docker images installed on your workstation
* `docker container list`: list the active images running on your workstation
* `docker system prune`: remove many types of "dangling" components from your workstation
* `docker image prune`: remove all "dangling" docker images from your workstation
* `docker container prune`: remove all stopped docker containers from your workstation
* `docker rmi $(docker images -q) --force`: remove all docker images from your workstation

### Commands for an Interactive Docker Shell

Since the above `docker run` command uses a Docker images that, by default, runs
`gradle grade` and then exits the Docker container, you may want to instead run
the following command so that you enter an "interactive terminal" that will
allow you to repeatedly run commands within the Docker container. Don't forget
that, if you are using the Windows operating system, then you will need to use a
different command to run Docker, as explained previously in this document.
Importantly, the command that you type if you are a Windows user should still
contain the `-it` at the start of the `docker run` and the `/bin/bash` at the
end of the command. However, the other components of this command need to be
customized for the Windows operating system.

If you use either MacOS or Linux, then this is the command that you would run to
enter into the interactive terminal provided by a Docker container:

```bash
docker run -it --rm --name dockagator \
  -v "$(pwd)":/project \
  -v "$HOME/.dockagator":/root/.local/share \
  gatoreducator/dockagator /bin/bash
```

If you use Windows, then this is the command that you would run to enter into
the interactive terminal provided by a Docker container:

```bash
docker run -t --rm --name dockagator \
  -v "%cd%:/project" \
  -v "%HomeDrive%%HomePath%/.dockagator:/root/.local/share" \
  gatoreducator/dockagator /bin/bash
```

Once you have typed this command, you can use the [GatorGrader
tool](https://github.com/GatorEducator/gatorgrader) in the Docker container by
typing the command `gradle grade` in your terminal. Running this command will
produce a lot of output that you should carefully inspect. If GatorGrader's
output shows that there are no mistakes in a course assignment, then your source
code and technical writing are passing all of the automated baseline checks.
However, if the output indicates that there are mistakes, then you will need to
understand what they are and then try to fix them.

Remember, to correctly run any of the commands mentioned in this guide, you must
be in the main (i.e., "home base") directory for a course assignment where the
`build.gradle` file is located.

### Upgrading the Docker Container

If the course instructor provides a new version of the Docker container called
`gatoreducator/dockagator` and you want to receive it immediately, you must
first delete the existing Docker container on your laptop by running the command
`docker rmi gatoreducator/dockagator`. Next, you can re-run one of the
aforementioned Docker commands, like the following one, which would work on
MacOS or Linux:

```
docker run -it --rm --name dockagator \
  -v "$(pwd)":/project \
  -v "$HOME/.dockagator":/root/.local/share \
  gatoreducator/dockagator /bin/bash
```

Please note that if you attempt to run `gradle grade` in an updated Docker
container it is possible that the command will execute incorrectly if you
previously used GatorGrader with a Docker container that featured a different
version of the Python programming language. In this situation, you should delete
the directories inside of the `.dockagator` directory and then again attempt to
run the `gradle grade` command inside of the Docker container. Specifically, you
will need to delete directories in `.dockagator` that are normally called
`gatorgrader`, `virtualenv`, and `virtualenvs`.

### Downloading Project Updates

If the course instructor pushes updates to this assignment and you received it
through GitHub Classroom and you would like to also receive these updates, then
you can type this command in the main directory for this assignment:

```
git remote add download git@github.com:Allegheny-Computer-Science-302-F2020/cs302-F2020-portfolio1-starter.git
```

You should only need to type this command once; running the command additional
times may yield an error message but will not negatively influence the state of
your Git repository. Now, you are ready to download the updates provided by the
GatorGrader maintainers by typing this command:

```
git pull download master
```

This second command can be run whenever the course instructor needs to provide
you with new source code for this assignment. However, please note that, if you
have edited the files that we updated, running the previous command may lead to
Git merge conflicts. If this happens, you may need to manually resolve them with
the help of the instructor or a student technical leader. Finally, please note
that the [Gradle plugin](https://github.com/GatorEducator/gatorgradle) for
[GatorGrader](https://github.com/GatorEducator/gatorgrader) will automatically
download the newest version of GatorGrader.

### Using GitHub Actions

This assignment uses [GitHub Actions](https://github.com/features/actions) to
automatically run [GatorGrader](https://github.com/GatorEducator/gatorgrader)
and additional checking programs every time you commit to your GitHub
repository. The checking will start as soon as you have accepted the assignment
&mdash; thus creating your own private repository &mdash; and the course
instructor and/or GitHub enables GitHub Actions on it. If you do not see either
a yellow &#9679; or a green ✔ or a red ❌ in your listing of commits, then
please ask the course instructor to see whether or not GitHub Actions was
correctly enabled.

### System Requirements

This assignment was developed to work with the following software and versions:

- Docker Desktop
- Operating Systems
  - Linux
  - MacOS
  - Windows 10 Pro
  - Windows 10 Enterprise
- Programming Language Tools
  - Gradle 6.6
  - MDL 0.5.0
  - Python 3.7 or 3.8

### Reporting Problems

If you have found a problem with this assignment's provided source code or
documentation, then you can go to the [Computer Science 302 Fall 2020 Planning
Repository](https://github.com/Allegheny-Computer-Science-302-F2020/cs302-F2020-plans)
and [raise an
issue](https://github.com/Allegheny-Computer-Science-302-F2020/cs302-F2020-plans/issues).
If you have found a problem with the [GatorGrader
tool](https://github.com/GatorEducator/gatorgrader) and the way that it checks
your assignment, then you can also [raise an
issue](https://github.com/GatorEducator/gatorgrader/issues) in that repository.
To ensure that your issue is properly resolved, please provide as many details
as is possible about the problem that you experienced. Individuals who find, and
use the appropriate GitHub issue tracker to correctly document, a mistake in any
aspect of this assignment will receive extra credit towards their grade for the
course.

### Receiving Assistance

If you are having trouble completing any part of this project, then please talk
with either the course instructor or a student technical leader during the
course session. Alternatively, you may ask questions in the Slack workspace for
this course. Finally, you can schedule a meeting during the course instructor's
office hours.
