# Login and datastore

Login to UiO network using the following:
```bash
ssh <username>@login.uio.no
```
Once you are in the UiO network, login to the compute enviroment and verify your home directory within the cluster as below:
```bash
ssh bioint01.hpc.uio.no
# Within bioint01.hpc.uio.no
pwd
# This should return /home/<USERNAME>
mkdir in-bios9000 # Or a name that you prefer
cd in-bios9000
pwd
# This should return /home/<USERNAME>/in-bios9000
# You can use this folder for storing and analysing data for the course. 
```

If you need a GUI/X11 (some lectures might use this), then replace _ssh_ with _ssh -Y_ in the above two ssh logins.

All the datasets that will be used for this course will be available in the following folder:
```bash
/work/IN-BIOSx/data
```
Remember to load the environment which contains all the softwares and tools necessary for this course each time you login:
```bash
source IN-BIOS9000-software-load
```
