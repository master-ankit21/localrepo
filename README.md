create table student

(sl integer(3) not null, name varchar(16) not null,

roll integer(3) primary key not null) ;

insert into student 

values(1,'Ankit',14);

select *from student;

alter table student

add gen varchar(1) default 'M';

desc student;

insert into student 

values(2,'Anmol ',21, 'M');

select *from student;

