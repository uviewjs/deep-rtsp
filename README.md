# deep-rtsp
介绍
快速接入海康，大华，宇视，天地伟业，三星等摄像头厂家的h264编码摄像头 输入图片说明

#### 软件架构
使用golang和vue进行构建

#### 操作步骤
`1.[ git clone https://gitee.com/deep-rtsp/deep-rtsp.git](https://github.com/uviewjs/deep-rtsp.git) `
2.将文件上传至服务器指定目录

#### 进入目标目录
`cd deep-rtsp`
#### 赋予执行权限
`sudo chmod u+x deep-rtsp`
#### 启动程序
`sudo ./deep-rtsp`
#### 访问服务 运行成功后，通过以下路径访问： `http://服务器IP:10088/app`
#### 注意事项
确保服务器已安装 tar 工具（一般系统默认自带）。 执行命令时需具备 sudo 权限（或使用 root 用户操作）。 若访问失败，检查服务器防火墙是否放行 `10088` `10087` 端口。

#### 参与贡献
汪小敏同学
