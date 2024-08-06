#书生大模型闯关任务-8G显存玩转书生大模型demo

本关任务主要包括：

1.InternLM2-Chat-1.8B 模型的部署（基础任务）
2.InternLM-XComposer2-VL-1.8B 模型的部署（进阶任务）
3.InternVL2-2B 模型的部署（进阶任务）

1.InternLM2-Chat-1.8B 模型的部署
demo代码如下图：</br>
<img src="img/code.png" /></br>
启动demo，用户在命令行输入问题后效果如下所示：</br>
<img src="img/1.png" /></br>

使用 Streamlit 部署 InternLM2-Chat-1.8B 模型，</br>
启动一个 Streamlit 服务：</br>
<img src="img/2.png" /></br>
在本地成功运行端口映射后如下所示：</br>
<img src="img/3png" /></br>
最终在网页中成功打开web ui后效果如下：</br>
<img src="img/4.png" />

2.InternLM-XComposer2-VL-1.8B 模型的部署
使用 LMDeploy 启动一个与 InternLM-XComposer2-VL-1.8B 模型交互的 Gradio 服务：</br>
<img src="img/6.png" /></br>
最终在网页中成功打开web ui后upload如下图片：</br>
<img src="img/football.jpg" /></br>
效果如下：</br>
<img src="img/5.png" /></br>

3.InternVL2-2B 模型的部署
使用 LMDeploy 启动一个与 InternVL2-2B 模型交互的 Gradio 服务，</br>
最终在网页中成功打开web ui后upload如下图片：</br>
<img src="img/elephant.jpg" /></br>
效果如下：</br>
<img src="img/7.png" /></br>

