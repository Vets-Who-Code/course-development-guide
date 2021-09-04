- [Building a Curriculum for VWC](#building-a-curriculum-for-vwc)
  * [Curriculum Structure](#curriculum-structure)
    + [:factory: Folder Structure :factory:](#-factory--folder-structure--factory-)
    + [Root level READMEs](#root-level-readmes)
      - [Rationale](#rationale)
      - [Objectives](#objectives)
      - [Prerequisites](#prerequisites)
      - [Syllabus](#syllabus)
      - [Next Step](#next-step)
  * [Build Learning Activities](#build-learning-activities)
  * [Evaluate the Learners Performance](#evaluate-the-learners-performance)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

# Building a Curriculum for VWC
Keep in mind that laying out a well thought-out and comprehensive curriculum that achieves our organizational goals is an iterative process. We seek to continually improve the effectiveness of our courses by improving learning outcomes. 

Primary focus at the beginning is on writing learning objectives and an overall content structure to support those objectives. 

## Curriculum Structure

### :factory: Folder Structure :factory:
Repository is named after the course *ex: web-development-curriculum*

Include a folder for each lesson within the module that will include that specific lessons activities and resources. 

Note: If you would like a specific folder order on Github displayed use a numbered prefix. As a rule of thumb start with a leading `0` example: `01`, `02`, `03` etc... this way folders will display top to bottom.

> :warning: TODO: Include a sample file structure for people to use as a template.

### Root level READMEs
Includes a root level readme that includes:

#### Rationale
Explain why learners should learn this and how it applies to them and the overall goal of the course.

If a learner knows why they should learn something and values it, they are much more likely to actually learn it. 

This also provides us an opportunity when designing a course to make sure we are only including lessons where we've evaluated the trade-offs and decided the lessons will be valued by the learners. 

#### Course Goals

#### Prerequisites
What other courses or skills do students need to complete the course.

What prior knowledge and skills should the learner have before taking this course. You may not be able to effectively determine this until you've completed the course design and development process. 

#### Syllabus
A general table of contents listing high level section headings. Generally no deeper than 2 indents.

#### Next Step
Describe what to do next. 

## Write Learning Objectives
Learning objectives are the key to effective lesson plans. Once you've got good learning objectives, preparing the rest of your lesson is much easier. Learning objectives give us a framework for deciding what to include in our training and what to leave out and provides a cohesive, logical path for our lessons. 

Don't agonize over this process and end up with complicated, confusing, or vague objectives, though. A solid learning objective is specific, observable, and measurable. What would the learner need to do to prove they learned the lesson? 

Follow these five steps:
-	Identify the learner's needs
-	Write the high-level goals for the lesson. What they are learning, and why is it important. 
-	Decide on the critical content.
-	Decide the level of learning for that critical content.
-	Write a specific, observable, and measurable learning objective. 

Example:
  ### Learning the Command-Line Interface
-	Students must demonstrate they can effectively use the CLI

-	The students will learn to use the CLI to have greater control and flexibility over their projects and environments. 

-	Critical Content:
	- The Shell and Environment
	- Navigating the Filesystem
	- Working with Files and Directories
	- Running and Managing Programs

-	The Level of Learning for each of the above elements is Application; the student will use their knowledge and understanding to complete a series of exercises. 

-	Upon completion of this lesson, the student will setup a web development environment from scratch using only the command line that includes;
    1. A project folder and files:
       - project-name/
         - images/
         - index.html – must include boilerplate linking styles.css and scripts.js.
          - styles.css
          - scripts.js
    2. Install Node and Prettier – setting up prettier on the project
    3. Initialize a Git repository and make initial commit.
    4. Push repo to GitHub
    -  **Extra Credit:** Do all this with a shell script


## Build Learning Activities
Our goal is to create learning activities that lead to attaining the learning objectives. This means we create or select only activities that lead the learner directly to meeting each objective. 

Learning activities should make up the majority of a lesson. A well-structured learning activity provides the opportunities to practice the new skill in isolation and with previously learned skills.

Example:
### Lesson name: Navigate the Filesystem
- **Lesson Objective:**  On completion of this lesson, the student will be able to identify their current position in the filesystem, move in and out of directories, - and read the contents of a file.
- **Learning Activity:** Terminal Capture the Flag - Learner navigates a series of folders to find a file with the Key. 
- **Evaluation:** Learner completes the lesson by submitting the Keycode in the end-of-lesson quiz. 

## Evaluate the Learners Performance
> :warning: TODO: Provide a detailed example that shows how the outcomes from the activities will be used to evaluate how well a learner meets the overall performance objectives


