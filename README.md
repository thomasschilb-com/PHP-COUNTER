# PHP-COUNTER

<b>COUNTS VISITORS PER IP</b>

<b>MYSQL</b>

1. CREATE DB IN SQL THEN:
<pre>
CREATE TABLE IF NOT EXISTS `counter` (
`cid` INT( 10 ) NOT NULL AUTO_INCREMENT ,
`ip` VARCHAR( 15 ) NOT NULL ,
PRIMARY KEY ( `cid` )
)
</pre>
2. EDIT CONNECTION DATA IN PHP FILE
3. INCLUDE('counter.php');

<b>NODB</b>

1. DON'T FORGET TO CHMOD 777 ALL FILES & FOLDERS
2. INCLUDE('no.php');
3. THAT'S ALL!
