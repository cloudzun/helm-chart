#添加chart仓库
helm repo add myrepo https://www.cloudzun.com/helm-chart

#查看repo
helm repo list

#搜索chart包
helm search repo myrepo

#安装aspnetapp包
helm install aspnetapp myrepo/aspnetapp

#卸载aspnetapp包
helm uninstall aspnetapp

#删除chart仓库
helm repo remove myrepo
