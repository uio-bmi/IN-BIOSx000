# Login

Login to UiO network using the following:
```bash
ssh <username>@login.uio.no
```
Once you are in the UiO network, login to the compute enviroment and change directory to your home area within the cluster as below:
```bash
ssh bioint01.hpc.uio.no
# Within bioint01.hpc.uio.no
cd /cluster/home/<USERNAME>
```

If you need a GUI/X11 (some lectures might use this), then replace _ssh_ with _ssh -Y_ in the above two ssh logins.

# Datastore
Once you are in bioint01.hpc.uio.no, you will reach /home/<USERNAME>. In case you want to use your home area, please change the folder to /cluster/home/<USERNAME> even though it is not advisable since this will consume your home area quote within the UiO system.

All the datasets that will be used for this course will be available in the following folder:
```bash
/work/IN-BIOSx/
/work/IN-BIOSx/data
```
Move to the above folder and create your work area as below and store all the files within this folder
```bash
cd /work/IN-BIOSx/
mkdir /work/IN-BIOSx/<USERNAME>
cd /work/IN-BIOSx/<USERNAME>
```
