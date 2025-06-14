# SQL常考题 
dense_rank() over (partition by A order by B) <br>
date_trunc('month', order_date) AS month <br>
price - LAG(price) OVER (PARTITION BY stock_id ORDER BY date) AS price_diff <br>
取最大值 Select sybl, max(price) as max from table <br>
取第三大就要用rank

# Python pandas常考题
pd.merge(stock, stock_prices, how = '', on = 'xx') <br>
pd.pct_change() <br>
data = pd.read_csv() <br>
如何筛选 <br>
df[df['col1' >= 10]][['col1','col2']] <br>
df.loc[pd['col1'] >= 10, ['col1', 'col2']]  ##### 更规范 <br>
stock.iloc[:,0]取第一行

#### series和其他数据结构的区别？
having index
#### VBA sub vs function?
sub does not return a res
#### tuple vs list?
可变性

#### interface vs abstract class
interface更加什么都没定义

# leetcode易错点
42接雨水 right_Max从n-1定义 <br>
166 步骤 易错点：mapping的方法，insert方法 遇见就插入 <br>
anagrams[tuple(char_cnt)].append(str)   tuple可以作为key. value可以做append <br>
return list(anagrams.values()) 记住转换list <br>
high five 易错点：id要互相对应，整数除法，id排序 <br>
longestCommonSubsequence 1143 common问题 二维dp <br>
生命游戏 def count(i,j) 4种状态 2种状态 def count怎么写 new_col new_row 判断边界 if 加入 <br>
分为讲思路和implement两部分。implement <br>
implement代码的时候是先写主要结构还是先考虑corner case <br>
dfs里面base case容易掉return
