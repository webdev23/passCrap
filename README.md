# ./passCrap
<pre><h4>
Retrieve 2,422,392,161 clear passwords in a 230GB SQLite3 database

<img src="https://media.giphy.com/media/3ohzdQgxboDlOInXTW/giphy.gif"></gif>

chmod +X passCrap
./passCrap

Or 

php <(curl -s https://raw.githubusercontent.com/webdev23/passCrap/master/passCrap)

Dump all passwords from www.mysql-password.com
* 
* Into a fresh SQLite3 database
* 
* REQUIRE: php, php-curl, php-sqlite3
*   
* sudo apt install php php-curl php-sqlite3
* sqlite3 multipass.db
* 
* Create a table: sqlite3 multipass.db

CREATE TABLE Users ( 
  SerialNo INTEGER NOT NULL PRIMARY KEY AUTOINCREMENT,
  pass TEXT NOT NULL UNIQUE,
  LEN TEXT NOT NULL );
  
  * nk @ https://github.com/webdev23/passCrap
  * ponyhacks.com 2017
  
