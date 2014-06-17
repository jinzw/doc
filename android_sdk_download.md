1. Android SDK Manager --> Options --> 勾选 Force https://... sources to be Fetched using http://...
2. 修改hosts文件，在文件后面添加
   ```
   #android更新

    203.208.46.146 dl.google.com

    203.208.46.146 dl-ssl.google.com
   ```
   hosts文件路径：
   
   Windows  C:\windows\system32\drivers\etc
   
   Linux  /etc/hosts
