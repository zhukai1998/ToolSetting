- 导入 CLion，配置启动程序
- Executable 修改为咱们编译后的 java 程序
- Before launch:Build,Activate tool window 删除 Build
- 在 ./src/hotspot/share/runtime/thread.cpp 代码的 3734 行的 create_vm 方法打下断点
- 开始 debug，验证配置是否成功
- 编译自己写的 Java 程序，先把 java 文件编译为 class 文件
- 配置启动程序，选定 Working diretory: 然后 填写类名 Program arguments
