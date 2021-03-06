# GITHUB GETTING STARTED
This guide is intended to get you started with GitHub and Git. It is not intended 
to be a full manual but it will guide you to (well written) manuals instead, providing
some ordering of the reading list.

## GitHub Guides
The [GitHub guides](https://guides.github.com) provides good tutorials for Git and GitHub.
You can read them in the order of appearance but here are three highlights.

### GitHub Handbook
The [GitHub Handbook](https://guides.github.com/introduction/git-handbook/) explains the Git
version control system and how it integrates with GitHub.

### Documenting your projects in GitHub
The [Wiki Guide](https://guides.github.com/features/wikis/) tells how to create README files
(like this one) to give short repository descriptions. To do this with GitHub markdown language 
is explained in [Mastering Markdown](https://guides.github.com/features/mastering-markdown/).
Suggestions what to include in a README file can be found also in [About-READMEs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes).
A bit more elaborative example to use these markdown files (.md files) is in [lukeghg](https://github.com/jariperttunen/lukeghg).

You may also use the repository **About** field in GitHub to write a few words about the project. It will appear in the repository 
listings and provide quick guide about project. 

Note the GitHub wiki pages are available for public repositories. Commercial version of GitHub is needed for private repositories. 

We plan to use [Doxygen](https://www.doxygen.nl/index.html) to integrate the software development and documentation.
Doxygen can exploit the program structure together with the annotated comments and automatically
generate software documentation in various formats (e.g. html and pdf). Regarding Motti this is mostly
applicable to Fortran and python. 

Documentation should give favourable time to others and the *future you* to understand
how to get involved and and participate in the software development. Programs are more often
read than written.

### Mastering Issues
GitHub Issues are to keep track of tasks, enhancements and bugs for your projects. This
is explained in [Mastering Issues](https://guides.github.com/features/issues/).

## GitHub Desktop Guide
The [GitHub Desktop Guide](https://docs.github.com/en/desktop) tells you how to use 
GitHub Desktop to manage your project work. It may look overwhelming at start but
just remember the *basic work flow* with Git/GitHub:
+ `git clone` \<project_url\>
  + Clone the GitHub repository once for the first time to yourself as a local repository
+ `git pull`
  + Update the local repository from the GitHub repository
+ `git add` \<files\>
  + Add new files or prepare the edited files for commit and push
+ `git commit`
  + Update the your local repository with files from previous `git add` commands.
+ `git push`
  + Push the `git commit` updates to the GitHub repository

These commands will take a big bulk of your work with Git/GitHub.

The [Hello World](https://guides.github.com/activities/hello-world/) in [GitHub guides](https://guides.github.com) 
shows the recommended work flow in GitHub with branches, pull requests etc. but we can take this at later time.

