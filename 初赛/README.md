飞的更高队初赛提交工程文件说明：

文件结构为:

![](media/0b36a505a7cd6895f47fe26418e6915c.png)

其中data文件夹内部的每一个子文件夹，以”xuelang_round1_test_b”为例，该文件夹下应直接存放图片以及标签文件，不能再有二级文件夹，正确的文件夹格式为如下所示：

![](media/a99901410a0d56a5f4d1aa91ff3ffb9c.png)

![](media/1d5e786c6b04805c468a079105adc50e.png)

操作步骤：

（1）您需要将官网上提供的4个文件解压放入data文件夹，分别是：xuelang_round1_test_b_20180802，xuelang_round1_train_part1_20180628，xuelang_round1_train_part2_20180705，xuelang_round1_train_part3_20180709，如上图片所示。

（2）验证方案：

　　打开code文件夹里面的main.py，运行。运行结束后在submit文件夹会有预测的csv文件。此程序包括图片的预处理（约3个多小时），模型的训练（约10个小时），最好一代模型对测试数据的预测（10分钟）生成csv文件并保存在submit文件夹下等全部操作所需的代码；
  

