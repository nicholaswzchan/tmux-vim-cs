### SSH into a remote machine
```
ssh user@mydomain.com
#or by ip address
ssh user@192.168.1.1
```
__exit:__ `exit`

### Install Something
```
#If it's a new server, update apt-get first thing
sudo apt-get update
#then you can install something - say Git
sudo apt-get install git
```

### Copy/Deploy files
```
#copy all of the files in this directory to the /home/will/newapp directory
rsync -av . will@domain.com:~/newapp
#delete a file and run rsync again, and it only copies the one mising file
```

### Generate an SSH keypair for passwordless SSH
```
#on your computer
cd ~/.ssh
#you might need to make the .ssh directory
ssh-keygen -C "my@email.com"
#hit enter a few times to generate key

#copy the file contents to the clipboard
cat id_rsa.pub | pbcopy

#log into your machine
ssh user@mydomain.com
#make the .ssh directory and get in it
mkdir .ssh
cd .ssh
#open authorized_keys in nano and paste the contents in
nano authorized_keys
#paste contents in and save by hitting ctrl+x
```
#exit and you can now ssh without a password!
