[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15300070&assignment_repo_type=AssignmentRepo)
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
Introduction to GitHub:

What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.

GitHub is an online application based on Git the distributes version control system to support a set of tools for combined software development. GitHub is used by developers as a platform to share code, review code, coordinate projects and collaborate on software projects with millions of other developers.
Primary Functions and Features of GitHub
Collaborative Projects: The Version Control System (Git) that is already installed on it, as well as the hosting capabilities of GitHub on the website offer vast opportunities to create various co-authored projects with its help among developers.
Issue Tracker: All the complaints that the developer may feel when using Git or GitHub can be reported to the tech support team. GitHub has rather built an issue tracking tool for every developer who uses GitHub to report the issues they encounter while using Git or GitHub.
Supporting Different Languages: Being a code hosting platform, GitHub offers assistance to a massive list of development languages and has support concerning the language. They assist in programming languages like C, C++, C#, Ruby, Java, JavaScript, HTML, Python, etc., and are not limited to those languages.
Pull Requests: When developers are viewing the codes in repositories, they may modify any of the files that may be required for enhancing the codes or rectifying any mistakes by using Pull Requests that instantly modifies the root node in the main repository.
Hosting Code: GitHub is an online platform that acts as a hosting service where developers can host different codes for different usages.
Community and Social Features: In order to express gratitude or interest, users can star repositories and follow other developers.
And in order to experiment or make modifications without impacting the original project, users can fork repositories to create their own private copies.

How GitHub encourages collaborative software development
Centralized Repository:
Serves as the primary repository for the project codebase to avoid complications resulting from different versions among the team members.
Branching and Pull Requests:
On the same subject, branches enable developers to do improvements or bug fixes in solitude. The Pull request facilitates discussions and reviews before development of changes is done in the main branch.
Code Reviews:
Push for ideas and knowledge sharing within the team. Members of a team can comment on changes, make a request to contribute and also approve maps and algorithms in order to keep the code quality.
Issue Tracking:
The shocking news helps in managing and prioritizing work. Concerns can be divided, classified, and followed, as well as, it will define the status of the task on the project.
Documentation:
This guarantees that anyone who is involved in the project has an updated provide with up-to-date information of how the project setup is done, usage guide, and other development best practices.
Automation:
Minimizes the number of demands and errors due to repetitive work, such as in testing, building and deploying of codes.
Community Engagement:
Such an opportunity enables developers to make modifications to specific tasks, work in pairs or groups, and communicate with other like-minded developers.

Repositories on GitHub:

What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.

In GitHub, a repository or “repo” is basically a place where your respective project resides. Both repositories store all files attachments of the project, such as codes, documents, and documentation of changes to the set files.

   Creating a New GitHub Repository 
1. Type in GitHub on Google and access the application by signing in with your account credentials.
2. Select "New repository" from the dropdown menu by clicking the "+" symbol located in the upper right corner of the GitHub site.
3. Decide on the name of your repository. This should be unique within your account.
4. Briefly describe what your project is about.
5. Decide whether your repository should be public, or only you and those with access can view your repository.
6. Initialize with a README: It is usually beneficial to include a README file. This file is a good place to say what your project is for and how to use the contents of this file.
7. Add.gitignore: This file instructs Git which files (like build files and dependencies) to ignore. You can select a.gitignore template that works for your project.
8. Choose a license for your repository. This determines how others can utilize your project.
9. Press ‘Create repository’ button.

    Essential Elements to Include in a GitHub Repository
