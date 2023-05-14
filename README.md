## About
Hey, this is my github page. Welcome~  
Visit [my web](https://zeneight.xyz) and [my blog](http://agungpriambada.blogspot.com)
#
Recent Notes/TodoList > [here](https://gist.github.com/zeneight/0b89468283d9702d0f03ebdc572ee6e8)
> this is just a list of some random links, code, projects and articles that I make and read.

## Lists Repo
- [anfederico/Clairvoyant](https://github.com/anfederico/Clairvoyant#readme) - Multiple badges. Clean logo. Simple install instructions. Clear overview of the project accompanied by a schematic. GIF demo. Extensive code examples.
- [junwatu/nodejs-gitbook](https://github.com/junwatu/pengenalan-nodejs-gitbook) - Ebook NodeJS in Indonesian.
- [javascript-tutorial/id.javascript.info](https://github.com/javascript-tutorial/id.javascript.info) - Modern JavaScript Tutorial in Indonesian.
- [ap_nw](https://zeneight.github.io/ap_nw) - Love html template.

## Useful Gists
- Install Datatable with laravel 5.3 > [link](https://gist.github.com/nasrulhazim/1b56a5fd455bb4bda07af179169aa17b)
- Install and change php version on linux > [link](https://gist.github.com/zeneight/7c9696ba252494e52bcb36e9d7fe4172)
- Add Custom CSS with Laravel Mix > [link](https://gist.github.com/iceberg53/4b57b34a3aa987e3e7459a19aa51ac49)
- laravel .htaccess on shared hosting > [link](https://gist.github.com/zeneight/a4c9733cf51dc6db7f5c9f89e879f4c6)
- mongodb import > [link](https://stackoverflow.com/questions/53078520/mongodb-how-to-import-dump-data-from-gz-file)

## Random Commands
- Change permission All Folder & SubFolders ```sudo chmod -R 755 /opt/lampp/htdocs```
- Clone Private Repo ```git clone https://username@github.com/username/repo_name```
- Operate mongodb service ```sudo systemctl (start/status/enable/stop) mongod```
- create a sysmlink path so that command can be run on terminal (ex: heroku) ```sudo ln -s /snap/bin/heroku /usr/bin/heroku```
- check if repo updated on remote ```git remote update```
- fix username is not in the sudoers ```sudo nano /etc/sudoers``` and then add this line below root/admin under #user privilege spec ```user_name ALL=(ALL)  ALL```
- Make file excecutable ```chmod +x filename```
- copy all files in folder ```cp -a ttf/. /usr/share/fonts/TTF/```
- switch php version on arch linux STEP 1 -> go to /usr/bin dir then run this ```sudo mv php php8``` to rename current php to php8 then after that STEP 2 -> make a symlink ex:  ```sudo ln -sf php7 php``` for php 7.4. If you want to change back to php8 just run STEP 2 command with another symlink
- mysql login ```mysql -u root -p```
- copy file to remote server with scp ```scp myfile.txt remoteuser@remoteserver:/remote/folder/```
- install PM2 if you don't have it: ```npm install pm2 -g && pm2 install pm2-logrotate```
- ```pm2 start server/server.js --name process-whatever``` > to add process
- ```pm2 monit``` > If you want to see the current console output
- ```pm2 save && pm2 startup``` > If you want to add it to startup
- ```xrandr --output HDMI-1 --auto``` > To set hdmi output (to set the layout go to > preferences > Display > Layout Editor)
- ```mysqldump -u root -p db > db.sql``` > To export data
- ```sudo a2dismod php5.6 && sudo a2enmod php7.4``` > To disable php module 5.6 and enable mod php 7.4
- ```pactl unload-module module-bluetooth-discover && pactl load-module module-bluetooth-discover``` > when bluetooth can't connect to device
- github permission denied when add agent. It means need to add manually the key -> ```ssh-add /path/to/my-non-standard-ssh-folder/id_rsa``` [more](https://stackoverflow.com/questions/26505980/github-permission-denied-ssh-add-agent-has-no-identities)
- always enable firewall when want to access ip from other device ```sudo ufw allow [PORT]/tcp``` [more](https://stackoverflow.com/questions/29758588/how-can-i-access-monit-http-remotely).
- ```docker update --restart unless-stopped $(docker ps -q)``` > restart all docker unless it stopped

## Dev Articles/Cheatsheet/Etc
- Local Strapi + cloud MongoDB Atlas > [link](https://medium.com/@firstsquares/local-strapi-cloud-mongodb-atlas-cc65288f0dee)


## Useful Articles
- Forbidden : You don't have permissions to access / on this server [link](https://www.digitalocean.com/community/questions/forbidden-you-don-t-have-permissions-to-access-on-this-server)
- create vhost with webmin [link](https://dwiay.com/2021/02/02/cara-membuat-virtual-host-dengan-webmin-gui-dan-webmin-cli/)
- turn old laptop to server [link](https://dev.to/jayesh_w/this-is-how-i-turned-my-old-laptop-into-a-server-1elf)
- give specific user to folder [link](https://askubuntu.com/questions/487527/give-specific-user-permission-to-write-to-a-folder-using-w-notation)
- make own git server [link](https://www.linux.com/training-tutorials/how-run-your-own-git-server/)
- Install Node & NPM [link](https://linuxize.com/post/how-to-install-node-js-on-ubuntu-18.04/)
- Install PostgreSQL [link](https://computingforgeeks.com/install-postgresql-11-on-ubuntu-linux/)
- Install Java [link](https://www.niagahoster.co.id/blog/cara-install-java-di-ubuntu/)
- Crontab configuration [link](https://www.baeldung.com/linux/run-command-start-up)
- Info about docker [link](https://alfredo-reyes-montero.gitbook.io/docker/)
- Download a git branch from remote server [link](https://stackoverflow.com/questions/2294313/how-to-download-a-branch-with-git)
- Install PHP, integrate with webservers and its dependencies [link](https://linuxize.com/post/how-to-install-php-8-on-ubuntu-20-04/)
- MySQL password does not satisfy the current policy requirements [link](https://stackoverflow.com/questions/43094726/your-password-does-not-satisfy-the-current-policy-requirements)
- authentication method unknown to the client [link](https://stackoverflow.com/questions/50026939/php-mysqli-connect-authentication-method-unknown-to-the-client-caching-sha2-pa)
- install go on linux [link](https://golangdocs.com/install-go-linux)
- change dateformat in javascript/jQuery [link](https://stackoverflow.com/questions/5250244/jquery-date-formatting?noredirect=1&lq=1)
- generate changelog [link](https://www.freecodecamp.org/news/a-beginners-guide-to-git-what-is-a-changelog-and-how-to-generate-it/)
- temporary hide and disable indexing on apache2 [link](https://stackoverflow.com/questions/38331397/how-to-protect-env-file-in-laravel)
- make sysmlink on linux [link](https://](https://www.freecodecamp.org/news/symlink-tutorial-in-linux-how-to-create-and-remove-a-symbolic-link/)
- allow remote MySQL [link](https://www.digitalocean.com/community/tutorials/how-to-allow-remote-access-to-mysql)
