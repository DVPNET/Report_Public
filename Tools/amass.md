[Amass] https://github.com/OWASP/Amass

## 工具介绍

OWASP Amass项目使用开源信息收集和主动侦察技术执行攻击面的网络映射和外部资产发现。

## 工具下载

## Homebrew

brew tap caffix/amass
brew install amass

## Snapcraft

## 命令安装

有go环境的前提下
go get -v github.com/OWASP/Amass/cmd/amass


## 工具指南

简单实用方法
amass enum -d example.com

该命令是能够枚举子域名，是最基本的用途。

也可以根据需求设置其他的参数。

https://github.com/OWASP/Amass/blob/master/doc/user_guide.md

## 工具优势

Amass得到OWASP的支持，OWASP应该为结果提供声望和信心。它会得到积极维护，并且很可能会得到长期支持，这意味着将来的任何错误都将得到解决。此外，Amass的采用率很高，这可能意味着更好的数据一致性以及与其他工具的集成。因此，它可以构成一个更好和更值得信赖的工具，以用于概念和参与度的证明，并且可能更容易说服您的客户或经理使用它来定期绘制组织的攻击面。

