# ShareBoard - an Object Oriented PHP Project

A web application that allows users to register, login and create posts with title, body and URL.

## Prerequisits

* Download the project from [GitHub](https://github.com/azigazisipi/shareboard/archive/master.zip)
* Download and install [Ampps](https://www.ampps.com/)

## Installation and configuration

* Run Ampps as administrator - thats important, ohterwise Ampps can't edit hostfile
* Open Ammps dashbooard in a browser: localhost/ampps
* Add domain shareboard
* Set a MySQL password - the project's mysql password is 'sqlpwd'.
* In phpMyAdmin create a new database named shareboard
* For database sharebord create the followong tables - id coloumns are unique!:

![table_shares](https://user-images.githubusercontent.com/32300859/47093828-47cee180-d22a-11e8-9a2c-d579d8dbd477.PNG)

![table_useers](https://user-images.githubusercontent.com/32300859/47093877-61702900-d22a-11e8-8348-7f4e8857dc77.PNG)

* Unpack the donloaded "shareboard-master.zip" file and the content of 'shareboard-master' folder copi to \YOUR_PATH\Ampps\www\shareboard folder
* Edit the following line in config.php and change the password to your own MySQL password

```
define("DB_PASS", "sqlpwd");
```

* Open 'localhoast/shareboard' in your browser
* Enjoy :-)
