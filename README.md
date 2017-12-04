# CDChatList
iOS 聊天界面的组件


想要提交代码请fork下，然后pullrequest，谢谢


## usage

>  作为pod依赖

    在podfile中添加
    source 'git@git-ma.paic.com.cn:aat/AATComponent_iOS.git'

```
 pod 'CDChatList'
```

>  将pod打包成framework

```
 pod package CDChatList.podspec --force  -verbose
```

>  将pod打包成静态库（需要手动处理资源文件）

```
 pod package CDChatList.podspec --library  --force  -verbose
```

## 更新

> 记得打tag
git tag -m "first release" "0.1.0"
$ git push --tags     #推送tag到远端仓库

> 添加前的检查
pod lib lint --allow-warnings -veribse

> 推送到git-ma仓库
pod repo push AATComponent_iOS CDChatList.podspec --verbose --allow-warnings
