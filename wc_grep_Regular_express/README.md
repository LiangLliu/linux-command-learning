# wc & grep & Regular & express 命令学习
### wc命令
* WC(Word count)用来统计指定文件中的字节数、字数、行数，并显示
  * ```WC [options] file
* 参数说明
  * ```-c``` : 统计字节数
  * ```-l``` : 统计行数
  * ```-m``` : 统计字符数
  * ```-w``` : 统计字数
  * ```-L``` : 打印最长行的长度
  * ```-help``` : 打印帮助纤细
  * ``` --version``` : 显示版本
* 示例
  * ```ls -l | wc -l``` : 使用管道符统计当前目录下的文件数
* 练习
    ![wc命令练习](images/wc_exercise.png)


### grep命令
* 文本搜索工具，它能使用正则表达式搜索文本，Global Regular Express Print(全局表达式版本)
* 命令格式：
  * ```grep [option] pattern file``` 
* 示例：
  * ```ps -ef | grep git``` : 查找指定进程
  * ```ps -ef | grep git -c``` : 查找指定进程个数
  * ```cat test.txt | grep -f test2.txt``` : 从文件中读取关键词进行搜索
  * ```cat test.txt | grep -f test2.txt``` : 从文件中读取关键词进行搜索，显示行号
  * ```cat "hello" test.txt``` : 从文件中查找关键词
  * ```cat test.txt | grep ^h``` : 找出以 h 开头的内容
  * ```cat test2.txt | grep ^[^h]``` : 输出 非h 开头的内容
  * ```cat test2.txt | grep ld$``` : 输出以 ld 结尾的内容
  * ```cat test2.txt | grep -E "e|ux"``` : 输出包含 e/ux的内容
  * ```grep '[a-z]\{4\}' *.txt``` : 输出下列文件中知道4个连续小写的字符串行
* 练习
    ![grep练习](images/grep_exercise.png)
