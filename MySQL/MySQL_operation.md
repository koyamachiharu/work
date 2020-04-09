## MySQL使用手順
1. MySQLにログイン
   >`cd C:/Program Files/MySQL/MySQL Server 5.7/bin`
   >
   >`mysql -u root -p` 
   >
   >**(※設定したパスワードを入力)**

   ![a](image_a.png) 

1. DBの状況確認
   >`show databases;`

   ![b](image_b.png) 

1. DB作成
   >`create database DB名;`
   >
   >※Query OKが出力され、`show databases;`にて作成したDB名が表示されればOK

   ![c](image_c.png) 

1. 使用するDBを選択
   >`use 作成したDB名;`

   ![d](image_d.png) 

1. テーブル作成
   >`create table 作成したいテーブル名(`
   >
   >挿入したいカラム名 型
   >
   >);

   ![e](image_e.png) 

1. テーブル/カラムの確認
   >`desc （テーブル名）;`
   >
   >※Query OK.が出力され、作成したテーブル名・カラム名が表示されればOK

   ![f](image_f.png) 

1. データ追加
   >`insert into テーブル名　values (カラム１に入れたい値,カラム2に入れたい値...);`

   ![g](image_g.png) 

1. データの取得
   >`select （取得したいカラム名1,カラム名2） from テーブル名;`

   ![h](image_h.png) 

   ![i](image_i.png) 