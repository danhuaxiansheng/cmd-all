# cmd-all
# 
更新低版本包：npm i --legacy-peer-deps


git 10054报错，在git管理器中执行：
git config --global http.sslVerify "false"

取消代理配置
git config --global --unset http.proxy

git config --global --unset https.proxy

查看git所有配置
git config --global -l

设置证书路径
git config --global http.sslBackend "openssl" 
git config --global http.sslCAInfo "C:\Program Files\Git\mingw64\ssl\cert.pem"
