# OpenClashConfig
针对OpenWRT固件环境下，OpenClash的相关指导及配置参数文件修改




## 说明
0. 本项目仅用于学习交流，请勿用于商业用途
1. 本项目仅针对OpenWRT固件环境下，OpenClash的相关指导及配置参数文件修改

## 参考资料
1. 不良林 - 解决订阅转换节点被盗用和无法转换大量节点，本地订阅转换教程，v2ray转clash，clash转v2ray，各种格式通用转换，节点格式转换，方便快捷(https://www.youtube.com/watch?v=UxvjT_nHLo4)
2. 不良林 - 【高危漏洞】大量用户节点被盗！实战演示获取所有人的节点和机场订阅链接，使用在线订阅转换节点安全预警，Subconverter订阅转换工具接口泄漏配置文件token，导致RCE安全漏洞，所有版本统统中招(https://www.youtube.com/watch?v=FclVhxp1g0Y&t=107s)
3. 安格视界 - 30分钟 OpenClash 最强攻略，FakeIP 最佳部署，无DNS污染，无DNS泄露，自动选择、负载均衡，丝滑切换节点，永不断网，全网最强配置模版免费送！完美网络9(https://www.youtube.com/watch?v=S2l_0g4EOHk)
4. Subconverter本地订阅转换软件 - https://github.com/tindy2013/subconverter



## 额外说明
1. 确保本地环境完成git的安装
2. 在本地创建项目目录 如：/Users/kennyyang/Documents/07_Trae_Workspace/ExcelMasterGUI。
3. 在 GitHub 上创建了一个私有仓库 如：https://github.com/shakenny/ExcelMasterGUI，并初始化了 .gitignore、README.md 和 LICENSE 文件。
4. 将本地项目与 GitHub 仓库关联
    4.1 初始化本地 Git 仓库
    ```
    cd /Users/kennyyang/Documents/07_Trae_Workspace/ExcelMasterGUI
    git init
    ```
    4.2 关联远程仓库
    ```
    git remote add origin https://github.com/shakenny/ExcelMasterGUI.git
    ```
    4.3 拉取远程仓库内容
    ```
    git pull origin main
    ```
    4.4 提交本地更改
    ```
    git add .
    git commit -m "Initial commit: Connect local project to GitHub"
    git push -u origin main
    ```
