# PHP-COUNTER

COUNTS VISITORS PER IP

MYSQL - CREATE DB IN SQL FIRST THEN EDIT CONNECTION DATA IN PHP FILE

<pre>
CREATE TABLE IF NOT EXISTS `counter` (
`cid` INT( 10 ) NOT NULL AUTO_INCREMENT ,
`ip` VARCHAR( 15 ) NOT NULL ,
PRIMARY KEY ( `cid` )
)
</pre>

NODB  - CHMOD 777 ALL FILES & FOLDERS WHEN YOU UPLOAD IT TO YOUR SERVER
