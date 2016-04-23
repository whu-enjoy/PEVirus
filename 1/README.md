<pre>
这个目录下是我自己写的第一个PE文件感染病毒，因为只是刚刚学，所以代码功能做的不是很完善

enjoy.c
	感染程序的代码文件
	int AdjustShellcode(unsigned char shellcode[],int virtualNewAddressOfEntryPoint,int codeOffset,int dataOffset);   修改shellcode中使用到的数据地址

enjoy.exe
	用VC6.0编译的release版本的Win32可执行文件
</pre>
