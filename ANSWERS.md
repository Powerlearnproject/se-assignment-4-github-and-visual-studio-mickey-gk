NAME: MICHAEL GONA KATANA                   EMAIL: mickeygkatana@gmail.com
ASSINGMENT: se-assignment-4-github-and-visual-studio-mickey-gk

# PART 1 OF THE ASSINMENT - GITHUB
QUIZ 1: GitHub, and its primary functions and features and how it supports collaborative software development.
# answers:
Github is a website and a cloud hosting service platform that helps software engineers and developers store, manage
and collaborate their codes with other developers.
its primary features and functions include.
    1. repository - are storage space for projects and codes.
    2. issues - a tracking system for bugs, enhancement and tasks.
    3. actions- automation tools for continuos intergration and continous development and other workflows.
    4. branches- parallel versions of a repository to work on different features or fixes.
    5. pull requests- proposals to merge changes from one branch to another, enabling code reviews.
github support collaborative software development in that,
    1. it enables multiple developers to work on the same project,
    2. it allows review of code between developers,
    3. it keep track of changes,
    4. and also automate workflows.
references and links:
[kinsta.com](https://kinsta.com/knowledgebase/what-is-github/)



QUIZ 2:  GitHub repository, creating a new repository and the essential elements that should be included in it.
# answers:
A GitHub repository is a storage space for a project's files, codes, and resources. It tracks changes to these files over time.
To create a new repository:
    1. create an account or log in to github
    2. click on the "+" icon in the top-right corner and select "New repository."
    3. fill in the repository name and description.
    4. choose the visibility as either public or private.
    5. you can initialize the repository with a README file, .gitignore file, and license.
    6. finish by clicking on "Create repository" button.
Some of the essential element to include in a git repo are:
    1. README.md file - this provides an overview of the project.
    2. LICENSE file - Specifies the licensing terms.
    3. .gitignore file - Lists files and directories to be ignored by Git.
links and references:
[github creating new repo](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository)
[about git](https://docs.github.com/en/get-started/using-git/about-git)



QUIZ 3: concept of version control in the context of Git. How GitHub enhance version control for developers.
# answers: 
Version control in relation to git, is a system that keeps track and records on changes done to files thus enabling developers to go
back to specific version of these files.
Github enhances verison control through:
    1. Remote repositories - Centralized storage for code accessible to all collaborators.
    2. Pull requests - Mechanisms for proposing changes and conducting code reviews.
    3. Issue tracking - Systems for managing bugs and features.
    4. Collaboration tools - Commenting, notifications, and project boards.
links and reference urls:
[dev.to version control](https://dev.to/saloman_james/a-comprehensive-guide-to-version-control-with-git-and-github-3m0n)
[git-scm](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)



QUIZ 4: branches in GitHub, their important. Process of creating a branch, making changes, and merging it back into the main branch.
# answers:
branches in github are parallel version of a repository that allow developers to work on the code without affecting main codebase.
the process of creating a branch is:
    1. navigate to the repository section, click "Branch: main" and enter a new branch name.
    2. also you can create a branch using git with the following code: git cheakout -b new-branch
to make changes to a branch.
    1. after editing or creating a new file, from git bash, type:
        (a) 'git add .' - to track the files
        (b) 'git commit -m "message" ' 
        (c) 'git push' - to push the changes to the repository.
to merge back into the main branch.
    1. open a pull request from the new branch to the main branch.
    2. review and discuss the changes made in the code.
    3. merge the pull reuest using the github interface.
urls and reference links:
[github about branches](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)
[creattind a new branch](https://www.howtogeek.com/714112/how-to-create-a-new-branch-in-github/)



QUIZ 5: pull request in GitHub, how it facilitate code reviews and collaboration. steps to create and review a pull request.
# answers:
A pull request is a proposal to merge changes from one branch into another. It helps in code review by other developers and team members before they merge the codes.
to create a pull request:
    1. navigate to the repository.
    2. click on the 'pull request' button or tab.
    3. click 'new pull request'
    4. select the base branch and the branch to compare.
    5. add a title and a description.
    6. click 'create pull request'.
to review a pull request.
    1. navigate to the pull request.
    2. review the changes and asd comments.
    3. request changes or approve the pull request.
    4. once approved, merge the pull request
urls and reference links.
[pull request github](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
[geeksforgeeks - creating a pull request](https://www.geeksforgeeks.org/how-to-create-a-pull-request-in-github/)



QUIZ 6: GitHub Actions are and how they can be used to automate workflows. An example of a simple CI/CD pipeline using GitHub Actions.
# answers:
Github actions are automation tools that enable workflows to be created and executed based on events within a repository. They are used with continuos intergrationa and continuos development (CI/CD), testinga and deployment.
an example of a CI/CD pipeline:
    1. first create a  '.github/workflows/ci.yml' file in your repository.
    2. define the workflow:
        name: CI Pipeline
        on: [push, pull_request]
        jobs:
        build:
            runs-on: ubuntu-latest
            steps:
            - uses: actions/checkout@v2
            - name: Set up Python
                uses: actions/setup-python@v2
                with:
                python-version: '3.x'
            - name: Install dependencies
                run: pip install -r requirements.txt
            - name: Run tests
                run: pytest



# PART 2 OF THE ASSIGNMENT: VISUAL STUDIO

QUIZ 7: Visual Studio, its key features and how it differ from Visual Studio Code.
# answers:
Visual studio is an intergrated development environment(IDE) by microsoft, used for developing software.
    1. Comprehensive Project Management: Visual Studio excels at managing large-scale projects with multiple files, dependencies, and configurations. Its intuitive solution explorer and project management tools keep everything organized and easily accessible.
    2. Advanced Debugging and Profiling: Debugging intricate code issues becomes a breeze with Visual Studio's powerful debugger and profiling tools. Step through code line by line, analyze memory usage, and identify performance bottlenecks with ease.
    3. Built-in Code Tools: Forget juggling multiple plugins – Visual Studio comes equipped with a plethora of built-in tools for code completion, syntax highlighting, refactoring, and testing, boosting your development efficiency.
    4. Rich Extensibility: While feature-packed, Visual Studio allows further customization through extensions to cater to specific needs and workflows

Visual studio differes form visual studio code in that, visual studio is a fully-fledged intergrated development environment with many features while visual studio code is a lightweight, open source code editor that supports for programming languages.
link and reference urls:
[geekboots](https://www.geekboots.com/story/visual-studio-vs-vs-code)



QUIZ 8: steps to integrate a GitHub repository with Visual Studio and how it
enhance the development workflow.
# answers:
To integrate github with visual studio.
    1. open visual studio.
    2. Go to "View" > "Team Explorer"
    3. click 'connect' under 'local git repositories'
    4. select 'github' and 'sign in'
    5. clone or create a new repository.
integrating github to visual studio helps in the following ways while developing software.
    1. direct access to repository and branches.
    2. version control and pull request.
    3. it simplifies code revies and collaboration between developers.
    4. it offers built in tools for building, testing and deploying code.
links and reference urls:
[dev.to](https://dev.to/satyakarki/how-to-use-visual-studio-for-github-repository-29l9)


QUIZ 9: debugging tools available in Visual Studio and how developers use these tools to identify and fix issues in their code
# answers:
    1. exception handling - this catches and handle expections in the code.
    2. call stack - this monitors the sequence of function calls.
    3. watch windows - this monitors variable values in the code.
    4. breakpoints - it pauses execution at specific lines in the code.
developers use these tools to go through code, inspect it and understand how it is executed, thus it helps in identifying and fixing issues araising in the code.




QUIZ 10: how GitHub and Visual Studio can be used together to support collaborative development and a real-world example of a project that benefits from this integration.
# answers:
github supports version control, pull and merge request and visual studio offers advance coding, debugging and project management, thus combining the two gives a perfect environment for collaborative development between developers.
a real world example for this is:
developers can use github to manage their code repository and visual studio for coding and debugging when developing web application. Team members can then clone the repository, create branches for new features, submit pull request for code review, and merge changes while leveraging  visual studio for development and debugging.
links and references.
[open ai](htpps://chatgpt.com)
[visual studio and github better together](https://visualstudio.microsoft.com/vs/github/#:~:text=Visual%20Studio%20and%20GitHub%20better%20together%201%20Seamless,Rebase%20...%207%20Create%20a%20Pull%20Request%20)
