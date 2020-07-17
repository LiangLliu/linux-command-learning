# which & whereis & locate 命令学习

### which 命令
* 用来查找文件
* 用法
  * ```which executable file name``` 
* 示例: 
  * ```which git``` : 查找文件，显示命令路径
* 练习
   ![which练习](images/which_exercise.png) 

### whereis 命令
* 只能用于程序名搜索，只能是二进制文件
* 用法
  * ```whereis [option] file``` 
* 示例: 
  * ```whereis git``` : 将文件相关的都查询出来
  * ```whereis -b git``` : 只查询二进制文件
* 练习
    ![whereis练习](images/whereis_exercise.png)

### locate 命令
* 快速的搜索文件系统中是否有指定的文件
* 用法
  * ```locate [option](Search string)```
* 示例
  * ```locate pwd``` : 查询和搜索内容相关的所有文件
* 练习
    命名未找到
    ![locate 练习](images/locate_exercise.png)

### 练习完成
![练习完成](images/exercise_complete.png)