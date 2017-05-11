# ./passCrap
<pre><h4>
Retrieve 2,422,392,161 clear passwords in a 230GB SQLite3 or csv database

SQlite3 version:
<img src="https://media.giphy.com/media/3ohzdQgxboDlOInXTW/giphy.gif"></img>
Csv mono thread version:
<img width="440" src="https://media.giphy.com/media/3oKIPpMOdFh2k6AaFG/giphy.gif"></img>
Csv multi sub-processus
<img width="440" src="https://media.giphy.com/media/xUPGct38mRrhuDYfWE/giphy.gif"></img>

### Run, using multi threads: ###

chmod +x sub && chmod +x passcrap
./passcrap

### passcrap_monocsv

chmod +x passcrap_monocsv
./passcrap_monocsv

#### SQLite3 version: ####

chmod +x passcrap_sqlite
./passcrap_sqlite

Or 

php <(curl -s https://raw.githubusercontent.com/webdev23/passCrap/master/passCrap_sqlite)

One liner pipe run:

    git init && git clone https://github.com/webdev23/passCrap.git && cd passCrap && chmod +x sub && chmod +x passcrap && ./passcrap


Dump all passwords from www.mysql-password.com
* 
* REQUIRE: php, php-curl, php-dom, php-sqlite3
*   
* sudo apt install php php-curl php-dom php-sqlite3

  
  * nk @ https://github.com/webdev23/passCrap
  * ponyhacks.com 2017
  
