
模拟抽卡
原神抽卡模拟器：这是一个基于 Python 的抽卡模拟程序，还原了《原神》的角色祈愿机制，包含软保底、硬保底和大小保底规则。

功能：
1、基础五星概率 0.6%
2、74 抽开始软保底，概率指数增长
3、90 抽硬保底
4、小保底歪后下一次必出 UP（大保底）
5、统计抽到一个 UP 角色所需的抽数分布（平均、最欧、最非）
6、绘制直方图可视化分布

运行环境：
1、Python 3.6+
2、依赖库：`numpy`, `matplotlib`

使用方法：
1、克隆仓库
2、安装依赖：`pip install numpy matplotlib`
3、 运行脚本：`python gacha_simulator.py`

输出示例：
1、真实抽卡模拟：
   平均抽数： 101.144
   最欧： 2
   最非： 180
2、直方图：<img width="640" height="480" alt="Figure_1" src="https://github.com/user-attachments/assets/d462947e-469f-41c5-b242-536259809e89" />