1. README.md: An description of the project, together with instructions for installation and usage and any other pertinent data, is provided in a README file. 
2. LICENSE: This file outlines the conditions on which the codes from your project may be used, modified, or even disseminated. Some of the most commonly used licenses are MIT, Apache 2.0 and GPL licenses.
3. .gitignore: This file specifies which files and directories should be ignored by Git. 
4. Source Code: This means it includes most of your project and is logically divided into subfolders and/or subdirectories. For instance, in a Python project, the structure can have the src/ directory comprising .py files.
5. Documentation: Any content falling outside of the README, such as examples of how to use the software, the API documentation, or contribution instructions, may be placed in a docs/ directory.
6. Contributing Guidelines: CONTRIBUTING.md denotes instructions for any other person interested in contributing to your project such as the coding style, branch creation, and pull request conventions.
7. Changelog: a file that documents all significant modifications made to the project. Users may stay updated about new features and upgrades thanks to this.
8. Issues on GitHub is a tool for managing bugs, enhancement requests and other tasks assigned to you. A similar way you can create labeled, assign issues, and connected with pull requests.
9. Pull Requests: Using pull requests, one can suggest amendments to the project they have been working on. It enables you to look at and talk about stuff and build in new code.
You can make sure that your repository is clear, well-structured, and collaborative by adding these crucial components.

Version Control with Git:

Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?
Version control is a system that tracks changes to a file or set of files over time so that you can recall specific versions later. It's especially crucial for software development, where multiple versions of code files are common and collaboration is often necessary.
These are the main advantages of utilizing Git for version control:
1. Workflow that is distributed: Every developer has a complete local copy of the repository, which allows them to work independently and test modifications without compromising the main source. This enhances teamwork and output.
2. Branching and Merging: Git facilitates the creation, merging, and deletion of branches, enabling developers to work separately on features before integrating their modifications. This facilitates a simultaneous, iterative development process.
3. History and traceability: Git keeps track of every modification made to the codebase, which makes it simple to examine, contrast, and undo changes as necessary. Accountability and transparency are therefore provided.
By giving developers a centralized location to store, manage, and collaborate on Git repositories, GitHub is a web-based hosting service that improves version control. Key benefits of using GitHub include:
1. Code loss prevention is ensured using GitHub's remote backup and sharing function for Git repositories. It also facilitates code sharing with collaborators and the general public.
2. Collaboration features: To make collaborative development workflows more efficient, GitHub provides services including pull requests, code reviews, and issue tracking.
3. Community and ecosystem: GitHub is a great place to find and contribute to code because it has a sizable developer community and hosts millions of open source projects.

In summary, Git provides a powerful distributed version control system, while GitHub enhances Git by offering a centralized platform for remote backup, sharing, and collaboration on software projects. Together, they form a comprehensive version control solution for modern software development teams.

Branching and Merging in GitHub:

 What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes,to the main branch and merging it back in.
 A branch in GitHub is essentially a parallel version of the repository that deviates from the main line of development. Branches let you isolate your work, experiment with new features, fix bugs, or implement changes without affecting the stable codebase in the main branch (often called main or master). Branches are a powerful feature that allows developers to work on different versions of a project simultaneously.
    Importance of Branches
 1. Since every branch is a separate environment, modifications done in one branch have no impact on other branches. Working on experiments, bug patches, and new features without jeopardizing the stability of the core codebase is made possible by this.
2. Branches make it possible for developers to work in parallel on various features or fixes without interfering with one another's work on other projects.
3. Using branches facilitates developer collaboration on a project. 8=0c99When a developer's work is complete, they may make a pull request to include their modifications into the master branch. Each developer can work on their own branch.
4. Branches offer a secure setting for investigation and experimentation. Without affecting the main codebase, developers can experiment with new concepts, make changes, then remove the branch if the changes are not appropriate.
The following is the procedure for branch creation, modification, and re-merging with the main branch:
1. Make a Branch: You can make a new branch in GitHub Desktop or the command line by basing it on the current branch, which is often the main branch. A new pointer that deviates from the main branch is produced as a result.
2. Change to the New Branch: Make the switch to the freshly formed branch. By doing this, you can make sure that any future changes you make get added to this branch rather than the main branch.
3. Make Changes: Make your modifications on the new branch, such as adding new functionality or resolving bugs.
4. Commit and Push Changes: Make sure to push the branch to the remote GitHub repository after you have committed your modifications to it on a regular basis.
5. Make a Pull Request: Open a GitHub pull request once you're prepared to integrate your modifications into the master branch. This enables review and input from other team members on your changes.
6. Code Review: Coworkers or team members are able to examine the modifications. They can offer suggestions for enhancements, make changes requests, and offer commentary on the code.
7. Merge the Pull Request: You can include the modifications from the new branch into the main branch once the pull request has been examined and accepted. Your changes will be incorporated into the main codebase as a result.
8. Delete the Branch: You can safely remove the branch after the modifications have been merged because it is no longer required.


