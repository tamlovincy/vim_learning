# vim_learning

* yy 复制游标所在行 	nyy	复制光标下n行
* dd 删除光标所在行    ndd   删除光标下n行
* p 粘贴
* 多行复制
  * `59，69 co 80`
  * `58,69 move 80`
* 批量替换
  * `69，80s#output#reg` 将69行到80行的output替换为reg
* 多行缩进
  * v进入visual模式，选择多行，用<或>缩进或者缩出
* 显示多个文档
  * vim file1 file2
  * : open file
  * :split 或 :vsplit
  * ctrl+w切换窗口
* 删除某一列
  * 将光标选中所在列，shift+v，shift+g，ctrl+v
  * 然后调整选中区域即可进行操作
* 快速移动光标至当前行首：键盘home键；快速移动光标至当前行末：键盘end键。其他命令暂时不用
* 整体操作某一列：
  * ctrl+v选择某一列
  * shift+i或者大写I开始进行整体插入某一列内容
  * esc即可产生整列同时修改相同的内容