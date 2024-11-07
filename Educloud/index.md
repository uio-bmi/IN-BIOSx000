# Educloud Fox cluster

The Educloud Fox cluster will be used for hands-on exercises in the course. All students will be given access.


### Getting access

* If you do not have a Norwegian digital ID, please contact the course administrator (`torognes@ifi.uio.no`) as soon as possible. We will have to meet in person and in order to get access you will need to provide your full name, email, birthdate, passport number and country. We could do this during the lunch break on Monday 28th, but please remember to have your passport number ready.

* Getting access if you have a Norwegian digital ID (BankID, MinID, BuyPass, Commfides) should be easy. Follow the steps below.

* Educloud requires two-factor authentication (2FA) to be set up in addition to a username and password. You need to install a mobile app to generate OTP codes for 2FA, if you haven't already. We strongly recommend the genuine `Microsoft Authenticator` app:

   * [Microsoft Authenticator for iOS](https://apps.apple.com/us/app/microsoft-authenticator/id983156458)
   * [Microsoft Authenticator for Android](https://play.google.com/store/apps/details?id=com.azure.authenticator)

* Go to [Educloud Self Service](https://selfservice.educloud.no/), and click 'Apply for project membership' under 'Project membership'. Login with BankID (or similar). Enter project code 'ec34' and review your personal information. To speed up processing, please notify `torognes@ifi.uio.no` by email when you have submitted the application.


### Log in to Fox

After you have obtained access and set up two-factor authentication, you can run
```
ssh ec-username@fox.educloud.no
```
in a terminal (replace `ec-username` with your own) to log in to one of the login nodes of the Fox cluster.

You will first be asked for the One-Time Code (6 digits) and then for the password. If you are asked for the One-Time Code more than once, two-factor authentication is probably not correctly set up, or you may have specified the wrong username (remember to include `ec-`). Please see the section below about problems.

* More info: [Fox login](https://www.uio.no/english/services/it/research/platforms/edu-research/help/login-fox.html)


### Problems?

* Some have reported problems when registering using BankID and FEIDE due to mismatches in personal details. Try to log in with BankID only, not FEIDE, and supply personal details manually.

* If you need to reset your password or your 2FA (OTP) you can login to [Educloud Self Service](https://selfservice.educloud.no/) with BankID again and change any of them. Click 'Change password' or 'Change OTP' under 'Your Personal Data'. Then choose to log in with ID-porten (not Educloud).

* We will have a session on the afternoon of Tuesday 29th were we make sure that everyone is able to log in to Fox.


### Basic info

* There are four login nodes (login-1, login-2, login-3, and login-4), four interactive nodes (int-1, int-2, int-3, and int-4), some GPU nodes (gpu-X), and many compute nodes (cX-YZ). The login nodes should not be used for cpu-heavy operations at all. Interactive nodes may be used for that, and will be used during the course. Be considerate of other users and do not overload the nodes. Please see the welcome message when loggining in. The compute nodes are used for batch operations through the Slurm queueing system only.

* Our project account is called `ec34`.

* The storage area that will be used is in `/projects/ec34/in-biosx000`. Data to be used in the course will be distributed in this area by the teachers.

* Your home directory is in `/fp/homes01/u01/ec-username` (replace `username` with your own). This is were each student should store their own files.

* You'll have access to the special partitions `ifi_bigmem` (large memory node) and `ìfi_accel` (node with GPUs) of the compute nodes if required.


### Fox documentation

* [Educloud user manual](https://www.uio.no/english/services/it/research/platforms/edu-research/help/)
* [Using Fox](https://www.uio.no/english/services/it/research/platforms/edu-research/help/hpc/docs/fox/index.md)
* [Interactive Fox machines](https://www.uio.no/english/services/it/research/platforms/edu-research/help/fox/interactive-machines.md)
