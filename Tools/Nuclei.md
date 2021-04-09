[Nuclei] https://github.com/projectdiscovery/nuclei

Nuclei 是一款基于模板向目标发送请求的工具，它提供对大量主机的快速扫描功能。 Nuclei提供扫描各种协议的功能，包括TCP，DNS，HTTP，文件等。借助强大灵活的模板，可以使用Nuclei对各种安全检查进行建模。

Nuclei 有一个专用的存储库，其中包含由数名安全研究员和工程师提供的各种类型的漏洞模板。 可以使用 -update-templates 标志预加载了随时可以使用的模板。

安装步骤:

go get -v github.com/projectdiscovery/nuclei/v2/cmd/nuclei

使用方法:

PoC 基于 .yaml 格式进行编写

<h3 align="center">
  <img src="https://raw.githubusercontent.com/projectdiscovery/nuclei/master/static/nuclei-flow.jpg" alt="nuclei-flow" width="700px"></a>
</h3>

官方提供了一些模板供社区白帽子使用与学习  

https://github.com/projectdiscovery/nuclei-templates

![image](https://user-images.githubusercontent.com/69717362/114150722-f1e8d980-994e-11eb-8169-675838166f53.png)

使用如下这条指令可以下载公开库中的最新模板

> nuclei -update-templates   

举例说明使用方法 (调用 cves 这个模板库对目标URL列表进行漏洞检测)   

> nuclei -l target_urls.txt -t cves/   
