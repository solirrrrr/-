华为实习笔试题目  
一、输入的字符串超过8个字符的，按8个截一段，最后不足8个的补0到8个，最后将重新得到的字符串按升序排列  
输入：输入一个数字N ，N个字符串 ，中间以空格隔开  
2  abc 123456789   
输出：排序后的字符串  
12345678 90000000 abc00000  
二、输入一个字符串，含有括号（大括号，小括号，中括号），数字和字母，数字（n）之后必跟一个括号（测试用例里的括号都是匹配的），代表括号内的字符串重复（n）次。括号里可以有嵌套，即括号里含有括号。将结果字符串逆序输出  
输入：abc3(A)  
输出: AAAcba  
输入：abc2(a3(b))  
输出：bbbabbbacba  
三、输入一个矩阵，矩阵中每个点都有一个高度，每个点可以朝上下左右四个方向走，并且下个点的高度必须大于当前点的高度，访问过的节点不能再访问。问小明从起点到终点总共有多少条路径.  
输入:  
5 4  
0 1 0 0  
0 2 3 3  
0 3 0 0  
0 4 5 6  
0 7 6 0  
0 1 4 1  
输出：  
2
