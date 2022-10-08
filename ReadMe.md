# 使用说明

修改lite_config.json中的参数即可

subscription：修改为自己的订阅链接即可

testmode: 多线程进行，2为两个线程

其他自己看

## 主要命令（开发）

运行命令：lite.exe --config ./lite_config.json --test ./other/veg.yaml

veg.yml无作用，就是一个简单的占位置的东西

## 使用指南

编译：

    使用pyinstaller打包编译（具体google）
    
提交到仓库：

    git add.
    git commit -m "xxx"
    git push origin main


发行版：

    在配置文件中修改配置后，直接点击ouput.exe即可，生成的v2的无后缀的东西就是订阅了，如有需要可以设置定时任务并提交到自己的仓库啦
    本人这里提供一个定时更新的，是电信的电脑测试的啦：v2ray订阅：
