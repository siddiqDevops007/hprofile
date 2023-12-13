# Prerequisites
##
- JDK 11
- Maven 3
- MySQL 8 

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
# Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql

-------------------
 612  cd .ssh
  613  ls
  614  ssh-keygen
  615  ls
  616  cat siddiqDevops007.pub
  617  cd
  618  ssh -i ~/.ssh/siddiqDevops007 -T git@github.com
  619  export GIT_SSH_COMMAND="ssh -i ~/.ssh/siddiqDevops007"
  620  mkdir actions
  621  cd actions/
  622  ls
  623  git clone git@github.com:siddiqDevops007/hprofile.git
  624  unset GIT_SSH_COMMAND 
  625  ls
  626  cd hprofile/
  627  ls
  628  git config core.sshCommand "ssh -i ~/.ssh/siddiqDevops007 -F /dev/null"
  629  cat .git/config 
  630  git config user.name siddiqDevops007
  631  git config user.email naushad.devops@gmail.com
  632  cat .git/config

-------------------
