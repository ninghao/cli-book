# 创建

`mkdir` 可以创建新的目录，`touch` 可以创建空白的文件。

先进入到某个地方，比如当前登录用户的桌面上：

```
cd ~
```

## mkdir

**mkdir**（make directory**）**，可以创建新的目录。

```
mkdir 要创建的目录
```

**练习：创建目录**

创建一个名字是 awesome-project 的目录，执行：

```
mkdir awesome-project
```

查看一下：

```
ls
```

你会看到创建的目录 awesome-project。如果想同时创建几个层级的目录，需要用一个`-p` 参数。像这样：

```
mkdir -p awesome-project/app/styles
```

这样会在 `awesome-project` 创建一个 `app` 目录，在 `app` 里面又创建了一个 `styles` 目录。

## touch

创建一个空白的文件可以使用 **touch** 命令：

```
touch README.md
```

在文件里追加一行文字：

```
echo '命令行' >> README.md
```

输出文件里的内容：

```
cat README.md
```

会返回 “命令行” 这三个字，这是 README.md 文件里的内容。

