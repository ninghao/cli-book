# 查看文件

查看文件里面的内容，你可以用 `vi` 打开这个文件，如果你只想输出文件里的内容，可以使用 `cat` 命令。如果文件比较大，你只想输出文件的最后一小部分，可以使用 `tail` 命令。

先在 ninghao-project/README.md 文件里添加点内容，可以这样做：

```
echo "hello" >> ninghao-project/README.md
```

## cat

**cat**，可以直接输出文件里的内容。

```
cat 要查看的文件
```

**练习：查看文件里的内容**

查看一下 ninghao-project/README.md 这个文件里的内容。执行：

```
cat ninghao-project/README.md
```

## tail

**tail**，可以输出文件里的最后一小部分内容。

```
tail 要查看的文件
```

**练习：输出文件的最后一小部分**

输出 ninghao-project/README.md 这个文件内容里的最后一小部分。执行：

```
tail ninghao-project/README.md
```



