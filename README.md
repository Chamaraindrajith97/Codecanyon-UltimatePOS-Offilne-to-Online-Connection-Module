# Codecanyon-UltimatePOS-Offilne-to-Online-Connection-Module
Codecanyon-UltimatePOS-Offilne-to-Online-Connection-Module


1) Install the offline.


2) Setup a phpMyadmin password (XAMPP)
==========================================================
Steps for phpMyadmin my sql password (XAMPP)

1) Open your phpMyadmin dashboard
2) go to user accounts
3) on the user section Get the root user and click [ Edit privileges ]
4) in the top section you will find change password button [ click on it ]
5) make a good pass and fill 2 pass field .
6) now hit the Go button.
7) now open your xampp dir ( c:/xampp ) --> to phpMyadmin dir [C:\xampp\phpMyAdmin]
8) open [ config.inc.php ] file with any text editor
9) find [ $cfg['Servers'][$i]['auth_type'] = 'config'; ]line and replace 'config' to ‘cookie’
10) go to [ $cfg['Servers'][$i]['AllowNoPassword'] = true; ] this line change ‘true’ to ‘false’.
11) last : save the file .
==========================================================

3) Create ".env" file in windows. (In windows some times coudln't create ".env" file.)
==========================================================
1) open terminal 
2) type command: echo > .env
==========================================================

4) 
