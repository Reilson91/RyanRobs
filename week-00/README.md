# Week 0 Overview
## Class 1 (Sat., Sept. 5)

### Agenda
| Activity | Led by | Type|
| ------------- | ------------- | ------------- |
| How to compile Java | Instructor | Classwork |
| Introduction to Code School | Instructor | Discussion |
| Q/A on pair programming & Git | Instructor | Discussion |
| GitHub Pages Lab | Programming Pair | Classwork |
| Class wrap-up and next steps | Instructor | Discussion |

### Resources
- [Student Prep Plan](html-css-prep-plan.md)

### Competencies
1. Use Git to create a remote repository, save it locally, change it and update it remotely
1. Use Github Pages to host a static website
1. Fork a repository and update your local copy with upstream changes
1. Creating a new project in IntelliJ
1. Running your code in IntelliJ


### Class 1
#### GitHub Pages Lab: Hosting your own portfolio on GitHub Pages (competencies 1 & 2)
1. Each pairing partner creates a [Github](https://github.com/) account (_if they don't have one_).
1. Pair Partner One (PP1) forks this [GitHub Pages starter repo](https://github.com/cmburk/github-pages)
1. PP1 changes the name of the repo to `<username>.github.io` to work as a [GitHub Pages site](https://guides.github.com/features/pages/)
1. PP1 clones the fork locally
1. PP1 adds the name of the pairing partners in the `<h1>` tag on the `index.html` page so that it reads "Pair1FirstName's and Pair2FirstName's Home Page"
1. PP1 updates their Git remote repo with the local changes
1. Pair Partner Two (PP2) forks PP1's repo, changing the name to of it to work as PP2's GitHug Pages site
1. PP1 and PP2 verify that the sites are the same at `https://[username].github.io`

#### Getting a copy of the assignment repo and keeping it up-to-date (competency 3)
1. PP1 and PP2 individually fork the [Program Increment 1 HTML/CSS assignment repo](https://gitlab.mccinfo.net/code-school/course-work/pi1-html-css) in Gitlab
1. PP1 and PP2 each clone it to their local environment
1. PP1 and PP2 each [configure their remote for the fork](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/configuring-a-remote-for-a-fork)
1. After Code School instructor makes a change to the repo, PP1 and PP2 each [sync their fork with upstream changes](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork)

#### Java without an IDE
1. Right click in any open space on your desktop and select the option ```Git Bash Here```. 
1. This will open Git Bash and it will be in the Desktop directory. Use the command ```pwd``` to **P**rint **W**orking **D**irectory.
1. Verify your installation of Java by typing in ```java -version```. It should contain a line similar to  ```openjdk version "11.0.8"```. The version might be a little different, but should still be 11.
    * If you see 8 or 1.8 instead, that's fine. Continue on with the lab (everything will still work the same), but please let an instructor know!
1. Create a file on your desktop and call it ```Hello.java```. You can type the command ```touch Hello.java```. The ```touch``` command will create a file with the given name if it doesn't exist.
1. Use your favorite text editor to edit ```Hello.java```. Create the "Hello, World!" application, where all the program does is print out "Hello, World!". You can use the code down below.
1. With the code written, try to compile your code. Back in Git Bash, type the command ```javac Hello.java```. This will create a new file called ```Hello.class```. If you have errors, the compiler will tell you and you will need to fix them.
1. With the class compiled, run the program! Type the command ```java Hello``` and you should see the output.
 
#### Java with an IDE (competency 4 & 5)
1. Open IntelliJ. IntelliJ will be the editor of choice for this class.
1. With IntelliJ open, at the top left, click ```File -> New -> Project...```.
1. On the left panel, make sure Java is selected.
1. For the Project SDK, Make sure to choose a version that is Java 11. The grey text tells you what the version is exactly.
    * As before, if you do not have a Java 11 version, just use 8 or 1.8 instead. Continue on with the lab (everything will still work the same), but please let an instructor know!
1. Don't check any options in the middle panel.
1. Click next.
1. Click ```Create project from template``` and select the ```Command Line App``` option.
1. Click next.
1. Name the project ```HelloWorldApp```.
1. Leave the project location as is.
1. Change the Base package to ```edu.mccneb```.
1. Click finish!
1. On the left panel is your project navigation panel. Expand the folder ```HelloWorldApp```.
1. Expand the ```src``` folder. This folder is where your Java code will go.
1. Expand the package ```edu.mccneb```. This is where your Main class exists. We will cover packages in a later class, but for now, know this is where java knows your code is.
1. In the Main class, add a print statement printing ```Hello, World!```. You can use the below code for reference.
1. In the Main class on the line containing ```public class Main {```, there is a green play button next to the line number. Click that button and select ```Run 'Main'```.
1. Watch IntelliJ open a terminal panel and execute your program!

### References

#### Hello, World! In Java

Make sure that the name of your file is the **SAME** as the name of the class. (A class named ```Hello``` should be in a file named ```Hello.java```)
```
public class Hello {
	public static void main (String[] args) {
		System.out.println("Hello, World!");
	}
}
```

