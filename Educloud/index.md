# Educloud Fox cluster

The Educloud Fox cluster will be used for hands-on exercises in the course. All students will be given access.


### Getting access

* You need a Norwegian digital ID (BankID, MinID, BuyPass, Commfides).

* You also need a Feide account at a Norwegian educational institution.

* Educloud also requires two-factor authentication (2FA) to be set up in addition to a username and password. You need to install a mobile app to generate 2FA codes (one-time codes). This app will generate a pseudo-random 6-digit code every 30 seconds. There are several such apps that you may use. We recommend `Google Authenticator` and `Microsoft Authenticator`:

   * [Google Authenticator for iOS](https://apps.apple.com/us/app/google-authenticator/id388497605)
   * [Google Authenticator for Android](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2)
   * [Microsoft Authenticator for iOS](https://apps.apple.com/us/app/microsoft-authenticator/id983156458)
   * [Microsoft Authenticator for Android](https://play.google.com/store/apps/details?id=com.azure.authenticator)

* [Apply for access to Educloud](https://www.uio.no/english/services/it/research/platforms/edu-research/help/apply-membership.html) and specify project code `ec34`. To speed up processing, please notify `torognes@ifi.uio.no` by email when you have applied.

* If you do not have a Norwegian digital ID or a Feide account: Please contact `torognes@ifi.uio.no` as soon as possible.


### Log in to Fox

After you have obtained access and set up two-factor authentication, you can run `ssh ec-username@fox.educloud.no` in a terminal (replace `ec-username` with your own) to log in to one of the login nodes of the Fox cluster.

You will first be asked for the One-Time code (6 digits) and then for the password. If you are asked for the One-Time code three times in a row and then for your password, the two-factor authentication is probably not correctly set up. Please see Reset 2FA below.

* [Fox login](https://www.uio.no/english/services/it/research/platforms/edu-research/help/login-fox.html)


### Problems?

* [Reset password](https://research.educloud.no/password_reset) You can login with your digital ID to get a new password.

* [Reset 2FA](https://research.educloud.no/2fa_reset) You can login with your digital ID to get a new QR code to reset 2FA authetication.


### Basic info

* There are four login nodes (login-1, login-2, login-3, and login-4), four interactive nodes (int-1, int-2, int-3, and int-4), some GPU nodes (gpu-X), and many compute nodes (cX-YZ). The login nodes should not be used for cpu-heavy operations at all. Interactive nodes may be used for that, and will be used during the course. Be considerate of other users and do not overload the nodes. Please see the welcome message when loggining in. The compute nodes are used for batch operations through the Slurm queueing system only.

* Our project account is called `ec34`.

* The storage area that will be used is in `/projects/ec34/in-biox000`.

* Your home directory is in `/fp/homes01/u01/ec-username` (replace `username` with your own).

* You'll have access to the special partitions `ifi_bigmem` (large memory node) and `ìfi_accel` (node with GPUs).


### Fox documentation

* [Educloud user manual](https://www.uio.no/english/services/it/research/platforms/edu-research/help/)
* [Using fox](https://www.uio.no/english/services/it/research/platforms/edu-research/help/hpc/docs/fox/index.md)
* [Interactive fox machines](https://www.uio.no/english/services/it/research/platforms/edu-research/help/hpc/docs/fox/interactive-machines.md)