Pull Requests and Code Reviews:

What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.
On GitHub, you can suggest modifications to a repository by submitting a branch for evaluation and possible merge into the main branch. This process is called a pull request. It enables engineers to debate and review modifications prior to their integration into the main codebase, which promotes collaboration and code reviews.
How Pull Requests Facilitate Code Reviews and Collaboration
1. Centralized Discussion: Pull requests establish a forum for discussion of suggested modifications in one place. Members of the team can debate possible problems, offer enhancement suggestions, and remark on individual lines of code.
2. Version Control: Pull requests preserve a history of modifications, remarks, and conversations, offering a transparent account of the reasons and methods behind changes.
3. Code Review: Pull requests let several reviewers look over the modifications to the code. Peer review ensures that coding standards are followed, that errors and issues are found early, and that the code is of high quality.
4. Branch Management: To lower the possibility of conflicts and problems in the production code, developers work on distinct branches and can progressively merge these branches into the main codebase through pull requests.
5. Continuous Integration: Pull requests can be combined with continuous integration (CI) technologies, which make sure that the new code doesn't interfere with current functionality by automatically running tests and checks on the suggested modifications.

Here are the steps to create and review a pull request:
Creating  Pull Request
1. If necessary, fork the repository: You should fork the repository to your own GitHub account if you don't have write access to it.
2. Clone the repository: Clone the repository on your PC.
git clone https://github.com/username/repo-name.git
3. Create a new Branch: Make a new branch for your feature or repair and switch to it. 
git checkout -b feature-branch-name
4. Make changes: In your local repository, make the required adjustments.
5. Commit Changes: Put your changes into stage and commit them.
git add .
git commit -m "Description of changes"
6. Push Changes: Push your changes to the branch on GitHub
git push origin feature-branch-name
7. Open the Pull Request: Open the pull request in GitHub.
      Reviewing a Pull Request
1. Visit the GitHub repository. Select the tab labeled "Pull requests" Locate the pull request you wish to review, then click on it.
2. To view the changes, select the "Files changed" tab. Go over each line of the code. By selecting the "+" symbol adjacent to the line numbers, you can add comments
3. Check the Changes (if any): Examine the branch locally and verify the modifications.
4. For the developer who performed the modifications, leave remarks or recommendations.
5. If the modifications meet your needs, accept the pull request; if not, reject it.

Pull Request Examples
Feature Additions: Add a new feature and create a pull request to merge it into the main branch after approval.
Bug Fixes: Fix a bug and create a pull request to merge the fix into the main branch.
Code Refactoring: Refactor code for better performance or readability and submit a pull request for team approval.
Dependency Updates: Update project dependencies to the latest versions and submit a pull request for review and integration


GitHub Actions:

Explain what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub Actions.
GitHub Actions is a solution that offers native CI/CD capability by automating processes related to issues, pull requests, and more. It provides a large variety of actions, which are reusable pieces of code that carry out particular tasks, and it interfaces with GitHub. Combining these steps can result in sophisticated workflows that automate testing, building, and deploying code, among other stages of the software development lifecycle.
Example of a Simple CI/CD Pipeline Using GitHub Actions
Here is an example of a simple CI/CD pipeline using GitHub Actions:
1. Make a Workflow Document: Make a file called.github/workflows/ci-cd-pipeline.yml in your repository.
2. Describe the Workflow: To the file, add the following YAML configuration:

name: CI Workflow
on: push
branches:
  - main
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout code
        uses: actions/checkout@v2
      - name: Setup .NET SDK
        uses: actions/setup-dotnet@v1
        with:
          dotnet-version: '5.x'
      - name: Restore dependencies
        run: dotnet restore
      - name: Build
        run: dotnet build --configuration Release
      - name: Run tests
        run: dotnet test --no-restore --verbosity normal

       Overview of the Workflow file
