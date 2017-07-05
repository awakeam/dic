# dic
A dictionary tools for bash shell.

## rely on
- python 2.7.13
- requests 2.12.3
- bs4 4.5.3

## Usage

**查询单词**

`$dic hello`

![image](https://github.com/awakeam/dic/tree/master/images/show1.png')

**后接多个单词**

`$dic hello world more`

![image](https://github.com/awakeam/dic/tree/master/images/show2.png')

**无限模式**

```
$dic
>>> hello
...
>>> world
...
```

![image](https://github.com/awakeam/dic/tree/master/images/show3.png')

**查询例句**

`$dic -l hello`

![image](https://github.com/awakeam/dic/tree/master/images/show4.png')
