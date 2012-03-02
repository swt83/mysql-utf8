#About

This code was lifted completely from http://www.phpwact.org/php/i18n/utf-8/mysql.  I have no idea who wrote it, but I've been using it for years.  Accessed via web browser, the script prints mysql code to convert an existing database to UTF8 collation.

##Usage

Just point your browser to ``mysql-utf8.php?user=MYUSER&pass=MYPASS&db=MYDB`` and the script will print a chunk of mysql code.  Copy the code, paste into phpMyAdmin, execute, and you're done.