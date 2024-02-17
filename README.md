# 这是在Ubuntu上安装kali渗透工具说明步骤



打开终端：你可以通过快捷键Ctrl+Alt+T来打开终端。

安装Git：如果你还没有安装Git，可以通过以下命令来安装它：


sql
sudo apt update  
sudo apt install git
克隆Kali渗透工具仓库：运行以下命令来克隆Kali渗透工具的GitHub仓库到本地：


bash
git clone https://github.com/LionSec/katoolin.git
这将下载并创建一个名为katoolin的目录，其中包含Kali渗透工具的安装脚本。


复制Python脚本到/usr/bin/目录：进入katoolin目录，并将katoolin.py脚本复制到/usr/bin/目录下：


bash
cd katoolin  
sudo cp katoolin.py /usr/bin/katoolin
添加可执行权限：为Python脚本添加可执行权限：


bash
sudo chmod ugo+x /usr/bin/katoolin
启动Katoolin：现在，你可以通过以下命令来启动Katoolin：


sudo katoolin
启动后，你将看到一个交互式菜单，可以根据终端中的菜单选项来选择和安装你需要的渗透测试工具。


请注意，目前Katoolin仅支持Ubuntu系统。如果你使用的是其他发行版，可能需要等待后续支持。


此外，确保你的系统上已经安装了Python 2.7版本。你可以通过运行python --version命令来查看Python版本。


完成上述步骤后，你就可以在Ubuntu上安装Kali渗透工具了。祝你使用愉快！

