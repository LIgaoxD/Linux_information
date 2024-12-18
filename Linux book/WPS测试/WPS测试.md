

# 下载WPS



#### 1.		进入浏览器必应搜索WPS，并下载

### ![18](D:\Desktop\Linux book\WPS测试\imgs\18.png)



#### 2.	安装wps



### ![17](D:\Desktop\Linux book\WPS测试\imgs\17.png)

### 

#### 3.	下载完成后通过如下指令进行安装： ---------到Downloads路径

```
cd
Downloads
```

#### 4.	下载完成后，通过如下指令进行安装：

```
sudo dpkg -i wps-office_11.1.0.11664_amd64.deb
```

![10](D:\Desktop\Linux book\WPS测试\imgs\10.png)



#### 5.	点击Activities



### ![20](D:\Desktop\Linux book\WPS测试\imgs\20.png)



###### 5.1	搜索wps

### ![21](D:\Desktop\Linux book\WPS测试\imgs\21.png)



###### 5.2	进入WPS会要求同意一个桌面协议，然后进入

### ![22](D:\Desktop\Linux book\WPS测试\imgs\22.png)



#### 6.	下载符号字体

###### 6.1	浏览器搜索服务器    下载wps-fonts.zip

```
http://web.tecxz.com:9080/file/
```

### ![19](D:\Desktop\Linux book\WPS测试\imgs\19.png)

### 

###### 6.2	解压资源包

```
unzip wps-fonts.zip
```

###### 			可以检查一下有七个包

```
ls /usr/share/fonts/wps-office
```

![11](D:\Desktop\Linux book\WPS测试\imgs\11.png)

###### 		@	一定注意是在Downloads下，如果没有则

### ![9](D:\Desktop\Linux book\WPS测试\imgs\9.png)

#### 7.	将文件移动到固定的文件夹中,顺便改个名字！

```
sudo mv wps-fonts-master/wps/* /usr/share/fonts/wps-office
```

#### 8.	更新当前用户下面的字体目录将文件移动到固定的文件夹中,顺便改个名字！

```
fc-cache -fv
```

### ![12](D:\Desktop\Linux book\WPS测试\imgs\12.png)