- name: identifies the process as "CI/CD Pipeline".
- on: Identifies the occasions that start the workflow. It operates in this instance on each push and pull request made to the main branch.
- jobs: defines the construction job. 
runs-on: Indicates the kind of runner to be utilized. Ubuntu-latest makes use of the most recent Ubuntu runtime version.
steps: outlines the actions that must be taken to complete the task:
Checkout code: utilizes the actions/checkout@v2 action to download the source code.
Set up Node: To install Node.js version 14, use the actions/setup-node@v2 action.
Install dependencies: Installs the Node.js requirements by running npm install.
Run tests: To run the test suite, run npm test.
Build the application: To build the application, use npm run build.
Deploy GitHub Pages: deploys the created application to GitHub Pages using the peaceiris/actions-gh-pages@v3 action, provided that the current branch is main.

In conclusion, With the help of GitHub Actions, developers may automate a variety of operations and optimize their software development workflows. Developers may ensure faster and more dependable software delivery by utilizing GitHub Actions to design custom workflows that automate operations like continuous integration and deployment.

Introduction to Visual Studio:

What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?
Visual Studio is a Microsoft integrated development environment (IDE) designed primarily for the building of complicated applications. It's appropriate for large-scale enterprise applications because it supports a broad variety of programming languages and development platforms.
      key Features
1. Project Templates: Offers a range of project templates for several application categories, including cloud services, mobile apps, Windows apps, and web apps.
2. IntelliSense: Productivity-boosting code completion and refactoring support.
3. Tools for integrated testing: assistance with automated user interface testing, load testing, and unit testing.
4. Supported Languages: Python, JavaScript, TypeScript, C#, C++, Visual Basic.NET, and more.
5. Advanced debugging tools such as breakpoints, watch windows, IntelliTrace, live debugging, and performance profiling are included in the diagnostics and debugging section.
6. Collaboration Tools: Azure DevOps for project management, continuous integration/continuous deployment (CI/CD), and version control; Git integration; Team Foundation Server (TFS).
7. Tools for managing databases: All-inclusive tools that incorporate SQL Server.
8. Extensibility: A large selection of extensions and plugins are available to increase its capabilities.

Visual Studio Code (VS Code) is a lightweight, open-source code editor that allows for rapid code editing and debugging. It's highly flexible and compatible with a wide range of programming languages.
         Key Features
1. Debugging: You may walk through code, create breakpoints, and examine variables with the built-in debugging tools for VS Code, which is compatible with a number of programming languages. 
2. Command Palette: By typing a keyword, you can use the Command Palette to access all of VS Code's commands. This facilitates finding and using a variety of features. 
3. VS Code has extensive code editing capabilities like as syntax highlighting, auto-completion, code formatting, and multi-cursor editing. 
4. Extensions: A multitude of extensions, such as those that support extra programming languages, frameworks, and tools, are supported by VS Code and bring new features and functionality. 
5. Customization: You can alter VS Code's theme, keyboard shortcuts, and other settings to suit your preferences.
6. Git Integration: Git and VS Code are integrated, which makes it simple to handle your source control procedures inside the editor. Changes can be pulled, pushed, staged, and committed. 
 7. Integrated Terminal: You can execute shell commands right within the editor using VS Code's integrated terminal. 
8. Lightweight: VS Code is a quick and lightweight code editor that runs on Windows, macOS, and Linux, in contrast to the more feature-rich Visual Studio IDE. 
9. Split View: With VS Code, you may divide the editor into many panes, which facilitates working on and comparing several files or code segments. 
10. Open-Source: Since Visual Studio Code is an open-source project, it is highly customizable and extensible, and it welcomes community contributions. 
      Key Differences
