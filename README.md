# 浅显的使用说明：
---------------------------------
点开view code中所要预览的文件：

1。可下载至本地jupyter目录位置，并使用jupyter打开。

2。因github网站原因显示、下载较慢，可点开对应文件后，复制地址栏里的地址，然后打开[这里](http://nbviewer.jupyter.org),将上述地址输入到栏中,即可在线预览。

---------------------------------


# 作业列表：
---------------------------------
## &#x2705;标准格式

  包含整体框架，常用库及命令，自定义绘图函数Zplt，随机颜色生成函数……，感谢刘晟翔同学对此的启发。

---------------------------------
## &#x2705;第一次作业：泰勒公式

  利用泰勒展开式对常见函数进行拟合。在本文档中引入ipywidgets库并使用其控件进行交互式编程，主要错误是“[]”的误用以及忽略了泰勒级数的收敛半径（感谢吴本畅和翁凯枫同学对此的指出）。

---------------------------------
## &#x2705;第二次作业：求根公式

  使用二分法、牛顿迭代法和梯度下降法分别求2022的九次方根，试图采用模块化的思路但因为参数传递的失误而未能取得预期效果。

---------------------------------
## &#x2705;第三次作业：Logistic Map

  对迭代方程 $x_{n+1}=rx_n(1-x_n)$ 的性质进行初步了解，绘制其分叉图。尝试了多合一图的绘制，对分叉图进行局部放大以观察它的自相似性。并在与鲁一帆同学的交流中启发对单参数表示遍历不重叠颜色空间的探索。

---------------------------------
## &#x2705;第四次作业：李雅普诺夫指数

  绘制李雅普诺夫指数图像以刻画给定系统相空间任意一条微扰的轨道以何种方式偏离原轨道，并借助图像表示求出疑似不动点。因时间关系，没有绘制蛛网图、初值敏感性的频率分布和周期二轨道的解析表达式（另：翁凯枫同学已做出了很好的探索）。在本文档末尾提出了一种不完善的颜色表示，仍待修正。
    最后特别感谢19级学长赵冲指出<肆>中循环内赋初值的错误，19级学长魏盛龙指出<贰>中播放器STEP必须为整数值的隐含条件。

---------------------------------
## &#x2705;第五次作业：洛伦兹系统

 &#x274C;未完成计算最大李雅普诺夫指数。
 绘制Lorentz系统状态演化与相图，探究初始条件对系统状态的影响。尝试了三维图像的绘制、借助ipywidgets实现动画、生成组合图及其PNG。
 特别鸣谢19级学长赵冲对Z轴标签添加的指导及指数部分的解惑，以及与翁凯枫，毛鹏皓，鲁一帆，来起正等同学和王新然学长的讨论交流，罗羽轩传授的matplotlib中3D视角改变。

---------------------------------
## &#x2705;第六次作业：非线性振子

计算单双线性弹簧振子的解析解，绘制两端固定线性弹簧振子的演化图、二维相图、三维相图并验证解析解与数值解的一致性。并考虑了非线性因子对演化图、二维相图、三维相图、能量的影响。
感谢周乐同学帮助梳理了两端固定线性双振子解析解求解过程。（注：请参考README给出的方法打开，因文件较大GitHub打开可能会出现乱码）

---------------------------------
## &#x2705;第七次作业：非线性双振子

绘制了非线性弹簧双振子在给定参数下的状态演化图、相图、庞加莱截面，并尝试计算最大李雅普诺夫指数，初步尝试FFT方法。特别鸣谢&#x1F339;&#x1F339;&#x1F339;：与翁凯枫，余超，鲁一帆，来起正等同学的讨论交流，特别是翁凯枫传授的FFT。

---------------------------------

## &#x2705;第八次作业：蒙特卡洛方法


---------------------------------
## &#x2705;第九次作业：蒙特卡洛方法·二


---------------------------------
## &#x2705;第十次作业：中心极限定理
  
  
---------------------------------
## &#x2705;第十一次作业：分形——几何维数

  了解分形基本的生成原理，并计算了随机行走过程与圆的计盒维数。
  与吴本畅，翁凯枫进行讨论，其中吴本畅同学对维数计算方法的扩展，变二维矩阵为一维数组，极大提高可分格数（提升约千倍）。
  
  ---------------------------------
## &#x2705;结课论文：基于分数布朗运动估算赫斯特指数与分形维数

 讨论了重标极差分析方法及其修正的有效性。借助分数布朗运动进一步证实了Hurst指数与分形盒维数之和为2的关系。
 设定不同赫斯特指数通过随机魏尔斯特拉斯函数模拟出一系列分数高斯噪声时间序列数据，在分析过程中通过给定H下各随机项取随机值演示了随着H值增大，图像逐渐趋于平滑的整个过程。
 在改变b时研究其类周期性，体现随机Weierstrass函数的类周期性主要由最大振幅项提供。
 H指数的计算在R/S分析中是通过双对数回归分析方法得到，其估计值的显著性检验同n的取值大小密切相关。n取值较大时，H指数估计值的显著性检验效果明显，n取值较小时，检验效果较差。
 在选择计算分形维数的方法时，考虑数据的特征和需求采取计盒维数法。在误差允许范围之内，Hurst指数与分形维数的数量关系为：H=2-D。 
 较为遗憾的是，未能给出对于此数量关系的严格证明。而且对于估算Hurst指数精度仍有待提高。


### 友情链接：[翁凯枫的库](https://github.com/imwkf/kebian)
# 感谢愿意一起交流讨论，一道成长的你们&#x1F60A;
