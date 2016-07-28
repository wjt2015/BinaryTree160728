# BinaryTree160728
本文件夹内的程序文件都是关于二叉树的，分别是： 
（1）、BTree_Depth_Balance.h,BTree_Depth_Balance.c，用于计算二叉树的深度和判断二叉树是否是平衡二叉树。 
（2）、LowestCommonAncestor.h,LowestCommonAncestor.c，用于查找二叉树内任意两个给定节点的最低公共祖先。 
（3）、non_recursive.h,non_recursive.c，非递归中序遍历二叉树。 
（4）、SingleColorLongestPath.h,SingleColorLongestPath.c，二叉树内每一个节点都有颜色，或红或白，给定一棵二叉树，
计算出最长的单色最长路径。 
（5）、SpecificSumPath.h，SpecificSumPath.c，给定一个整数和一棵二叉树，
找出二叉树内的一条从根节点到叶节点的 简单路径，使该路径内每个节点的关键字之和等于给定的整数。



还有几个辅助性文件： 
（1）、app.h，包含必要的标准头文件和一些宏定义。 
（2）、BTree.h,BTree.c，定义二叉树的节点结构和基本操作。
（3）、Stack.h,Stack.c，定义栈，用于操作二叉树。
（4）、c.deps，包含每个.c文件的依赖关系，用于生成目标文件。

inData.txt,inData2.txt,inData3.txt，都是输入数据的文件，都可独立使用。

BTree_main.c，程序主文件，定义有main()函数，调用其他的功能函数完成特定的二叉树操作。
