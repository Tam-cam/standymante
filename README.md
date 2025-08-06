# common

这个项目下主要放共用的文 主要是 model rootconfig serviceApi 等

# goctl
复制目录下的goctl goctl-swagger 到 gobin 目录下面，赋予执行权限即可

# 生成model的命令
    // 在common的目录下
    goctl model mongo -api api-model/xxxModel/xxx.api

# 生成api结构命令
 
    // 任意进程目录下 
    goctl api go -api doc/xxx.api 


# 生成swagger json的命令
    goctl api plugin  -api doc/xxx.api 


