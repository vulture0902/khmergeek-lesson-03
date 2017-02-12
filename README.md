# khmergeek-lesson-03

 - how to access mysql from basic php.

1.how to create mysql server on linux.


=================================
# Let's create a DB.


```
mysql-ctl install
```

```
mysql-ctl cli
```

```
SHOW CHARACTER SET;
```

```
SHOW CREATE DATABASE db01;
```

```
CREATE DATABASE db01 CHARACTER SET utf8;
```


```
USE db01;
```

```
CREATE TABLE tb1 (id int, name varchar(20));
```

```
SHOW COLUMNS FROM tb1; #test
```

```
INSERT INTO `tb1`(`id`, `name`) VALUES(1, 'KhmerWord');
```

```
SELECT * FROM tb1;
```

[![Gyazo](https://gyazo.com/42256f4126eb0b70ea073012c4363a89.png)](https://gyazo.com/42256f4126eb0b70ea073012c4363a89)


for delete DB.

```
DROP DATABASE db01;
```

