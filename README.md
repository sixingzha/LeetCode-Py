# 算法通关手册（LeetCode）

- 作者：ITCharge
- 公众号：程序员充电站
- 版本：1.0 beta

> 一本面向有 Python 编程基础，但缺乏算法知识、刷题经验的教科书和工具书。

## 关于本书

笔者其实在大学期间就有在 OJ 系统上刷题写题解的习惯。但是毕业工作之后，日常忙于开发需求和业务逻辑，基本上就没再接触算法和刷题了。但是我心里一直有一个想法，就是把自己学到的算法知识和刷题经验整合起来，分享给大家，和大家交流一下算法知识和做题心得。一方面可以帮助大家学习算法，另一方面也有助于自己更深层次的理解算法。

这本书不仅仅只是一本算法题解书，更是一本算法基础知识的讲解书。我打算从基础的数据结构和基础的算法开始讲解，然后再进行具体题目讲解。让大家从理论到实际刷题，双方面的掌握算法知识。

## 关于作者

我是一名 iOS / macOS 的开发程序员，另外也是北航软院的一名非全硕士（在读）。曾在大学期间参加过 3 年的 ACM 比赛， 但水平有限，未能取得很好的成绩。但是 3 年的 ACM 经历，给我最大的收获是训练了自己的逻辑思维和解决实际问题的能力，这种能力为我今后的工作、学习打下了坚实的基础。

我从 2021 年 03 月 30 日开始每日在 LeetCode 刷题，到 2021 年 09 月 08 日已经刷了 430+ 道题目，并且完成了 370+ 道题解。努力向着 500+、1000+、1500+ 道题前进。

## 内容章节

