#### 1.Detached head是什么，有什么危害，怎么解决
```
即切换到指定的某一次提交，HEAD 就会处于 detached 状态（游离状态）
```
* links
  * [Git HEAD detached from XXX (git HEAD 游离) 解决办法](https://blog.csdn.net/u011240877/article/details/76273335)
  * [图解Git](https://marklodato.github.io/visual-git-guide/index-zh-cn.html#detached)
#### 2.Git fetch 和 pull 有什么区别
```
└── refs
    ├── heads
    │   └── master
    ├── remotes
    │   └── origin
    │       ├── HEAD
    │       ├── master
    │       ├── next
    │       ├── pu
    │       └── todo
    └── tags
```
* links
  * [git fetch和git pull之间的区别](https://blog.csdn.net/a19881029/article/details/42245955)
#### 3.Git reset 和 revert有什么区别,revert HEAD~2 和 指定倒数第三个commit有区别么（获取指定commit只针对当次commit内容撤销）,可以reset远程分支么
```
git revert可以用在公共分支上，git reset应该用在私有分支上
git reset HEAD~2
git checkout HEAD~2
git revert HEAD~2
```
* links
  * [代码回滚：git reset、git checkout和git revert区别和联系](https://www.cnblogs.com/houpeiyong/p/5890748.html)
  * [在git里撤销几乎任何操作](http://blog.jobbole.com/87700/)
#### 4. Git reflog命令?
* links
  * [git log 和 reflog](http://www.cnblogs.com/luyuefeng/p/8046443.html)
