# 帮助

记住命令，特别是命令的用法挺难，不同的命令都有各自的可以使用的参数。一般的命令都支持 `--help` 参数，它会为你显示命令的帮助信息，比如可用的参数，参数的作用等等。或者也可以使用 `man` 命令查看命令的帮助手册。

查看帮助，例如看一下 `curl` 命令的帮助信息：

```
curl --help
```

返回信息截取：

```
Usage: curl [options...] <url>
Options: (H) means HTTP/HTTPS only, (F) means FTP only
     --anyauth       Pick "any" authentication method (H)
 -a, --append        Append to target file when uploading (F/SFTP)
     --basic         Use HTTP Basic Authentication (H)
     --cacert FILE   CA certificate to verify peer against (SSL)
     --capath DIR    CA directory to verify peer against (SSL)
 -E, --cert CERT[:PASSWD]  Client certificate file and password (SSL)
 ...
```

或者使用 `man` 命令查看命令的使用手册：

```
man curl
```

返回截取：

```
NAME
       curl - transfer a URL

SYNOPSIS
       curl [options] [URL...]

DESCRIPTION
       curl  is  a tool to transfer data from or to a server, using one of the
       supported protocols (DICT, FILE, FTP, FTPS, GOPHER, HTTP, HTTPS,  IMAP,
       IMAPS,  LDAP,  LDAPS,  POP3,  POP3S,  RTMP, RTSP, SCP, SFTP, SMB, SMBS,
       SMTP, SMTPS, TELNET and TFTP). The command is designed to work  without
       user interaction.
...
```

向后翻页按 `F`，向前翻页按 `B`，搜索按 `/` ，然后输入要搜索的关键词，退出按 `Q`。

## 解释

如果你在某个地方看到一条命令，里面用了很多参数你不懂是什么意思，可以在 [https://explainshell.com/](https://explainshell.com/) 网站上搜索一下。

![](/assets/explainshell.png)

