# herokuOnedrive
1，打开 heroku.com 注册；  
2，新建一个app；  
3，在app里面deploy代码，选用绑定github的方式（在这之前把代码fork过去）；  
4，使用给的url访问，并开始安装，获得token后，在Settings里面的Config Vars（类似环境变量）里面添加refresh_token。  
     
heroku的环境变量有点好处就是可以存放超长，不像SCF只能放128个。    

整体是原来的代码，所以设置方法都是在环境变量添加；  

代码：https://github.com/qkqpttgf/herokuOnedrive  
DEMO：https://herooneindex.herokuapp.com/  
DEMO2：https://rinm.herokuapp.com/  
管理密码：y  
  
heroknu其实很多人在用了，还能学习科学。也有人直接搬oneindex上去用了，但要安装完后带着token文件一起上传，不然现场安装token存不住。  
