# PAT-Advanced-Level

*准备浙大的机试 记录下过程和心得^_^*

+ a1002: cmp函数一定要保证能return，否则会导致段错误

+ a1003: 二维数组的fill，eg：G[maxn][maxn],  fill(G[0], G[0] + maxn * maxn)

  dijkstra算法： 考虑当最短路径有多条时，要求哪些参数（最短路径题往往还有第二指标，即除距离最短之外还要别的要求）。本题要求最短路径条数以及最大点权和。


+ a1101: 有个别测试点不满足的时候要考虑边界情况，本题0的情况要加\n，

  快排中确定主元：当元素位置与排序结果相比没有变化并且在结果序列中它左边的所有值的最⼤大值都⽐ 比它⼩的
  时候就可以认为它可以是主元

+ a1102：二叉树的静态表示法：

  ```
  struct node{
    typename data;
    int l;
    int r;
          // 还可以添加其他的一些属性
  } Node[maxn]; // maxn 为最大节点数
  ```

  输入时要注意字符与数字之间的转换。

+ a1103  DFS + 剪枝

+ a1104   

   !!! double * int * int 与 int * int * double 可能会有区别。int * int * double时  int * int 可能溢出。

+ a1105

+ a1106  树的遍历

  普通的树的表示
  ```
  vector<int> child[maxn]  // maxn为最大结点数， 如果有点权可以用结构体

  ```
+ a1107 并查集
