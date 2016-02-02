title: hexo_deploy
toc: 
date: 2016-01-29 16:15:45
categories: hexo
---

配置_config.yml
``` 
deploy:
  type: git
  repo: https://github.com/hbcaijun/hbcaijun.github.io.git
  branch: master 
  
```
另外在win7下面需要用git bash， 用cmd会出现错误。
```
bash: /dev/tty: No such device or address
error: failed to execute prompt script (exit code 1)
fatal: could not read Username for 'https://jacpy.github.com': No error

```