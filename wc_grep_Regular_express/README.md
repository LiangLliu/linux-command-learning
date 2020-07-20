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

