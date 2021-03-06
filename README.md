# gitpractice

## TASK
### Please add yourself to the sign-in list and make your first commit to a file called sign_in.md. We are going to learn how to do this in a variety of ways.
[sign_in.md](https://github.com/pisontechnology/gitpractice/blob/master/sign_in.md)

* Add/make change to sign_in.md through git web
* Add/make change to sign_in.md through git bash
* Add/make/check out change to sign_in.md file in a test branch using git bash and then commiting and merging through a "pull request"
   
## SETUP
### Install GIT  
 * http://rogerdudler.github.io/git-guide/
 
### Clone the repository
* **git clone username@host:/path/to/repository**
   * git clone https://github.com/pisontechnology/gitpractice.git

## Working With Files
### Get Status/ Pull
   * we do not need to do this right now, because we just cloned. Normally, this would be your first step in your routine/ flow. This should always been done prior to working to get the most recent updates from the server. Failure to do this will likely result in your machine getting "ahead" of the server, and an increase in merge conflicts.
   * **git status**
   * **git pull** 
   
### Make some changes to it (add your name) and save.

### Add the changed file to the index   
   * **git add "filename"** 
      * "git add README.md"
   * **"git add ." (for all files)**
   
### Commit the files to the index to be synced with the remote server
* **git commit**
   * allows you to add a longer message
* **git commit -m "message"**
   * git commit -m "7.13.2017 / mk / added my name to the readme task"
   
 ### Push the files
   * **git push**
   
### Great guide (important commands and flow explained): [GitHub Guide](http://rogerdudler.github.io/git-guide/)
      
### Markdown guide for readme (.md) documentation is here: [markdown_cheatsheet.md](https://github.com/pisontechnology/gitpractice/blob/master/markdown_cheatsheet.md)

