EMACS CONFIGURATION NOTES
===========================

* Setup ssh keys
  1. Create ssh keys
     ssh-keygen -t rsa -b 4096 -C "i.obesulus@gmail.com"
  2. Copy the public key into Github -> Settings -> SSH -> Add key
     - cat ~/.ssh/id_rsa.pub
  3. Authenticate public key
     ssh-add ~/.ssh/id_rsa
* Create a Github repository
  1. Click on the +
  2. Copy the SSH location
  3. git remote add origin git@github.com:pcinereus/.emacs.d.git
  4. git pull -u origin master
  5. git push -u origin master
