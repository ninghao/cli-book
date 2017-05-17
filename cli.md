# 命令行界面

当您听到 “打开命令行”，我的意思就是让您打开在自己电脑上的一个命令行界面工具。在这个工具里，我们需要去执行一些任务，比如去管理服务器，为项目做版本控制等等。不同的平台，用的这个命令行工具的名字不一样。

## **Windows**

系统本身带 cmd 与 Powershell，但都缺少很多常用并实用的工具，这些工具是 UNIX 类型的系统里特有的。比如连接服务器用的 ssh。我建议使用 **cmder**，它分成两个版本 mini 与 full，推荐使用 full （完整）版本的 cmder，它里面包含了大量的 UNIX 系统上专有的工具，而且 full 版本的 cmder 里面还包含了 git 工具，所以你不再需要单独安装  git 工具了。

cmder 官方网站：[http://cmder.net/](http://cmder.net/)

### cmder

cmder 有几种模式，cmd，Powershell，Bash，mintty。还有几种对应的管理员模式，在 Windows 的命令行下执行任务，有时候需要用到管理员的身份。所以在运行命令行界面的时候，你应该选择使用管理员身份运行。

我推荐使用两种模式，Powershell 与 mintty（类似 Unix/Linux ）。Poweshell 是 Windows 自带的命令行界面，cmder 的 Powershell 模式就是基于 Windows 的 Poweshell 之上运行的，增加了一些它本身带的工具。mintty 模式并没有基于 Windows Console API，它的某些特性跟 Windows 不太一样。如果你更习惯在 Unix / Linux 模式的命令行界面下工作，可以使用 cmder 的 mintty 模式。

**模式的选择**

打开 cmder 以后，窗口右下角有个绿色的 + 号图标，点开它可以选择创建不同模式的 cmder 标签。比如可以是 Powershel - Powershell as Admin，用管理员身份运行的 Poweshell 模式。也可以是 bash - mintty as Admin，用管理员身份运行的 mintty 。

> 做本书练习的时候，我建议您创建两个 cmder 标签，一个用 Poweshell as Admin 这种模式，另一个用 mintty as Admin 模式。你可以分别在这两种模式下去执行书中的任务，然后观察这两种模式的区别。

相关视频：[cmder](https://ninghao.net/video/4601?a=51729)

## **macOS**

可以使用系统自带的 “**终端**”，英文名是 “Terminal”。也可以去下载安装 iTerm，它可以替代终端。iTerm 比终端更强大，不过你得学会使用它，还得去配置。一开始我们只需要在命令行下执行很简单的任务，所以使用系统自带的终端也就足够了。

ctrl + space / command + space，搜索 terminal，可以找到并打开终端。

相关视频：[终端 terminal](https://ninghao.net/video/4556?a=51729)

