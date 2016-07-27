Git is a version control system.
Git is free software.

git config --global user.name "Your Name"
git config --global user.email "email@example.com"

mkdir learngit
cd learngit
pwd

git init
//create readme.txt with notepad++
git add readme.txt
git commit -m "wrote a readme file"

1.路径分隔符，cmd 是 "\" ，bash 是 "/"
2.转义字符，cmd 是 ^ 和双引号，bash 有双引号，单引号和 "\"
3.顺序执行两个命令，cmd 是 cmd1 && cmd1 而 bash 是 cmd1 ; cmd2
4.and 执行两个命令，cmd 是 cmd1 & cmd2 而 bash 是 cmd1 && cmd2
5.通配符实现原理不同，比如 cmd 中使用 dir *.dll 的这个“*.dll”的通配符是 dir 自己实现的，但是在 bash 中 ls *.txt 通配符是 bash 实现的，也就是说传入 ls 命令的实际参数相当于 1.txt 2.txt ... 这样子
6.PATH 的分隔符， cmd 是分号，bash 是冒号
7.虽然 echo 都是内置命令，但是功能有一些差异
8.放在后台执行，bash 是 & ，而 cmd 是 start 命令
9.bash 的很多功能，比如 alias ，cmd 没有对应物
