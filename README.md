# learning-notes
前端技术学习笔记

test 上传

全局代理

git config --global http.proxy 127.0.0.1:1080

局部代理

在github clone 仓库内执行
git config --local http.proxy 127.0.0.1:1080
(127.0.0.1:1080）
查询是否使用代理：
查询全局代理
git config --global http.proxy
查询局部代理
git config --local http.proxy
取消代理：
git config --global --unset http.proxy
git config --local --unset http.proxy
