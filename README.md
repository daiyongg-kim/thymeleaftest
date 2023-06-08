

database table
create table board(id BIGINT  unsigned NOT NULL AUTO_INCREMENT, title VARCHAR(50), content TEXT, PRIMARY KEY (id));

insert into board (title, content) values ('제목', '내용');
insert into board (title, content) values ('hello', '홍길동');

