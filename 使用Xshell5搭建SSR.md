## 使用Xshell5搭建SSR

####  	1. 购买服务器

​		根据[教程](<https://www.freeluffy.com/ss-server-on-vultr/>)提示登陆购买服务器

#### 	2. 启动服务器

​		启动[服务器](https://my.vultr.com/)

#### 	3. 在windows 环境下使用Xshell 远程Vultr VPS

​		根据[教程](https://www.vultrblog.com/windows-xshell-vultr-vps/.html)

#### 	4. 使用Xshell搭建SSR

​		根据[教程](<http://feelsight.cn/post/68.html>)	

​		*部署管理脚本*

```typescript
yum -y install wget

wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/ssr.sh && chmod +x ssr.sh && bash ssr.sh
```

​		*快捷管理命令*

```typescript
bash ssr.sh
```



​	

