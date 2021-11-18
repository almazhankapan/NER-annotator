# Guide to Contributing
This documents allows potential contributors, whether in the open source community or in a private organization, to view the project's rules on contributing. 

## The Git workflow that the team follows: 
1. Clone the repository to start working on it: 
```
git clone url
```
2. Pull changes from the master branch to the local repo: 
```
git checkout main
git pull origin main
```
3. Create a new branch (from master) when working on a task/spike (except for working on .md files) and switch to that branch. Note that name of the branch should consist of the issue number and short description of the task. For example, if you are working on issue #81 with the title 'update readme', your new branch can be named as issue-81-update-readme
```
git checkout -b issue-81-update-readme
```
4. Commit your changes and add a short, meaningful message. If you are working on a specific task/spike, mention issue id of the task in the commit message: 
```
git commit -m'some changes for the task/spike with issue id #XX'
```

5. Push your changes to the branch. If have not pushed before: 
```
git push --set-upstream origin issue-2-update-readme
```
Otherwise: <br>
```
git push origin contributing
```

6. Submit pull request from the task/spike branch to the master branch and let other team members review your code. Optionally, attach the pull request to the task/spike by setting the 'Linked pull requests' in the issue tab. <br>

7. If changes are approved, merge the branch updates with the master branch and resolve any conficts by using the VS code editor. <br>

8. Team members can delete the task/spike branch after pull request is approved. <br>


## Rules for contributors
1. If you are an external contributor who does not have admin access to the project, please fork the repository to your account on github by pressing the 'fork' button. <br>
2. Then, clone the forked folder and pull any recent changes as specified in the git workflow above. 
3. If you have made changes to the project and want to contribute them, submit pull request from your active branch with the changes to the master branch of the original folder as explained in the gitworkflow above. 
4. To contact the project team members, please refer to the team info in the [README.md](./README.md) file. 


## Instructions for setting up the local development environment in order to work on this project

To set up the local development environment, please install the following software:   <br>
- Install [Git](https://git-scm.com/) to follow the git workflow specified for team members and external contributors. 
- Install [Node.js](https://nodejs.org/) to contribute to and test the code. 
- Install [React.js](https://reactjs.org/) to contribute to and test the code. 
- Install [Visual Studio Code](https://code.visualstudio.com/download) and recommended linter to standardize the formatting of the code. <br>
Additional instructions will be added later. <br>

## Instructions for building and testing the project (update with that information once the project reaches that stage)
Instructions are to be developed. 

