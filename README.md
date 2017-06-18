# SwordtoOffer
经典常考必备面试算法，包括但不仅限于《剑指Offer》，《程序员面试金典》中的题目，持续更新中...

现具体包括如下问题的解法：

 - 阶乘的递归和非递归解法；
 
 - 二分查找的递归和非递归解法；
 
 - 斐波那契数列的四种解法：经典递归法、优化递归法、循环迭代法，数组法；

 - 杨辉三角的创建、存取、打印算法；
 
 - 字符串回文判断的三种解法：递归法，循环迭代法， StringBuilder法；
 
 - 诺比塔问题的递归解法；
 
 - 【Offer 3】二维数组中的查找的两种解法：时间复杂度分别为O(nlgn)和O(n)；
 
 - 【Offer 28】字符串全排序的两种解法：递归法 和 循环迭代法(字典序全排列)；

 - 【Offer 4】字符串空格置换算法；

 - 【Offer 6】已知二叉树中序和前序遍历序列，重新构建二叉树；

 - 【Offer 5】链表的倒序打印；
 
 - 【Offer 29, 30】快排Parititon算法的应用(序列的中位数，第K大元素，最小K个元素，超过序列一半的元素)；

 - 【Offer 7】用两个栈实现队列(一个用作插入，一个用作删除)；

 - 【Offer 25】二叉树和为特定数值的路径(递归算法，前序遍历的应用)；

 - 结点为int型的二叉树及其常用算法实现；
 
 - 【Offer 9】递归算法的数学模型(数学归纳法)、经典递归问题(斐波那契数列、变态跳台阶)、斐波那契数列的应用(跳台阶、矩阵覆盖等)；
 
 - 【Offer 8】二分搜索算法及其应用(旋转数组的最小元素)：序列有序或部分有序；
 
 - 【Offer 13】给定链表头结点和待删除节点，以O(1)的时间复杂度删除链表中的待删除节点：换一种思路考虑，删除当前节点就是把待删除节点的值替换成其后继节点的值，并删除其后继节点；

 - 【Offer 10】位运算相关算法，核心思想：a & (a -1) 意味着将a的最右边的1变成0，其可应用于求解：一个数的二进制中1的个数问题、数m的二进制需要改变多少次才能变成数n的二进制、判断一个树是否是2的幂；判断一个数的奇偶性；

 - 【Offer 15】寻找链表中的倒数第K个节点算法(双指针法)；

 - 【Offer 11】幂运算算法(减少相乘次数，递归算法)；

 - 【Offer 12】从1开始打印最大的n位数算法(用字符串表示大数，进位原理的掌握)；

 - 【Offer 16】链表反转算法（可以见解“以O(1)的时间复杂度删除链表中的待删除节点”的算法思想，图示法(原头节点的指针指向一个初始为null的节点)、递归算法）；

 - 【Offer 14】数组中奇偶数划分算法，不保证原数列奇、偶数的相对位置的解法：快排划分算法的应用，双指针法(头指针/尾指针)；保证原数列奇、偶数的相对位置的解法：双指针法(分别指向最新奇数与最老偶数)。

 - 【Offer 17】合并两个排序列表：递归解法干净利落，循环解法考虑细节较多；

 - 【Offer 18】树的子结构：递归算法的设计与实现；

 - 【Offer 19】二叉树镜像：递归算法设计与实现，画图、找规律；

 - 【Offer 20】顺时针打印矩阵(可以不是方阵)：递归算法的设计与实现，递归终止条件的考虑(只剩一行，只剩一列，只剩一个元素)；

 - 【Offer 21】包含min函数的栈：利用一个额外的栈来保存存储栈中的最小值；

 - 【Offer 22】栈的压入/弹出序列匹配：用一个栈来模拟给定压入和弹出序列，若最后栈变为空，则符合要求；

 - 【Offer 23】从上往下打印二叉树：二叉树的广序遍历，借助于队列；

 - 【Offer 24】二叉搜索树的后序遍历序列：二叉搜索树的概念(左子树 < 根结点 < 右子树)以及递归算法的设计；

 - 【Offer 25】二叉树中和为某一值的路径：递归算法的设计和前序遍历的应用(两种解法)；

 - 【Offer 26】复杂链表的复制：复杂问题的分解(三种解法[三种解法时间、空间复杂度不同]);

 - 【Offer 27】二叉搜索树转换为双向链表：二叉搜索树的概念(左子树 < 根结点 < 右子树)以及递归算法的设计，两种解法；

 - 【Offer 28】字符串全排列：递归算法的设计和前序遍历的应用(两种解法)，注意字符串中含有重复字符的情况，即是否需要去重；

 - 【Offer 28 扩展】字符串包含字符的所有组合：分治与递归(共包括三步：1.取出重复字符，使字符串个字符互异；2.分别获取含1...n个字符的组合;3.将上一步所得到的所有组合合并)。
 
 本次更新二叉搜索树与双向链表、字符串全排列、字符串所有字符的全部组合等三个主要算法


Ps:源码中每个包对应一个问题。若项目中的源代码存在谬误，请不吝指出，在此拜谢！
 
