# SQL DML
Data Manipulation Language

    ＋-------＋--------＋
    | select |  檢索   |
    ＋-------＋--------＋
    | insert |   插入  ｜   
    ＋-------＋--------＋
    ｜update |   更新  ｜
    ＋-------＋--------＋
    ｜ delete|   刪除   |
    ＋-------＋--------＋
    
# Query 查詢
    ＋-------＋--------＋

select == query ， 是使用頻率最高的資料庫操作指令。

* 取出資料表中所有欄位資料 from | where (內部結合、外部結合、自我結合)

* 取出資料表中某指定條件成立下的整欄位資料

* 取出資料表中資料並進行群組合計排列

* 取出資料表中資料並進行排序排列

      Select * From <table_name> Where <boolean_expression> Group by <expression> Order By <expression>
      
# Subquery 子查詢或稱副查詢

      main query + Where Exists + sub query 

      main query + From + sub query
      
# 建立資料表 (從 DML 變成 DDL)

   除了 create table 以外，也可用 
   
      Select * Into <new_table_name> From <table_name> 

# So On... 其他操作指令

* Limit 限制查詢結果

* Union 集合資料做聯集運算

*

      


 
  
