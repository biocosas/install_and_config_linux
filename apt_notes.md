

https://wiki.debian.org/SecureApt


Add repository
--------------------------------------------------------------------------------

See installed keys:

    apt-key list

    apt-key fingerprint 0EBFCD88


Add keys

    apt-key add file
    curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
    wget -qO - https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
    wget -qO - https://www.mongodb.org/static/pgp/server-4.2.asc | sudo apt-key add -



Files
--------------------------------------------------------------------------------

List of sources:

    /etc/apt/sources.list.d
    /etc/apt/sources.list

List of keys:

    /etc/apt/trusted.gpg
    /etc/apt/trusted.gpg.d

Release files:

    /var/lib/apt/lists