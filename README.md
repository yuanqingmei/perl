# perl使用工具进行调试

类似浏览器的F12功能，Perl也提供了调试工具ptkdb。使用该工具需要两个模型包：Tk和ptkdb。

使用如下命令可以安装着两个包

[python] view plain copy
perl -MCPAN -e'install Tk'  
perl -MCPAN -e'install Devel::ptkdb'  
使用工具进行调试


[python] view plain copy
perl -d:ptkdb Perl程序名称  
