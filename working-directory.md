# 工作目录

工具目录指的就是你在命令行界面下的时候，当前所在的位置。打开命令行界面以后，一般默认你会在登录的用户的主目录下面。

## 输出工作目录

**pwd** （ print working directory）。它可以输出你当前自己所在的位置（工作目录）。执行：

```
pwd
```

返回的是工作目录的位置：

```
/Users/wanghao
```

`/Users/wanghao`，最开始的 `/` 表示的是根（root），macOS 与 Linux 操作系统，目录位置最前面如果是 `/`，那它表示的就是系统的根目录。

Windows 的根目录会用盘符表示，比如 `C:\`  或 `D:\` ，并且 Windows 里面表示目录层级的斜线是 `\` 。

```
C:\Users\wanghao
```

## 改变工作目录

**cd**（change directory）命令可以改变当前所在的工作目录。执行：

```
cd desktop
```

意思就是把工作目录改成当前目录下的 `desktop` 这个目录，`cd` 后面加上目录的位置，上面我用的是一个相对位置，也就是 `desktop` 这个目录应该是在当前我所在的位置的下面。

再看一下：

```
pwd
```

macOS / Linux：

```
/Users/wanghao/desktop
```

Windows ：

```
C:\Users\wanghao\desktop
```



