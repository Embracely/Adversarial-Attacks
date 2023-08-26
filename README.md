# Adversarial-Attacks
对抗攻击主要分为黑盒攻击、白盒攻击、目标攻击、无目标攻击。因为白盒攻击的成功率已经达到了百分百，所以我们主要研究黑盒攻击。
黑盒攻击中主要的研究方向如下：
1. 提升迁移率：基于已知模型进行预训练，把预训练后的攻击模型应用在其他模型上验证成功率
2. 减少查询次数：查询梯度方向等，来降低时间成本

现在共有六个tensorflow框架下的对抗攻击方法：

blackbox-attack：包含了batch-attack、boundary-attack和zoo-attack  

SI-MI-FGSM：包含了MI-FGSM、NI-FGSM、SI-MI-FGSM、SI-NI-FGSM  

Distributionally adversarial attack：基于三个数据集进行检验  

HSJA:基于L2、Linf约束下的目标、无目标攻击  

Semantic：改变颜色来生成对抗样本  

SparseFool：改变个别像素值来生成对抗样本，类似的方法还有one-pixel-attack和JSMA  

（ps:上传的文件可能进行了部分修改，如果要看源代码，请参考对应项目下readme的链接）
