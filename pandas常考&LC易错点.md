# SQL常考题 
dense_rank() over (partition by A order by B)
date_trunc('month', order_date) AS month
price - LAG(price) OVER (PARTITION BY stock_id ORDER BY date) AS price_diff
取最大值 Select sybl, max(price) as max from table
取第三大就要用rank

# Python pandas常考题 #############
pd.merge(stock, stock_prices, how = '', on = 'xx')
pd.pct_change()
data = pd.read_csv()
如何筛选
df[df['col1' >= 10]][['col1','col2']]
df.loc[pd['col1'] >= 10, ['col1', 'col2']]  ##### 更规范
stock.iloc[:,0]取第一行

Q. series和其他数据结构的区别？
having index

Q. VBA sub vs function?
sub does not return a res

Q. tuple vs list?
可变性

Q. interface vs abstract class
interface更加什么都没定义

# leetcode易错点 ################
42接雨水 right_Max从n-1定义
166 步骤 易错点：mapping的方法，insert方法 遇见就插入
anagrams[tuple(char_cnt)].append(str)   tuple可以作为key. value可以做append
return list(anagrams.values()) 记住转换list
high five 易错点：id要互相对应，整数除法，id排序
longestCommonSubsequence 1143 common问题 二维dp
生命游戏 def count(i,j) 4种状态 2种状态 def count怎么写 new_col new_row 判断边界 if 加入
分为讲思路和implement两部分。implement
implement代码的时候是先写主要结构还是先考虑corner case

dfs里面base case容易掉return
