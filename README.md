# SimpleCleanDockerMySQL
This is simply a docker compose file that will build an instance of MySQL and PHPMyAdmin on your computer that you can use over and over again to practice commands.  It does not store any of the data so each start is a fresh database. 

## Step 1 
Clone this repository on your computer and then cd into the directory and run the docker compose up command. 

```
docker compose up --build
```

## Step 2 
go to the web address localhost:8080 and verify that the phpMyAdmin Login is there. 

Your credentials will be 
* database = mysql
* user = root
* password = GoTechMavs!

## Overview 
You now have a version of phpMyAdmin on your computer that is forgetful.  You can play around with the databases as much as you want.  Each type you close your container, it will reset everything back to the first usage. 
