# Mariadb Notes

### Create data base

```sql
create databse foo;
```
### show databases
```sql
show databases;
```

### create user
```sql
grant all on foo.* to 'user'@'localhost' identified by 'password';
```

### use database

```sql
use foo;
```

### print tables 

```sql
drop tables;
```

### view table 

```sql
describe bar;
```
### create table

```sql
create table bar (
    -> id int,
    -> qux varchar(20),
    -> PRIMARY KEY(id));
```

### insert in table 

```sql
insert into drinks values (001, 'qux')
```

### query all data 

```sql
select * from bar;
```





