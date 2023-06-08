


# How to Install MariaDB on MacOS.


## Installation
1) Update the local repository index of homebrew package installer
    $ brew update
2) Install with homebrew
    $ brew install mariadb

# Launch mariadb
    $brew services start mariadb

# Log in as root
    $sudo mysql -u root


#create database and table 
create database mydb;
use mydb; 
create table board(id BIGINT  unsigned NOT NULL AUTO_INCREMENT, title VARCHAR(50), content TEXT, PRIMARY KEY (id));


#insert data
insert into board (title, content) values ('제목', '내용');
insert into board (title, content) values ('hello', '홍길동');



