evol_security_publication_2012
==============================

Security Evolution Paper Publication (2012)


Instructions
------------

On OSX Mountain Lion
```bash
git clone git@github.com:bkarak/evol_security_publication_2012.git
sudo easy_install pip
sudo pip install pika python-daemon pymongo
cd evol_security_publication_2012
./process.py -a findbugs -b findbags -e findbugs -c 83.212.106.194 -u findbugs -w findbags -x 83.212.106.194 -y findbugs -z findbugs -d
```

On Debian Squeeze (more python pkgs required):
```bash
sudo apt-get install python-pip git
git clone git@github.com:bkarak/evol_security_publication_2012.git
sudo pip install pika python-daemon pymongo argparse
cd evol_security_publication_2012
./process.py -a findbugs -b findbags -e findbugs -c 83.212.106.194 -u findbugs -w findbags -x 83.212.106.194 -y findbugs -z findbugs -d
```

Connection details
------------------

RabbitMQ connection details
```
host = 83.212.106.194
user = findbugs
passwd = findbags
```

MongoDB connection details
```
host = 83.212.106.194
user = findbugs
passwd = findbags
db = findbugs
```

