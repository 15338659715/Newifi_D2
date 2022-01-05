# 第一步去注册GITHUB帐号登录后。
# https://github.com/hackyes/OpenWrt-CI
# 克隆上面仓库到自己的仓库里


# https://hackyes.github.io/openwrt-menuconfig/index.html
# 打开上面链接在线生成配置文件
# 选择自己要编译的插件等
# 配置完后复制内容信息，修改仓库文件 .config
# 把配置全部替换成你刚才生成的。
# 点击右上角 star 变为实心后就开始编译了。

# OpenWrt云编译

#### 每天凌晨2点自动编译
#### 大雕仓库 https://github.com/coolsnowwolf/lede

### 把本仓库克隆到自己的仓库里
#### 打开下面链接生成.config配置文件
#### [https://hackyes.github.io/openwrt-menuconfig/index.html](https://hackyes.github.io/openwrt-menuconfig/index.html)

#### 编辑 .config 文件，把内容清空替换成上面链接生成的配置内容

### 点这右上角 ✰Star  变成 ★Unstar 即可开始编译

### 等待编译成功后，到Actions里下载固件即可
