# basic-mysql
學習基礎的 SQL 語法
<hr>

**零**<br>
安裝好 SQL 後，建立名稱為 website 的資料庫，並完成指定條件。
![GITHUB]( https://github.com/sky0922/basic-mysql/blob/main/00.jpg)

建立過程如下：<br>
![GITHUB]( https://github.com/sky0922/basic-mysql/blob/main/01.jpg)

**一、**<br>
使用 INSERT 指令新增一筆資料到 user 資料表中，<br>
這筆資料的 username 和 password 欄位必須是 ply。<br>
接著繼續新增至少 4 筆隨意的資料。<br>

**二、**<br>
使用 SELECT 指令取得所有在 user 資料表中的使用者資料。<br>
![GITHUB]( https://github.com/sky0922/basic-mysql/blob/main/02.jpg)

**三、**<br>
使用 SELECT 指令取得 user 資料表中總共有幾筆資料。<br>
![GITHUB]( https://github.com/sky0922/basic-mysql/blob/main/03.jpg)

**四、**<br>
使用 SELECT 指令取得所有在 user 資料表中的使用者資料，並按照 time 欄位，由近到遠排序。<br>
![GITHUB]( https://github.com/sky0922/basic-mysql/blob/main/04.jpg)

**五、**<br>
使用 SELECT 指令取得 user 資料表中第 2 ~ 4 共三筆資料，並按照 time 欄位，由近到遠排序。<br>
![GITHUB]( https://github.com/sky0922/basic-mysql/blob/main/05.jpg)

**六、**<br>
使用 SELECT 指令取得欄位 username 是 ply 的使用者資料。<br>
![GITHUB]( https://github.com/sky0922/basic-mysql/blob/main/06.jpg)

**七、**<br>
使用 SELECT 指令取得欄位 username 是 ply、且欄位 password 也是 ply 的資料。<br>
![GITHUB]( https://github.com/sky0922/basic-mysql/blob/main/07.jpg)

**八、**<br>
使用 UPDATE 指令更新欄位 username 是 ply 的使用者資料，將資料中的 name 欄位改成【丁滿】。<br>
![GITHUB]( https://github.com/sky0922/basic-mysql/blob/main/08.jpg)

**九、**<br>
使用 DELETE 指令刪除所有在 user 資料表中的資料。<br>
![GITHUB]( https://github.com/sky0922/basic-mysql/blob/main/09.jpg)

<hr>

**結合資料表 SQL JOIN 的操作 (Optional)**<br>
建立名稱為 message 的資料表，並完成指定條件。<br>
![GITHUB]( https://github.com/sky0922/basic-mysql/blob/main/10.jpg)

確認資料表格式是否正確及另外兩個資料表內容<br>
![GITHUB]( https://github.com/sky0922/basic-mysql/blob/main/11.jpg)


**一、**<br>
使用 SELECT 搭配 JOIN 的語法，取得所有留言，資料中須包含留言會員的姓名。<br>
![GITHUB]( https://github.com/sky0922/basic-mysql/blob/main/12.jpg)

**二、**<br>
使用 SELECT 搭配 JOIN 的語法，<br>
取得 user 資料表中欄位 username 是 ply 的所有留言，<br>
資料中須包含留言會員的姓名。<br>
![GITHUB]( https://github.com/sky0922/basic-mysql/blob/main/13.jpg)
