# 数据结构
利用c语言实现《数据结构》课本代码（原书中以伪码形式出现）
## 1.绪论
本单元介绍了数据结构的基本概念和知识，并给出了数据结构实现的通用形式
### 1.1什么是数据结构
   我个人理解数据结构就是处理数据与数据之间关系的一门学科。它属于非数值计算的问题，描述的不再是数学方程，而是表图树之类的数据关系。比如图书馆管理系统，交通路口的道路规划等
### 1.2基本概念和术语
   #### 
   数据：对客观事物的符号表示，一般以数字和字符来表示。
   #### 
   数据元素：数据的基本单位，一个数据元素可有若干个数据项组成，比如书目信息作为一个数据元素，但其中的每一项都可以作为一个数据项（书名，作者）。数据项是数据中的最小单元
   #### 
   数据对象：性质相同的数据元素的集合
   ####
   数据结构：相互之间存在的一种或者多种特定关系的数据元素的集合。其中包括集合、线性结构、树形结构、图状结构。。。
   * 集合：数据元素除了同属于一个集合，无其他关系
   * 线性结构：数据元素存在一对一的关系。
   * 树形结构：存在一对多
   * 图状结构：多对多
   ####
   数据结构的形式定义为一个二元组：Data_structure=(D,S),D为数据元素的有限集，S为D上关系的有限集。
   ####
   逻辑结构：上述描述的关系是数据元素之间的逻辑关系，成为逻辑结构。
   ####
   存储结构：数据结构在计算机中的表示为数据的存储结构，包括顺序存储和链式存储。
   ####
   数据类型：是一个值的集合和定义在这个值集上的一组操作。
   * 原子类型：不可分解，整形，实型。。。。
   * 结构类型：由若干成分按某种结构组成的，可分解
   ####
   抽象数据类型（ADT）：一个数学模型以及定义在该模型上的一组操作。其定义与计算机内部实现无关。只取决于一组逻辑特性。
   #####
   一个含抽象数据类型的软件模块通常包含定义、表示和实现3个部分。
   * 定义由一个值域和定义在该值域上的一组操作组成
   * 表示：（D，S，P）D为数据对象，S为D上的关系集，P为对D的基本操作。
   * 基本操作用以下格式：
   `  
   ADT 抽象数据类型名{  
     数据对象：<数据对象的定义>  
     数据关系：<数据关系的定义>  
     基本操作：<>  
   }  `
   
   
   
