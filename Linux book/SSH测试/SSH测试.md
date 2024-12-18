# SSH测试：

#### 1.先安装一个openssh-server:

```
sudo apt install openssh-server
```

![屏幕截图 2022-12-19 151813](D:\Desktop\Linux book\SSH测试\imgs\ssh1.png)



#### 2.启动服务:

```
sudo systemctl restart sshd
```

#### 3.查看服务:

```
sudo systemctl status sshd
```

![屏幕截图 2022-12-19 151902](D:\Desktop\Linux book\SSH测试\imgs\ssh2.png)



#### 4.查看自己的IP地址

```
ip a
```



![屏幕截图 2022-12-19 151954](D:\Desktop\Linux book\SSH测试\imgs\ssh3.png)



#### 5.输入IP开始测试