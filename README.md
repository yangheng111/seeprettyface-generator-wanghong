# 网红脸生成器-V2.0
<br />
&emsp;&emsp;<b>注明：这个项目之前收费过一段时间，在此衷心地感谢那些购买者给我提供的支持。目前已全部免费开源，希望能帮助到更多的人。如果真的对您有帮助的话，可以给予一些小小的赞助蟹蟹~</b><br />
--------------------------------------------------------------------------------------------------------------------<br /><br />
&emsp;&emsp;V2.0改进内容：1024px上画质提升，生成图片更大更清晰。<br />
&emsp;&emsp;这是一个用StyleGAN训练出的网红脸生成器，生成效果如下所示。<br /><br /><br />


# 生成示例

## &emsp;&emsp;256px单张样本
&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/a312863063/seeprettyface-generator-wanghong/blob/master/examples/256px_example1.png)<br/><br/>
&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/a312863063/seeprettyface-generator-wanghong/blob/master/examples/256px_example2.png)<br/><br/>
&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/a312863063/seeprettyface-generator-wanghong/blob/master/examples/256px_example3.png)<br/><br/>

## &emsp;&emsp;1024px单张样本
&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/a312863063/seeprettyface-generator-wanghong/blob/master/examples/example1.png)<br/><br/>
&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/a312863063/seeprettyface-generator-wanghong/blob/master/examples/example2.png)<br/><br/>

查看更多的1024px生成样本可以前往[这里](https://pan.baidu.com/s/1Sn6j9g-8sddIvViGEawAWQ)（提取码：3iqt），是一个含有1万张生成样本的网红脸数据集。<br /><br /><br />

## 概览（有筛选）
![Image text](https://github.com/a312863063/seeprettyface-generator-wanghong/blob/master/examples/64_examples.jpg)
<br /><br /><br />

# 网红脸属性编辑
&emsp;&emsp;人脸属性编辑支持在年龄、笑容、角度、性别和光照等23个维度上对生成人物作出调整（详细了解请前往[人脸属性编辑器](https://github.com/a312863063/seeprettyface-face_editor)处）。这儿只展示3种调整样例。
## 笑容调整
![Image text](https://github.com/a312863063/seeprettyface-generator-wanghong/blob/master/examples/edit_smile.jpg)
<br/><br/>
## 角度调整
![Image text](https://github.com/a312863063/seeprettyface-generator-wanghong/blob/master/examples/edit_angle.jpg)
<br/><br/>
## 光照调整
![Image text](https://github.com/a312863063/seeprettyface-generator-wanghong/blob/master/examples/edit_exposure.jpg)
<br/><br/>

# 运行代码
## 环境配置
&emsp;&emsp;Both Linux and Windows are supported, but we strongly recommend Linux for performance and compatibility reasons.<br/>
&emsp;&emsp;64-bit Python 3.6 installation. We recommend Anaconda3 with numpy 1.14.3 or newer.<br/>
&emsp;&emsp;TensorFlow 1.10.0 or newer with GPU support.<br/>
&emsp;&emsp;NVIDIA driver 391.35 or newer, CUDA toolkit 9.0 or newer, cuDNN 7.3.1 or newer.<br/>

## 运行步骤
&emsp;&emsp;1.在model文件夹中按照txt地址下载2个模型，放在该位置<br/>
&emsp;&emsp;2.在generate_wanghong.py中选择对应的模型，并运行generate_wanghong.py<br/>
<br /><br /><br />
## 获取训练集：[点此下载](http://www.seeprettyface.com/mydataset_page2.html)
![Image text](https://github.com/a312863063/seeprettyface/blob/master/EP001-01.png)<br/><br/><br/>

## 小小的赞助~
<p align="center">
	<img src="https://github.com/a312863063/seeprettyface/blob/master/sponsor.jpg" alt="Sample"  width="324" height="504">
	<p align="center">
		<em>模型训练不易，若对您有帮助可给予小小的支持~</em>
	</p>
</p>
<br/><br/><br/>