1. Purpose:
Visual Studio is an all-inclusive Integrated Development Environment (IDE) specifically made for C++ and.NET projects.
With extensions, Visual Studio Code is an open-source, lightweight code editor for developers that supports a variety of programming languages.
2. Platform Support:
Visual Studio: Limited support for Linux and macOS; mostly intended for Windows users.
Cross-platform Visual Studio Code is accessible on Linux, macOS, and Windows.
3. Performance: 
Because of its extensive feature set and higher size, Visual Studio may operate more slowly.
Visual Studio Code: Is better suited for brief modifications and smaller projects because it is typically lighter and faster.
4. Cost:
Visual Studio: Provides a Community Edition that is free of cost, however monthly fees apply to the Professional and Enterprise editions.
Visual Studio Code: It is entirely free and open-source, and while the majority of its extensions are likewise free, some require a fee to use.
5. Functionality: 
Visual Studio is appropriate for complex projects since it provides sophisticated capabilities including project management, debugging, and IntelliSense.
Visual Studio Code: Intended for smaller projects and rapid updates, it offers a more limited feature set and depends on extensions for more capability.
6. Size:
Compared to VS Code, Visual Studio requires a lot more disk space (20–50 GB).
It is possible to execute Visual Studio Code with less than 500 MB of disk space.
7. Debugging:
Interactive debugging is one of the sophisticated debugging features available in Visual Studio.
Visual Studio Code: Relies on extensions for more sophisticated functions, but only offers rudimentary debugging tools.
8. Extensions:
When compared to VS Code, Visual Studio's library of extensions is more extensive.
Visual Studio Code: Offers a wide range of extensions for different activities and programming languages.
9. Customazation:
Visual Studio provides a wide range of customization possibilities via its settings and extensions.
With a more simplified interface, Visual Studio Code also allows customization through settings and plugins.
10. IntelliSense:
Advanced IntelliSense and IntelliCode features are available in Visual Studio for IntelliSense.
Compared to Visual Studio, Visual Studio Code has a less sophisticated IntelliSense.
In conclusion, Visual Studio Code is a highly adaptable and lightweight code editor perfect for a variety of development jobs, whereas Visual Studio is a robust, feature-rich IDE best suited for large-scale and sophisticated application development.

Integrating GitHub with Visual Studio:

Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?
To integrate a GitHub repository with Visual Studio, follow these steps:
1. Install the GitHub Extension:
Open Visual Studio.
Go to the Extensions and Updates window.
Search for the "GitHub" extension.
Install and restart Visual Studio.
2. Sign In to GitHub:
Open Visual Studio.
Click on the "Extensions" icon on the Activity Bar.
Select the "GitHub" extension.
Click on "Sign into GitHub" and follow the prompts to authenticate with your GitHub account
3. Clone a Repository:
Open Visual Studio.
Select "Clone a repository" from the Start Window.
Enter the repository URL and select "Clone".
Visual Studio will clone the repository and open it in the Solution Explorer.
4. Open a Repository:
Open Visual Studio.
Select "Open a project or solution" from the Start Window.
Browse to the cloned repository and select it to open it.
5. Publish to GitHub:
Open Visual Studio.
Select the repository in the Solution Explorer.
Right-click on the repository and select "Publish to GitHub".
Choose the repository name, description, and whether to make it public or private
This integration makes it easier to access GitHub repositories right within Visual Studio, which improves the development workflow. Important characteristics consist of:
1. Effortless Repository Administration: Repositories can be opened, cloned, and managed straight from Visual Studio.
2. Version Control: Use Git to collaborate with others and keep track of changes.
3. CI/CD Workflows: Configure continuous integration and deployment (CI/CD) using GitHub Actions.
4. Artificial Intelligence-Driven Efficiency: Use GitHub Copilot to get chat-based support and AI-driven code completions.
This integration maintains a strong version control system and collaborative features while streamlining the development process and freeing up developers to concentrate on coding.
Debugging in Visual Studio:

Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?

Developers can identify, analyze, and fix issues in their code using Visual Studio's comprehensive debugging tools. The following are the primary debugging tools available in Visual Studio:

