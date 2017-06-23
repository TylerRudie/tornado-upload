Tornado-Upload
============

Demo Application showing implimentation of upload functionality in Tornado


Fork of  vamsiikrishna demo of the Python Tornado Server.

Setup requires the following command on Raspbian Jessie to run:
----
```
sudo apt-get install build-essential python-dev
sudo pip install tornado
git clone https://github.com/TylerRudie/tornado-upload.git
```
Create folder or link `ln -s /path/to/folder/save/`  called 'uploadedFiles'

Start the server using `./startServer.sh`
Stop the server using  `./stopServer.sh`
