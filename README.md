# source_insight_4
===============================================
使用流程
-------------------
- **`安装流程`**
	
	直接点击 sourceinsight_4.0.86.0-setup.exe ，
	然后用sourceinsight4.exe 替换掉安装目录中的sourceinsight4.exe，

- **`破解流程`**
	
	运行替换后的二进制文件sourceinsight4.exe,按着如下提示进行破解:
	在弹出的对话框中选择第三项并导入文件 si4.pediy.lic, 点击Next 即可破解
	![破解](./image/破解提示图.png)
        
	禁止source insight联网：
	打开“网络共享中心”，选择左下角的“Windows防火墙”，然后选择“高级设计”->选择“出站规则”->“新建规则”->选择类型为“程序”->输入source insight的安装路径下的启动程序sourceinsight4.exe->阻止连         接->所有类型的网络都选上->取个你喜欢的名称
	
- **` 卸载流程`**
	
	1. “win ”+ R  或者  “开始” -> “运行”，输入“regedit”，回车；
	2. 在弹出的注册表管理器中，选择“编辑”-> “查找”->“source insight”，或按照下述路径展开：HKEY_CURRENT_USER -> software -> Source Dynamics -> Source Insight
	3. 将该项下面的source insight 需要清除的对应版本项目选中，右键“删除“
