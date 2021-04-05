# Contributing
An OSSUM's main purpose and function is accurately and intuitively showing a complete overview of a curriculum's courses, and hosting a database for prospective students to track their work.

In order to promote consistency, there are a number of guidelines for contributions.

## Permanence
Any and all OSSUMs made must be hosted using OSSUM's shared notion account in order to prevent further changes without collaboration within *this* repository. Include within the relevant branch the link to the notion page, and a copy will be made and added to the branch for you.

## Bug Fixes
If you find any spelling errors, feel free to correct them and share the updated version in a pull request, with information over what you fixed. A permanent copy will be made afterwards, and it will be updated.

## Covering new curricula
Covering new curricula is helpful! In the case that you wish to cover an open source curriculum, keep in mind the following things before creating a pull request.

### Resource data
Course information included within their page contains the following information:

* **Subsection**: The subsection of the curriculum in which the course is a part of.
* **Course**: A link to the relevant course.
* **Prerequisites**: Backlinks or information regarding all requirements to take the course. If none are required, then this part is optional.

Supplemental Material information included within their page contains the following information:

* **Link**: A link to the supplemental material.
* *Contents*: A toggle block containing either a transcription of the material's contents, or relevant information about the full scope of the link's contents.

### Tracking Number
Resources within the Curriculum section must be ordered from 001 onwards in the expected order a student is to take them. The tracking number 000 is reserved for curriculum information only.

If there are different course tracks a student can take, label them with a letter—*A, B, C, and onwards... skipping X*—and group the courses by their letter in the order in which it is expected a student to take them.

If a course *may* require extra supplemental material or courses outside of the curriculum, include the relevant information within the **Extras** section, and label it using the same tracking number of the course it supplements. Include the letter X following the tracking number.

### Course Labelling
Label the course using the following label types:

* **Track**: The course's track in which it belongs. For example: Intro CS, Core CS, and Advanced CS within OSSU's computer-science curriculum.

* **Subsection**: The subsection within the track that the course belongs to. For example: Programming, Mathematics, or Systems within OSSU's computer-science curriculum.

If the course qualifies, label them with the following optional label types:

* **Elective**: Elective courses are not all required, but taking one or more is usually mandatory. They are not seperated tracks.

* **Project/Final Project**: Project and Final Project courses consist of a major project one is required to finish in order to complete the curriculum.

Make sure to include a seperate label to show whether the resource is a course, or supplemental material.

### Elective Disclosure
If a number of courses are electives in which one set of electives may be completed, but not necessarily all, then disclose this information within a Callout block within the course's information.

Label the course as an elective within the database, and include all relevant courses required for the chosen elective within the Callout block.
