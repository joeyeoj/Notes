* 官网下载软件包
[https://www.java.com/en/download/](https://www.java.com/en/download/)
* 按照提示安装即可
* 测试是否安装成功
```
java -version
```
* 查询安装路径
```
/usr/libexec/java_home -V 
```
* 配置环境变量
  * 显示当前目录下的所有文件及文件夹
    ```
    ls -a
    ```
  * 打开文件
    ```
    vi .zprofile
    i #进入编译模式
    export JAVA_HOME="/Library/Java/JavaVirtualMachines/jdk1.8.0_221.jdk/Contents/Home"
    export PATH="$PATH:$JAVA_HOME/bin"
    # 按下esc键，退出编译模式
    :wq! #保存并退出
    ```
