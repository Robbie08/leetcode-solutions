# leetcode-solutions

This repo is set in place to act as a container for Leetcode solutions. Ideally asside from just the code itself, it would be useful to everyone if you also provide some comments or separate text file expalining your solution. Of course, this is optional but it would improve the understanding and intuition of how your solution was written.

### Languages :
This repo is language agnostic, so feel free to include solutions for whatever language you wish, as long as it is supported by Leetcode. 

<b>NOTE: </b> If the language of a soltuion you are about to contribute does not exists make sure to create a new directory with the existing language name and include your soltions inside there.

### How to contribute :
1. Fork repo to your personal space(this is done on github)
2. Clone your fork 
   - `$ git clone git@github.com:<your_github_username>/leetcode-solutions.git`
3. Set up your upstream to the original repo 
   - `$ git remote add upstream git@github.com:Robbie08/leetcode-solutions.git`
4. Create a feature branch on your clone (This can be named anything, I recommend the question number you are submitting)
   - `$ git checkout -b my-awesome-feature`
5. Make and commit your changes (NOTE: make sure to follow commit message standards)
   - Please create a new dir for the language you are using if there isn't an existing one already
   - For new solutions use "New: ..." 
   - For updates to existing solutions use "Update: ..."
6. Ensure to your solutions passes all test cases and is an "Accepted" solution by leetcode before proceeding
7. Make sure your master branch is up to date with upstream by rebasing
   - `$ git checkout master`
   - `$ git fetch upstream`
   - `$ git rebase upstream/master`
8. Rebase your feature branch
   - `$ git checkout my-awesome-feature`
   - `$ git rebase master`
9. Squash commits through interactive rebasing, use rebasing tutorials if needed: [article](https://thoughtbot.com/blog/git-interactive-rebase-squash-amend-rewriting-history)  or  [youtube video](https://www.youtube.com/watch?v=V5KrD7CmO4o)
10. Push your feature to your origin (your fork!!)
    - `$ git push origin my-awesome-feature`
11. Make a pull request from feature branch to original master
12. Once it has been approved by 1 person (who might request changes), you can go ahead and rebase with the master 
