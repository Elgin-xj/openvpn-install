# openvpn-install
<hr>
<h3>环境：</h3>
<div>Ubuntu Server 16.04 LTS 64bit Minimal（VirMach）</div>
<div>参考至:<a href="https://github.com/hwdsl2">Lin Song</a></div>
<hr>
首先，我们先将脚本文件下载到我们的服务器当中：
<div class="highlight highlight-source-shell">
	<pre>
		wget https://raw.githubusercontent.com/angristan/openvpn-install/master/openvpn-install.sh
	</pre>
</div>		
接着给脚本文件设置上执行文件权限
<div class="highlight highlight-source-shell">
	<pre>
		chmod +x openvpn-install.sh
	</pre>
</div>
运行脚本文件，在第一次运行时，它会询问您（英文）的问题以安装服务器，你只需要输入数字进行选择环境
<div class="highlight highlight-source-shell">
	<pre>
		./openvpn-install.sh
	</pre>
</div>
之后的添加客户端，删除客户端或完全卸载OpenVPN，只需重新启动脚本：
<div class="highlight highlight-source-shell">
	<pre>
		./openvpn-install.sh
	</pre>
</div>
安装完毕后会生成一个.ovpn文件，在命令界面查看文件路径并下载到客户端进行配置导入即可
