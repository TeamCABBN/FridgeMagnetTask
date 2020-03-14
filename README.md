# FridgeMagnetTask

[Here!](https://teamcabbn.github.io/FridgeMagnetTask/fridge.html)


## Workflow using git branches
New features can be developed on branches so that you don't accidentally break something on the master branch. Also allows people to develop multiple branches at once without worrying about code constantly changing during development

### To start a new branch:

Clone the repository you want to work on to your computer. To use this repo as an example:
``
git clone git@github.com:TeamCABBN/FridgeMagnetTask.git
``

Git pull to grab any changes

``
git pull
``

If you want to check which branch you're currently on
``
git branch
``

To create a new branch with the name of "test branch"
``
git checkout -b "testBranch"
``

Then you would add your new feature by changing the files and adding your own code. Be sure to commit at logical points. To push your changes to github you need to tell it where to store the code of the branch using the following code (Change testBranch to the name of your branch):
``
git push --set-upstream origin testBranch
``

Now your new feature will be on github. To merge it with the master copy of the code click the create pull request button on the repository page.
Get someone else to review the new changes and when everyone is happy it's working then you can press the 'Merge pull request' button
