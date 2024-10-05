# Vectors

## 矢量/向量



物理学中的物理量，像质量
$m$、密度
$ρ$、能量
$E$、温度
$T$、压强
$P$等，选定单位后只用一个数字来表示其大小，这类没有方向的量叫做**标量**（scalar）。标量一般带有正、负号，但也有标量是恒正的。

既有大小又有方向的量叫做**矢量**或**向量**（vector），例如位移
$\Delta$
s、速度
$v$、加速度
$a$、动量
$p$、力
$F$等。

矢量在印刷中常用粗体表示(e.g. 
**A**)，手写则上加箭头（e.g. $\overrightarrow{A}$），
作图中用一个加箭头的线段来表示矢量，线段长度正比于矢量大小，箭头的方向表示矢量的方向。

### 二维矢量：
$\vec{A} = (A_x,A_y) = A_x\cdot\hat{i} + A_y\cdot\hat{j}$, 

其中
$(A_x,A_y)$为将矢量**A**起点移至坐标原点后矢量的终点坐标，

$\hat{i}$, 
$\hat{j}$称为坐标系的**基矢**，分别为从原点指向x轴正方向(Ox)的长度为1的单位向量和从原点指向y轴正方向（Oy）的长度为1的单位向量，有
$\hat{i} = (1,0)$，
$\hat{j} = (0,1)$，

$A_x\cdot\hat{i}, A_y\cdot\hat{j}$分别为矢量**A**在x、y方向上的分量矢量，
$A_x，A_y$分别为矢量**A**在x、y方向上的分量，它们的大小分别等于矢量**A**在x、y轴上的投影长度。

$|\vec{A}|$称为矢量A的**模**或**模量**，是一个标量，它等于矢量**A**的大小，也即表示该矢量的线段之长度，是一个正的量。

$|\vec{A}| = \sqrt{A_x^2 + A_y^2}$

$A_x = |\vec{A}|\cdot\cos(\alpha)，A_y = |\vec{A}|\cdot\sin(\alpha)$
，其中
$\alpha$为矢量**A**与x轴正方向(Ox)（或与
$\hat{i}$）的夹角。

### 三维矢量：
类似的，有
$\vec{A} = (A_x,A_y,A_z) = A_x\cdot\hat{i} + A_y\cdot\hat{j} + A_z\cdot\hat{k}$, 

$|\vec{A}| = \sqrt{A_x^2 + A_y^2 + A_z^2}$

其中
$\hat{i}，\hat{j}，\hat{k}$分别为三维直角坐标系x轴、y轴、z轴正方向的基矢，想象右手四指由伸直到弯曲的动作过程，四指转动方向对应矢量
$\hat{i}$转向矢量
$\hat{j}$的转动，那么拇指所指方向即矢量
$\hat{k}$的方向。这便是国际惯例所使用的右手系。

矢量**A**在Ox，Oy，Oz轴方向上的投影，即矢量**A**的x，y，z分量，分别为
$A_x = |\vec{A}|\cos(\alpha),A_y = |\vec{A}|\cos(\beta),A_z = |\vec{A}|\cos(\gamma)$

同样的，矢量**A**在Ox，Oy，Oz轴方向上的投影矢量，即矢量**A**的x，y，z分量矢量，分别为
$A_x\cdot\hat{i} = |\vec{A}|\cdot\cos(\alpha)\cdot\hat{i}，A_y\cdot\hat{j} = |\vec{A}|\cdot\cos(\beta)\cdot\hat{j}，A_z\cdot\hat{k} = |\vec{A}|\cdot\cos(\gamma)\cdot\hat{k}$

矢量**A**的方向矢量，也即长度为1，方向为矢量**A**的方向的单位矢量
$\hat{a} = \frac {\vec{A}} {\sqrt{A_x^2 + A_y^2 + A_z^2}}$
