# Information

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

