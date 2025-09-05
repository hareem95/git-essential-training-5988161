# Git Essential Training
This is the repository for the LinkedIn Learning course Git Essential Training. The full course is available from [LinkedIn Learning][lil-course-url].

![lil-thumbnail-url]

## Course Description

<p>If you’ve ever wondered why someone should use Git or how to use it for version control, this is a great course to get started. Join Azure MVP and GitHub Star Barbara Forbes as she guides you through the installation process, the Git workflow, setting up and pushing code into a repo, and committing changes, all with a focus on version control and how Git can help you achieve it. Find out why people use Git. Learn how Git works, locally or through a provider, and how you can get it installed, configured, and running the way you need it to work. Follow the full process of pushing your code with Git, then explore ways to make changes to files. Discover important concepts in Git, like how to ignore files you don’t want to include, how branching and merging can help you with development, what should be in a commit, and how to troubleshoot common errors.</p><p>This course is integrated with GitHub Codespaces, an instant cloud developer environment that offers all the functionality of your favorite IDE without the need for any local machine setup. With GitHub Codespaces, you can get hands-on practice from any machine, at any time—all while using a tool that you’ll likely encounter in the workplace. Check out “Using GitHub Codespaces" with this course to learn how to get started.</p>

_See the readme file in the main branch for updated instructions and information._
## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

## Installing
1. To use these exercise files, you must have the following installed:
	- [list of requirements for course]
2. Clone this repository into your local machine using the terminal (Mac), CMD (Windows), or a GUI tool like SourceTree.
3. [Course-specific instructions]

### Instructor

Barbara Forbes

Azure MVP and GitHub Star
                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/barbara-forbes?u=104).


[0]: # (Replace these placeholder URLs with actual course URLs)

[lil-course-url]: https://www.linkedin.com/learning/git-essential-training-25677984
[lil-thumbnail-url]: https://media.licdn.com/dms/image/v2/D4D0DAQFtri24YywCRA/learning-public-crop_675_1200/B4DZaSCsxDGwAc-/0/1746206904098?e=2147483647&v=beta&t=kWaRJNyIgQ-qsLPNYMvXiqqQgEhud2WqEhf2m-L3f5M

