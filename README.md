# GPLT
⚔️Group Programming Ladder Tournament

## L1-001 Hello World （5 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805147132084224)

[C++ (5/5)](https://github.com/Heliovic/GPLT/blob/master/L1-001/main.cpp)

## L1-002 打印沙漏 （20 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805145370476544)

[C++ (20/20)](https://github.com/Heliovic/GPLT/blob/master/L1-002/main.cpp)

### 解题思路

设上面的倒三角形层数为 t，中间的单个符号为第一层，则一个完整的三角形所需符号数目为 1 + 3 + 5 + ··· + 2t - 1 = t^2。所以整个沙漏需要的符号个数为 2t^2 - 1。令 2t^2 - 1 = N，即可算出最大层数和所需符号数，注意，这里都是整数运算，向下取整。之后按照符号和层数之间的函数关系打印。

## L1-003 个位数统计 （15 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805143738892288)

[C++ (15/15)](https://github.com/Heliovic/GPLT/blob/master/L1-003/main.cpp)

### 解题思路

打表。

## L1-004 计算摄氏温度 （5 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805142086336512)

[C++ (5/5)](https://github.com/Heliovic/GPLT/blob/master/L1-004/main.cpp)

## L1-005 考试座位号 （15 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805140211482624)

[C++ (15/15)](https://github.com/Heliovic/GPLT/blob/master/L1-005/main.cpp)

## L1-006 连续因子 （20 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805138600869888)

[C++ (20/20)](https://github.com/Heliovic/GPLT/blob/master/L1-006/main.cpp)

### 解题思路

若 N 是质数，则显然只有 N 本身。

否则，对每个 i <= sqrt (N)，检查从 i 开始的连续的数之积是否能整除 N。记录下最长的连续数起止位置并取最长。

## L1-007 念数字 （10 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805136889593856)

[C++ (10/10)](https://github.com/Heliovic/GPLT/blob/master/L1-007/main.cpp)

## L1-008 求整数段和 （10 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805135224455168)

[C++ (10/10)](https://github.com/Heliovic/GPLT/blob/master/L1-008/main.cpp)

## L1-009 N个数求和 （20 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805133597065216)

[C++ (20/20)](https://github.com/Heliovic/GPLT/blob/master/L1-009/main.cpp)

### 解题思路

分数化简与求和。

## L1-010 比较大小 （10 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805132040978432)

[C++ (10/10)](https://github.com/Heliovic/GPLT/blob/master/L1-010/main.cpp)

### 解题思路

注意 ```while (scanf("%d", &t) != EOF)``` 的写法。

## L1-011 A-B （20 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805130426171392)

[C++ (20/20)](https://github.com/Heliovic/GPLT/blob/master/L1-011/main.cpp)

### 解题思路

散列。

## L1-012 计算指数 （5 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805128870084608)

[C++ (5/5)](https://github.com/Heliovic/GPLT/blob/master/L1-012/main.cpp)

### 解题思路

快速幂。

## L1-013 计算阶乘和 （10 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805127389495296)

[C++ (10/10)](https://github.com/Heliovic/GPLT/blob/master/L1-013/main.cpp)

## L1-014 简单题 （5 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805125929877504)

[C++ (5/5)](https://github.com/Heliovic/GPLT/blob/master/L1-014/main.cpp)

## L1-015 跟奥巴马一起画方块 （15 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805124398956544)

[C++ (15/15)](https://github.com/Heliovic/GPLT/blob/master/L1-015/main.cpp)

## L1-016 查验身份证 （15 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805122985476096)

[C++ (15/15)](https://github.com/Heliovic/GPLT/blob/master/L1-016/main.cpp)

## L1-017 到底有多二 （15 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805121500692480)

[C++ (15/15)](https://github.com/Heliovic/GPLT/blob/master/L1-017/main.cpp)

## L1-018 大笨钟 （10 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805119944605696)

[C++ (10/10)](https://github.com/Heliovic/GPLT/blob/master/L1-018/main.cpp)

## L1-019 谁先倒 （15 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805118568873984)

[C++ (15/15)](https://github.com/Heliovic/GPLT/blob/master/L1-019/main.cpp)

## L1-020 帅到没朋友 （20 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805117167976448)

[C++ (20/20)](https://github.com/Heliovic/GPLT/blob/master/L1-020/main.cpp)

## L1-021 重要的话说三遍 （5 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805115792244736)

[C++ (5/5)](https://github.com/Heliovic/GPLT/blob/master/L1-021/main.cpp)

## L1-022 奇偶分家 （10 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805114445873152)

[C++ (10/10)](https://github.com/Heliovic/GPLT/blob/master/L1-022/main.cpp)

## L1-023 输出GPLT （20 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805113036587008)

[C++ (20/20)](https://github.com/Heliovic/GPLT/blob/master/L1-023/main.cpp)

### 解题思路

打表。

## L1-024 后天 （5 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805111694409728)

[C++ (5/5)](https://github.com/Heliovic/GPLT/blob/master/L1-024/main.cpp)

## L1-025 正整数A+B （15 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805110318678016)

[C++ (15/15)](https://github.com/Heliovic/GPLT/blob/master/L1-025/main.cpp)

## L1-026 I Love GPLT （5 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805108934557696)

[C++ (5/5)](https://github.com/Heliovic/GPLT/blob/master/L1-026/main.cpp)

## L1-027 出租 （20 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805107638517760)

[C++ (20/20)](https://github.com/Heliovic/GPLT/blob/master/L1-027/main.cpp)

## L1-028 判断素数 （10 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805106325700608)

[C++ (10/10)](https://github.com/Heliovic/GPLT/blob/master/L1-028/main.cpp)

## L1-029 是不是太胖了 （5 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805104983523328)

[C++ (5/5)](https://github.com/Heliovic/GPLT/blob/master/L1-029/main.cpp)

## L1-030 一帮一 （15 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805103557459968)

[C++ (15/15)](https://github.com/Heliovic/GPLT/blob/master/L1-030/main.cpp)

## L1-031 到底是不是太胖了 （10 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805102173339648)

[C++ (10/10)](https://github.com/Heliovic/GPLT/blob/master/L1-031/main.cpp)

### 解题思路

注意，在一些平台上此题示例运行结果为：

```
You are wan mei!
You are wan mei!
You are tai pang le!
```

若出现该问题，注意控制浮点的精度，下面的代码也能 AC。

```cpp
void judge(double h, double w)
{
    double standard = (h - 100) * 0.9 * 2;
    if (abs(w - standard) - standard * 0.1 < -0.00001)
        printf("You are wan mei!\n");
    else if (w > standard)
        printf("You are tai pang le!\n");
    else
        printf("You are tai shou le!\n");
}
```

## L1-032 Left-pad （20 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805100684361728)

[C++ (20/20)](https://github.com/Heliovic/GPLT/blob/master/L1-032/main.cpp)

### 解题思路

使用 ```cin.ignore()``` 吸收多余回车。

## L1-033 出生年 （15 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805099426070528)

[C++ (15/15)](https://github.com/Heliovic/GPLT/blob/master/L1-033/main.cpp)

### 解题思路

字符串处理。

## L1-034 点赞 （20 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805098188750848)

[C++ (20/20)](https://github.com/Heliovic/GPLT/blob/master/L1-034/main.cpp)

## L1-035 情人节 （15 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805097018540032)

[C++ (15/15)](https://github.com/Heliovic/GPLT/blob/master/L1-035/main.cpp)

## L1-036 A乘以B （5 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805095676362752)

[C++ (5/5)](https://github.com/Heliovic/GPLT/blob/master/L1-036/main.cpp)

## L1-037 A除以B （10 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805094485180416)

[C++ (10/10)](https://github.com/Heliovic/GPLT/blob/master/L1-037/main.cpp)

## L1-038 新世界 （5 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805093038145536)

[C++ (5/5)](https://github.com/Heliovic/GPLT/blob/master/L1-038/main.cpp)

## L1-039 古风排版 （20 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805091888906240)

[C++ (20/20)](https://github.com/Heliovic/GPLT/blob/master/L1-039/main.cpp)

## L1-040 最佳情侣身高差 （10 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805090748055552)

[C++ (10/10)](https://github.com/Heliovic/GPLT/blob/master/L1-040/main.cpp)

## L1-041 寻找250 （10 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805089657536512)

[C++ (10/10)](https://github.com/Heliovic/GPLT/blob/master/L1-041/main.cpp)

### 解题思路

注意 `while (scanf("%d", &n) != EOF)` 的写法。在 iostream 中对应 `while (cin >> x)`

## L1-042 日期格式化 （5 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805088529268736)

[C++ (5/5)](https://github.com/Heliovic/GPLT/blob/master/L1-042/main.cpp)

## L1-043 阅览室 （20 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805087447138304)

[C++ (20/20)](https://github.com/Heliovic/GPLT/blob/master/L1-043/main.cpp)

### 解题思路

按照书号排序，之后检查相邻的记录是否是有效记录。

## L1-044 稳赢 （15 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805086365007872)

[C++ (10/10)](https://github.com/Heliovic/GPLT/blob/master/L1-044/main.cpp)

## L1-045 宇宙无敌大招呼 （5 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805085295460352)

[C++ (5/5)](https://github.com/Heliovic/GPLT/blob/master/L1-045/main.cpp)

## L1-046 整除光棍 （20 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805084284633088)

[C++ (20/20)](https://github.com/Heliovic/GPLT/blob/master/L1-046/main.cpp)

### 解题思路

除法模拟，好题！

## L1-047 装睡 （10 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805083282194432)

[C++ (10/10)](https://github.com/Heliovic/GPLT/blob/master/L1-047/main.cpp)

## L1-048 矩阵A乘以B （15 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805082313310208)

[C++ (15/15)](https://github.com/Heliovic/GPLT/blob/master/L1-048/main.cpp)

### 解题思路

矩阵乘法模拟。

## L1-049 天梯赛座位分配 （20 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805081289900032)

[C++ (20/20)](https://github.com/Heliovic/GPLT/blob/master/L1-049/main.cpp)

## L1-050 倒数第N个字符串 （15 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805080346181632)

[C++ (15/15)](https://github.com/Heliovic/GPLT/blob/master/L1-050/main.cpp)

### 解题思路

进制转换。先算出正数第几个数，之后将该十进制数转为 26 进制数。在 26 进制中，a-z 对应 0-25。转为 26 进制后长度不够时，记得输出 [前导 0(a)](https://github.com/Heliovic/GPLT/blob/master/L1-050/main.cpp#L32)

## L1-051 打折 （5 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805079364714496)

[C++ (5/5)](https://github.com/Heliovic/GPLT/blob/master/L1-051/main.cpp)

## L1-052 2018我们要赢 （5 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805078400024576)

[C++ (5/5)](https://github.com/Heliovic/GPLT/blob/master/L1-052/main.cpp)

## L1-053 电子汪 （10 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805077443723264)

[C++ (10/10)](https://github.com/Heliovic/GPLT/blob/master/L1-053/main.cpp)

## L1-054 福到了 （15 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805076512587776)

[C++ (15/15)](https://github.com/Heliovic/GPLT/blob/master/L1-054/main.cpp)

## L1-055 谁是赢家 （10 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805075543703552)

[C++ (10/10)](https://github.com/Heliovic/GPLT/blob/master/L1-055/main.cpp)

## L1-056 猜数字 （20 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805074646122496)

[C++ (20/20)](https://github.com/Heliovic/GPLT/blob/master/L1-056/main.cpp)

## L1-057 PTA使我精神焕发 (5 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/1111914599408664576)

[C++ (5/5)](https://github.com/Heliovic/GPLT/blob/master/L1-057/main.cpp)

## L1-058 6翻了 (15 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/1111914599408664577)

[C++ (15/15)](https://github.com/Heliovic/GPLT/blob/master/L1-058/main.cpp)

### 解题思路

string 类的 replace 使用。

## L1-059 敲笨钟 (20 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/1111914599412858880)

[C++ (20/20)](https://github.com/Heliovic/GPLT/blob/master/L1-059/main.cpp)

### 解题思路

string 类的查找替换。

## L1-060 心理阴影面积 (5 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/1111914599412858881)

[C++ (5/5)](https://github.com/Heliovic/GPLT/blob/master/L1-060/main.cpp)

## L1-061 新胖子公式 (10 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/1111914599412858882)

[C++ (10/10)](https://github.com/Heliovic/GPLT/blob/master/L1-061/main.cpp)

## L1-062 幸运彩票 (15 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/1111914599412858883)

[C++ (15/15)](https://github.com/Heliovic/GPLT/blob/master/L1-062/main.cpp)

## L1-063 吃鱼还是吃肉 (10 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/1111914599412858883)

[C++ (15/15)](https://github.com/Heliovic/GPLT/blob/master/L1-062/main.cpp)

## L2-001 紧急救援 （25 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805073643683840)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-001/main.cpp)

### 解题思路

Dijkstra。这里使用 path_num[i] 来记录从起点到 i 有多少条最短路。path_num 的更新逻辑：

```cpp
if (dis[i] > dis[u] + graph[u][i])
{
    // ...
    path_num[i] = path_num[u];
}
else if (dis[i] == dis[u] + graph[u][i])
{
    // ...
    path_num[i] += path_num[u];
}
```

还要注意在 Dijkstra 算法中，若某轮找不到新的 u，说明剩余未访问的点不在与起始点同一个连通分量中，应直接返回： 
https://github.com/Heliovic/GPLT/blob/master/L2-001/main.cpp#L62 

此题还可以使用 Dijkstra + DFS。使用 ```vector<int> path[MAX_N]``` 记录所有前驱后 DFS 获得所有路径。

## L2-002 链表去重 （25 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805072641245184)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-002/main.cpp)

### 解题思路

散列打表，链表操作。

## L2-003 月饼 （25 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805071789801472)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-003/main.cpp)

### 解题思路

贪心方法。

## L2-004 这是二叉搜索树吗？ （25 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805070971912192)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-004/main.cpp)

### 解题思路

二叉树的构建、遍历。

## L2-005 集合相似度 （25 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805070149828608)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-005/main.cpp)

### 解题思路

STL set 的使用。注意，若使用如下代码读取 set 会附加拷贝的时间，导致超时：

```cpp
set<int> s1, s2;
s1 = sts[t1];
s2 = sts[t2];
```

正确的做法是，使用指针:

```cpp
set<int> *s1, *s2;
s1 = &sts[t1];
s2 = &sts[t2];
```

## L2-006 树的遍历 （25 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805069361299456)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-006/main.cpp)

### 解题思路

二叉树重建。

## L2-007 家庭房产 （25 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805068539215872)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-007/main.cpp)

### 解题思路

BFS。

## L2-008 最长对称子串 （25 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805067704549376)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-008/main.cpp)

### 解题思路

动态规划求最长对称子串。

## L2-009 抢红包 （25 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805066890854400)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-009/main.cpp)

### 解题思路

简单模拟。

## L2-010 排座位 （25 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805066135879680)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-010/main.cpp)

### 解题思路

并查集。

## L2-011 玩转二叉树 （25 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805065406070784)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-011/main.cpp)

### 解题思路

二叉树重建、镜像遍历。

## L2-012 关于堆的判断 （25 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805064676261888)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-012/main.cpp)

### 解题思路

堆的插入、堆的性质。

## L2-013 红色警报 （25 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805063963230208)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-013/main.cpp)

### 解题思路

DFS 求联通分量数。

## L2-014 列车调度 （25 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805063166312448)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-014/main.cpp)

### 解题思路

模拟 + 二分查找。

## L2-015 互评成绩 （25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805062432309248)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-015/main.cpp)

## L2-016 愿天下有情人都是失散多年的兄妹 （25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805061769609216)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-016/main.cpp)

### 解题思路

DFS。

## L2-017 人以群分 （25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805061056577536)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-017/main.cpp)

## L2-018 多项式A除以B （25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805060372905984)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-018/main.cpp)

### 解题思路

模拟。

## L2-019 悄悄关注 （25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805059731177472)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-019/main.cpp)

### 解题思路

STL set、map 的基本操作。

## L2-020 功夫传人 （25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805059118809088)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-020/main.cpp)

### 解题思路

DFS。

## L2-021 点赞狂魔 （25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805058485469184)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-021/main.cpp)

### 解题思路

STL set 的使用。

## L2-022 重排链表 （25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805057860517888)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-022/main.cpp)

### 解题思路

注意，题中所给的节点可能不属于链表内的节点。

## L2-023 图着色问题 （25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805057298481152)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-023/main.cpp)

### 解题思路

暴力遍历所有边。

## L2-024 部落 （25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805056736444416)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-024/main.cpp)

### 解题思路

并查集。

## L2-025 分而治之 （25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805056195379200)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-025/main.cpp)

### 解题思路

利用图中顶点的度求解。

## L2-026 小字辈 （25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805055679479808)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-026/main.cpp)

### 解题思路

树的 BFS。

## L2-027 名人堂与代金券 （25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805055176163328)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-027/main.cpp)

### 解题思路

结构体排序。

## L2-028 秀恩爱分得快 （25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805054698012672)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-028/main.cpp)

### 解题思路

不该算的不算。

## L2-029 特立独行的幸福 (25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/1111914599412858886)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-029/main.cpp)

## L2-030 冰岛人 (25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/1111914599412858887)

[C++ (22/25)](https://github.com/Heliovic/GPLT/blob/master/L2-030/main.cpp)

## L2-031 深入虎穴 (25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/1111914599412858888)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-031/main.cpp)

### 解题思路

BFS。

## L2-032 彩虹瓶 (25 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/1111914599412858889)

[C++ (25/25)](https://github.com/Heliovic/GPLT/blob/master/L2-032/main.cpp)

### 解题思路

模拟。

## L3-001 凑零钱 （30 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805054207279104)

[C++ (30/30)](https://github.com/Heliovic/GPLT/blob/master/L3-001/main.cpp)

### 解题思路

0-1背包问题，动态规划。

## L3-002 特殊堆栈 （30 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805053695574016)

[C++ (30/30)](https://github.com/Heliovic/GPLT/blob/master/L3-002/main.cpp)

### 解题思路

用 vector 模拟堆栈、二分查找。

## L3-003 社交集群 （30 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805053141925888)

[C++ (30/30)](https://github.com/Heliovic/GPLT/blob/master/L3-003/main.cpp)

### 解题思路

并查集。

## L3-004 肿瘤诊断 （30 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805052626026496)

[C++ (30/30)](https://github.com/Heliovic/GPLT/blob/master/L3-004/main.cpp)

### 解题思路

BFS。

## L3-005 垃圾箱分布 （30 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805052131098624)

[C++ (30/30)](https://github.com/Heliovic/GPLT/blob/master/L3-005/main.cpp)

### 解题思路

Dijkstra。

## L3-007 天梯地图 （30 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805051153825792)

[C++ (30/30)](https://github.com/Heliovic/GPLT/blob/master/L3-007/main.cpp)

### 解题思路

Dijkstra + DFS。~~【测试点 4】答案错误~~ 错误原因纯属手滑。

## L3-008 喊山 （30 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805050709229568)

[C++ (30/30)](https://github.com/Heliovic/GPLT/blob/master/L3-008/main.cpp)

### 解题思路

BFS。注意，若图论问题需要求关于层级的解，DFS 可能会导致最小层数错误，求层级时最好使用 BFS。

## L3-009 长城 （30 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805050277216256)

[C++ (30/30)](https://github.com/Heliovic/GPLT/blob/master/L3-009/main.cpp)

### 解题思路

使用 [Graham](https://github.com/Heliovic/AlgorithmSet/blob/master/Graham/main.cpp) 算法求凸包，记录那些在求凸包过程中三个点向左拐的中间“凸点”，这些点就是所求点。好题。

## L3-010 是否完全二叉搜索树 （30 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805049870368768)

[C++ (30/30)](https://github.com/Heliovic/GPLT/blob/master/L3-010/main.cpp)

### 解题思路

静态树的构建，使用左2n，右2n+1的结构，最终判断是否时完全二叉树。

## L3-011 直捣黄龙 （30 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805049455132672)

[C++ (30/30)](https://github.com/Heliovic/GPLT/blob/master/L3-011/main.cpp)

### 解题思路

Dijkstra + DFS。

## L3-012 水果忍者 （30 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805049102811136)

[C++ (30/30)](https://github.com/Heliovic/GPLT/blob/master/L3-012/main.cpp)

### 解题思路

先对所有水果的上顶点求下凸包，再对所有水果下顶点求上凸包。

显然，在上顶点的凸包上取任意两个相邻点连接形成的直线必在所有上顶点之下。因此，只需遍历这些上顶点的下凸包上相邻点形成的直线，检查是否所有水果的下顶点都在这条直线之下，若是，则这条直线就是所求。

若遍历完之后未找到这样的相邻点，则在下顶点的上凸包上遍历相邻点形成的直线，检查是否所有水果的上顶点在这条直线的上面，若是，则这条直线就是所求。

注意特判 [N = 1](https://github.com/Heliovic/GPLT/blob/master/L3-012/main.cpp#L132)。

**注意使用整形/长整型时求斜率应转为 double，注意在某个数的正负不确定的情况下，不等式两端不可随意乘以这个数！。**

好题！

## L3-013 非常弹的球 （30 分）

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805048788238336)

[C++ (30/30)](https://github.com/Heliovic/GPLT/blob/master/L3-013/main.cpp)

### 解题思路

数学模拟，注意求极限写法：

```cpp
while (E > 1e-10)
{
    E *= dp;
    x += (2 * E) / (m * g);
}
```

## L3-014 周游世界 （30 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805048482054144)

[C++ (30/30)](https://github.com/Heliovic/GPLT/blob/master/L3-014/main.cpp)

### 解题思路

Dijkstra + DFS。

~~【测试点 5】运行超时。~~ 使用 [priority_queue](https://github.com/Heliovic/AlgorithmSet/blob/master/Dijkstra_priority_queue/main.cpp) 加速 Dijkstra。

## L3-015 球队“食物链” （30 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805048175869952)

[C++ (30/30)](https://github.com/Heliovic/GPLT/blob/master/L3-015/main.cpp)

### 解题思路

DFS + 剪枝。

注意 [此处](https://github.com/Heliovic/GPLT/blob/master/L3-015/main.cpp#L30) 的剪枝策略。若剩余未访问的节点都不存在到起始节点的边，说明最后无法形成有向环，直接回溯。

## L3-016 二叉搜索树的结构 （30 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805047903240192)

[C++ (30/30)](https://github.com/Heliovic/GPLT/blob/master/L3-016/main.cpp)

### 解题思路

[streamstring](https://github.com/Heliovic/GPLT/blob/master/L3-016/main.cpp#L190) 格式化处理字符串，同sprintf、sscanf。字符串处理时有类似于正则表达式的作用，**非常重要！！！考前必看！！！**

每次使用 streamstring 前先[清空](https://github.com/Heliovic/GPLT/blob/master/L3-016/main.cpp#L142)，防止出错找不到原因。

## L3-017 森森快递 （30 分)

[Problem description](https://pintia.cn/problem-sets/994805046380707840/problems/994805047638999040)

[C++ (17/30)](https://github.com/Heliovic/GPLT/blob/master/L3-017/main.cpp)

### 解题思路

贪心 + 树状数组/线段树。

未通过后三个测试点，再说吧。
