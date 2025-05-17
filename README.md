# 中药智选——从0开始的Web开发
## 用户使用说明：
### 1、配置数据库
首先先创建mysql数据库，运行文件当前目录下的.sql文件，将数据库导入到自己的数据库中。
接着在application.yml 中配置自己的username 和 password
![image](https://github.com/user-attachments/assets/2db5af20-3e07-4ae3-b083-f6ca3be79d00)
### 2、使用说明
一共有三个账号
患者账号
账号 xiaobai 
密码 1234
医生账号
账号 doctor
密码 1234
管理员账号
账号 admin
密码 1234
登录进去后 不同用户有不同的使用界面和操作方法
### 3、导入大模型api
获取到deepseek/ChatGpt的api 后
替换掉application.yml的 网址和 key 
![image](https://github.com/user-attachments/assets/541629f0-8301-4ccd-9f69-31aac09e4a32)
接着就可以使用用户端的大模型了
### 4、运行
首先运行StartApplication.java
接着在本地输入localhost:8080/login 就可以进入到我们的网页了
### 5、功能展示
![image](https://github.com/user-attachments/assets/6429bf6f-ed5b-4af9-be18-308f8ede47a5)
![image](https://github.com/user-attachments/assets/cf0a7efc-6cf7-4301-92b2-591cee242fb3)
![image](https://github.com/user-attachments/assets/4310a5b0-68e1-40c8-99f2-873060575803)
![image](https://github.com/user-attachments/assets/db5e14d8-4d1b-43ce-9f6b-b308345167ce)
![image](https://github.com/user-attachments/assets/821e97f6-c2c3-45b7-a570-309422dc817c)
![image](https://github.com/user-attachments/assets/b7c6bc25-f339-4c9c-b34f-828d54c98fa1)
![image](https://github.com/user-attachments/assets/62f1813e-9d5c-4227-9193-12133f2c0293)
