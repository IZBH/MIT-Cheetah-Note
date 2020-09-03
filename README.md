# MIT-Cheetah-
## MIT Cheetah仿真平台源码笔记以及一部分第三方组件
### 仓库说明
>在看MIT Cheetah仿真平台的源码的过程中所做的笔记的整理，为了更好地理解源码，因此对应代码中提到的部分参考论文，手动整理了这份笔记，希望与同好交流，笔记中的错误之处欢迎指正。
       
### 文件结构     
`ref` 文件夹中存储相关的论文和电子书的pdf格式文件。     
`BalanceController` 对应源码中BalanceController相关文件的剖析,主要是调用qpOASES求解器完成对四足机器人GRF的优化求解过程。     
`Quadruped` 对应源码中Quadruped相关文件的剖析，主要是构建四足机器人的动力学和运动学模型。     
`LegController` 对应源码中LegController相关文件的剖析，主要是四足机器人腿部运动学的参数处理以及正、逆运动学的计算。       
`FootSwingTrajectory` 对应源码中FootSwingTrajectory相关文件的剖析，主要是对摆动腿的足端位置、速度和加速度通过三次贝塞尔曲线插值进行规划。     
`PositionVelocityEstimator`

### 其他
原始项目地址：[https://github.com/mit-biomimetics/Cheetah-Software](https://github.com/mit-biomimetics/Cheetah-Software)       
qpOASES求解器地址：[https://github.com/coin-or/qpOASES](https://github.com/coin-or/qpOASES)
       
## Loading......
