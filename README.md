# filesync
 Linux计算机指定路径的同步工具
 在A计算机运行，同步到指定的目录到B计算机，B计算机无需安装运行。
 
## 条件
 1. 仅能运行在Linux服务器
 2. A、B计算机都需要安装ssh，并开通端口
 3. 需要在B计算机上建立对A计算机的信任关系
 
## 使用方法
### 建立AB计算机的信任关系
  1.在A计算机运行
    $ ssh-keygen -t rsa
  （默认配置既可）
  2.复制A计算机的文件 ~/.ssh/id_rsa.pub 到 B计算机 ~/.ssh/authorized_keys
### 下载安装
 
### 配置
 
### 运行
  
