## MySQLインストール手順
1. 下記URLよりインストール物件を入手し、インストールを行う

    [〇インストール物件はここから入手](https://downloads.mysql.com/archives/installer/])

   ![1](image1.png) 
    
1. Installer画面が起動したら下記画面が表示されるので「Full」を選択し、「Next」で次へ進む

   ![2](image2.png) 
   
1. 「Execute」を選択し、すべてインストール出来たら「Next」で次へ進む

   ![3](image3.png) 

   ![4](image4.png) 
    

1. 確認を行い、「Next」で次へ進む

   ![5](image5.png) 

1. Standalone MySQL Serverを選択し、「Next」で次へ進む

   ![6](image6.png) 

1. 確認を行い、「Next」で次へ進む

   ![7](image7.png)

1. パスワード「root」を設定し、「Next」で次へ進む

   ![8](image8.png) 

1. 確認を行い、「Next」で次へ進む

   ![9](image9.png)

1. 「Execute」を選択し、すべてインストール出来たら「Next」で次へ進む

   ![10](image10.png)

1. 確認を行い、「Next」で次へ進む

   ![11](image11.png)

1. 確認を行い、「Next」で次へ進む

   ![12](image12.png)

1. パスワードを入力し、succeededが表示されたら「Next」で次へ進む

   ![13](image13.png)

1. 「Execute」を選択し、すべてインストール出来たら「Next」で次へ進む

   ![14](image814.png)

1. 確認を行い、「Next」で次へ進む

   ![15](image15.png)

1. 「Finish」を押下後、下記コマンドを入力しSQLに接続できるか確認を行う。
   > `cd C:/Program Files/MySQL/MySQL Server 5.7/bin`
   >
   >`mysqld --version`
   >
   >`mysql -u root -p`
   >
   >**(※設定したパスワードを入力)**
   >
   >`quit`←ログアウト
   

   **下記実行結果**

   ![16](image16.png)



