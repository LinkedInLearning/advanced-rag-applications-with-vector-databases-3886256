# Advanced RAG Applications with Vector Databases
This is the repository for the LinkedIn Learning course `Advanced RAG Applications with Vector Databases`. The full course is available from [LinkedIn Learning][lil-course-url].

![lil-thumbnail-url]

## Course Description

Retrieval-augmented generation (RAG) is everywhere these days, and vector databases are what give them their power. But RAG isn’t as simple as some companies claim, so it can be easy to get overwhelmed. In this course, discover state-of-the-art RAG methods, including how to optimize text-based RAG via chunking, embedding, and metadata usage, and how to conduct basic image search with a vector database. You’ll also get a chance to practice multimodal RAG by embedding and storing data and querying images with text. Along the way, instructor Yujian Tang provides practical, hands-on demonstrations and exercise challenges to test out your new skills.

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
	- Python 3.10 or 3.11
    - requirements.txt
2. Clone this repository into your local machine using the terminal (Mac), CMD (Windows), or a GUI tool like SourceTree.

## Instructor

Yujian Tang

AI Builder                  

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/yujian-tang?u=104).


[0]: # (Replace these placeholder URLs with actual course URLs)

[lil-course-url]: https://www.linkedin.com/learning/advanced-rag-applications-with-vector-databases
[lil-thumbnail-url]: https://media.licdn.com/dms/image/v2/D4E0DAQFonI7LTbFo_g/learning-public-crop_675_1200/learning-public-crop_675_1200/0/1727723235646?e=2147483647&v=beta&t=KcI1L2PD0dAs_AAGyJoMpneLG2Xb_HqAeue6F65UDHM

