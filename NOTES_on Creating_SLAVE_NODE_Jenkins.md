- SSH into Jenkins slave server
- Create a user called Jenkins
- Can use command `` adduser jenkins ``
- Make the password `jenkins`
- This should create a /home/jenkins directory
- In the /home/jenkins  create a ``.ssh`` directory
- In the .ssh directory create a `known_hosts` and an `authorized_keys` file
- Add the appropriate public key to these files

## On the Jenkins server configuration
- Add remote root directory /home/jenkins
- Under host just put the ip of the slave 
- Under credentials make sure the username (name of the credential) is jenkins (or the name of the user you chose to create)
- Make sure to include the passphrase (the one you made for the user)
