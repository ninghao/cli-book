# **列出**

ls（list）可以列出目录里的内容。

直接使用 ls：

```
ls
```

返回的是当前目录里的东西。

ls 后面加上路径：

```
ls ~
```

返回的是指定位置下的东西。类似这样：

```
Applications            Movies
Desktop                Music
Documents            Pictures
```

**所有**

在 macOS / Linux 系统上，用点开头的文件与目录会被隐藏起来，如果你想列出目录里包含的所有内容，包括这些用点开头的文件或目录，要加上一个 a 参数，像这样：

```
ls -a
```

**长格式**

ls 命令后面加上 l 参数，可以使用长格式表示内容：

```
ls -l ~
```

返回的东西像这样：

```
drwx------@  4 wanghao  staff   136  3  1 10:56 Applications
drwx------+ 12 wanghao  staff   408  5 16 13:31 Desktop
drwx------+ 11 wanghao  staff   374  5 11 20:56 Documents
drwx------+  6 wanghao  staff   204  5 15 22:44 Downloads
```

返回的列表里面包含更详细的信息，比如文件或目录的权限，拥有者，用户组等等。

**组合**

命令的参数也可以组合使用：

```
ls -la
```

用了一个 `l` 参数，还有一个 `a` 参数。

**排序**

列出的内容，按内容的修改时间排列，最近修改的排在最前面。

```
ls -lt /Users/wanghao
```

返回：

```
drwx------@ 71 wanghao  staff  2414  5 16 13:38 Library
drwx------+ 12 wanghao  staff   408  5 16 13:31 Desktop
drwx------+  6 wanghao  staff   204  5 15 22:44 Downloads
```



