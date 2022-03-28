# racktables
IDC资产管理"RackTables"

- 部署方法   
 1:docker build -t . rackrables:v1   
 2:下载最新版https://www.racktables.org/ 拷贝到volume中启动即可.  
 3:运行容器   
 ```
 sudo docker run --privileged -ti -p 9199:9199 --name=ops_racktables --net=jms_net -d racktables:v2
 ```

- 机柜视图/地址管理/硬件管理/拓扑等信息
![image](https://user-images.githubusercontent.com/19662303/160372949-84504848-e43e-4d99-a3ae-03b337ca4c2d.png).  
![image](https://user-images.githubusercontent.com/19662303/160374279-e7996b47-c479-4564-87cc-5b48657933ed.png)

  

