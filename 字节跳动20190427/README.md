字节跳动笔试题目  
一、母牛从3-7岁初每年会生产1头母牛，10岁后死亡（10岁仍然存活）。假设初始有1头刚出生的母牛，请问第n年有多少头母牛？（年从第一年开始计数）  
注：第3年初会出生第一头牛，故第3年有两头母牛  
    第5年初第3年出生的牛会生产，故第五年有5头母牛。  
输入：3  
输出：2  
输入：5  
输出：5  
输入：12  
输出：123  
二、小包最近迷上了一款叫做雀魂的麻将游戏，但是这个游戏规则太复杂。新规则麻将如下：  
1.总共有36张牌，每张牌是1~9.每个数字四张牌。  
2.你手里有其中的14张牌，如果这14张牌满足如下条件，即算作和牌  
* 14张牌中有2张相同数字的牌，称为雀头  
* 除去上述2张牌，剩下12张牌可以组成4个顺子或刻子。顺子的意思是递增的连续3个数字牌（例如234，567等），刻子的意思是相同数字的3个数字牌（例如111）  
例如：  
1 1 1 2 2 2 6 6 6 7 7 7 9 9可以组成1，2，6，7的4个刻子和9的雀头，可以和牌  
1 1 1 1 2 2 3 3 5 6 7 7 8 9用1做雀头，组123，123，567，789的四个顺子，可以和牌  
1 1 1 2 2 2 3 3 3 5 6 7 7 9无论用1 2 3 7哪个做雀头，都无法组成和牌的条件  
现在，小包从36张牌中抽取了13张牌，他想知道在剩下的23张牌中，再取一张牌，取到哪几种数字牌可以和牌  
输入描述：输入只有一行，包含13个数字  
  
三、万万没想到之抓捕孔连顺  
1.我们再字节跳动大街的N个建筑中选定3个埋伏地点  
2.为了相互照应，相距最远的两名特工之间距离不超过D  
给定N、D以及可选建筑的坐标，计算在这次行动中，共有多少种埋伏选择。  
注意：  
* 两个特工不能埋伏在同一地点  
* 三个特工是等价的，即同样的位置组合（a,b,c）只算一种埋伏，不能因特工之间互换位置而重复使用  
  
四、给定一个长度为n的，仅包含0，1的数列。例如1，0，0，1，1，1，0，1我们可以轻易算出，它的最长全1区间长度为3.从数组的第4个数数到第6个数。现在你获得了k次可以将位置上的0变为1的机会，但你可以不用完你的所有机会。请你给出，你使用了你的变化机会后，这个数列的最长全1区间最大是多少。   
输入描述：输入第一行是2个整数n和k，代表数组长度和你的变化机会    
         输入第二行是n个整数，每个整数是0或1.代表初始数列
