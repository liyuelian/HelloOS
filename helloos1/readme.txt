1.汇编文件helloos.nas
2.在当前文件夹打开cmd窗口，使用命令 ..\z_tools\nask.exe helloos.nas helloos.img
将其编译为 helloos.img 镜像文件
3.点击 !cons_nt.bat ，在窗口中使用命令 run.bat，就可以用 QEMU 模拟器运行镜像文件

ps：可以将2步骤做成一个批处理文件 asm.bat
这样只需要在！cons_nt.bat中输入asm就可以生成helloos.img文件，然后再执行 run 指令就可以得到一样的结果