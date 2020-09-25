# Git

Git is a version control tool is not necessary for simple static websites, but as we go for dynamic web-apps the complexity increases and it's best to use VCS.

## Git enable us to do:
  * Keep track of changes to code, we can save snapshots of our codes.
  * Synchronizes code between different people, you can co-work with others at the same time.
  * Test changes to code without losing the original.
  * Revert back to old version of code.
  
## Our goal is to:
  * How to use this tool
  * Learn various git commands
  * Unleash the features of VCS as you begin working with larger and larger projects.

Github can be used to host the code repository.

Goto: https://www.github.com/new to create a new repository

* Use below command to initialize local code repository.
  
  <code>git init</code>

* Use below command to download a copy of code repository from url.

  <code>git clone url</code>

  <code>git clone --branch branchname remote-repo-url</code>

  eg: <code>git clone --branch master https://github.com/sinku1196/WebProgramming.git</code>

* Use below command to add a new file to track changes.
  
  <code>git add filename</code>

* You may receive: *** Please tell me who you are, incase you haven't configured your account's default identity

  Run

  <code>git config --global user.email "you@example.com"</code>

  <code>git config --global user.name "Your Name"</code>

* Use below command after making changes to your code, to save a new snapshot of your code.

  <code>git commit -m "message"</code>

* Use below command to know what's currently going inside the code repository.
  
  <code>git status</code>

  You may receive something different than actual, that's because of you've pulled an empty repo that don't have master branch yet. Fix: push initial commit

* Use below command to publish the changes
  
  <code>git push</code>

  You may receive something different if your email is not visible to public. Fix: set email visibility to public.

* Use below command to commit all the changes without adding individual files then commiting individually. Instead use this shorthand to commit all the changes at a time.
  
  <code>git commit -am "Your message here"</code>

* Use below command to keep track of all of the commits.
  
  <code>git log</code>

* Use below command to get rid of unintended changes and get back to previous commit.

  <code>git reset</code>
  
  <code>git reset --hard commit</code>

  eg: <code>git reset -- hard origin/master</code>

* Use below command to know on which branch you're currently working on.

  <code>git branch</code>

* Use below command to create a new branch.

  <code>git checkout -b branch-name</code>

* Use below command to switch between branches.

  <code>git checkout branch-name</code>

* Use below command to merge current branch into given branch.

  <code>git merge name</code>
  - Most of the time merge conflict will occur, in only few cases git will be able to merge code. In case of merge conflicts, manually merge conflits and commit.
  
* You can fork a repository, use to make your own verison of a code repository.

* You can open pull request for your code, once you're done with your code.

* Once your open a pull request others can pull and commit your change.

* You can also host a website(HTML, CSS, JavaScript) for your code repository using github pages for free.

* Git and Github are useful when working with larger projects, it provides a lot of tools to work together on the same project simultaneously.