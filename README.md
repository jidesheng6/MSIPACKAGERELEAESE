# NginxSetup.exe

> 该文件为openresty-1.21.4.1打包后的安装包，已添加常见Nginx配置参数，如：去除Server头，uwsgi、fastcgi、proxy的超时配置，uwsgi、fastcgi、proxy的buffer等等配置。

### 默认基础加固配置一览

![image](https://user-images.githubusercontent.com/25132549/224351457-94b79aa2-d887-42ae-b406-60c6f22a6b8d.png)

![image](https://user-images.githubusercontent.com/25132549/224351522-d7e65bc9-6c9d-4e5e-a4c5-60ecd06cb091.png)

![image](https://user-images.githubusercontent.com/25132549/224351585-615e2551-69c4-4528-b8d3-7dbefd932835.png)


### 1、安装
- 一般情况下不建议安装在默认目录，可能会导致Nginx因为权限问题无法启动，安装包内自带vc++运行库，安装之前会自动检测进行安装

![image](https://user-images.githubusercontent.com/25132549/224347229-2febf7a5-13b3-4f11-a527-b0242bb56b9b.png)

- 安装完毕后，可自行选择是否需要启动测试页和Nginx，如果需要启动测试页，则Nginx必须也启动。

![image](https://user-images.githubusercontent.com/25132549/224347550-61d7d5d0-0bfc-468e-9e69-6abc4d6c97f4.png)

- 默认启动测试页和Nginx后如图所示

![image](https://user-images.githubusercontent.com/25132549/224348155-5f78e507-dfd5-46f2-8e26-5e01d0705785.png)

### 2、注册服务

- 关闭Nginx。无论是否开启Nginx，均建议先点击桌面上的关闭Nginx快捷方式，该快捷方式指向安装目录下的stop_nginx.bat文件

![image](https://user-images.githubusercontent.com/25132549/224348691-456b1176-a768-4dba-a785-400a189ed154.png)

- 注册Nginx服务。安装完毕后，如果需要注册Nginx服务，请在开始菜单搜索Nginx，如下图所示，并点击注册服务，该快捷方式指向安装目录下的install_service.bat文件，由nssm进行服务注册。

![image](https://user-images.githubusercontent.com/25132549/224349193-8b94e5e5-34ca-415e-98fc-9ba6dac6084b.png)

- 提示操作完成后，表示Nginx服务注册成功，并自动启动服务。

![image](https://user-images.githubusercontent.com/25132549/224349755-ca51fb2e-14ff-4169-8e70-23bc6ff1a766.png)


### 3、卸载

**如果需要卸载Nginx，由于部分功能不是安装程序内置，所以需要注意以下两点**

1、如果已经注册了服务，需要先移除服务再进行卸载

2、如果Nginx已经启动，需要关闭Nginx在进行卸载

---

- 移除服务。请点击开始菜单内的移除Nginx服务

![image](https://user-images.githubusercontent.com/25132549/224350556-d461e075-41bb-4627-be91-3806d6dca97c.png)

- 关闭Nginx，请点击桌面上的Nginx快捷方式

![image](https://user-images.githubusercontent.com/25132549/224348691-456b1176-a768-4dba-a785-400a189ed154.png)

- 确认两点满足要求后，开始菜单内点击卸载Nginx图标即可。

![image](https://user-images.githubusercontent.com/25132549/224351046-6a2b3d27-74e2-4c5a-bb2c-b130f06d4084.png)





# XXXX.exe

占位
