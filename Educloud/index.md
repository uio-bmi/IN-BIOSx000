# Educloud Fox cluster

The Educloud Fox cluster will be used for hands-on exercises in the course. All students will be given access.


### Getting access

* You need a Norwegian digital ID (BankID, MinID, BuyPass, Commfides). If you do not have a Norwegian digital ID: Please contact `torognes@ifi.uio.no` as soon as possible. Please include your full name, email address and birth date.

* Educloud also requires two-factor authentication (2FA) to be set up in addition to a username and password. You need to install a mobile app to generate 2FA codes (one-time codes). This app will generate a new pseudo-random 6-digit code every 30 seconds. There are several such apps that you may use. We highly recommend `Microsoft Authenticator`:

   * [Microsoft Authenticator for iOS](https://apps.apple.com/us/app/microsoft-authenticator/id983156458)
   * [Microsoft Authenticator for Android](https://play.google.com/store/apps/details?id=com.azure.authenticator)

* Go to [Apply for access to Educloud](https://research.educloud.no/register), click `Apply for access to a project`. Login with Feide (preferable, if affiliated with UiO, including visitors) or enter your personal details. Specify project `ec34` (BMI). To speed up processing, please notify `torognes@ifi.uio.no` by email when you have applied.


### Log in to Fox

After you have obtained access and set up two-factor authentication, you can run
```
ssh ec-username@fox.educloud.no
```
in a terminal (replace `ec-username` with your own) to log in to one of the login nodes of the Fox cluster.

You will first be asked for the One-Time code (6 digits) and then for the password. If you are asked for the One-Time code three times in a row and then asked for your password, the two-factor authentication is probably not correctly set up, or you may have specified the wrong username (remember to include `ec-`). Please see Reset 2FA below.

* [Fox login](https://www.uio.no/english/services/it/research/platforms/edu-research/help/login-fox.html)


### Problems?

* [Reset password](https://research.educloud.no/password_reset) You can login with your digital ID to get a new password.

* [Reset 2FA](https://research.educloud.no/2fa_reset) You can login with your digital ID to get a new QR code to reset 2FA authentication.

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
* [Interactive Fox machines](https://www.uio.no/english/services/it/research/platforms/edu-research/help/hpc/docs/fox/interactive-machines.md)