1. Breakpoints: To halt execution and examine the application's status at that time, developers can place breakpoints at particular lines of code.
2. Stepping Commands: Developers can execute the code line-by-line and track how variables change by pausing at a breakpoint and using the step into, step over, and step out commands.
3. Call Stack: The Call Stack window aids developers in comprehending the application's flow by displaying the series of method calls that led to the present execution point.
4. Watch Windows: As they go through their code, developers may keep an eye on the values of variables and expressions with watch windows.
To add a watch, either put an expression straight into the Watch window or right-click on a variable and select "Add Watch."
5. Immediate Window: While debugging, developers can evaluate expressions and run code snippets using the Immediate Window.
6. Performance and Memory Profiling: Visual Studio has tools for measuring memory utilization and profiling the performance of applications. These tools are very helpful in locating memory leaks and performance bottlenecks.
7. IntelliTrace: This capability lets developers "rewind" and troubleshoot problems that happened in production environments by logging an application's execution history.
8. Variable Inspection: To view the values of variables during debugging, the debugger offers a number of windows, including Autos, Locals, and Watch.
How to Use Debugging Tools in Real World Steps
1. Determine suspicious code sections and set breakpoints.
2. The Immediate Window is useful for testing hypotheses and validating code behavior
3. You can navigate through the code by using the step commands (F10, F11).
4. To monitor variable values, use the Watch, Locals, and Autos windows.
5. Perform a runtime analysis of the outputs and diagnostics by reviewing the Output window and the Diagnostic Tools.
6. Debug Mode: Press F5 to start debugging or Ctrl + F5 to start without debugging
7. Examine the call stack to determine the path taken by the execution.

Collaborative Development using GitHub and Visual Studio:

Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.

When combined, GitHub and Visual Studio offer a potent collaborative development platform that makes it possible for teams to effectively organize, exchange, and create code. This integration makes it easier to collaborate and be more productive by combining the powerful development tools of Visual Studio with the version control features of GitHub. Here is a thorough explanation of their collaboration as well as an illustration of a real-world project that makes use of this integration.
GitHub: A web-based platform that hosts Git repositories, enabling numerous developers to collaborate on a project at once. It provides tools for project management as well as capabilities like pull requests, problem tracking, and code reviews.
Visual Studio is an all-inclusive Integrated Development Environment (IDE) that facilitates the use of numerous development tools and programming languages. Developers may clone repositories, commit changes, push to remote branches, and create pull requests straight from Visual Studio thanks to its integration with GitHub, which provides built-in Git support.
The GitHub and Visual Studio connection makes it possible for developers to collaborate easily on the same codebase. This is how it operates:
1. Sharing Code: To store and distribute the source code for a project, developers can set up a GitHub repository. Cloning this repository and beginning local project development is made simple by Visual Studio.
2. Branching and Merging: GitHub can be used for the purpose of merging changes made to new branches into the main codebase after they have been reviewed. Developers can utilize Visual Studio to generate new branches for this purpose.
3. Pull Requests: A developer can use GitHub to create a pull request in order to submit modifications. As a result, the modifications can be reviewed, discussed, and eventually incorporated by the entire team.
4. Issues and Project Management: Visual Studio has a strong integration with GitHub's issue tracking and project management functionalities. Issues can be created, assigned, and tracked by developers directly from the IDE.
5. Real-time Collaboration: By sharing their coding environment, developers can work together in real-time with Visual Studio Live Share. Pair programming, remote debugging, and other synchronous processes are made possible by this.
A real-world example of a project that benefits from this GitHub and Visual Studio integration is the development of a complex enterprise web application:
The development team is distributed, which means that the team members work from various locations. For source code, they employ a actual space on the GitHub repository and issues for the application. Using Visual Studio, developers can fetch the repo to their local system, create branches to implement and design features, and merge feature changesets back to the main branch after reviewing by other team members.
To invite another Live Share user to the session a developer begins a session and can provide assistance to a fellow teammate. This let them to debug problems with each other, share opinions on certain design choices, and synchronize code.
The issue-tracking and project management of GitHub allow the project manager to plan sprints, assign tasks, and keep track of the project progress. The above issues can be viewed and modified by developers within a Visual Studio environment – it keeps everyone informed.


Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
