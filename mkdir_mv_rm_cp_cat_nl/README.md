# mkdir & rm & mv & cp & cat & nl 命令学习
 ### mkdir [options] directory
 * mkdir命令
   * ```mkdir directory``` : 创建文件夹
   * ```mkdir -p directory/directory ``` : 可以是一个路径，此时如果路径中的某些目录不存在，加上这个选项后，系统会自动建立好不存在的目录。一次可以创建多级目录。
   * ```mkdir -m 777 directory``` : 创建目录时，给目录设置权限
   * ```mkdir -v directory``` : 每次创建新目录都显示信息
   * ```mkdir -vp scf/{lib/,bin/,doc/{info,product}}}``` : 一个命令创建项目的目录结构 
 * 测试结果  
    ![练习结果](images/madir_exercise.png)