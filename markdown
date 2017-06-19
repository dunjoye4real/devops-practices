Requirements:
Vagrant ===> brew cask install vagrant  ==> brew cask install vagrant-manager
VirtualBox ==> brew install virtualbox
Ansible ====> brew install Ansible


setup Stack:
Node.Js: For backend Services and API(install nodejs+NPM ==== brew install node) //sit back and relax
Nginx: For serving static pages and static files and also acting as a reverse proxy in front of Nodejs services. running on :3001 and :3002
Process Manager(PM2): For restarting nodejs apps if down and also facilities for load balancing, monitoring and logging

to run
fetch role with==> ansible-galaxy install -r Requirements.yml
vagrant up
