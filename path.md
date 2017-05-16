# 路径

进入到某个目录的下面，去编辑在某个位置上的文件。你应该了解文件与目录的路径在命令行界面下的表示方法。

## 层级

目录的层级关系一般使用 `/` 来表示，Windows 上用的是 `\` 。

**macOS / Linux**

```
/Users/wanghao/desktop
```

**Windows**

```
C:\Users\wanghao\desktop
```

上面都表示的是 desktop 这个东西的路径。在 macOS / Linux 上，这个 `desktop` 是在根目录下的 `Users` 目录下的 `wanghao` 这个目录里面。Windows 上的这个 desktop 是在 C 盘下的 `Users` 目录下的 `wanghao` 这个目录里面。

## 相对

文件与目录的位置可以表示相对的形式表示。如果路径里面不包含系统的根（root），那这个路径就属于相对路径 。这个根在 macOS / Linux 上指的是路径最前面的 `/` ，Windows 上指的是路径最前面的盘符，比如 `C:\` 或 `D:\` 。

## 绝对

绝对路径的最前面要包含系统的根。不管你在哪里，都可以使用绝对路径定位到目录或文件。而相对路径要看你当前所在的位置是哪里才能判断路径真正表示的位置是哪里。

比如你执行改变工作目录的命令，像这样：

```
cd desktop
```

如果你当前是在 `/Users/wanghao` 目录的下面，那 `cd desktop` 以后，所在的位置就是 `/Users/wanghao/desktop`。如果你当前是在 `/Users/xiaoxue` 这个目录的下面，那执行命令以后，你的位置是在 `/Users/xiaoxue/desktop` 这里。

但是如果你这样做：

```
cd /Users/wanghao/desktop
```

这样不管你之前是在哪里，执行上面这行命令以后，你所在的位置就是 `/Users/wanghao/desktop`，因为这里你用了一个绝对路径。

## 特殊符号

在路径里有些特殊符号表示一些特殊的意义。

**~**

~ 波浪号，表示的是用户主目录，它是一个相对的位置。这里说的用户指的是你当前登录的用户，比如我用 `wanghao` 用户登录到系统，在 macOS 系统上这个 `~` 表示的路径应该就是 `/Users/wanghao` 。在 Linux 系统上，这个路径应该是 `/home/wanghao`。在 Windows 上，这个路径会是 `C:\Users\wanghao` 。



