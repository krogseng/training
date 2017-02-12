# training
* 1. Create new repo and default to no .gitignore, select license. 
* 2. Clone it down to local directory.
* 3. Switch to new directory.
* 4. Touch .gitignore in root directory.
* 5. Go to github.com/github/gitignore
* 6. In the Global directory, look for Linux.
* 7. Copy and paste to local .gitignore.
* 8. In the Global directory, look for VisualStudioCode
* 9. Copy and paste  from .vscode, include  .gitignore
* 10. Copy and paste from upper dir Node.gitignore
###consider this sequence: operating system, text editor, language
* Install eslint, then run eslint --init for default settings
* Consider airbnb eslintrc
* 11. Make package json by running npm -init
* 12. Open up and edit it.
* 13. Look at description, license, author contact 
* 14. Set test: in scripts ("test":"mocha") and then install mocha with --save-dev or -default
* 15. Install eslint --save-dev
* 16. Modify package.json to 
"lint": "estlint .", 
    "pretest": "npm run lint",
* 17. Install "start": "node server" (or whatever is starting file) in the scripts file, after the lint statement.
* 18. 
