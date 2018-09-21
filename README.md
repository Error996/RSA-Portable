利用mbedssl库实现，无需各种lib、so、a等链接库

拷贝mbedtls文件夹到你编译环境的include目录里（EDK2和BIOS平台请拷贝到pkg项目的include目录里，一般是MdePkg）

编译指令，每个文件夹 gcc *.c

EDK2和bios平台，可以利用AppPkg/Applications/Main来编译
