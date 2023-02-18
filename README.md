# Learning-Ruby
- This repository will comprise of my learning process on Ruby and it will track my progress
## Setting up linters (linters tutorials)
. To set up linters, follow these steps below; (note this linters check is fro ruby it doesnt include html, css or js)
 - git init
 - git add README.md
 - git commit -m "first commit"
 - git branch -M main
 - git remote add origin git@github.com/akuutsang/Learning-Ruby.git
 - git push -u origin main
   Here you are initializing the project using your main branch.
 - after these steps, create a development branch and add a README file and commit push and checkout to development branch.
. In the first commit of your development branch, create a .github/workflows folder and add a copy of .github/workflow/linters.yml (it is very important to remember that the workflow has an S, if u creat a file with just 'workflow' instead of 'workflows' you are bound t experirence errors)

. After creating your folders and files, you can follow the link below, to microverse github account, and chose the type of linters you want, but because we only need linters for Ruby, we will sellect that of Ruby.
 - https://github.com/microverseinc/linters-config/blob/master/ruby/.rubocop.yml (microverse github linters-checkers link)