- [绪论](https://github.com/itcharge/LeetCode-Py/blob/main/Contents/Chapter-01/index.md)
  - [算法与数据结构](https://github.com/itcharge/LeetCode-Py/blob/main/Contents/Chapter-01/01-Data-Structures-Algorithms.md)
  - 算法复杂度
  - [LeetCode 入门与攻略](https://github.com/itcharge/LeetCode-Py/blob/main/Contents/Chapter-01/03-LeetCode-Guide.md)
- 数组

  - 数组简介
  - 排序算法
    - 冒泡排序
    - 选择排序
    - 插入排序
    - 计数排序
    - 堆排序
    - 快速排序
    - 谢尔排序
    - 桶排序
  - 查找
    - 线性查找
    - 二分查找
    - 三分查找
  - 双指针
  - 滑动窗口
  - 树状数组
- 栈和队列

  - 栈和深度优先搜索
  - 队列和宽度优先搜索
- 链表
  - 元素处理
  - 排序
  - 查找
- 字符串

  -  单模式串匹配

     - BF 算法
     - BM 算法
     - KMP 算法
     - RK 算法
     - Sunday 算法

  -  多模式串匹配

     - 字典树

     - AC 自动机
- 树

  - 二叉树
  - 二叉搜索树
  - 线段树
  - 并查集
- 哈希表
- 图

  - 图的简介与存储方式
  - 拓扑排序
  - 欧拉路径
  - 哈密顿路径
  - 生成树
    - 最小生成树
    - 次小生成树
    - 最小树形图
  - 单源最短路
  - 多源最短路径
  - K 短路径
  - 差分约束系统
  - 强连通分量
  - 双联通分量
  - LCA
  - 二分图
  - 网络流
- 基础算法

  - 位运算
  - 枚举算法
  - 递归算法
  - 贪心算法
  - 分治算法
  - 回溯算法
  - 动态规划
- LeetCode 题解

---

## LeetCode 题解（已完成 379 道）
 | 题号 | 标题 | 题解 | 标签 | 难度 |
| :------ | :------ | :------ | :------ | :------ |
| 0001 | [两数之和](https://leetcode-cn.com/problems/two-sum/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0001.%20%E4%B8%A4%E6%95%B0%E4%B9%8B%E5%92%8C.md) | 数组、哈希表 | 简单 |
| 0002 | [两数相加](https://leetcode-cn.com/problems/add-two-numbers/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0002.%20%E4%B8%A4%E6%95%B0%E7%9B%B8%E5%8A%A0.md) | 递归、链表、数学 | 中等 |
| 0003 | [无重复字符的最长子串](https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0003.%20%E6%97%A0%E9%87%8D%E5%A4%8D%E5%AD%97%E7%AC%A6%E7%9A%84%E6%9C%80%E9%95%BF%E5%AD%90%E4%B8%B2.md) | 字符串、哈希表、双指针、字符串、滑动窗口 | 中等 |
| 0004 | [寻找两个正序数组的中位数](https://leetcode-cn.com/problems/median-of-two-sorted-arrays/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0004.%20%E5%AF%BB%E6%89%BE%E4%B8%A4%E4%B8%AA%E6%AD%A3%E5%BA%8F%E6%95%B0%E7%BB%84%E7%9A%84%E4%B8%AD%E4%BD%8D%E6%95%B0.md) | 数组、二分查找、分治算法 | 困难 |
| 0005 | [最长回文子串](https://leetcode-cn.com/problems/longest-palindromic-substring/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0005.%20%E6%9C%80%E9%95%BF%E5%9B%9E%E6%96%87%E5%AD%90%E4%B8%B2.md) | 字符串、动态规划 | 中等 |
| 0007 | [整数反转](https://leetcode-cn.com/problems/reverse-integer/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0007.%20%E6%95%B4%E6%95%B0%E5%8F%8D%E8%BD%AC.md) | 数学 | 简单 |
| 0008 | [字符串转换整数 (atoi)](https://leetcode-cn.com/problems/string-to-integer-atoi/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0008.%20%E5%AD%97%E7%AC%A6%E4%B8%B2%E8%BD%AC%E6%8D%A2%E6%95%B4%E6%95%B0%20%28atoi%29.md) | 数学、字符串 | 中等 |
| 0009 | [回文数](https://leetcode-cn.com/problems/palindrome-number/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0009.%20%E5%9B%9E%E6%96%87%E6%95%B0.md) | 数学 | 简单 |
| 0011 | [盛最多水的容器](https://leetcode-cn.com/problems/container-with-most-water/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0011.%20%E7%9B%9B%E6%9C%80%E5%A4%9A%E6%B0%B4%E7%9A%84%E5%AE%B9%E5%99%A8.md) | 贪心、数组、双指针 | 中等 |
| 0012 | [整数转罗马数字](https://leetcode-cn.com/problems/integer-to-roman/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0012.%20%E6%95%B4%E6%95%B0%E8%BD%AC%E7%BD%97%E9%A9%AC%E6%95%B0%E5%AD%97.md) | 数学、字符串 | 中等 |
| 0013 | [罗马数字转整数](https://leetcode-cn.com/problems/roman-to-integer/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0013.%20%E7%BD%97%E9%A9%AC%E6%95%B0%E5%AD%97%E8%BD%AC%E6%95%B4%E6%95%B0.md) | 数学、字符串 | 简单 |
| 0014 | [最长公共前缀](https://leetcode-cn.com/problems/longest-common-prefix/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0014.%20%E6%9C%80%E9%95%BF%E5%85%AC%E5%85%B1%E5%89%8D%E7%BC%80.md) | 字符串 | 简单 |
| 0015 | [三数之和](https://leetcode-cn.com/problems/3sum/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0015.%20%E4%B8%89%E6%95%B0%E4%B9%8B%E5%92%8C.md) | 数组、双指针 | 中等 |
| 0017 | [电话号码的字母组合](https://leetcode-cn.com/problems/letter-combinations-of-a-phone-number/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0017.%20%E7%94%B5%E8%AF%9D%E5%8F%B7%E7%A0%81%E7%9A%84%E5%AD%97%E6%AF%8D%E7%BB%84%E5%90%88.md) | 深度优先搜索、递归、字符串、回溯算法 | 中等 |
| 0018 | [四数之和](https://leetcode-cn.com/problems/4sum/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0018.%20%E5%9B%9B%E6%95%B0%E4%B9%8B%E5%92%8C.md) | 数组、哈希表、双指针 | 中等 |
| 0019 | [删除链表的倒数第 N 个结点](https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0019.%20%E5%88%A0%E9%99%A4%E9%93%BE%E8%A1%A8%E7%9A%84%E5%80%92%E6%95%B0%E7%AC%AC%20N%20%E4%B8%AA%E7%BB%93%E7%82%B9.md) | 链表、双指针 | 中等 |
| 0020 | [有效的括号](https://leetcode-cn.com/problems/valid-parentheses/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0020.%20%E6%9C%89%E6%95%88%E7%9A%84%E6%8B%AC%E5%8F%B7.md) | 栈、字符串 | 简单 |
| 0021 | [合并两个有序链表](https://leetcode-cn.com/problems/merge-two-sorted-lists/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0021.%20%E5%90%88%E5%B9%B6%E4%B8%A4%E4%B8%AA%E6%9C%89%E5%BA%8F%E9%93%BE%E8%A1%A8.md) | 递归、链表 | 简单 |
| 0022 | [括号生成](https://leetcode-cn.com/problems/generate-parentheses/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0022.%20%E6%8B%AC%E5%8F%B7%E7%94%9F%E6%88%90.md) | 字符串、回溯算法 | 中等 |
| 0023 | [合并K个升序链表](https://leetcode-cn.com/problems/merge-k-sorted-lists/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0023.%20%E5%90%88%E5%B9%B6K%E4%B8%AA%E5%8D%87%E5%BA%8F%E9%93%BE%E8%A1%A8.md) | 链表、分治、堆（优先队列）、归并排序 | 简单 |
| 0024 | [两两交换链表中的节点](https://leetcode-cn.com/problems/swap-nodes-in-pairs/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0024.%20%E4%B8%A4%E4%B8%A4%E4%BA%A4%E6%8D%A2%E9%93%BE%E8%A1%A8%E4%B8%AD%E7%9A%84%E8%8A%82%E7%82%B9.md) | 递归、链表 | 中等 |
| 0026 | [删除有序数组中的重复项](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-array/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0026.%20%E5%88%A0%E9%99%A4%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84%E4%B8%AD%E7%9A%84%E9%87%8D%E5%A4%8D%E9%A1%B9.md) | 数组、双指针 | 简单 |
| 0027 | [移除元素](https://leetcode-cn.com/problems/remove-element/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0027.%20%E7%A7%BB%E9%99%A4%E5%85%83%E7%B4%A0.md) | 数组、双指针 | 简单 |
| 0028 | [实现 strStr()](https://leetcode-cn.com/problems/implement-strstr/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0028.%20%E5%AE%9E%E7%8E%B0%20strStr%28%29.md) | 字符串、双指针 | 简单 |
| 0029 | [两数相除](https://leetcode-cn.com/problems/divide-two-integers/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0029.%20%E4%B8%A4%E6%95%B0%E7%9B%B8%E9%99%A4.md) | 数学、二分查找 | 中等 |
| 0033 | [搜索旋转排序数组](https://leetcode-cn.com/problems/search-in-rotated-sorted-array/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0033.%20%E6%90%9C%E7%B4%A2%E6%97%8B%E8%BD%AC%E6%8E%92%E5%BA%8F%E6%95%B0%E7%BB%84.md) | 数组、二分查找 | 中等 |
| 0034 | [在排序数组中查找元素的第一个和最后一个位置](https://leetcode-cn.com/problems/find-first-and-last-position-of-element-in-sorted-array/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0034.%20%E5%9C%A8%E6%8E%92%E5%BA%8F%E6%95%B0%E7%BB%84%E4%B8%AD%E6%9F%A5%E6%89%BE%E5%85%83%E7%B4%A0%E7%9A%84%E7%AC%AC%E4%B8%80%E4%B8%AA%E5%92%8C%E6%9C%80%E5%90%8E%E4%B8%80%E4%B8%AA%E4%BD%8D%E7%BD%AE.md) | 数组、二分查找 | 中等 |
| 0035 | [搜索插入位置](https://leetcode-cn.com/problems/search-insert-position/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0035.%20%E6%90%9C%E7%B4%A2%E6%8F%92%E5%85%A5%E4%BD%8D%E7%BD%AE.md) | 数组、二分查找 | 简单 |
| 0036 | [有效的数独](https://leetcode-cn.com/problems/valid-sudoku/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0036.%20%E6%9C%89%E6%95%88%E7%9A%84%E6%95%B0%E7%8B%AC.md) | 哈希表 | 中等 |
| 0037 | [解数独](https://leetcode-cn.com/problems/sudoku-solver/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0037.%20%E8%A7%A3%E6%95%B0%E7%8B%AC.md) | 数组、回溯、矩阵 | 困难 |
| 0038 | [外观数列](https://leetcode-cn.com/problems/count-and-say/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0038.%20%E5%A4%96%E8%A7%82%E6%95%B0%E5%88%97.md) | 字符串 | 简单 |
| 0039 | [组合总和](https://leetcode-cn.com/problems/combination-sum/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0039.%20%E7%BB%84%E5%90%88%E6%80%BB%E5%92%8C.md) | 数组、回溯 | 中等 |
| 0040 | [组合总和 II](https://leetcode-cn.com/problems/combination-sum-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0040.%20%E7%BB%84%E5%90%88%E6%80%BB%E5%92%8C%20II.md) | 数组、回溯 | 中等 |
| 0045 | [跳跃游戏 II](https://leetcode-cn.com/problems/jump-game-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0045.%20%E8%B7%B3%E8%B7%83%E6%B8%B8%E6%88%8F%20II.md) | 贪心、数组、动态规划 | 中等 |
| 0046 | [全排列](https://leetcode-cn.com/problems/permutations/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0046.%20%E5%85%A8%E6%8E%92%E5%88%97.md) | 回溯算法 | 中等 |
| 0047 | [全排列 II](https://leetcode-cn.com/problems/permutations-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0047.%20%E5%85%A8%E6%8E%92%E5%88%97%20II.md) | 数组、回溯 | 中等 |
| 0048 | [旋转图像](https://leetcode-cn.com/problems/rotate-image/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0048.%20%E6%97%8B%E8%BD%AC%E5%9B%BE%E5%83%8F.md) | 数组 | 中等 |
| 0049 | [字母异位词分组](https://leetcode-cn.com/problems/group-anagrams/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0049.%20%E5%AD%97%E6%AF%8D%E5%BC%82%E4%BD%8D%E8%AF%8D%E5%88%86%E7%BB%84.md) | 字符串、哈希表 | 中等 |
| 0050 | [Pow(x, n)](https://leetcode-cn.com/problems/powx-n/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0050.%20Pow%28x%2C%20n%29.md) | 数学、二分查找 | 中等 |
| 0051 | [N 皇后](https://leetcode-cn.com/problems/n-queens/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0051.%20N%20%E7%9A%87%E5%90%8E.md) | 数组、回溯 | 困难 |
| 0053 | [最大子序和](https://leetcode-cn.com/problems/maximum-subarray/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0053.%20%E6%9C%80%E5%A4%A7%E5%AD%90%E5%BA%8F%E5%92%8C.md) | 数组、分治算法、动态规划 | 简单 |
| 0054 | [螺旋矩阵](https://leetcode-cn.com/problems/spiral-matrix/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0054.%20%E8%9E%BA%E6%97%8B%E7%9F%A9%E9%98%B5.md) | 数组 | 中等 |
| 0055 | [跳跃游戏](https://leetcode-cn.com/problems/jump-game/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0055.%20%E8%B7%B3%E8%B7%83%E6%B8%B8%E6%88%8F.md) | 贪心算法、数组、动态规划 | 中等 |
| 0056 | [合并区间](https://leetcode-cn.com/problems/merge-intervals/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0056.%20%E5%90%88%E5%B9%B6%E5%8C%BA%E9%97%B4.md) | 数组、排序 | 中等 |
| 0058 | [最后一个单词的长度](https://leetcode-cn.com/problems/length-of-last-word/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0058.%20%E6%9C%80%E5%90%8E%E4%B8%80%E4%B8%AA%E5%8D%95%E8%AF%8D%E7%9A%84%E9%95%BF%E5%BA%A6.md) | 字符串 | 简单 |
| 0061 | [旋转链表](https://leetcode-cn.com/problems/rotate-list/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0061.%20%E6%97%8B%E8%BD%AC%E9%93%BE%E8%A1%A8.md) | 链表、双指针 | 中等 |
| 0062 | [不同路径](https://leetcode-cn.com/problems/unique-paths/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0062.%20%E4%B8%8D%E5%90%8C%E8%B7%AF%E5%BE%84.md) | 数组、动态规划 | 中等 |
| 0063 | [不同路径 II](https://leetcode-cn.com/problems/unique-paths-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0063.%20%E4%B8%8D%E5%90%8C%E8%B7%AF%E5%BE%84%20II.md) | 数组、动态规划、矩阵 | 中等 |
| 0066 | [加一](https://leetcode-cn.com/problems/plus-one/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0066.%20%E5%8A%A0%E4%B8%80.md) | 数组 | 简单 |
| 0067 | [二进制求和](https://leetcode-cn.com/problems/add-binary/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0067.%20%E4%BA%8C%E8%BF%9B%E5%88%B6%E6%B1%82%E5%92%8C.md) | 数学、字符串、位运算 | 简单 |
| 0069 | [x 的平方根](https://leetcode-cn.com/problems/sqrtx/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0069.%20x%20%E7%9A%84%E5%B9%B3%E6%96%B9%E6%A0%B9.md) | 数学、二分查找 | 简单 |
| 0070 | [爬楼梯](https://leetcode-cn.com/problems/climbing-stairs/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0070.%20%E7%88%AC%E6%A5%BC%E6%A2%AF.md) | 动态规划 | 简单 |
| 0072 | [编辑距离](https://leetcode-cn.com/problems/edit-distance/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0072.%20%E7%BC%96%E8%BE%91%E8%B7%9D%E7%A6%BB.md) | 字符串、动态规划 | 困难 |
| 0073 | [矩阵置零](https://leetcode-cn.com/problems/set-matrix-zeroes/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0073.%20%E7%9F%A9%E9%98%B5%E7%BD%AE%E9%9B%B6.md) | 数组 | 中等 |
| 0075 | [颜色分类](https://leetcode-cn.com/problems/sort-colors/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0075.%20%E9%A2%9C%E8%89%B2%E5%88%86%E7%B1%BB.md) | 数组、排序、双指针 | 中等 |
| 0076 | [最小覆盖子串](https://leetcode-cn.com/problems/minimum-window-substring/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0076.%20%E6%9C%80%E5%B0%8F%E8%A6%86%E7%9B%96%E5%AD%90%E4%B8%B2.md) | 哈希表、字符串、滑动窗口 | 困难 |
| 0077 | [组合](https://leetcode-cn.com/problems/combinations/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0077.%20%E7%BB%84%E5%90%88.md) | 数组、回溯 | 中等 |
| 0078 | [子集](https://leetcode-cn.com/problems/subsets/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0078.%20%E5%AD%90%E9%9B%86.md) | 位运算、数组、回溯算法 | 中等 |
| 0079 | [单词搜索](https://leetcode-cn.com/problems/word-search/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0079.%20%E5%8D%95%E8%AF%8D%E6%90%9C%E7%B4%A2.md) | 数组、回溯算法 | 中等 |
| 0080 | [删除有序数组中的重复项 II](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-array-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0080.%20%E5%88%A0%E9%99%A4%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84%E4%B8%AD%E7%9A%84%E9%87%8D%E5%A4%8D%E9%A1%B9%20II.md) | 数组、双指针 | 中等 |
| 0081 | [搜索旋转排序数组 II](https://leetcode-cn.com/problems/search-in-rotated-sorted-array-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0081.%20%E6%90%9C%E7%B4%A2%E6%97%8B%E8%BD%AC%E6%8E%92%E5%BA%8F%E6%95%B0%E7%BB%84%20II.md) | 数组、二分查找 | 中等 |
| 0083 | [删除排序链表中的重复元素](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-list/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0083.%20%E5%88%A0%E9%99%A4%E6%8E%92%E5%BA%8F%E9%93%BE%E8%A1%A8%E4%B8%AD%E7%9A%84%E9%87%8D%E5%A4%8D%E5%85%83%E7%B4%A0.md) | 链表 | 简单 |
| 0088 | [合并两个有序数组](https://leetcode-cn.com/problems/merge-sorted-array/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0088.%20%E5%90%88%E5%B9%B6%E4%B8%A4%E4%B8%AA%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84.md) | 数组、双指针 | 简单 |
| 0089 | [格雷编码](https://leetcode-cn.com/problems/gray-code/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0089.%20%E6%A0%BC%E9%9B%B7%E7%BC%96%E7%A0%81.md) | 位运算、数学、回溯 | 中等 |
| 0091 | [解码方法](https://leetcode-cn.com/problems/decode-ways/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0091.%20%E8%A7%A3%E7%A0%81%E6%96%B9%E6%B3%95.md) | 字符串、动态规划 | 中等 |
| 0093 | [复原 IP 地址](https://leetcode-cn.com/problems/restore-ip-addresses/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0093.%20%E5%A4%8D%E5%8E%9F%20IP%20%E5%9C%B0%E5%9D%80.md) | 字符串、回溯 | 中等 |
| 0094 | [二叉树的中序遍历](https://leetcode-cn.com/problems/binary-tree-inorder-traversal/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0094.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E4%B8%AD%E5%BA%8F%E9%81%8D%E5%8E%86.md) | 栈、树、哈希表 | 简单 |
| 0095 | [不同的二叉搜索树 II](https://leetcode-cn.com/problems/unique-binary-search-trees-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0095.%20%E4%B8%8D%E5%90%8C%E7%9A%84%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%20II.md) | 树、二叉搜索树、动态规划、回溯、二叉树 | 中等 |
| 0096 | [不同的二叉搜索树](https://leetcode-cn.com/problems/unique-binary-search-trees/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0096.%20%E4%B8%8D%E5%90%8C%E7%9A%84%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91.md) | 树、二叉搜索树、数学、动态规划、二叉树 | 中等 |
| 0098 | [验证二叉搜索树](https://leetcode-cn.com/problems/validate-binary-search-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0098.%20%E9%AA%8C%E8%AF%81%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91.md) | 树、深度优先搜索、递归 | 中等 |
| 0100 | [相同的树](https://leetcode-cn.com/problems/same-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0100.%20%E7%9B%B8%E5%90%8C%E7%9A%84%E6%A0%91.md) | 树、深度优先搜索 | 简单 |
| 0101 | [对称二叉树](https://leetcode-cn.com/problems/symmetric-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0101.%20%E5%AF%B9%E7%A7%B0%E4%BA%8C%E5%8F%89%E6%A0%91.md) | 树、深度优先搜索、广度优先搜索 | 简单 |
| 0102 | [二叉树的层序遍历](https://leetcode-cn.com/problems/binary-tree-level-order-traversal/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0102.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E5%B1%82%E5%BA%8F%E9%81%8D%E5%8E%86.md) | 树、广度优先搜索 | 中等 |
| 0103 | [二叉树的锯齿形层序遍历](https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0103.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E9%94%AF%E9%BD%BF%E5%BD%A2%E5%B1%82%E5%BA%8F%E9%81%8D%E5%8E%86.md) |   | 简单 |
| 0104 | [二叉树的最大深度](https://leetcode-cn.com/problems/maximum-depth-of-binary-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0104.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E6%9C%80%E5%A4%A7%E6%B7%B1%E5%BA%A6.md) | 树、深度优先搜索、递归 | 简单 |
| 0105 | [从前序与中序遍历序列构造二叉树](https://leetcode-cn.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0105.%20%E4%BB%8E%E5%89%8D%E5%BA%8F%E4%B8%8E%E4%B8%AD%E5%BA%8F%E9%81%8D%E5%8E%86%E5%BA%8F%E5%88%97%E6%9E%84%E9%80%A0%E4%BA%8C%E5%8F%89%E6%A0%91.md) | 树、数组、哈希表、分治、二叉树 | 中等 |
| 0106 | [从中序与后序遍历序列构造二叉树](https://leetcode-cn.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0106.%20%E4%BB%8E%E4%B8%AD%E5%BA%8F%E4%B8%8E%E5%90%8E%E5%BA%8F%E9%81%8D%E5%8E%86%E5%BA%8F%E5%88%97%E6%9E%84%E9%80%A0%E4%BA%8C%E5%8F%89%E6%A0%91.md) | 树、数组、哈希表、分治、二叉树 | 中等 |
| 0107 | [二叉树的层序遍历 II](https://leetcode-cn.com/problems/binary-tree-level-order-traversal-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0107.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E5%B1%82%E5%BA%8F%E9%81%8D%E5%8E%86%20II.md) | 树、广度优先搜索 | 中等 |
| 0108 | [将有序数组转换为二叉搜索树](https://leetcode-cn.com/problems/convert-sorted-array-to-binary-search-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0108.%20%E5%B0%86%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84%E8%BD%AC%E6%8D%A2%E4%B8%BA%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91.md) | 树、深度优先搜索 | 简单 |
| 0110 | [平衡二叉树](https://leetcode-cn.com/problems/balanced-binary-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0110.%20%E5%B9%B3%E8%A1%A1%E4%BA%8C%E5%8F%89%E6%A0%91.md) | 树、深度优先搜索、递归 | 简单 |
| 0111 | [二叉树的最小深度](https://leetcode-cn.com/problems/minimum-depth-of-binary-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0111.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E6%9C%80%E5%B0%8F%E6%B7%B1%E5%BA%A6.md) | 树、深度优先搜索、广度优先搜索 | 简单 |
| 0112 | [路径总和](https://leetcode-cn.com/problems/path-sum/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0112.%20%E8%B7%AF%E5%BE%84%E6%80%BB%E5%92%8C.md) | 树、深度优先搜索 | 简单 |
| 0113 | [路径总和 II](https://leetcode-cn.com/problems/path-sum-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0113.%20%E8%B7%AF%E5%BE%84%E6%80%BB%E5%92%8C%20II.md) | 树、深度优先搜索、回溯、二叉树 | 中等 |
| 0115 | [不同的子序列](https://leetcode-cn.com/problems/distinct-subsequences/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0115.%20%E4%B8%8D%E5%90%8C%E7%9A%84%E5%AD%90%E5%BA%8F%E5%88%97.md) | 字符串、动态规划 | 困难 |
| 0116 | [填充每个节点的下一个右侧节点指针](https://leetcode-cn.com/problems/populating-next-right-pointers-in-each-node/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0116.%20%E5%A1%AB%E5%85%85%E6%AF%8F%E4%B8%AA%E8%8A%82%E7%82%B9%E7%9A%84%E4%B8%8B%E4%B8%80%E4%B8%AA%E5%8F%B3%E4%BE%A7%E8%8A%82%E7%82%B9%E6%8C%87%E9%92%88.md) | 树、深度优先搜索、广度优先搜索 | 中等 |
| 0117 | [填充每个节点的下一个右侧节点指针 II](https://leetcode-cn.com/problems/populating-next-right-pointers-in-each-node-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0117.%20%E5%A1%AB%E5%85%85%E6%AF%8F%E4%B8%AA%E8%8A%82%E7%82%B9%E7%9A%84%E4%B8%8B%E4%B8%80%E4%B8%AA%E5%8F%B3%E4%BE%A7%E8%8A%82%E7%82%B9%E6%8C%87%E9%92%88%20II.md) | 树、深度优先遍历 | 中等 |
| 0118 | [杨辉三角](https://leetcode-cn.com/problems/pascals-triangle/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0118.%20%E6%9D%A8%E8%BE%89%E4%B8%89%E8%A7%92.md) | 数组 | 简单 |
| 0119 | [杨辉三角 II](https://leetcode-cn.com/problems/pascals-triangle-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0119.%20%E6%9D%A8%E8%BE%89%E4%B8%89%E8%A7%92%20II.md) | 数组 | 简单 |
| 0121 | [买卖股票的最佳时机](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0121.%20%E4%B9%B0%E5%8D%96%E8%82%A1%E7%A5%A8%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA.md) | 数组、动态规划 | 简单 |
| 0122 | [买卖股票的最佳时机 II](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0122.%20%E4%B9%B0%E5%8D%96%E8%82%A1%E7%A5%A8%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA%20II.md) | 数组、贪心算法 | 简单 |
| 0123 | [买卖股票的最佳时机 III](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-iii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0123.%20%E4%B9%B0%E5%8D%96%E8%82%A1%E7%A5%A8%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA%20III.md) | 数组、动态规划 | 困难 |
| 0124 | [二叉树中的最大路径和](https://leetcode-cn.com/problems/binary-tree-maximum-path-sum/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0124.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E4%B8%AD%E7%9A%84%E6%9C%80%E5%A4%A7%E8%B7%AF%E5%BE%84%E5%92%8C.md) | 树、深度优先搜索、动态规划、二叉树 | 困难 |
| 0125 | [验证回文串](https://leetcode-cn.com/problems/valid-palindrome/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0125.%20%E9%AA%8C%E8%AF%81%E5%9B%9E%E6%96%87%E4%B8%B2.md) | 字符串、双指针 | 简单 |
| 0127 | [单词接龙](https://leetcode-cn.com/problems/word-ladder/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0127.%20%E5%8D%95%E8%AF%8D%E6%8E%A5%E9%BE%99.md) | 广度优先搜索、哈希表、字符串 | 困难 |
| 0130 | [被围绕的区域](https://leetcode-cn.com/problems/surrounded-regions/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0130.%20%E8%A2%AB%E5%9B%B4%E7%BB%95%E7%9A%84%E5%8C%BA%E5%9F%9F.md) | 深度优先搜索、广度优先搜索、并查集、数组、矩阵 | 中等 |
| 0131 | [分割回文串](https://leetcode-cn.com/problems/palindrome-partitioning/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0131.%20%E5%88%86%E5%89%B2%E5%9B%9E%E6%96%87%E4%B8%B2.md) | 字符串、动态规划、回溯 | 中等 |
| 0133 | [克隆图](https://leetcode-cn.com/problems/clone-graph/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0133.%20%E5%85%8B%E9%9A%86%E5%9B%BE.md) | 深度优先搜索、广度优先搜索、图 | 中等 |
| 0134 | [加油站](https://leetcode-cn.com/problems/gas-station/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0134.%20%E5%8A%A0%E6%B2%B9%E7%AB%99.md) | 贪心、数组 | 中等 |
| 0135 | [分发糖果](https://leetcode-cn.com/problems/candy/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0135.%20%E5%88%86%E5%8F%91%E7%B3%96%E6%9E%9C.md) | 贪心、数组 | 困难 |
| 0136 | [只出现一次的数字](https://leetcode-cn.com/problems/single-number/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0136.%20%E5%8F%AA%E5%87%BA%E7%8E%B0%E4%B8%80%E6%AC%A1%E7%9A%84%E6%95%B0%E5%AD%97.md) | 位运算、位运算 | 简单 |
| 0138 | [复制带随机指针的链表](https://leetcode-cn.com/problems/copy-list-with-random-pointer/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0138.%20%E5%A4%8D%E5%88%B6%E5%B8%A6%E9%9A%8F%E6%9C%BA%E6%8C%87%E9%92%88%E7%9A%84%E9%93%BE%E8%A1%A8.md) | 链表、哈希表 | 中等 |
| 0139 | [单词拆分](https://leetcode-cn.com/problems/word-break/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0139.%20%E5%8D%95%E8%AF%8D%E6%8B%86%E5%88%86.md) | 字典树、记忆化搜索、哈希表、字符串、动态规划 | 中等 |
| 0141 | [环形链表](https://leetcode-cn.com/problems/linked-list-cycle/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0141.%20%E7%8E%AF%E5%BD%A2%E9%93%BE%E8%A1%A8.md) | 链表、双指针 | 简单 |
| 0142 | [环形链表 II](https://leetcode-cn.com/problems/linked-list-cycle-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0142.%20%E7%8E%AF%E5%BD%A2%E9%93%BE%E8%A1%A8%20II.md) | 链表、双指针 | 中等 |
| 0144 | [二叉树的前序遍历](https://leetcode-cn.com/problems/binary-tree-preorder-traversal/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0144.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E5%89%8D%E5%BA%8F%E9%81%8D%E5%8E%86.md) | 栈、树 | 中等 |
| 0145 | [二叉树的后序遍历](https://leetcode-cn.com/problems/binary-tree-postorder-traversal/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0145.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E5%90%8E%E5%BA%8F%E9%81%8D%E5%8E%86.md) | 栈、树 | 简单 |
| 0148 | [排序链表](https://leetcode-cn.com/problems/sort-list/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0148.%20%E6%8E%92%E5%BA%8F%E9%93%BE%E8%A1%A8.md) | 链表、双指针、分治、排序、归并排序 | 中等 |
| 0149 | [直线上最多的点数](https://leetcode-cn.com/problems/max-points-on-a-line/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0149.%20%E7%9B%B4%E7%BA%BF%E4%B8%8A%E6%9C%80%E5%A4%9A%E7%9A%84%E7%82%B9%E6%95%B0.md) | 哈希表、数学 | 困难 |
| 0150 | [逆波兰表达式求值](https://leetcode-cn.com/problems/evaluate-reverse-polish-notation/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0150.%20%E9%80%86%E6%B3%A2%E5%85%B0%E8%A1%A8%E8%BE%BE%E5%BC%8F%E6%B1%82%E5%80%BC.md) | 栈 | 中等 |
| 0151 | [翻转字符串里的单词](https://leetcode-cn.com/problems/reverse-words-in-a-string/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0151.%20%E7%BF%BB%E8%BD%AC%E5%AD%97%E7%AC%A6%E4%B8%B2%E9%87%8C%E7%9A%84%E5%8D%95%E8%AF%8D.md) | 双指针、字符串 | 中等 |
| 0152 | [乘积最大子数组](https://leetcode-cn.com/problems/maximum-product-subarray/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0152.%20%E4%B9%98%E7%A7%AF%E6%9C%80%E5%A4%A7%E5%AD%90%E6%95%B0%E7%BB%84.md) | 数组、动态规划 | 中等 |
| 0153 | [寻找旋转排序数组中的最小值](https://leetcode-cn.com/problems/find-minimum-in-rotated-sorted-array/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0153.%20%E5%AF%BB%E6%89%BE%E6%97%8B%E8%BD%AC%E6%8E%92%E5%BA%8F%E6%95%B0%E7%BB%84%E4%B8%AD%E7%9A%84%E6%9C%80%E5%B0%8F%E5%80%BC.md) | 数组、二分查找 | 中等 |
| 0154 | [寻找旋转排序数组中的最小值 II](https://leetcode-cn.com/problems/find-minimum-in-rotated-sorted-array-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0154.%20%E5%AF%BB%E6%89%BE%E6%97%8B%E8%BD%AC%E6%8E%92%E5%BA%8F%E6%95%B0%E7%BB%84%E4%B8%AD%E7%9A%84%E6%9C%80%E5%B0%8F%E5%80%BC%20II.md) | 数组、二分查找 | 困难 |
| 0155 | [最小栈](https://leetcode-cn.com/problems/min-stack/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0155.%20%E6%9C%80%E5%B0%8F%E6%A0%88.md) | 栈、设计 | 简单 |
| 0159 | [至多包含两个不同字符的最长子串](https://leetcode-cn.com/problems/longest-substring-with-at-most-two-distinct-characters/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0159.%20%E8%87%B3%E5%A4%9A%E5%8C%85%E5%90%AB%E4%B8%A4%E4%B8%AA%E4%B8%8D%E5%90%8C%E5%AD%97%E7%AC%A6%E7%9A%84%E6%9C%80%E9%95%BF%E5%AD%90%E4%B8%B2.md) | 哈希表、双指针、字符串、滑动窗口 | 中等 |
| 0160 | [相交链表](https://leetcode-cn.com/problems/intersection-of-two-linked-lists/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0160.%20%E7%9B%B8%E4%BA%A4%E9%93%BE%E8%A1%A8.md) | 链表、双指针 | 简单 |
| 0166 | [分数到小数](https://leetcode-cn.com/problems/fraction-to-recurring-decimal/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0166.%20%E5%88%86%E6%95%B0%E5%88%B0%E5%B0%8F%E6%95%B0.md) | 哈希表、数学 | 中等 |
| 0167 | [两数之和 II - 输入有序数组](https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0167.%20%E4%B8%A4%E6%95%B0%E4%B9%8B%E5%92%8C%20II%20-%20%E8%BE%93%E5%85%A5%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84.md) | 数组、双指针、二分查找 | 简单 |
| 0168 | [Excel表列名称](https://leetcode-cn.com/problems/excel-sheet-column-title/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0168.%20Excel%E8%A1%A8%E5%88%97%E5%90%8D%E7%A7%B0.md) | 数学 | 简单 |
| 0169 | [多数元素](https://leetcode-cn.com/problems/majority-element/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0169.%20%E5%A4%9A%E6%95%B0%E5%85%83%E7%B4%A0.md) | 数组、哈希表 | 简单 |
| 0170 | [两数之和 III - 数据结构设计](https://leetcode-cn.com/problems/two-sum-iii-data-structure-design/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0170.%20%E4%B8%A4%E6%95%B0%E4%B9%8B%E5%92%8C%20III%20-%20%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E8%AE%BE%E8%AE%A1.md) | 设计、哈希表 | 简单 |
| 0173 | [二叉搜索树迭代器](https://leetcode-cn.com/problems/binary-search-tree-iterator/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0173.%20%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E8%BF%AD%E4%BB%A3%E5%99%A8.md) | 栈、树、设计 | 中等 |
| 0179 | [最大数](https://leetcode-cn.com/problems/largest-number/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0179.%20%E6%9C%80%E5%A4%A7%E6%95%B0.md) | 贪心、字符串、排序 | 中等 |
| 0188 | [买卖股票的最佳时机 IV](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-iv/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0188.%20%E4%B9%B0%E5%8D%96%E8%82%A1%E7%A5%A8%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA%20IV.md) |   | 简单 |
| 0189 | [旋转数组](https://leetcode-cn.com/problems/rotate-array/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0189.%20%E6%97%8B%E8%BD%AC%E6%95%B0%E7%BB%84.md) | 数组 | 中等 |
| 0190 | [颠倒二进制位](https://leetcode-cn.com/problems/reverse-bits/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0190.%20%E9%A2%A0%E5%80%92%E4%BA%8C%E8%BF%9B%E5%88%B6%E4%BD%8D.md) | 位运算 | 简单 |
| 0191 | [位1的个数](https://leetcode-cn.com/problems/number-of-1-bits/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0191.%20%E4%BD%8D1%E7%9A%84%E4%B8%AA%E6%95%B0.md) | 位运算 | 简单 |
| 0198 | [打家劫舍](https://leetcode-cn.com/problems/house-robber/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0198.%20%E6%89%93%E5%AE%B6%E5%8A%AB%E8%88%8D.md) | 动态规划 | 中等 |
| 0199 | [二叉树的右视图](https://leetcode-cn.com/problems/binary-tree-right-side-view/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0199.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E5%8F%B3%E8%A7%86%E5%9B%BE.md) | 树、深度优先搜索、广度优先搜索、递归、队列 | 中等 |
| 0200 | [岛屿数量](https://leetcode-cn.com/problems/number-of-islands/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0200.%20%E5%B2%9B%E5%B1%BF%E6%95%B0%E9%87%8F.md) | 搜索 | 中等 |
| 0202 | [快乐数](https://leetcode-cn.com/problems/happy-number/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0202.%20%E5%BF%AB%E4%B9%90%E6%95%B0.md) | 哈希表、数学 | 简单 |
| 0203 | [移除链表元素](https://leetcode-cn.com/problems/remove-linked-list-elements/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0203.%20%E7%A7%BB%E9%99%A4%E9%93%BE%E8%A1%A8%E5%85%83%E7%B4%A0.md) | 链表 | 简单 |
| 0204 | [计数质数](https://leetcode-cn.com/problems/count-primes/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0204.%20%E8%AE%A1%E6%95%B0%E8%B4%A8%E6%95%B0.md) | 数学、哈希表 | 简单 |
| 0205 | [同构字符串](https://leetcode-cn.com/problems/isomorphic-strings/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0205.%20%E5%90%8C%E6%9E%84%E5%AD%97%E7%AC%A6%E4%B8%B2.md) | 哈希表 | 简单 |
| 0206 | [反转链表](https://leetcode-cn.com/problems/reverse-linked-list/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0206.%20%E5%8F%8D%E8%BD%AC%E9%93%BE%E8%A1%A8.md) | 链表 | 简单 |
| 0207 | [课程表](https://leetcode-cn.com/problems/course-schedule/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0207.%20%E8%AF%BE%E7%A8%8B%E8%A1%A8.md) | 深度优先搜索、广度优先搜索、图、拓扑排序 | 中等 |
| 0209 | [长度最小的子数组](https://leetcode-cn.com/problems/minimum-size-subarray-sum/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0209.%20%E9%95%BF%E5%BA%A6%E6%9C%80%E5%B0%8F%E7%9A%84%E5%AD%90%E6%95%B0%E7%BB%84.md) | 数组、双指针、二分查找 | 中等 |
| 0210 | [课程表 II](https://leetcode-cn.com/problems/course-schedule-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0210.%20%E8%AF%BE%E7%A8%8B%E8%A1%A8%20II.md) | 深度优先搜索、广度优先搜索、图、拓扑排序 | 中等 |
| 0213 | [打家劫舍 II](https://leetcode-cn.com/problems/house-robber-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0213.%20%E6%89%93%E5%AE%B6%E5%8A%AB%E8%88%8D%20II.md) | 动态规划 | 中等 |
| 0215 | [数组中的第K个最大元素](https://leetcode-cn.com/problems/kth-largest-element-in-an-array/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0215.%20%E6%95%B0%E7%BB%84%E4%B8%AD%E7%9A%84%E7%AC%ACK%E4%B8%AA%E6%9C%80%E5%A4%A7%E5%85%83%E7%B4%A0.md) | 数组、堆排序 | 中等 |
| 0217 | [存在重复元素](https://leetcode-cn.com/problems/contains-duplicate/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0217.%20%E5%AD%98%E5%9C%A8%E9%87%8D%E5%A4%8D%E5%85%83%E7%B4%A0.md) | 数组、哈希表 | 简单 |
| 0219 | [存在重复元素 II](https://leetcode-cn.com/problems/contains-duplicate-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0219.%20%E5%AD%98%E5%9C%A8%E9%87%8D%E5%A4%8D%E5%85%83%E7%B4%A0%20II.md) | 数组、哈希表 | 简单 |
| 0220 | [存在重复元素 III](https://leetcode-cn.com/problems/contains-duplicate-iii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0220.%20%E5%AD%98%E5%9C%A8%E9%87%8D%E5%A4%8D%E5%85%83%E7%B4%A0%20III.md) | 排序、有序集合、哈希表 | 中等 |
| 0222 | [完全二叉树的节点个数](https://leetcode-cn.com/problems/count-complete-tree-nodes/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0222.%20%E5%AE%8C%E5%85%A8%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E8%8A%82%E7%82%B9%E4%B8%AA%E6%95%B0.md) | 树、深度优先搜索、二分查找、二叉树 | 中等 |
| 0223 | [矩形面积](https://leetcode-cn.com/problems/rectangle-area/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0223.%20%E7%9F%A9%E5%BD%A2%E9%9D%A2%E7%A7%AF.md) | 数学 | 简单 |
| 0225 | [用队列实现栈](https://leetcode-cn.com/problems/implement-stack-using-queues/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0225.%20%E7%94%A8%E9%98%9F%E5%88%97%E5%AE%9E%E7%8E%B0%E6%A0%88.md) | 栈、设计 | 简单 |
| 0226 | [翻转二叉树](https://leetcode-cn.com/problems/invert-binary-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0226.%20%E7%BF%BB%E8%BD%AC%E4%BA%8C%E5%8F%89%E6%A0%91.md) | 树、递归 | 简单 |
| 0227 | [基本计算器 II](https://leetcode-cn.com/problems/basic-calculator-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0227.%20%E5%9F%BA%E6%9C%AC%E8%AE%A1%E7%AE%97%E5%99%A8%20II.md) | 栈、字符串 | 中等 |
| 0231 | [2的幂](https://leetcode-cn.com/problems/power-of-two/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0231.%202%E7%9A%84%E5%B9%82.md) | 位运算、数学 | 简单 |
| 0232 | [用栈实现队列](https://leetcode-cn.com/problems/implement-queue-using-stacks/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0232.%20%E7%94%A8%E6%A0%88%E5%AE%9E%E7%8E%B0%E9%98%9F%E5%88%97.md) | 栈、设计 | 简单 |
| 0234 | [回文链表](https://leetcode-cn.com/problems/palindrome-linked-list/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0234.%20%E5%9B%9E%E6%96%87%E9%93%BE%E8%A1%A8.md) | 链表、双指针 | 简单 |
| 0235 | [二叉搜索树的最近公共祖先](https://leetcode-cn.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0235.%20%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E7%9A%84%E6%9C%80%E8%BF%91%E5%85%AC%E5%85%B1%E7%A5%96%E5%85%88.md) | 树 | 简单 |
| 0236 | [二叉树的最近公共祖先](https://leetcode-cn.com/problems/lowest-common-ancestor-of-a-binary-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0236.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E6%9C%80%E8%BF%91%E5%85%AC%E5%85%B1%E7%A5%96%E5%85%88.md) | 树 | 中等 |
| 0237 | [删除链表中的节点](https://leetcode-cn.com/problems/delete-node-in-a-linked-list/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0237.%20%E5%88%A0%E9%99%A4%E9%93%BE%E8%A1%A8%E4%B8%AD%E7%9A%84%E8%8A%82%E7%82%B9.md) | 链表 | 简单 |
| 0238 | [除自身以外数组的乘积](https://leetcode-cn.com/problems/product-of-array-except-self/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0238.%20%E9%99%A4%E8%87%AA%E8%BA%AB%E4%BB%A5%E5%A4%96%E6%95%B0%E7%BB%84%E7%9A%84%E4%B9%98%E7%A7%AF.md) | 数组 | 中等 |
| 0239 | [滑动窗口最大值](https://leetcode-cn.com/problems/sliding-window-maximum/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0239.%20%E6%BB%91%E5%8A%A8%E7%AA%97%E5%8F%A3%E6%9C%80%E5%A4%A7%E5%80%BC.md) | 队列，数组、滑动窗口、单调队列、堆（优先队列） | 困难 |
| 0240 | [搜索二维矩阵 II](https://leetcode-cn.com/problems/search-a-2d-matrix-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0240.%20%E6%90%9C%E7%B4%A2%E4%BA%8C%E7%BB%B4%E7%9F%A9%E9%98%B5%20II.md) | 二分查找、分治算法 | 中等 |
| 0242 | [有效的字母异位词](https://leetcode-cn.com/problems/valid-anagram/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0242.%20%E6%9C%89%E6%95%88%E7%9A%84%E5%AD%97%E6%AF%8D%E5%BC%82%E4%BD%8D%E8%AF%8D.md) | 字符串、哈希表、排序 | 简单 |
| 0249 | [移位字符串分组](https://leetcode-cn.com/problems/group-shifted-strings/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0249.%20%E7%A7%BB%E4%BD%8D%E5%AD%97%E7%AC%A6%E4%B8%B2%E5%88%86%E7%BB%84.md) | 哈希表、字符串 | 中等 |
| 0257 | [二叉树的所有路径](https://leetcode-cn.com/problems/binary-tree-paths/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0257.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E6%89%80%E6%9C%89%E8%B7%AF%E5%BE%84.md) | 树、深度优先搜索 | 简单 |
| 0258 | [各位相加](https://leetcode-cn.com/problems/add-digits/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0258.%20%E5%90%84%E4%BD%8D%E7%9B%B8%E5%8A%A0.md) | 数学 | 简单 |
| 0263 | [丑数](https://leetcode-cn.com/problems/ugly-number) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0263.%20%E4%B8%91%E6%95%B0.md) | 数学 | 简单 |
| 0264 | [丑数 II](https://leetcode-cn.com/problems/ugly-number-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0264.%20%E4%B8%91%E6%95%B0%20II.md) | 哈希表、数学、动态规划、堆（优先队列） | 中等 |
| 0268 | [丢失的数字](https://leetcode-cn.com/problems/missing-number/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0268.%20%E4%B8%A2%E5%A4%B1%E7%9A%84%E6%95%B0%E5%AD%97.md) | 位运算、数组、数学 | 简单 |
| 0270 | [最接近的二叉搜索树值](https://leetcode-cn.com/problems/closest-binary-search-tree-value/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0270.%20%E6%9C%80%E6%8E%A5%E8%BF%91%E7%9A%84%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E5%80%BC.md) | 树、二分查找 | 简单 |
| 0278 | [第一个错误的版本](https://leetcode-cn.com/problems/first-bad-version/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0278.%20%E7%AC%AC%E4%B8%80%E4%B8%AA%E9%94%99%E8%AF%AF%E7%9A%84%E7%89%88%E6%9C%AC.md) | 数组、二分查找 | 简单 |
| 0279 | [完全平方数](https://leetcode-cn.com/problems/perfect-squares/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0279.%20%E5%AE%8C%E5%85%A8%E5%B9%B3%E6%96%B9%E6%95%B0.md) | 广度优先搜索、数学、动态规划 | 中等 |
| 0283 | [移动零](https://leetcode-cn.com/problems/move-zeroes/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0283.%20%E7%A7%BB%E5%8A%A8%E9%9B%B6.md) | 数组、双指针 | 简单 |
| 0286 | [墙与门](https://leetcode-cn.com/problems/walls-and-gates/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0286.%20%E5%A2%99%E4%B8%8E%E9%97%A8.md) | 广度优先搜索 | 中等 |
| 0287 | [寻找重复数](https://leetcode-cn.com/problems/find-the-duplicate-number/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0287.%20%E5%AF%BB%E6%89%BE%E9%87%8D%E5%A4%8D%E6%95%B0.md) | 数组、双指针、二分查找 | 中等 |
| 0288 | [单词的唯一缩写](https://leetcode-cn.com/problems/unique-word-abbreviation/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0288.%20%E5%8D%95%E8%AF%8D%E7%9A%84%E5%94%AF%E4%B8%80%E7%BC%A9%E5%86%99.md) | 设计、哈希表 | 中等 |
| 0290 | [单词规律](https://leetcode-cn.com/problems/word-pattern/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0290.%20%E5%8D%95%E8%AF%8D%E8%A7%84%E5%BE%8B.md) | 哈希表 | 简单 |
| 0292 | [Nim 游戏](https://leetcode-cn.com/problems/nim-game/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0292.%20Nim%20%E6%B8%B8%E6%88%8F.md) | 数学 | 简单 |
| 0295 | [数据流的中位数](https://leetcode-cn.com/problems/find-median-from-data-stream/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0295.%20%E6%95%B0%E6%8D%AE%E6%B5%81%E7%9A%84%E4%B8%AD%E4%BD%8D%E6%95%B0.md) | 设计、双指针、数据流、排序、堆（优先队列） | 困难 |
| 0297 | [二叉树的序列化与反序列化](https://leetcode-cn.com/problems/serialize-and-deserialize-binary-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0297.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E5%BA%8F%E5%88%97%E5%8C%96%E4%B8%8E%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96.md) | 树、设计 | 困难 |
| 0300 | [最长递增子序列](https://leetcode-cn.com/problems/longest-increasing-subsequence/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0300.%20%E6%9C%80%E9%95%BF%E9%80%92%E5%A2%9E%E5%AD%90%E5%BA%8F%E5%88%97.md) | 二分查找、动态规划 | 中等 |
| 0309 | [最佳买卖股票时机含冷冻期](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0309.%20%E6%9C%80%E4%BD%B3%E4%B9%B0%E5%8D%96%E8%82%A1%E7%A5%A8%E6%97%B6%E6%9C%BA%E5%90%AB%E5%86%B7%E5%86%BB%E6%9C%9F.md) | 数组、动态规划 | 中等 |
| 0322 | [零钱兑换](https://leetcode-cn.com/problems/coin-change/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0322.%20%E9%9B%B6%E9%92%B1%E5%85%91%E6%8D%A2.md) | 动态规划 | 中等 |
| 0326 | [3 的幂](https://leetcode-cn.com/problems/power-of-three/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0326.%203%20%E7%9A%84%E5%B9%82.md) | 数学 | 简单 |
| 0328 | [奇偶链表](https://leetcode-cn.com/problems/odd-even-linked-list/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0328.%20%E5%A5%87%E5%81%B6%E9%93%BE%E8%A1%A8.md) | 链表 | 中等 |
| 0329 | [矩阵中的最长递增路径](https://leetcode-cn.com/problems/longest-increasing-path-in-a-matrix/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0329.%20%E7%9F%A9%E9%98%B5%E4%B8%AD%E7%9A%84%E6%9C%80%E9%95%BF%E9%80%92%E5%A2%9E%E8%B7%AF%E5%BE%84.md) | 深度优先搜索、广度优先搜索、图、拓扑排序、记忆化搜索、动态规划 | 困难 |
| 0334 | [递增的三元子序列](https://leetcode-cn.com/problems/increasing-triplet-subsequence/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0334.%20%E9%80%92%E5%A2%9E%E7%9A%84%E4%B8%89%E5%85%83%E5%AD%90%E5%BA%8F%E5%88%97.md) |   | 中等 |
| 0337 | [打家劫舍 III](https://leetcode-cn.com/problems/house-robber-iii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0337.%20%E6%89%93%E5%AE%B6%E5%8A%AB%E8%88%8D%20III.md) | 树、深度优先搜索、动态规划、二叉树 | 中等 |
| 0342 | [4的幂](https://leetcode-cn.com/problems/power-of-four/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0342.%204%E7%9A%84%E5%B9%82.md) | 位运算 | 简单 |
| 0343 | [整数拆分](https://leetcode-cn.com/problems/integer-break) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0343.%20%E6%95%B4%E6%95%B0%E6%8B%86%E5%88%86.md) | 数学、动态规划 | 中等 |
| 0344 | [反转字符串](https://leetcode-cn.com/problems/reverse-string/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0344.%20%E5%8F%8D%E8%BD%AC%E5%AD%97%E7%AC%A6%E4%B8%B2.md) | 字符串 | 简单 |
| 0345 | [反转字符串中的元音字母](https://leetcode-cn.com/problems/reverse-vowels-of-a-string/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0345.%20%E5%8F%8D%E8%BD%AC%E5%AD%97%E7%AC%A6%E4%B8%B2%E4%B8%AD%E7%9A%84%E5%85%83%E9%9F%B3%E5%AD%97%E6%AF%8D.md) | 字符串 | 简单 |
| 0347 | [前 K 个高频元素](https://leetcode-cn.com/problems/top-k-frequent-elements/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0347.%20%E5%89%8D%20K%20%E4%B8%AA%E9%AB%98%E9%A2%91%E5%85%83%E7%B4%A0.md) | 堆、哈希表 | 中等 |
| 0349 | [两个数组的交集](https://leetcode-cn.com/problems/intersection-of-two-arrays/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0349.%20%E4%B8%A4%E4%B8%AA%E6%95%B0%E7%BB%84%E7%9A%84%E4%BA%A4%E9%9B%86.md) | 数组、哈希表 | 简单 |
| 0350 | [两个数组的交集 II](https://leetcode-cn.com/problems/intersection-of-two-arrays-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0350.%20%E4%B8%A4%E4%B8%AA%E6%95%B0%E7%BB%84%E7%9A%84%E4%BA%A4%E9%9B%86%20II.md) | 数组、哈希表 | 简单 |
| 0354 | [俄罗斯套娃信封问题](https://leetcode-cn.com/problems/russian-doll-envelopes/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0354.%20%E4%BF%84%E7%BD%97%E6%96%AF%E5%A5%97%E5%A8%83%E4%BF%A1%E5%B0%81%E9%97%AE%E9%A2%98.md) | 动态规划、二分查找 | 困难 |
| 0359 | [日志速率限制器](https://leetcode-cn.com/problems/logger-rate-limiter/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0359.%20%E6%97%A5%E5%BF%97%E9%80%9F%E7%8E%87%E9%99%90%E5%88%B6%E5%99%A8.md) | 设计、哈希表 | 简单 |
| 0367 | [有效的完全平方数](https://leetcode-cn.com/problems/valid-perfect-square/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0367.%20%E6%9C%89%E6%95%88%E7%9A%84%E5%AE%8C%E5%85%A8%E5%B9%B3%E6%96%B9%E6%95%B0.md) | 数学、二分查找 | 简单 |
| 0371 | [两整数之和](https://leetcode-cn.com/problems/sum-of-two-integers/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0371.%20%E4%B8%A4%E6%95%B4%E6%95%B0%E4%B9%8B%E5%92%8C.md) | 位运算 | 中等 |
| 0374 | [猜数字大小](https://leetcode-cn.com/problems/guess-number-higher-or-lower/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0374.%20%E7%8C%9C%E6%95%B0%E5%AD%97%E5%A4%A7%E5%B0%8F.md) | 二分查找 | 简单 |
| 0376 | [摆动序列](https://leetcode-cn.com/problems/wiggle-subsequence/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0376.%20%E6%91%86%E5%8A%A8%E5%BA%8F%E5%88%97.md) | 贪心、数组、动态规划 | 中等 |
| 0377 | [组合总和 Ⅳ](https://leetcode-cn.com/problems/combination-sum-iv/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0377.%20%E7%BB%84%E5%90%88%E6%80%BB%E5%92%8C%20%E2%85%A3.md) | 数组、动态规划 | 中等 |
| 0380 | [常数时间插入、删除和获取随机元素](https://leetcode-cn.com/problems/insert-delete-getrandom-o1/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0380.%20%E5%B8%B8%E6%95%B0%E6%97%B6%E9%97%B4%E6%8F%92%E5%85%A5%E3%80%81%E5%88%A0%E9%99%A4%E5%92%8C%E8%8E%B7%E5%8F%96%E9%9A%8F%E6%9C%BA%E5%85%83%E7%B4%A0.md) | 数组、哈希表 | 中等 |
| 0387 | [字符串中的第一个唯一字符](https://leetcode-cn.com/problems/first-unique-character-in-a-string/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0387.%20%E5%AD%97%E7%AC%A6%E4%B8%B2%E4%B8%AD%E7%9A%84%E7%AC%AC%E4%B8%80%E4%B8%AA%E5%94%AF%E4%B8%80%E5%AD%97%E7%AC%A6.md) | 字符串、哈希表 | 简单 |
| 0389 | [找不同](https://leetcode-cn.com/problems/find-the-difference/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0389.%20%E6%89%BE%E4%B8%8D%E5%90%8C.md) | 位运算、哈希表 | 简单 |
| 0392 | [判断子序列](https://leetcode-cn.com/problems/is-subsequence/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0392.%20%E5%88%A4%E6%96%AD%E5%AD%90%E5%BA%8F%E5%88%97.md) | 双指针、字符串、动态规划 | 简单 |
| 0394 | [字符串解码](https://leetcode-cn.com/problems/decode-string/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0394.%20%E5%AD%97%E7%AC%A6%E4%B8%B2%E8%A7%A3%E7%A0%81.md) | 栈、深度优先搜索 | 中等 |
| 0399 | [除法求值](https://leetcode-cn.com/problems/evaluate-division/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0399.%20%E9%99%A4%E6%B3%95%E6%B1%82%E5%80%BC.md) | 深度优先搜索、广度优先搜索、并查集、图、数组、最短路 | 中等 |
| 0404 | [左叶子之和](https://leetcode-cn.com/problems/sum-of-left-leaves/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0404.%20%E5%B7%A6%E5%8F%B6%E5%AD%90%E4%B9%8B%E5%92%8C.md) | 树 | 简单 |
| 0406 | [根据身高重建队列](https://leetcode-cn.com/problems/queue-reconstruction-by-height/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0406.%20%E6%A0%B9%E6%8D%AE%E8%BA%AB%E9%AB%98%E9%87%8D%E5%BB%BA%E9%98%9F%E5%88%97.md) | 贪心、数组、排序 | 中等 |
| 0410 | [分割数组的最大值](https://leetcode-cn.com/problems/split-array-largest-sum/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0410.%20%E5%88%86%E5%89%B2%E6%95%B0%E7%BB%84%E7%9A%84%E6%9C%80%E5%A4%A7%E5%80%BC.md) | 二分查找、动态规划 | 困难 |
| 0412 | [Fizz Buzz](https://leetcode-cn.com/problems/fizz-buzz/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0412.%20Fizz%20Buzz.md) |   | 简单 |
| 0415 | [字符串相加](https://leetcode-cn.com/problems/add-strings/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0415.%20%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%9B%B8%E5%8A%A0.md) | 字符串、大数加法 | 简单 |
| 0416 | [分割等和子集](https://leetcode-cn.com/problems/partition-equal-subset-sum/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0416.%20%E5%88%86%E5%89%B2%E7%AD%89%E5%92%8C%E5%AD%90%E9%9B%86.md) | 数组、动态规划 | 中等 |
| 0424 | [替换后的最长重复字符](https://leetcode-cn.com/problems/longest-repeating-character-replacement/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0424.%20%E6%9B%BF%E6%8D%A2%E5%90%8E%E7%9A%84%E6%9C%80%E9%95%BF%E9%87%8D%E5%A4%8D%E5%AD%97%E7%AC%A6.md) | 双指针、滑动窗口 | 中等 |
| 0426 | [将二叉搜索树转化为排序的双向链表](https://leetcode-cn.com/problems/convert-binary-search-tree-to-sorted-doubly-linked-list/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0426.%20%E5%B0%86%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E8%BD%AC%E5%8C%96%E4%B8%BA%E6%8E%92%E5%BA%8F%E7%9A%84%E5%8F%8C%E5%90%91%E9%93%BE%E8%A1%A8.md) | 栈、树、深度优先搜索、二叉搜索树、链表、二叉树、双向链表 | 中等 |
| 0430 | [扁平化多级双向链表](https://leetcode-cn.com/problems/flatten-a-multilevel-doubly-linked-list/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0430.%20%E6%89%81%E5%B9%B3%E5%8C%96%E5%A4%9A%E7%BA%A7%E5%8F%8C%E5%90%91%E9%93%BE%E8%A1%A8.md) | 链表 | 中等 |
| 0435 | [无重叠区间](https://leetcode-cn.com/problems/non-overlapping-intervals/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0435.%20%E6%97%A0%E9%87%8D%E5%8F%A0%E5%8C%BA%E9%97%B4.md) | 贪心、数组、动态规划、排序 | 中等 |
| 0447 | [回旋镖的数量](https://leetcode-cn.com/problems/number-of-boomerangs/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0447.%20%E5%9B%9E%E6%97%8B%E9%95%96%E7%9A%84%E6%95%B0%E9%87%8F.md) | 哈希表、数学 | 中等 |
| 0450 | [删除二叉搜索树中的节点](https://leetcode-cn.com/problems/delete-node-in-a-bst/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0450.%20%E5%88%A0%E9%99%A4%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E4%B8%AD%E7%9A%84%E8%8A%82%E7%82%B9.md) | 树 | 中等 |
| 0452 | [用最少数量的箭引爆气球](https://leetcode-cn.com/problems/minimum-number-of-arrows-to-burst-balloons/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0452.%20%E7%94%A8%E6%9C%80%E5%B0%91%E6%95%B0%E9%87%8F%E7%9A%84%E7%AE%AD%E5%BC%95%E7%88%86%E6%B0%94%E7%90%83.md) | 贪心、数组、排序 | 中等 |
| 0454 | [四数相加 II](https://leetcode-cn.com/problems/4sum-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0454.%20%E5%9B%9B%E6%95%B0%E7%9B%B8%E5%8A%A0%20II.md) | 哈希表 | 中等 |
| 0455 | [分发饼干](https://leetcode-cn.com/problems/assign-cookies/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0455.%20%E5%88%86%E5%8F%91%E9%A5%BC%E5%B9%B2.md) | 贪心、数组、排序 | 简单 |
| 0461 | [汉明距离](https://leetcode-cn.com/problems/hamming-distance/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0461.%20%E6%B1%89%E6%98%8E%E8%B7%9D%E7%A6%BB.md) | 位运算 | 简单 |
| 0474 | [一和零](https://leetcode-cn.com/problems/ones-and-zeroes/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0474.%20%E4%B8%80%E5%92%8C%E9%9B%B6.md) | 数组、字符串、动态规划 | 中等 |
| 0485 | [最大连续 1 的个数](https://leetcode-cn.com/problems/max-consecutive-ones/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0485.%20%E6%9C%80%E5%A4%A7%E8%BF%9E%E7%BB%AD%201%20%E7%9A%84%E4%B8%AA%E6%95%B0.md) | 数组 | 简单 |
| 0491 | [递增子序列](https://leetcode-cn.com/problems/increasing-subsequences/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0491.%20%E9%80%92%E5%A2%9E%E5%AD%90%E5%BA%8F%E5%88%97.md) | 位运算、数组、哈希、回溯 | 中等 |
| 0494 | [目标和](https://leetcode-cn.com/problems/target-sum/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0494.%20%E7%9B%AE%E6%A0%87%E5%92%8C.md) | 深度优先搜索、动态规划 | 中等 |
| 0501 | [二叉搜索树中的众数](https://leetcode-cn.com/problems/find-mode-in-binary-search-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0501.%20%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E4%B8%AD%E7%9A%84%E4%BC%97%E6%95%B0.md) | 树、深度优先搜索、二叉搜索树、二叉树 | 简单 |
| 0504 | [七进制数](https://leetcode-cn.com/problems/base-7/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0504.%20%E4%B8%83%E8%BF%9B%E5%88%B6%E6%95%B0.md) |   | 简单 |
| 0509 | [斐波那契数](https://leetcode-cn.com/problems/fibonacci-number/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0509.%20%E6%96%90%E6%B3%A2%E9%82%A3%E5%A5%91%E6%95%B0.md) | 数组 | 简单 |
| 0513 | [找树左下角的值](https://leetcode-cn.com/problems/find-bottom-left-tree-value/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0513.%20%E6%89%BE%E6%A0%91%E5%B7%A6%E4%B8%8B%E8%A7%92%E7%9A%84%E5%80%BC.md) | 树、深度优先搜索、广度优先搜索、二叉树 | 中等 |
| 0516 | [最长回文子序列](https://leetcode-cn.com/problems/longest-palindromic-subsequence/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0516.%20%E6%9C%80%E9%95%BF%E5%9B%9E%E6%96%87%E5%AD%90%E5%BA%8F%E5%88%97.md) | 字符串、动态规划 | 中等 |
| 0518 | [零钱兑换 II](https://leetcode-cn.com/problems/coin-change-2/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0518.%20%E9%9B%B6%E9%92%B1%E5%85%91%E6%8D%A2%20II.md) | 数组、动态规划 | 中等 |
| 0530 | [二叉搜索树的最小绝对差](https://leetcode-cn.com/problems/minimum-absolute-difference-in-bst/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0530.%20%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E7%9A%84%E6%9C%80%E5%B0%8F%E7%BB%9D%E5%AF%B9%E5%B7%AE.md) | 树、深度优先搜索、广度优先搜索、二叉搜索树、二叉树 | 简单 |
| 0538 | [把二叉搜索树转换为累加树](https://leetcode-cn.com/problems/convert-bst-to-greater-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0538.%20%E6%8A%8A%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E8%BD%AC%E6%8D%A2%E4%B8%BA%E7%B4%AF%E5%8A%A0%E6%A0%91.md) | 树、深度优先搜索、二叉搜索树、二叉树 | 中等 |
| 0542 | [01 矩阵](https://leetcode-cn.com/problems/01-matrix/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0542.%2001%20%E7%9F%A9%E9%98%B5.md) | 深度优先搜索、广度优先搜索 | 中等 |
| 0543 | [二叉树的直径](https://leetcode-cn.com/problems/diameter-of-binary-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0543.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E7%9B%B4%E5%BE%84.md) | 二叉树 | 简单 |
| 0547 | [省份数量](https://leetcode-cn.com/problems/number-of-provinces/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0547.%20%E7%9C%81%E4%BB%BD%E6%95%B0%E9%87%8F.md) | 深度优先搜索、广度优先搜索、并查集、图 | 中等 |
| 0557 | [反转字符串中的单词 III](https://leetcode-cn.com/problems/reverse-words-in-a-string-iii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0557.%20%E5%8F%8D%E8%BD%AC%E5%AD%97%E7%AC%A6%E4%B8%B2%E4%B8%AD%E7%9A%84%E5%8D%95%E8%AF%8D%20III.md) | 字符串 | 简单 |
| 0561 | [数组拆分 I](https://leetcode-cn.com/problems/array-partition-i/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0561.%20%E6%95%B0%E7%BB%84%E6%8B%86%E5%88%86%20I.md) | 数组 | 简单 |
| 0583 | [两个字符串的删除操作](https://leetcode-cn.com/problems/delete-operation-for-two-strings/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0583.%20%E4%B8%A4%E4%B8%AA%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%9A%84%E5%88%A0%E9%99%A4%E6%93%8D%E4%BD%9C.md) | 字符串、动态规划 | 中等 |
| 0599 | [两个列表的最小索引总和](https://leetcode-cn.com/problems/minimum-index-sum-of-two-lists/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0599.%20%E4%B8%A4%E4%B8%AA%E5%88%97%E8%A1%A8%E7%9A%84%E6%9C%80%E5%B0%8F%E7%B4%A2%E5%BC%95%E6%80%BB%E5%92%8C.md) | 哈希表 | 简单 |
| 0617 | [合并二叉树](https://leetcode-cn.com/problems/merge-two-binary-trees) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0617.%20%E5%90%88%E5%B9%B6%E4%BA%8C%E5%8F%89%E6%A0%91.md) | 树、深度优先搜索、广度优先搜索、二叉树 | 简单 |
| 0621 | [任务调度器](https://leetcode-cn.com/problems/task-scheduler/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0621.%20%E4%BB%BB%E5%8A%A1%E8%B0%83%E5%BA%A6%E5%99%A8.md) | 贪心算法、队列、数组 | 中等 |
| 0622 | [设计循环队列](https://leetcode-cn.com/problems/design-circular-queue/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0622.%20%E8%AE%BE%E8%AE%A1%E5%BE%AA%E7%8E%AF%E9%98%9F%E5%88%97.md) | 队列 | 中等 |
| 0633 | [平方数之和](https://leetcode-cn.com/problems/sum-of-square-numbers/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0633.%20%E5%B9%B3%E6%96%B9%E6%95%B0%E4%B9%8B%E5%92%8C.md) | 双指针 | 中等 |
| 0647 | [回文子串](https://leetcode-cn.com/problems/palindromic-substrings/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0647.%20%E5%9B%9E%E6%96%87%E5%AD%90%E4%B8%B2.md) | 字符串、动态规划 | 中等 |
| 0652 | [寻找重复的子树](https://leetcode-cn.com/problems/find-duplicate-subtrees/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0652.%20%E5%AF%BB%E6%89%BE%E9%87%8D%E5%A4%8D%E7%9A%84%E5%AD%90%E6%A0%91.md) | 树、哈希表 | 中等 |
| 0654 | [最大二叉树](https://leetcode-cn.com/problems/maximum-binary-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0654.%20%E6%9C%80%E5%A4%A7%E4%BA%8C%E5%8F%89%E6%A0%91.md) | 栈、树、数组、分治、二叉树、单调栈 | 中等 |
| 0658 | [找到 K 个最接近的元素](https://leetcode-cn.com/problems/find-k-closest-elements/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0658.%20%E6%89%BE%E5%88%B0%20K%20%E4%B8%AA%E6%9C%80%E6%8E%A5%E8%BF%91%E7%9A%84%E5%85%83%E7%B4%A0.md) | 二分查找 | 中等 |
| 0665 | [非递减数列](https://leetcode-cn.com/problems/non-decreasing-array/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0665.%20%E9%9D%9E%E9%80%92%E5%87%8F%E6%95%B0%E5%88%97.md) | 数组 | 简单 |
| 0669 | [修剪二叉搜索树](https://leetcode-cn.com/problems/trim-a-binary-search-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0669.%20%E4%BF%AE%E5%89%AA%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91.md) | 树、深度优先搜索、二叉搜索树、二叉树 | 中等 |
| 0673 | [最长递增子序列的个数](https://leetcode-cn.com/problems/number-of-longest-increasing-subsequence/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0673.%20%E6%9C%80%E9%95%BF%E9%80%92%E5%A2%9E%E5%AD%90%E5%BA%8F%E5%88%97%E7%9A%84%E4%B8%AA%E6%95%B0.md) | 动态规划 | 中等 |
| 0674 | [最长连续递增序列](https://leetcode-cn.com/problems/longest-continuous-increasing-subsequence/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0674.%20%E6%9C%80%E9%95%BF%E8%BF%9E%E7%BB%AD%E9%80%92%E5%A2%9E%E5%BA%8F%E5%88%97.md) | 数组 | 简单 |
| 0684 | [冗余连接](https://leetcode-cn.com/problems/redundant-connection/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0684.%20%E5%86%97%E4%BD%99%E8%BF%9E%E6%8E%A5.md) | 深度优先搜索、广度优先搜索、并查集、图 | 中等 |
| 0690 | [员工的重要性](https://leetcode-cn.com/problems/employee-importance/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0690.%20%E5%91%98%E5%B7%A5%E7%9A%84%E9%87%8D%E8%A6%81%E6%80%A7.md) | 深度优先搜索、广度优先搜索、哈希表 | 简单 |
| 0695 | [岛屿的最大面积](https://leetcode-cn.com/problems/max-area-of-island/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0695.%20%E5%B2%9B%E5%B1%BF%E7%9A%84%E6%9C%80%E5%A4%A7%E9%9D%A2%E7%A7%AF.md) | 搜索 | 中等 |
| 0700 | [二叉搜索树中的搜索](https://leetcode-cn.com/problems/search-in-a-binary-search-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0700.%20%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E4%B8%AD%E7%9A%84%E6%90%9C%E7%B4%A2.md) | 数 | 简单 |
| 0701 | [二叉搜索树中的插入操作](https://leetcode-cn.com/problems/insert-into-a-binary-search-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0701.%20%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E4%B8%AD%E7%9A%84%E6%8F%92%E5%85%A5%E6%93%8D%E4%BD%9C.md) | 树 | 中等 |
| 0702 | [搜索长度未知的有序数组](https://leetcode-cn.com/problems/search-in-a-sorted-array-of-unknown-size/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0702.%20%E6%90%9C%E7%B4%A2%E9%95%BF%E5%BA%A6%E6%9C%AA%E7%9F%A5%E7%9A%84%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84.md) | 二分查找 | 中等 |
| 0703 | [数据流中的第 K 大元素](https://leetcode-cn.com/problems/kth-largest-element-in-a-stream/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0703.%20%E6%95%B0%E6%8D%AE%E6%B5%81%E4%B8%AD%E7%9A%84%E7%AC%AC%20K%20%E5%A4%A7%E5%85%83%E7%B4%A0.md) | 树、设计、二叉搜索树、二叉树、数据流、堆（优先队列） | 简单 |
| 0704 | [二分查找](https://leetcode-cn.com/problems/binary-search/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0704.%20%E4%BA%8C%E5%88%86%E6%9F%A5%E6%89%BE.md) | 二分查找 | 简单 |
| 0705 | [设计哈希集合](https://leetcode-cn.com/problems/design-hashset/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0705.%20%E8%AE%BE%E8%AE%A1%E5%93%88%E5%B8%8C%E9%9B%86%E5%90%88.md) | 哈希表 | 简单 |
| 0706 | [设计哈希映射](https://leetcode-cn.com/problems/design-hashmap/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0706.%20%E8%AE%BE%E8%AE%A1%E5%93%88%E5%B8%8C%E6%98%A0%E5%B0%84.md) | 哈希表 | 简单 |
| 0707 | [设计链表](https://leetcode-cn.com/problems/design-linked-list/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0707.%20%E8%AE%BE%E8%AE%A1%E9%93%BE%E8%A1%A8.md) | 链表 | 中等 |
| 0714 | [买卖股票的最佳时机含手续费](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0714.%20%E4%B9%B0%E5%8D%96%E8%82%A1%E7%A5%A8%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA%E5%90%AB%E6%89%8B%E7%BB%AD%E8%B4%B9.md) | 贪心、数组、动态规划 | 中等 |
| 0718 | [最长重复子数组](https://leetcode-cn.com/problems/maximum-length-of-repeated-subarray/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0718.%20%E6%9C%80%E9%95%BF%E9%87%8D%E5%A4%8D%E5%AD%90%E6%95%B0%E7%BB%84.md) | 数组、二分查找、动态规划、滑动窗口、哈希函数、滚动哈希 | 中等 |
| 0719 | [找出第 k 小的距离对](https://leetcode-cn.com/problems/find-k-th-smallest-pair-distance/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0719.%20%E6%89%BE%E5%87%BA%E7%AC%AC%20k%20%E5%B0%8F%E7%9A%84%E8%B7%9D%E7%A6%BB%E5%AF%B9.md) | 堆、数组、二分查找 | 困难 |
| 0724 | [寻找数组的中心下标](https://leetcode-cn.com/problems/find-pivot-index/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0724.%20%E5%AF%BB%E6%89%BE%E6%95%B0%E7%BB%84%E7%9A%84%E4%B8%AD%E5%BF%83%E4%B8%8B%E6%A0%87.md) | 数组 | 简单 |
| 0733 | [图像渲染](https://leetcode-cn.com/problems/flood-fill/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0733.%20%E5%9B%BE%E5%83%8F%E6%B8%B2%E6%9F%93.md) | 深度优先搜索 | 简单 |
| 0738 | [单调递增的数字](https://leetcode-cn.com/problems/monotone-increasing-digits/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0738.%20%E5%8D%95%E8%B0%83%E9%80%92%E5%A2%9E%E7%9A%84%E6%95%B0%E5%AD%97.md) | 贪心、数学 | 中等 |
| 0739 | [每日温度](https://leetcode-cn.com/problems/daily-temperatures/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0739.%20%E6%AF%8F%E6%97%A5%E6%B8%A9%E5%BA%A6.md) | 栈、哈希表 | 中等 |
| 0744 | [寻找比目标字母大的最小字母](https://leetcode-cn.com/problems/find-smallest-letter-greater-than-target/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0744.%20%E5%AF%BB%E6%89%BE%E6%AF%94%E7%9B%AE%E6%A0%87%E5%AD%97%E6%AF%8D%E5%A4%A7%E7%9A%84%E6%9C%80%E5%B0%8F%E5%AD%97%E6%AF%8D.md) | 二分查找 | 简单 |
| 0746 | [使用最小花费爬楼梯](https://leetcode-cn.com/problems/min-cost-climbing-stairs/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0746.%20%E4%BD%BF%E7%94%A8%E6%9C%80%E5%B0%8F%E8%8A%B1%E8%B4%B9%E7%88%AC%E6%A5%BC%E6%A2%AF.md) | 数组、动态规划 | 简单 |
| 0752 | [打开转盘锁](https://leetcode-cn.com/problems/open-the-lock/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0752.%20%E6%89%93%E5%BC%80%E8%BD%AC%E7%9B%98%E9%94%81.md) | 广度优先搜索 | 中等 |
| 0763 | [划分字母区间](https://leetcode-cn.com/problems/partition-labels/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0763.%20%E5%88%92%E5%88%86%E5%AD%97%E6%AF%8D%E5%8C%BA%E9%97%B4.md) | 贪心、哈希表、双指针、字符串 | 中等 |
| 0765 | [情侣牵手](https://leetcode-cn.com/problems/couples-holding-hands/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0765.%20%E6%83%85%E4%BE%A3%E7%89%B5%E6%89%8B.md) | 贪心、深度优先搜索、广度优先搜索、并查集、图 | 困难 |
| 0778 | [水位上升的泳池中游泳](https://leetcode-cn.com/problems/swim-in-rising-water/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0778.%20%E6%B0%B4%E4%BD%8D%E4%B8%8A%E5%8D%87%E7%9A%84%E6%B3%B3%E6%B1%A0%E4%B8%AD%E6%B8%B8%E6%B3%B3.md) | 深度优先搜索、广度优先搜索、并查集、数组、二分查找、矩阵、堆（优先队列） | 困难 |
| 0779 | [第K个语法符号](https://leetcode-cn.com/problems/k-th-symbol-in-grammar/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0779.%20%E7%AC%ACK%E4%B8%AA%E8%AF%AD%E6%B3%95%E7%AC%A6%E5%8F%B7.md) | 递归 | 中等 |
| 0801 | [使序列递增的最小交换次数](https://leetcode-cn.com/problems/minimum-swaps-to-make-sequences-increasing/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0801.%20%E4%BD%BF%E5%BA%8F%E5%88%97%E9%80%92%E5%A2%9E%E7%9A%84%E6%9C%80%E5%B0%8F%E4%BA%A4%E6%8D%A2%E6%AC%A1%E6%95%B0.md) | 动态规划 | 中等 |
| 0832 | [翻转图像](https://leetcode-cn.com/problems/flipping-an-image) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0832.%20%E7%BF%BB%E8%BD%AC%E5%9B%BE%E5%83%8F.md) | 数组、双指针、矩阵、模拟 | 简单 |
| 0836 | [矩形重叠](https://leetcode-cn.com/problems/rectangle-overlap/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0836.%20%E7%9F%A9%E5%BD%A2%E9%87%8D%E5%8F%A0.md) | 数学 | 简单 |
| 0841 | [钥匙和房间](https://leetcode-cn.com/problems/keys-and-rooms/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0841.%20%E9%92%A5%E5%8C%99%E5%92%8C%E6%88%BF%E9%97%B4.md) | 深度优先搜索、图 | 中等 |
| 0860 | [柠檬水找零](https://leetcode-cn.com/problems/lemonade-change/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0860.%20%E6%9F%A0%E6%AA%AC%E6%B0%B4%E6%89%BE%E9%9B%B6.md) | 贪心、数组 | 简单 |
| 0867 | [转置矩阵](https://leetcode-cn.com/problems/transpose-matrix/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0867.%20%E8%BD%AC%E7%BD%AE%E7%9F%A9%E9%98%B5.md) | 数组 | 简单 |
| 0872 | [叶子相似的树](https://leetcode-cn.com/problems/leaf-similar-trees) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0872.%20%E5%8F%B6%E5%AD%90%E7%9B%B8%E4%BC%BC%E7%9A%84%E6%A0%91.md) | 树、深度优先搜索、二叉树 | 简单 |
| 0873 | [最长的斐波那契子序列的长度](https://leetcode-cn.com/problems/length-of-longest-fibonacci-subsequence/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0873.%20%E6%9C%80%E9%95%BF%E7%9A%84%E6%96%90%E6%B3%A2%E9%82%A3%E5%A5%91%E5%AD%90%E5%BA%8F%E5%88%97%E7%9A%84%E9%95%BF%E5%BA%A6.md) | 数组、哈希表、动态规划 | 中等 |
| 0876 | [链表的中间结点](https://leetcode-cn.com/problems/middle-of-the-linked-list/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0876.%20%E9%93%BE%E8%A1%A8%E7%9A%84%E4%B8%AD%E9%97%B4%E7%BB%93%E7%82%B9.md) | 链表、指针 | 简单 |
| 0918 | [环形子数组的最大和](https://leetcode-cn.com/problems/maximum-sum-circular-subarray/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0918.%20%E7%8E%AF%E5%BD%A2%E5%AD%90%E6%95%B0%E7%BB%84%E7%9A%84%E6%9C%80%E5%A4%A7%E5%92%8C.md) | 数组、动态规划 | 中等 |
| 0938 | [二叉搜索树的范围和](https://leetcode-cn.com/problems/range-sum-of-bst/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0938.%20%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E7%9A%84%E8%8C%83%E5%9B%B4%E5%92%8C.md) | 二叉树 | 简单 |
| 0946 | [验证栈序列](https://leetcode-cn.com/problems/validate-stack-sequences/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0946.%20%E9%AA%8C%E8%AF%81%E6%A0%88%E5%BA%8F%E5%88%97.md) | 栈、数组、模拟 | 中等 |
| 0947 | [移除最多的同行或同列石头](https://leetcode-cn.com/problems/most-stones-removed-with-same-row-or-column/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0947.%20%E7%A7%BB%E9%99%A4%E6%9C%80%E5%A4%9A%E7%9A%84%E5%90%8C%E8%A1%8C%E6%88%96%E5%90%8C%E5%88%97%E7%9F%B3%E5%A4%B4.md) | 深度优先搜索、并查集、图 | 中等 |
| 0959 | [由斜杠划分区域](https://leetcode-cn.com/problems/regions-cut-by-slashes/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0959.%20%E7%94%B1%E6%96%9C%E6%9D%A0%E5%88%92%E5%88%86%E5%8C%BA%E5%9F%9F.md) | 深度优先搜索、广度优先搜索、并查集、图 | 中等 |
| 0968 | [监控二叉树](https://leetcode-cn.com/problems/binary-tree-cameras/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0968.%20%E7%9B%91%E6%8E%A7%E4%BA%8C%E5%8F%89%E6%A0%91.md) | 树、深度优先搜索、动态规划、二叉树 | 困难 |
| 0990 | [等式方程的可满足性](https://leetcode-cn.com/problems/satisfiability-of-equality-equations) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0990.%20%E7%AD%89%E5%BC%8F%E6%96%B9%E7%A8%8B%E7%9A%84%E5%8F%AF%E6%BB%A1%E8%B6%B3%E6%80%A7.md) | 并查集、图、数组、字符串 | 中等 |
| 0993 | [二叉树的堂兄弟节点](https://leetcode-cn.com/problems/cousins-in-binary-tree/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/0993.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E5%A0%82%E5%85%84%E5%BC%9F%E8%8A%82%E7%82%B9.md) | 树、广度优先搜索 | 简单 |
| 1004 | [最大连续1的个数 III](https://leetcode-cn.com/problems/max-consecutive-ones-iii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1004.%20%E6%9C%80%E5%A4%A7%E8%BF%9E%E7%BB%AD1%E7%9A%84%E4%B8%AA%E6%95%B0%20III.md) | 双指针、滑动窗口 | 中等 |
| 1005 | [K 次取反后最大化的数组和](https://leetcode-cn.com/problems/maximize-sum-of-array-after-k-negations/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1005.%20K%20%E6%AC%A1%E5%8F%96%E5%8F%8D%E5%90%8E%E6%9C%80%E5%A4%A7%E5%8C%96%E7%9A%84%E6%95%B0%E7%BB%84%E5%92%8C.md) | 贪心、数组、排序 | 简单 |
| 1011 | [在 D 天内送达包裹的能力](https://leetcode-cn.com/problems/capacity-to-ship-packages-within-d-days/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1011.%20%E5%9C%A8%20D%20%E5%A4%A9%E5%86%85%E9%80%81%E8%BE%BE%E5%8C%85%E8%A3%B9%E7%9A%84%E8%83%BD%E5%8A%9B.md) | 数组、二分查找 | 中等 |
| 1025 | [除数博弈](https://leetcode-cn.com/problems/divisor-game) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1025.%20%E9%99%A4%E6%95%B0%E5%8D%9A%E5%BC%88.md) | 脑筋急转弯、数学、动态规划、博弈 | 简单 |
| 1035 | [不相交的线](https://leetcode-cn.com/problems/uncrossed-lines/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1035.%20%E4%B8%8D%E7%9B%B8%E4%BA%A4%E7%9A%84%E7%BA%BF.md) | 数组、动态规划 | 中等 |
| 1047 | [删除字符串中的所有相邻重复项](https://leetcode-cn.com/problems/remove-all-adjacent-duplicates-in-string/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1047.%20%E5%88%A0%E9%99%A4%E5%AD%97%E7%AC%A6%E4%B8%B2%E4%B8%AD%E7%9A%84%E6%89%80%E6%9C%89%E7%9B%B8%E9%82%BB%E9%87%8D%E5%A4%8D%E9%A1%B9.md) | 字符串、栈 | 简单 |
| 1049 | [最后一块石头的重量 II](https://leetcode-cn.com/problems/last-stone-weight-ii/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1049.%20%E6%9C%80%E5%90%8E%E4%B8%80%E5%9D%97%E7%9F%B3%E5%A4%B4%E7%9A%84%E9%87%8D%E9%87%8F%20II.md) | 数组、动态规划 | 中等 |
| 1137 | [第 N 个泰波那契数](https://leetcode-cn.com/problems/n-th-tribonacci-number) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1137.%20%E7%AC%AC%20N%20%E4%B8%AA%E6%B3%B0%E6%B3%A2%E9%82%A3%E5%A5%91%E6%95%B0.md) | 记忆化搜索、数学、动态规划 | 简单 |
| 1143 | [最长公共子序列](https://leetcode-cn.com/problems/longest-common-subsequence/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1143.%20%E6%9C%80%E9%95%BF%E5%85%AC%E5%85%B1%E5%AD%90%E5%BA%8F%E5%88%97.md) | 字符串、动态规划 | 中等 |
| 1202 | [交换字符串中的元素](https://leetcode-cn.com/problems/smallest-string-with-swaps/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1202.%20%E4%BA%A4%E6%8D%A2%E5%AD%97%E7%AC%A6%E4%B8%B2%E4%B8%AD%E7%9A%84%E5%85%83%E7%B4%A0.md) | 深度优先搜索、广度优先搜索、并查集、哈希表、字符串 | 中等 |
| 1227 | [飞机座位分配概率](https://leetcode-cn.com/problems/airplane-seat-assignment-probability/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1227.%20%E9%A3%9E%E6%9C%BA%E5%BA%A7%E4%BD%8D%E5%88%86%E9%85%8D%E6%A6%82%E7%8E%87.md) | 数学、动态规划 | 中等 |
| 1232 | [缀点成线](https://leetcode-cn.com/problems/check-if-it-is-a-straight-line/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1232.%20%E7%BC%80%E7%82%B9%E6%88%90%E7%BA%BF.md) | 几何、数组、数学 | 简单 |
| 1319 | [连通网络的操作次数](https://leetcode-cn.com/problems/number-of-operations-to-make-network-connected/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1319.%20%E8%BF%9E%E9%80%9A%E7%BD%91%E7%BB%9C%E7%9A%84%E6%93%8D%E4%BD%9C%E6%AC%A1%E6%95%B0.md) | 深度优先搜索、广度优先搜索、并查集、图 | 中等 |
| 1480 | [一维数组的动态和](https://leetcode-cn.com/problems/running-sum-of-1d-array/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1480.%20%E4%B8%80%E7%BB%B4%E6%95%B0%E7%BB%84%E7%9A%84%E5%8A%A8%E6%80%81%E5%92%8C.md) | 数组 | 简单 |
| 1486 | [数组异或操作](https://leetcode-cn.com/problems/xor-operation-in-an-array/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1486.%20%E6%95%B0%E7%BB%84%E5%BC%82%E6%88%96%E6%93%8D%E4%BD%9C.md) | 位运算、数组 | 简单 |
| 1561 | [你可以获得的最大硬币数目](https://leetcode-cn.com/problems/maximum-number-of-coins-you-can-get) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1561.%20%E4%BD%A0%E5%8F%AF%E4%BB%A5%E8%8E%B7%E5%BE%97%E7%9A%84%E6%9C%80%E5%A4%A7%E7%A1%AC%E5%B8%81%E6%95%B0%E7%9B%AE.md) | 贪心、数组、数学、博弈、排序 | 中等 |
| 1603 | [设计停车系统](https://leetcode-cn.com/problems/design-parking-system) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1603.%20%E8%AE%BE%E8%AE%A1%E5%81%9C%E8%BD%A6%E7%B3%BB%E7%BB%9F.md) | 设计、计数、模拟 | 简单 |
| 1631 | [最小体力消耗路径](https://leetcode-cn.com/problems/path-with-minimum-effort/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1631.%20%E6%9C%80%E5%B0%8F%E4%BD%93%E5%8A%9B%E6%B6%88%E8%80%97%E8%B7%AF%E5%BE%84.md) | 深度优先搜索、广度优先搜索、并查集、数组、二分查找、矩阵、堆（优先队列） | 中等 |
| 1720 | [解码异或后的数组](https://leetcode-cn.com/problems/decode-xored-array/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/1720.%20%E8%A7%A3%E7%A0%81%E5%BC%82%E6%88%96%E5%90%8E%E7%9A%84%E6%95%B0%E7%BB%84.md) | 位运算 | 简单 |
| 剑指 Offer 03 | [数组中重复的数字](https://leetcode-cn.com/problems/shu-zu-zhong-zhong-fu-de-shu-zi-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2003.%20%E6%95%B0%E7%BB%84%E4%B8%AD%E9%87%8D%E5%A4%8D%E7%9A%84%E6%95%B0%E5%AD%97.md) | 数组、哈希表、排序 | 简单 |
| 剑指 Offer 04 | [二维数组中的查找](https://leetcode-cn.com/problems/er-wei-shu-zu-zhong-de-cha-zhao-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2004.%20%E4%BA%8C%E7%BB%B4%E6%95%B0%E7%BB%84%E4%B8%AD%E7%9A%84%E6%9F%A5%E6%89%BE.md) | 数组、二分查找、分治、矩阵 | 中等 |
| 剑指 Offer 05 | [替换空格](https://leetcode-cn.com/problems/ti-huan-kong-ge-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2005.%20%E6%9B%BF%E6%8D%A2%E7%A9%BA%E6%A0%BC.md) | 字符串 | 简单 |
| 剑指 Offer 06 | [从尾到头打印链表](https://leetcode-cn.com/problems/cong-wei-dao-tou-da-yin-lian-biao-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2006.%20%E4%BB%8E%E5%B0%BE%E5%88%B0%E5%A4%B4%E6%89%93%E5%8D%B0%E9%93%BE%E8%A1%A8.md) | 栈、递归、链表、双指针 | 简单 |
| 剑指 Offer 07 | [重建二叉树](https://leetcode-cn.com/problems/zhong-jian-er-cha-shu-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2007.%20%E9%87%8D%E5%BB%BA%E4%BA%8C%E5%8F%89%E6%A0%91.md) | 树、数组、哈希表、分治、二叉树 | 中等 |
| 剑指 Offer 09 | [用两个栈实现队列](https://leetcode-cn.com/problems/yong-liang-ge-zhan-shi-xian-dui-lie-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2009.%20%E7%94%A8%E4%B8%A4%E4%B8%AA%E6%A0%88%E5%AE%9E%E7%8E%B0%E9%98%9F%E5%88%97.md) | 栈、设计、队列 | 简单 |
| 剑指 Offer 10 - I | [斐波那契数列](https://leetcode-cn.com/problems/fei-bo-na-qi-shu-lie-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2010%20-%20I.%20%E6%96%90%E6%B3%A2%E9%82%A3%E5%A5%91%E6%95%B0%E5%88%97.md) | 记忆化搜索、数学、动态规划 | 简单 |
| 剑指 Offer 10 - II | [青蛙跳台阶问题](https://leetcode-cn.com/problems/qing-wa-tiao-tai-jie-wen-ti-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2010%20-%20II.%20%E9%9D%92%E8%9B%99%E8%B7%B3%E5%8F%B0%E9%98%B6%E9%97%AE%E9%A2%98.md) | 记忆化搜索、数学、动态规划 | 简单 |
| 剑指 Offer 11 | [旋转数组的最小数字](https://leetcode-cn.com/problems/xuan-zhuan-shu-zu-de-zui-xiao-shu-zi-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2011.%20%E6%97%8B%E8%BD%AC%E6%95%B0%E7%BB%84%E7%9A%84%E6%9C%80%E5%B0%8F%E6%95%B0%E5%AD%97.md) | 数组、二分查找 | 简单 |
| 剑指 Offer 12 | [矩阵中的路径](https://leetcode-cn.com/problems/ju-zhen-zhong-de-lu-jing-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2012.%20%E7%9F%A9%E9%98%B5%E4%B8%AD%E7%9A%84%E8%B7%AF%E5%BE%84.md) | 数组、回溯、矩阵 | 中等 |
| 剑指 Offer 13 | [机器人的运动范围](https://leetcode-cn.com/problems/ji-qi-ren-de-yun-dong-fan-wei-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2013.%20%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%9A%84%E8%BF%90%E5%8A%A8%E8%8C%83%E5%9B%B4.md) | 深度优先搜索、广度优先搜索、动态规划 | 中等 |
| 剑指 Offer 14 - I | [剪绳子](https://leetcode-cn.com/problems/jian-sheng-zi-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2014%20-%20I.%20%E5%89%AA%E7%BB%B3%E5%AD%90.md) | 数学、动态规划 | 中等 |
| 剑指 Offer 15 | [二进制中1的个数](https://leetcode-cn.com/problems/er-jin-zhi-zhong-1de-ge-shu-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2015.%20%E4%BA%8C%E8%BF%9B%E5%88%B6%E4%B8%AD1%E7%9A%84%E4%B8%AA%E6%95%B0.md) | 位运算 | 简单 |
| 剑指 Offer 16 | [数值的整数次方](https://leetcode-cn.com/problems/shu-zhi-de-zheng-shu-ci-fang-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2016.%20%E6%95%B0%E5%80%BC%E7%9A%84%E6%95%B4%E6%95%B0%E6%AC%A1%E6%96%B9.md) | 递归、数学 | 中等 |
| 剑指 Offer 17 | [打印从1到最大的n位数](https://leetcode-cn.com/problems/da-yin-cong-1dao-zui-da-de-nwei-shu-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2017.%20%E6%89%93%E5%8D%B0%E4%BB%8E1%E5%88%B0%E6%9C%80%E5%A4%A7%E7%9A%84n%E4%BD%8D%E6%95%B0.md) | 数组、数学 | 简单 |
| 剑指 Offer 18 | [删除链表的节点](https://leetcode-cn.com/problems/shan-chu-lian-biao-de-jie-dian-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2018.%20%E5%88%A0%E9%99%A4%E9%93%BE%E8%A1%A8%E7%9A%84%E8%8A%82%E7%82%B9.md) | 链表 | 简单 |
| 剑指 Offer 21 | [调整数组顺序使奇数位于偶数前面](https://leetcode-cn.com/problems/diao-zheng-shu-zu-shun-xu-shi-qi-shu-wei-yu-ou-shu-qian-mian-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2021.%20%E8%B0%83%E6%95%B4%E6%95%B0%E7%BB%84%E9%A1%BA%E5%BA%8F%E4%BD%BF%E5%A5%87%E6%95%B0%E4%BD%8D%E4%BA%8E%E5%81%B6%E6%95%B0%E5%89%8D%E9%9D%A2.md) | 数组、双指针、排序 | 简单 |
| 剑指 Offer 22 | [链表中倒数第k个节点](https://leetcode-cn.com/problems/lian-biao-zhong-dao-shu-di-kge-jie-dian-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2022.%20%E9%93%BE%E8%A1%A8%E4%B8%AD%E5%80%92%E6%95%B0%E7%AC%ACk%E4%B8%AA%E8%8A%82%E7%82%B9.md) | 链表、双指针 | 简单 |
| 剑指 Offer 24 | [反转链表](https://leetcode-cn.com/problems/fan-zhuan-lian-biao-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2024.%20%E5%8F%8D%E8%BD%AC%E9%93%BE%E8%A1%A8.md) | 递归、链表 | 简单 |
| 剑指 Offer 25 | [合并两个排序的链表](https://leetcode-cn.com/problems/he-bing-liang-ge-pai-xu-de-lian-biao-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2025.%20%E5%90%88%E5%B9%B6%E4%B8%A4%E4%B8%AA%E6%8E%92%E5%BA%8F%E7%9A%84%E9%93%BE%E8%A1%A8.md) | 递归、链表 | 简单 |
| 剑指 Offer 26 | [树的子结构](https://leetcode-cn.com/problems/shu-de-zi-jie-gou-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2026.%20%E6%A0%91%E7%9A%84%E5%AD%90%E7%BB%93%E6%9E%84.md) | 树、深度优先搜索、二叉树 | 中等 |
| 剑指 Offer 27 | [二叉树的镜像](https://leetcode-cn.com/problems/er-cha-shu-de-jing-xiang-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2027.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E9%95%9C%E5%83%8F.md) | 树、深度优先搜索、广度优先搜索、二叉树 | 简单 |
| 剑指 Offer 28 | [对称的二叉树](https://leetcode-cn.com/problems/dui-cheng-de-er-cha-shu-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2028.%20%E5%AF%B9%E7%A7%B0%E7%9A%84%E4%BA%8C%E5%8F%89%E6%A0%91.md) | 树、深度优先搜索、广度优先搜索、二叉树 | 简单 |
| 剑指 Offer 29 | [顺时针打印矩阵](https://leetcode-cn.com/problems/shun-shi-zhen-da-yin-ju-zhen-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2029.%20%E9%A1%BA%E6%97%B6%E9%92%88%E6%89%93%E5%8D%B0%E7%9F%A9%E9%98%B5.md) | 数组、矩阵、模拟 | 简单 |
| 剑指 Offer 30 | [包含min函数的栈](https://leetcode-cn.com/problems/bao-han-minhan-shu-de-zhan-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2030.%20%E5%8C%85%E5%90%ABmin%E5%87%BD%E6%95%B0%E7%9A%84%E6%A0%88.md) | 栈、设计 | 简单 |
| 剑指 Offer 31 | [栈的压入、弹出序列](https://leetcode-cn.com/problems/zhan-de-ya-ru-dan-chu-xu-lie-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2031.%20%E6%A0%88%E7%9A%84%E5%8E%8B%E5%85%A5%E3%80%81%E5%BC%B9%E5%87%BA%E5%BA%8F%E5%88%97.md) | 栈、数组、模拟 | 中等 |
| 剑指 Offer 32 - I | [从上到下打印二叉树](https://leetcode-cn.com/problems/cong-shang-dao-xia-da-yin-er-cha-shu-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2032%20-%20I.%20%E4%BB%8E%E4%B8%8A%E5%88%B0%E4%B8%8B%E6%89%93%E5%8D%B0%E4%BA%8C%E5%8F%89%E6%A0%91.md) | 树、广度优先搜索、二叉树 | 中等 |
| 剑指 Offer 32 - II | [从上到下打印二叉树 II](https://leetcode-cn.com/problems/cong-shang-dao-xia-da-yin-er-cha-shu-ii-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2032%20-%20II.%20%E4%BB%8E%E4%B8%8A%E5%88%B0%E4%B8%8B%E6%89%93%E5%8D%B0%E4%BA%8C%E5%8F%89%E6%A0%91%20II.md) | 树、广度优先搜索、二叉树 | 简单 |
| 剑指 Offer 32 - III | [从上到下打印二叉树 III](https://leetcode-cn.com/problems/cong-shang-dao-xia-da-yin-er-cha-shu-iii-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2032%20-%20III.%20%E4%BB%8E%E4%B8%8A%E5%88%B0%E4%B8%8B%E6%89%93%E5%8D%B0%E4%BA%8C%E5%8F%89%E6%A0%91%20III.md) | 树、广度优先搜索、二叉树 | 中等 |
| 剑指 Offer 33 | [二叉搜索树的后序遍历序列](https://leetcode-cn.com/problems/er-cha-sou-suo-shu-de-hou-xu-bian-li-xu-lie-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2033.%20%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E7%9A%84%E5%90%8E%E5%BA%8F%E9%81%8D%E5%8E%86%E5%BA%8F%E5%88%97.md) | 栈、树、二叉搜索树、递归、二叉树、单调栈 | 中等 |
| 剑指 Offer 34 | [二叉树中和为某一值的路径](https://leetcode-cn.com/problems/er-cha-shu-zhong-he-wei-mou-yi-zhi-de-lu-jing-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2034.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E4%B8%AD%E5%92%8C%E4%B8%BA%E6%9F%90%E4%B8%80%E5%80%BC%E7%9A%84%E8%B7%AF%E5%BE%84.md) | 树、深度优先搜索、回溯、二叉树 | 中等 |
| 剑指 Offer 35 | [复杂链表的复制](https://leetcode-cn.com/problems/fu-za-lian-biao-de-fu-zhi-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2035.%20%E5%A4%8D%E6%9D%82%E9%93%BE%E8%A1%A8%E7%9A%84%E5%A4%8D%E5%88%B6.md) | 哈希表、链表 | 中等 |
| 剑指 Offer 36 | [二叉搜索树与双向链表](https://leetcode-cn.com/problems/er-cha-sou-suo-shu-yu-shuang-xiang-lian-biao-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2036.%20%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E4%B8%8E%E5%8F%8C%E5%90%91%E9%93%BE%E8%A1%A8.md) | 栈、树、深度优先搜索、二叉搜索树、链表、二叉树、双向链表 | 中等 |
| 剑指 Offer 37 | [序列化二叉树](https://leetcode-cn.com/problems/xu-lie-hua-er-cha-shu-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2037.%20%E5%BA%8F%E5%88%97%E5%8C%96%E4%BA%8C%E5%8F%89%E6%A0%91.md) | 树、深度优先搜索、广度优先搜索、设计、字符串、二叉树 | 困难 |
| 剑指 Offer 38 | [字符串的排列](https://leetcode-cn.com/problems/zi-fu-chuan-de-pai-lie-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2038.%20%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%9A%84%E6%8E%92%E5%88%97.md) | 字符串、回溯 | 中等 |
| 剑指 Offer 39 | [数组中出现次数超过一半的数字](https://leetcode-cn.com/problems/shu-zu-zhong-chu-xian-ci-shu-chao-guo-yi-ban-de-shu-zi-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2039.%20%E6%95%B0%E7%BB%84%E4%B8%AD%E5%87%BA%E7%8E%B0%E6%AC%A1%E6%95%B0%E8%B6%85%E8%BF%87%E4%B8%80%E5%8D%8A%E7%9A%84%E6%95%B0%E5%AD%97.md) | 数组、哈希表、分治、计数、排序 | 简单 |
| 剑指 Offer 40 | [最小的k个数](https://leetcode-cn.com/problems/zui-xiao-de-kge-shu-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2040.%20%E6%9C%80%E5%B0%8F%E7%9A%84k%E4%B8%AA%E6%95%B0.md) | 数组、分治、快速选择、排序、堆（优先队列） | 简单 |
| 剑指 Offer 41 | [数据流中的中位数](https://leetcode-cn.com/problems/shu-ju-liu-zhong-de-zhong-wei-shu-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2041.%20%E6%95%B0%E6%8D%AE%E6%B5%81%E4%B8%AD%E7%9A%84%E4%B8%AD%E4%BD%8D%E6%95%B0.md) | 设计、双指针、数据流、排序、堆（优先队列） | 困难 |
| 剑指 Offer 42 | [连续子数组的最大和](https://leetcode-cn.com/problems/lian-xu-zi-shu-zu-de-zui-da-he-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2042.%20%E8%BF%9E%E7%BB%AD%E5%AD%90%E6%95%B0%E7%BB%84%E7%9A%84%E6%9C%80%E5%A4%A7%E5%92%8C.md) | 数组、分治、动态规划 | 简单 |
| 剑指 Offer 45 | [把数组排成最小的数](https://leetcode-cn.com/problems/ba-shu-zu-pai-cheng-zui-xiao-de-shu-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2045.%20%E6%8A%8A%E6%95%B0%E7%BB%84%E6%8E%92%E6%88%90%E6%9C%80%E5%B0%8F%E7%9A%84%E6%95%B0.md) | 贪心、字符串、排序 | 中等 |
| 剑指 Offer 46 | [把数字翻译成字符串](https://leetcode-cn.com/problems/ba-shu-zi-fan-yi-cheng-zi-fu-chuan-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2046.%20%E6%8A%8A%E6%95%B0%E5%AD%97%E7%BF%BB%E8%AF%91%E6%88%90%E5%AD%97%E7%AC%A6%E4%B8%B2.md) | 字符串、动态规划 | 中等 |
| 剑指 Offer 47 | [礼物的最大价值](https://leetcode-cn.com/problems/li-wu-de-zui-da-jie-zhi-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2047.%20%E7%A4%BC%E7%89%A9%E7%9A%84%E6%9C%80%E5%A4%A7%E4%BB%B7%E5%80%BC.md) | 数组、动态规划、矩阵 | 中等 |
| 剑指 Offer 48 | [最长不含重复字符的子字符串](https://leetcode-cn.com/problems/zui-chang-bu-han-zhong-fu-zi-fu-de-zi-zi-fu-chuan-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2048.%20%E6%9C%80%E9%95%BF%E4%B8%8D%E5%90%AB%E9%87%8D%E5%A4%8D%E5%AD%97%E7%AC%A6%E7%9A%84%E5%AD%90%E5%AD%97%E7%AC%A6%E4%B8%B2.md) | 哈希表、字符串、滑动窗口 | 中等 |
| 剑指 Offer 49 | [丑数](https://leetcode-cn.com/problems/chou-shu-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2049.%20%E4%B8%91%E6%95%B0.md) | 哈希表、数学、动态规划、堆（优先队列） | 中等 |
| 剑指 Offer 50 | [第一个只出现一次的字符](https://leetcode-cn.com/problems/di-yi-ge-zhi-chu-xian-yi-ci-de-zi-fu-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2050.%20%E7%AC%AC%E4%B8%80%E4%B8%AA%E5%8F%AA%E5%87%BA%E7%8E%B0%E4%B8%80%E6%AC%A1%E7%9A%84%E5%AD%97%E7%AC%A6.md) | 队列、哈希表、字符串、计数 | 简单 |
| 剑指 Offer 51 | [数组中的逆序对](https://leetcode-cn.com/problems/shu-zu-zhong-de-ni-xu-dui-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2051.%20%E6%95%B0%E7%BB%84%E4%B8%AD%E7%9A%84%E9%80%86%E5%BA%8F%E5%AF%B9.md) | 树状数组、线段树、数组、二分查找、分治、有序集合、归并排序 | 困难 |
| 剑指 Offer 52 | [两个链表的第一个公共节点](https://leetcode-cn.com/problems/liang-ge-lian-biao-de-di-yi-ge-gong-gong-jie-dian-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2052.%20%E4%B8%A4%E4%B8%AA%E9%93%BE%E8%A1%A8%E7%9A%84%E7%AC%AC%E4%B8%80%E4%B8%AA%E5%85%AC%E5%85%B1%E8%8A%82%E7%82%B9.md) | 哈希表、链表、双指针 | 简单 |
| 剑指 Offer 53 - I | [在排序数组中查找数字 I](https://leetcode-cn.com/problems/zai-pai-xu-shu-zu-zhong-cha-zhao-shu-zi-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2053%20-%20I.%20%E5%9C%A8%E6%8E%92%E5%BA%8F%E6%95%B0%E7%BB%84%E4%B8%AD%E6%9F%A5%E6%89%BE%E6%95%B0%E5%AD%97%20I.md) | 数组、二分查找 | 简单 |
| 剑指 Offer 53 - II | [0～n-1中缺失的数字](https://leetcode-cn.com/problems/que-shi-de-shu-zi-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2053%20-%20II.%200%EF%BD%9En-1%E4%B8%AD%E7%BC%BA%E5%A4%B1%E7%9A%84%E6%95%B0%E5%AD%97.md) | 位运算、数组、哈希表、数学、二分查找 | 简单 |
| 剑指 Offer 54 | [二叉搜索树的第k大节点](https://leetcode-cn.com/problems/er-cha-sou-suo-shu-de-di-kda-jie-dian-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2054.%20%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E7%9A%84%E7%AC%ACk%E5%A4%A7%E8%8A%82%E7%82%B9.md) | 树、深度优先搜索、二叉搜索树、二叉树 | 简单 |
| 剑指 Offer 55 - I | [二叉树的深度](https://leetcode-cn.com/problems/er-cha-shu-de-shen-du-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2055%20-%20I.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E6%B7%B1%E5%BA%A6.md) | 树、深度优先搜索、广度优先搜索、二叉树 | 简单 |
| 剑指 Offer 55 - II | [平衡二叉树](https://leetcode-cn.com/problems/ping-heng-er-cha-shu-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2055%20-%20II.%20%E5%B9%B3%E8%A1%A1%E4%BA%8C%E5%8F%89%E6%A0%91.md) | 树、深度优先搜索、二叉树 | 简单 |
| 剑指 Offer 57 | [和为s的两个数字](https://leetcode-cn.com/problems/he-wei-sde-liang-ge-shu-zi-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2057.%20%E5%92%8C%E4%B8%BAs%E7%9A%84%E4%B8%A4%E4%B8%AA%E6%95%B0%E5%AD%97.md) | 数组、双指针、二分查找 | 简单 |
| 剑指 Offer 57 - II | [和为s的连续正数序列](https://leetcode-cn.com/problems/he-wei-sde-lian-xu-zheng-shu-xu-lie-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2057%20-%20II.%20%E5%92%8C%E4%B8%BAs%E7%9A%84%E8%BF%9E%E7%BB%AD%E6%AD%A3%E6%95%B0%E5%BA%8F%E5%88%97.md) | 数学、双指针、枚举 | 简单 |
| 剑指 Offer 58 - I | [翻转单词顺序](https://leetcode-cn.com/problems/fan-zhuan-dan-ci-shun-xu-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2058%20-%20I.%20%E7%BF%BB%E8%BD%AC%E5%8D%95%E8%AF%8D%E9%A1%BA%E5%BA%8F.md) | 双指针、字符串 | 简单 |
| 剑指 Offer 58 - II | [左旋转字符串](https://leetcode-cn.com/problems/zuo-xuan-zhuan-zi-fu-chuan-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2058%20-%20II.%20%E5%B7%A6%E6%97%8B%E8%BD%AC%E5%AD%97%E7%AC%A6%E4%B8%B2.md) | 数学、双指针、字符串 | 简单 |
| 剑指 Offer 59 - I | [滑动窗口的最大值](https://leetcode-cn.com/problems/hua-dong-chuang-kou-de-zui-da-zhi-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2059%20-%20I.%20%E6%BB%91%E5%8A%A8%E7%AA%97%E5%8F%A3%E7%9A%84%E6%9C%80%E5%A4%A7%E5%80%BC.md) | 队列、滑动窗口、单调队列、堆（优先队列） | 困难 |
| 剑指 Offer 59 - II | [队列的最大值](https://leetcode-cn.com/problems/dui-lie-de-zui-da-zhi-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2059%20-%20II.%20%E9%98%9F%E5%88%97%E7%9A%84%E6%9C%80%E5%A4%A7%E5%80%BC.md) | 设计、队列、单调队列 | 中等 |
| 剑指 Offer 61 | [扑克牌中的顺子](https://leetcode-cn.com/problems/bu-ke-pai-zhong-de-shun-zi-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2061.%20%E6%89%91%E5%85%8B%E7%89%8C%E4%B8%AD%E7%9A%84%E9%A1%BA%E5%AD%90.md) | 数组、排序 | 简单 |
| 剑指 Offer 62 | [圆圈中最后剩下的数字](https://leetcode-cn.com/problems/yuan-quan-zhong-zui-hou-sheng-xia-de-shu-zi-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2062.%20%E5%9C%86%E5%9C%88%E4%B8%AD%E6%9C%80%E5%90%8E%E5%89%A9%E4%B8%8B%E7%9A%84%E6%95%B0%E5%AD%97.md) | 递归、数学 | 简单 |
| 剑指 Offer 63 | [股票的最大利润](https://leetcode-cn.com/problems/gu-piao-de-zui-da-li-run-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2063.%20%E8%82%A1%E7%A5%A8%E7%9A%84%E6%9C%80%E5%A4%A7%E5%88%A9%E6%B6%A6.md) | 数组、动态规划 | 中等 |
| 剑指 Offer 64 | [求1+2+…+n](https://leetcode-cn.com/problems/qiu-12n-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2064.%20%E6%B1%821%2B2%2B%E2%80%A6%2Bn.md) | 位运算、递归、脑筋急转弯 | 中等 |
| 剑指 Offer 65 | [不用加减乘除做加法](https://leetcode-cn.com/problems/bu-yong-jia-jian-cheng-chu-zuo-jia-fa-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2065.%20%E4%B8%8D%E7%94%A8%E5%8A%A0%E5%87%8F%E4%B9%98%E9%99%A4%E5%81%9A%E5%8A%A0%E6%B3%95.md) | 位运算、数组 | 简单 |
| 剑指 Offer 66 | [构建乘积数组](https://leetcode-cn.com/problems/gou-jian-cheng-ji-shu-zu-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2066.%20%E6%9E%84%E5%BB%BA%E4%B9%98%E7%A7%AF%E6%95%B0%E7%BB%84.md) | 数组、前缀和 | 中等 |
| 剑指 Offer 67 | [把字符串转换成整数](https://leetcode-cn.com/problems/ba-zi-fu-chuan-zhuan-huan-cheng-zheng-shu-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2067.%20%E6%8A%8A%E5%AD%97%E7%AC%A6%E4%B8%B2%E8%BD%AC%E6%8D%A2%E6%88%90%E6%95%B4%E6%95%B0.md) | 字符串 | 中等 |
| 剑指 Offer 68 - I | [二叉搜索树的最近公共祖先](https://leetcode-cn.com/problems/er-cha-sou-suo-shu-de-zui-jin-gong-gong-zu-xian-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2068%20-%20I.%20%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E7%9A%84%E6%9C%80%E8%BF%91%E5%85%AC%E5%85%B1%E7%A5%96%E5%85%88.md) | 树、深度优先搜索、二叉搜索树、二叉树 | 简单 |
| 剑指 Offer 68 - II | [二叉树的最近公共祖先](https://leetcode-cn.com/problems/er-cha-shu-de-zui-jin-gong-gong-zu-xian-lcof/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%2068%20-%20II.%20%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E6%9C%80%E8%BF%91%E5%85%AC%E5%85%B1%E7%A5%96%E5%85%88.md) | 树、深度优先搜索、二叉树 | 简单 |
| 剑指 Offer II 116 | [朋友圈](https://leetcode-cn.com/problems/bLyHh0/) | [Python](https://github.com/itcharge/LeetCode-Py/blob/main/Solutions/%E5%89%91%E6%8C%87%20Offer%20II%20116.%20%E6%9C%8B%E5%8F%8B%E5%9C%88.md) | 深度优先搜索、广度优先搜索、并查集、图 | 中等 |