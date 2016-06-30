### OS X Custom

删除jetbrains产品自带的jre
```bash
sudo find /Applications/* -name *jre*|xargs rm -rf
```

vim语法高亮等
```bash
curl https://raw.githubusercontent.com/menghx/misc4linux/master/vimrc > ~/.vimrc
```

同步环境变量
```bash
curl https://raw.githubusercontent.com/menghx/misc4linux/master/com.iosxc.mxwork.plist > ~/Library/LaunchAgents/com.iosxc.mxwork.plist
launchctl load ~/Library/LaunchAgents/com.iosxc.mxwork.plist
launchctl start ~/Library/LaunchAgents/com.iosxc.mxwork.plist
```

自定义Path
```bash
sudo curl https://raw.githubusercontent.com/menghx/misc4linux/master/osxwork > /etc/path.d/go
```