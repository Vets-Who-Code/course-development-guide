- [Building a Course for VWC](#building-a-course-for-vwc)
  * [Course Structure](#course-structure)
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

# Building a Course for VWC
Keep in mind that laying out a well thought-out and comprehensive course that achieves our organizational goals is an iterative process. We seek to continually improve the effectiveness of our courses by improving learning outcomes. 

Primary focus at the beginning is on writing learning objectives and an overall content structure to support those objectives. 

## Course Structure

### :factory: Folder Structure :factory:
Repository is named after the course *ex: web-development-course*

Include a folder for each lesson within the module that will include that specific lessons activities and resources. 

Note: If you would like a specific folder order on Github displayed use a numbered prefix. As a rule of thumb start with a leading `0` example: `01`, `02`, `03` etc... this way folders will display top to bottom.

📁 **Course Folder:** contains Root level README as defined below.
- 📁 **Module Folder:** contains module README.
	 - 📁 **Lesson Folder:** Contains Lesson README and relevant references, activities, and examples.

_Course's will have multiple modules and modules can have multiple lessons_

### Root level READMEs
Includes a root level readme that includes:

#### Rationale
Explain why learners should learn this and how it applies to them and the overall goal of the course.

If a learner knows why they should learn something and values it, they are much more likely to actually learn it. 

This also provides us an opportunity when designing a course to make sure we are only including lessons where we've evaluated the trade-offs and decided the lessons will be valued by the learners. 

#### Course Goals
Course goals provide a high-level overview of what the learner will be able to accomplish once they've completed the course. The goals should be knowledge or skill-oriented and should be specific, observable, and measurable. 

For VWC, the course goals are based on job descriptions and feedback from hiring managers in support of our larger organizational goals. 

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


  ### Example: Learning the Command-Line Interface
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


### Example for Lesson: Navigate the Filesystem
- **Lesson Objective:**  On completion of this lesson, the student will be able to identify their current position in the filesystem, list folders and files, move in and out of folders, and read the contents of a file.
- **Learning Activity:** Terminal Capture the Flag - Learner navigates a series of folders to find a file with the Key. 
- **Evaluation:** Learner completes the lesson by submitting the Keycode in the end-of-lesson quiz. 

## Evaluate the Learners Performance
Testing is a natural part of learning. It helps the learner and teacher either confirm if the learner met the learning objective or identify if the learner needs help. 

Testing shouldn't just be a multiple-choice quiz at the end of each lesson. In the example we've created above, finding the key in a capture the flag style exercise is a great way to ensure the learner meets all the lesson objectives while also providing a fun way of exploring and mastering their new skills. 

If there are critical knowledge elements to the lesson, it's best to use recall style questions, fill in the blank style, or to write about the topic, rather than multiple-choice style exams. 

Here is a system for approaching evaluations:
- **Task:** The task should be taken directly from the learning objectives.
- **Conditions:** This defines the context or environment the evaluation will take place.
- **Standard:** Describes the criteria used to determine whether or not the student meets the learning objective.

### Example for Lesson: Navigate the Filesystem
- **Task:** The student must navigate a series of folders and files to find a hidden key file in one of the folders. 
- **Conditions:** Students are provided a zipped project folder that they will need to unzip and place on their desktop and use their terminal/shell of choice.
- **Standard:** The student must navigate the project folder and find the provided key in under 5 minutes using only the commands taught in this lesson.

All feedback should be either _corrective_, helping the learner identify gaps or mistakes in their understanding, or _confirming_, clearly indicating the learner has achieved the lesson objective. 

