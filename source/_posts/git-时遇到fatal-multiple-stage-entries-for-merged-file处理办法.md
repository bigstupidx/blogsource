title: 'git 时遇到fatal:multiple stage entries for merged file处理办法'
date: 2015-11-03 20:48:38
tags: [git, bug]
---

**进入到git的根目录下**
1. rm .git/index
2. git add ./
3. git commit -am "信息"