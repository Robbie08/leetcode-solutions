# leetcode-solutions

### How to contribute :
1. Fork repo to your personal space(this is done on github)
2. Clone your fork 
   - `$ git@github.com:<your_github>/leetcode-solutions.git`
3. Set up your upstream to the original repo 
   - `$ git remote add upstream git@github.com:Robbie08/leetcode-solutions.git`
4. Create a feature branch on your clone (This can be named anything, I recommend the question number you are submitting)
   - `$ git checkout -b my-awesome-feature`
5. Make and commit your changes (NOTE: make sure to follow commit message standards)
   - Please create a new dir for the language you are using if there isn't an existing one already
   - For new solutions use "New: ..." 
   - For updates to solutions use "Update: ..."
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
11. Make a pull request from for feature branch to original master
12. Once it has been approved by 1 person (who might request changes), you can go ahead and rebase with the master 
