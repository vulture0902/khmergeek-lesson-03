# khmergeek-lesson-03

 - how to access mysql from basic php for khmer code.

What kind of things you can learn in this lesson?


[1.how to create mysql server on linux.](https://github.com/vulture0902/khmergeek-lesson-03#lets-create-a-db)

```
2.how to access mysql from php code.
3.How to display from DB a khmer fonts.
```


[![top-image](https://i.gyazo.com/1ef3bdb97ea3b81dd9cc74d98485f325.gif)](https://gyazo.com/1ef3bdb97ea3b81dd9cc74d98485f325)

=================================
Access to  GitHub
https://github.com/


[![sign_up](https://i.gyazo.com/fcbc0598296a3f0d85ce810e5847fed8.png)](https://gyazo.com/fcbc0598296a3f0d85ce810e5847fed8)

push [sign up for free]

type your User name
type your Email
type your Password

[![CreatApp](https://i.gyazo.com/577fb3fbc6870eecb8b1a9d89561f44b.png)](https://gyazo.com/577fb3fbc6870eecb8b1a9d89561f44b)
Select Free Account

[![Sign up](https://i.gyazo.com/88c900a681f288bbcf4e75a01058a8c2.png)](https://gyazo.com/88c900a681f288bbcf4e75a01058a8c2)
push [Finish Sign Up]

=================================
Access to Cloud9
https://c9.io/

[![Gyazo](https://i.gyazo.com/40bc5180e72951edc224cb7f23582ee3.png)](https://gyazo.com/40bc5180e72951edc224cb7f23582ee3)
[![Gyazo](https://i.gyazo.com/b7f87c1fdf3c6d17aad347f585131461.png)](https://gyazo.com/b7f87c1fdf3c6d17aad347f585131461)
[![Gyazo](https://i.gyazo.com/bba2154ab9bb9d4801291048c212e6dc.png)](https://gyazo.com/bba2154ab9bb9d4801291048c212e6dc)
[![Gyazo](https://i.gyazo.com/ab45827bdf36fc2f1b36af20ddbc6ade.png)](https://gyazo.com/ab45827bdf36fc2f1b36af20ddbc6ade)
[![Gyazo](https://i.gyazo.com/74818b244b288658ce934c1973e4a76f.png)](https://gyazo.com/74818b244b288658ce934c1973e4a76f)
[![Gyazo](https://i.gyazo.com/d562bbf34891251e8368225ed9d81698.png)](https://gyazo.com/d562bbf34891251e8368225ed9d81698)
[![Gyazo](https://i.gyazo.com/36bd50e39671e7b8cc815045821f8198.png)](https://gyazo.com/36bd50e39671e7b8cc815045821f8198)
[![Gyazo](https://i.gyazo.com/0ec68aadd22d0a1ad11c2b86bdf115a6.png)](https://gyazo.com/0ec68aadd22d0a1ad11c2b86bdf115a6)
[![Gyazo](https://i.gyazo.com/e1011e472e8655564912366cd383d087.png)](https://gyazo.com/e1011e472e8655564912366cd383d087)

[![Gyazo](https://i.gyazo.com/7a45800fe32c74e2fabed35749b863b2.png)](https://gyazo.com/7a45800fe32c74e2fabed35749b863b2)


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
DROP DATABASE db01;
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

