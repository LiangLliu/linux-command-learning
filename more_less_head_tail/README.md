# more & less & head & tail 学习
### more command
* 命令用法
  * more [oprion] file
* 示例：
  * ```more +3 test.txt``` : 从第三行开始显示内容
  * ```more +/hello test.txt``` : 查找文件中hello的地方，从这里输出
  * ```more -5 test.txt``` : 设置每页五行显示问价
  * ```ls /etc | more -10``` : 配合管道显示内页的行数 