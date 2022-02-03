# tb-web-gist

# Docker
Download and install Docker. Once installed, run it:
<br>**docker compose build**

Once Docker is running:
<br>**docker compose up -d**
-d will discount terminal/command propomt with docker, you can run docker up command without -d.

This will take some time the first time it runs. It builds the custom PHP image, as well as downloads the other ones needed for this to work (MariaDB/Redis/Mailcatcher).

You can take down the container with following command:
<br>**docker compose down**

# PHP artisan
1. Open CLI from docker to bring up the terminal;
2. Type **cd ..** and enter;
3. Type **pwd** and enter. You should see /var/www;
4. Type **php artisan** and enter;
5. Type **php artisan migrate:fresh** and enter;
6. Go to your web browser and type 127.0.0.1  -  you should see "Prototype Test Project"
7. Go to http://127.0.0.1/nova  - you should see login page

# Git
set up upstream
- $ git pull --set-upstream origin main  
leave commit comment  
- $ git commit --am "message"  
**git commit -a automatically stage all tracked, modified files before the commit** If you think the git add stage of the workflow is too cumbersome, Git allows you to skip that part with the -a option. This basically tells Git to run git add on any file that is "tracked" - that is, any file that was in your last commit and has been modified. This allows you to do a more Subversion style workflow if you want, simply editing files and then running git commit -a when you want to snapshot everything that has been changed. You still need to run git add to start tracking new files, though, just like Subversion.  
Using the option -am allows you to add and create a message for the commit in one command.


# CLI
- $ cd .. Navigate to parent directory
- $ ls List directory contents
- $ ls -la List detailed directory contents, including hidden files
- $ mkdir directory Create new directory named directory
- $ clear clear the command line window
- $ rm file delete file
- $ rm -r directory delete directory
- $ rm -f file force-delete file
- $ mv file-old file-new Rename file-old to file-new
- $ mv file directory Move file to directory
- $ cp file directory Copy file to directory
- $ cp -r directory1 directory2 Copy directory1 and its contents to directory2
