# MCBBS-Wiki-Editcount

使用指南：
1. 安装Python 3.9（3.8应该也行），并安装openpyxl，requests和retrying库。
2. 15行，<code>folder = r"D:\python\mcbbswiki"</code>改成你自己的文件目录。
3. 翻到最下面，82行注释符号去掉，把参数改成你想爬取的部分（Github仓库已有1-34925的数据，不要重复）
4. 83行把34925改成上一步最后的那个参数，数字1不变（除非你要统计某个范围内的编辑情况）
5. 执行脚本即可。

MCBBS Wiki地址：https://mcbbs-wiki.cn/
