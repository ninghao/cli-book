# 编辑

`mv` 可以重命名或者移动目录与文件，编辑文件可以使用 `vi` 编辑器。

## 

## 

## 删除

**rm**（remove），可以删除目录或文件。

```
rm 要删除的内容的路径
```

**练习：删除文件**

```
rm ninghao-project/README.md
```

**练习：删除整个目录**

上面的命令会删除掉 `ninghao-project` 目录下的 `README.md` 这个文件。要删除一个目录里包含的所有内容，要加上 `r` 选项，想不出现确认提示，还要再加一个 `f` 选项。

```
rm -rf ninghao-project
```



