# Intro to DevOps Course
## Issues to be resolved before integrating into DevOps ND

### Current Lesson 1

#### The Project

* Video is likely obsolete, references Jenkins etc.

#### A is for Automation

* Talks about Lessons 2 and 3, need to edit to remove last sentence

#### M is for Measurement

* "We'll talk more about measurement in Lesson 3": need to edit to remove last sentence

#### Outro

* "We'll see you in Lesson 2": Neither Karl nor Dwayne are in new Lesson 2
* Is the survey going to be used? Who will look over the responses? Has anyone been looking at them?


### Current Lesson 2

#### Solving the Environment Problem

* Add instructor note saying which project in ND covers CI 

#### Installation Requirements

* Are they up to date for latest OS releases? 

#### Quiz: Building the Image

* Karl says to change to the `packer-templates` directory and follow the instructions in the README. The README is not in that directory but in one level above. 
* Instruction `packer build -only=virtualbox-iso application-server.json` led to several errors before eventual success:

```
read: operation timed out
==> virtualbox-iso: ISO download failed.
Build 'virtualbox-iso' errored: ISO download failed.

checksums didn't match expected
==> virtualbox-iso: ISO download failed.
Build 'virtualbox-iso' errored: ISO download failed.

==> Some builds didn't complete successfully and had errors:
--> virtualbox-iso: ISO download failed.
```

#### Quiz: Launching the App

* Instructions in README don't suggest forking repo first, as Karl does in his video. Should README be revised?
* Running `sudo npm install` led to several errors: No license field, deprecated, cannot run in wd, etc.
* Running `grunt -v` leads to:
```
Warning: Cannot read property 'connected' of undefined Use --force to continue.
Aborted due to warnings.
```
* Answers video alone should have the instructor note that gives away the answer!
* README mentions running on cloud before the reading node that follows quiz; reorganize README

#### Access Configuration for Cloud
* Are instructions correct?
* Do we want to specify one cloud provider instead of many choices?

#### Outro
* Mentions Lesson 3


