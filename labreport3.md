# **Streamlining ssh Configuration**
**.ssh/config file:**
![Image](lab3image3.png)
![Image](newlab1image.png)
(I used Notepad to edit the config file)
---
**Logging in using ssh ieng6:**
![Image](lab3image1.png)
---
**Using scp on alias:**
![Image](newlab3image2.png)
---
**Description of streamlining:**
The goal of streamlining the ssh configuration is to login to a server without needing to type as much out. To do this, a config file is added to the .ssh file with commands in order to quickly access the correct account in the server (shown in the screenshots above).
---

# **Setup Github Access from ieng6**
**Public Key Location:**
![Image](lab3image2.png)
---
**Private Key Location:**
![Image](lab3image3.png)
---
**Running git commands:**
![Image](lab3image4.png)
---
**Link to Commit:**
[Link to Commit](https://github.com/Georgexli3/markdown-parser/commit/77427a46ee90ba9e3399877e754144ce6701fe93)
---
**Description of Github Access:**
In order to easily access the github server remotely, an ssh key can be used to bypass the need to login to github using a password. This allows commits and pushing to origin remotely from a local machine without the need of always going into github.
---

# **Copy whole directories with scp -r**
**Copying:**
![Image](lab3image5.png)
![Image](lab3image6.png)
---
**Compile and run:**
![Image](lab3image7.png)
![Image](lab3image8.png)
---
**Description of copying whole directories:**
By using scp -r, whole directories are allowed to be added to a server remotely. This is much better than the alternative which is using scp on every single file to add it to a server which may take a long time depending on how many files need to be added.