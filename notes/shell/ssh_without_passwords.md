# navigate to your .ssh folder where your private and public keys are stored.

cd ~/.ssh

# then copy the public key to your .ssh folder on the server

scp id_rsa.pub acory@hills.ccsf.edu:~/.ssh/authorized_keys

# bam... no more typing in passwords
# IF YOU NEED A NEW SSH KEY

ssh-keygen -t rsa

# the above command will generate a new public and private ssh key I believe?

# http://goo.gl/6ccvfJ
