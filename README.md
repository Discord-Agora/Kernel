- [中文](#Discord机器人框架内核)
- [English](#Discord-Bot-Framework-Kernel)

# Discord机器人框架内核
![doc/discord-bot-framework.drawio.png](https://github.com/retr0-init/discord-bot-framework-doc/blob/master/discord-bot-framework.drawio.png)

如上图所示，这是与模块相结合与互动的内核。其中所有的功能应该是必要、极简的，并且也要为了更好地模块化集成提供极可能多的接口。

模块模板在[这里](https://github.com/retr0-init/Discord-Bot-Framework-Module-Template.git)。这是一个模板仓库，可以创建用于模块开发的仓库。为了能让您的模块以最好的方式与内核一起工作，请按照其中的`README.md`中的准则进行开发。

## 如何运行
1. 安装python3. 它的版本应该至少为`3.10`.
2. 安装[firejail](https://github.com/netblue30/firejail).
3. 在正确配置的python环境下运行`./run.sh`.

# Discord Bot Framework Kernel
![doc/discord-bot-framework-en.drawio.png](https://github.com/retr0-init/discord-bot-framework-doc/blob/master/discord-bot-framework-en.drawio.png)

As shown above, this is the kernel to interact with modules. All features are meant to be essential, minimal while providing as many ports as possible for greater modularity.

The module template is [here](https://github.com/retr0-init/Discord-Bot-Framework-Module-Template.git). It's a template repository that can create a new repository for module development. Please follow the template guidelines as stated in its `README.md` file to make it properly work with the kernel.

## How to run it
1. Install python3, whose version is `>=3.10`.
2. Install [firejail](https://github.com/netblue30/firejail).
3. Run `./run.sh` under the correct python environment.