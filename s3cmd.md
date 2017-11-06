開啟VS-CODE

commamd+shift+P

輸入code

選擇 殼層命令:在PATH中安裝"code"命令
![](/s3cmd_pic/s3cmd_pic01.png)

開啟CMD輸入

/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
![](/s3cmd_pic/s3cmd_pic02.png)

brew install s3cmd
![](/s3cmd_pic/s3cmd_pic03.png)

s3cmd --configure
![](/s3cmd_pic/s3cmd_pic04.png)
API KEY
![](/s3cmd_pic/s3cmd_pic09.png)

host_base = s3.hicloud.net.tw

host_bucket = %(bucket)s.s3.hicloud.net.tw
![](/s3cmd_pic/s3cmd_pic05.png)

![](/s3cmd_pic/s3cmd_pic06.png)

code .s3cfg
![](/s3cmd_pic/s3cmd_pic07.png)


![](/s3cmd_pic/s3cmd_pic08.png)
host_base = s3.hicloud.net.tw

host_bucket = %(bucket)s.s3.hicloud.net.tw

signature_v2 = True