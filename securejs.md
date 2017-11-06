# AZTL
開啟VS-CODE
~~~
commamd+shift+P
輸入code
選擇 殼層命令:在PATH中安裝"code"命令
~~~
![](/secure_pic/securejs_pic01.png)

開啟CMD輸入
~~~
code ~/.bash_profile
~~~
![](/secure_pic/securejs_pic02.png)

將路徑修改為securejs的路徑
![](/secure_pic/securejs_pic03.png)

輸入
~~~
source ~/.bash_profile
~~~
![](/secure_pic/securejs_pic04.png)

cd到securejs的路徑輸入
~~~
chmod -R 777 securejs
~~~
![](/secure_pic/securejs_pic07.png)

輸入securejs -v
![](/secure_pic/securejs_pic08.png)

CMD輸入
~~~
securejs -su
~~~
## securejs設定
~~~
Would you like to setup a proxy? (yes/no): no

Enter a nickname for this machine so it can easily be identified on Arxan Developer Portal (AZTL-MAC-PRO05.local): 

Would you like to automatically retrieve a token? (yes/no): yes

Enter ADP username: xxx.xxx@allianz.com.tw

Enter ADP password: 

Is this configuration correct? (yes/no): yes
~~~
