# 更新SDK

## 更新
在需要更新的SDK根目录下执行：  
```
# 如果没有拉取远程仓库,需要先拉取对应bundle仓库
git clone git@github.com:FireflyTeam/bundle.git -b rkxxxx_linux_bundle
# 更新
./bundle/update rkxxxx_linux_bundle
```
更新后的代码会放在FETCH_HEAD分支中，接下来就可以做代码合并更新。  
