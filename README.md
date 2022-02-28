How to contribute to this project:

 1. Open the GitHub repository page for the project you want to create a pull request for.
 2. In the upper right hand corner of the page click on the "Fork" button to create a copy of this repository under your account.
 3. Open the command line/terminal on your computer
 4. Clone the fork of the project to your computer

 ```shell 
 $ git clone https://github.com/username/project-name.git
 ```

 5. Add a new remote reference to the original project

 ```shell
$ git remote add original https://github.com/username/project-name.git
 ```

 6. Open the newly cloned project in your favorite code editor
 7. Make the changes to the code (in this project that means adding your message to the `MESSAGES.md` file)
 8. Create a new commit

```shell
$ git add -A
$ git commit -m "Your commit message goes here"
 ```
 9. Push your changes up to GitHub (to your forked repository)
 10. Open a pull request from your forked GitHub repository page
 11. Fill out a title and description
 12. Submit your pull request and celebrate!