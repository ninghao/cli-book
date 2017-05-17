# 复制

**cp**（copy），可以复制指定的文件与目录。

```
cp 要复制的源 复制到的目标
```

**练习：复制文件**

复制一份 ninghao-project 下面的 README.md ，放到 ninghao-project/app 这个目录的下面。

```
cp ninghao-project/README.md ninghao-project/app/
```

**练习：复制目录**

要复制一个目录连同它里面包含的所有文件与子目录，需要用一个 `-R` 选项。比如复制一下 ninghao-project 这个目录，复制品的名字是 ninghao-project-bak，执行：

```
cp -R ninghao-project ninghao-project-bak
```



