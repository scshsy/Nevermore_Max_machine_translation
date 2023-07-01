
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

**原版链接 https://github.com/nevermore3d/Nevermore_Max **

**测试版文件和CAD模型都已经在github上了。** 


_至少需要300x300毫米的打印床！!_


**建议使用0.2层厚度，0.4喷嘴[0.6+Aarachnae正在评估中]。**

打印指南：


**框架:**

非常容易翘曲，尤其是用标准ABS材料打印！即使你从未遇到过翘曲问题，这也处于塑料冷却应力的边缘。我已经成功地用TitanX打印了这个模型，其他用户用ESun ABS+也有不错的效果。由于它永远不会受到PETG TG温度的影响，所以这也可以是一个很好的选择。需要采取额外的附着预防措施（使用水平补偿调整z轴偏移量、纳米粘合剂、更高的床温或者可能的温室温度等）。同时也不要忘记将弹性床板贴好，否则弹性床板可能会成为变形的来源。



**面板**


面板具有大量的表面积。如果你不使用冷却后会从床上松落的丝路 - 需要弯曲你的床才能移除零件 - 有一定的风险，薄的PEI表面（0.15-0.30毫米厚度或者相近的厚度）会被拉开，导致PEI上出现气泡。如果你有薄的PEI或其他易受损的表面，请在打印和床之间使用一层释放层（我通常使用玉米淀粉溶解在水中，然后刷涂在热床上，等它蒸发后即可，对于PEI和ABS的组合，而言，零件将容易释放，任何留在零件或床上的淀粉残留物可以用水洗掉）。

**碳筐**


未桥接的网格抽出物将颗粒物保留在过滤器内，通常高度为0.4毫米，宽度为0.8毫米。如果宽度分为两行（有一定的重叠，0.4-0.46应该可以，可以在你的切片软件中检查），打印效果最佳。高度也应分为两层（允许第一层以稍低的挤出倍率进行打印，如桥接设置所述，第二层为常规支撑层）。

**其他零件**
其他零件应该像其他打印件一样打印。

**9/9：增加了安装指南。**
<!-- PROJECT LOGO -->
<br />
<p align="center">
  <https://github.com/0ndsk4/VoronUsers/tree/0ndsk4/printer_mods/0ndsk4/Nevermore_Air_Filter">
    <img src="Images/Nevermore_Max_v2_Beta3.png" alt="Logo">
							   <p align="center">
  <https://github.com/0ndsk4/VoronUsers/tree/0ndsk4/printer_mods/0ndsk4/Nevermore_Air_Filter">
    <img src="Images/Nevermore_Max_v2_Beta.png" alt="Angle">
	  <p align="center">
  <https://github.com/0ndsk4/VoronUsers/tree/0ndsk4/printer_mods/0ndsk4/Nevermore_Air_Filter">
    <img src="Images/Nevermore_Max_v2_Beta_2.png" alt="Angle2">
  </a>

  <h3 align="center">Nevermore Max 3D打印机空气过滤器</h3>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>目录</summary>
  <ol>
    <li>
      <a href="#About-The-Nevermore">为什么要选择Nevermore Max？</a>
      <ul>
        <li><a href="#Why">为什么选择Nevermore？</a></li>
		<li><a href="#But-we-already-have-a-filtered-exhaust">但我们已经有过滤排气系统了？</a></li>
		<li><a href="#I-have-worked-with-plastics-and-I-am-fine">我已经处理塑料很久，没问题！</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">入门指南</a>
      <ul>
        <li><a href="#BOM">物料清单和采购指南</a></li>
        <li><a href="#installation">安装</a></li>
		<li><a href="#Built-with">使用的材料</a></li>
      </ul>
    </li>
    <li><a href="#contributing">贡献</a></li>
    <li><a href="#license">许可证</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## 关于Nevermore Max



为什么要选择一个Max，而不是一个Micro？那个小的家伙打印简单，灵活，看起来很棒......为什么要费力去制造一个大的、可以咀嚼打印材料的单位呢？
			 
嗯 - 有一些原因，可能会或可能不会影响您对什么过滤器最适合您的决定。

我们懒惰。微型滤芯很小，可能用不了多久。有些人两周后就会再次闻到丝材的味道。虽然更换快速且容易，但仍然很麻烦！Max过滤器的活性炭含量是微型过滤器的20倍。20倍的活性炭可以使其使用寿命...更长。

我们需要更好。活性炭过滤效果随着活性炭床深度的增加而变得越来越好。在微型过滤器较小的气流区域内，深度床会迅速阻塞气流。有没有想过为什么Micro XL滤芯只比标准滤芯长10毫米？气流衰减就是这么快。微型滤芯的表面积略高于1000平方毫米。一个大号Max过滤器在内周边将这个数值增加了十倍以上，在外周边则增加了50倍以上。这意味着同样功率的风扇可以以_更低_压力降低来移动_更多_的空气。

我们捕捉颗粒：3D打印机挤出产生VOCs和颗粒。微型过滤器专注于VOCs，因为它们散发出最糟糕的气味，并具有直接毒性效果；一旦离开打印室，这些VOCs就很难捕获。然而，PM颗粒是全球主要死亡原因之一，不应忽视。我曾提倡在微型过滤器中使用常规的房间大小的HEPA过滤器来捕获颗粒，但Max过滤器内置了一个HEPA过滤系统。您的打印机产生的99%以上的颗粒将被每次通过时清除，您不会再向房间或肺部增加脏空气。

我们需要更冷：3D 打印和 3D 打印过滤需要不同的条件。例如，我们_喜欢_保持60C 的打印室以减少ABS 翘曲。与此同时，在温度上升时， VOCs 变得越来越热并从活性炭中解吸。传感器测试表明，在一个使用过的碳过滤器上 _增加_打印室的VOCs。任何高于50C的温度通常都不利于将有害物质保留在活性炭上。虽然已经证明微型过滤器即使在80C的加热床下进气口处也能工作，但毫无疑问它大大缩短了碳更换的时间！将过滤器单元放在打印机外部可以使碳比打印机几度凉快，这对使用寿命有很大帮助。

我们需要更多技术：更多空间用于更酷的设备。想知道什么时候换碳吗？在Max过滤器上，您可以为进气口和排气口添加VOC传感器，测量过滤器的过滤效果！多亏了Dr Dave，我们甚至有数据显示哪些传感器可靠地检测到我们试图捕捉的芳香族VOCs（许多传感器几乎无法检测到挤出产生的VOCs，因为它们是为其他应用而设计的）。我选择将项目分为基本版本（只包括HEPA+碳+风扇），但可以完全升级到专业版本，包括VOC传感器（温度、湿度、过滤效率）、LED/屏幕/控制器板、伺服碳密封（最佳碳寿命，无室内VOC碳耗竭）以及4010排风口（负压+通风控制）。

更少的噪音：面对现实吧。高功率的5015产生一定的噪音。两个则产生更多。通过增加活性炭过滤器的大小，减少压力降低，我们可以在保持相同空气流动的同时降低过滤器风扇的速度。我们还可以提高风扇转速，快速清洁打印室。

如果您同意以上观点，那么Max过滤器就是您的最佳选择！	
			  
			
<!-- GETTING STARTED -->
## 开始

准备好要构建一个Nevermore Max了吗？太棒了！与第一个版本相比，新的Max组装起来要简单得多！

<div id="BOM"></div>

### 组装清单和采购指南
有关采购指南、详细信息和材料清单，请查看：[BOM](BOM.md)

与超薄螺栓不同，m3笔记本电脑螺钉似乎也很适用，并且容易购买。 (自己推敲&淘宝)

### 安装
安装指南正在开发中，alpha版演示应该能帮助你完成90%的安装：[安装指南](https://www.canva.com/design/DAFLeYZF86Y/dYEmVobjTJoAHgrsha3OjA/view?utm_content=DAFLeYZF86Y&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink)

### 建模软件
Voron Nevermore空气滤清器是在[Fusion 360](http://autodesk.com)中建模的

<!-- USAGE EXAMPLES -->


### 哈？

说到底，新的单程过滤排气（在全新状态下）可能有70％的VOC去除效率，同时仍会将30％的有害物质排放到你呼吸的空气中。在磨损50％效率条件下实现四次循环过滤器，仍可以去除94％的有害物质。或者六次循环可以去除99％！

你可以获得的通道数取决于您密封建筑室内的程度。密封室越好，VOCs循环到碳中并耗尽滤网的空间就会越少（洋葱、墙纸或屁等VOCs可能不像熔化塑料VOCs那样不健康，但它们仍然在碳中占据空间）。

一些人可能难以实现良好的密封室，这是回收过滤器最大的缺点-他们是空气流量中性。意思是说，由于没有东西将空气拉入房间，通过任何剩余缝隙空气可以自由扩散到外部。而且那些空气可能完全没有被清洁......

为了既能拥有蛋糕又能吃蛋糕（是的，你可以！），Max可以整合一个4010排风扇，在房间内维持微弱的负压-空气仍会通过任何剩余的裂缝被拉入房间，而不是漏到外面。不要将它调高，它只是为了轻轻驱逐空气，这样通过滤网的大部分空气流量仍然是循环的。

通过排气排放的空气至少经过了碳过滤器、除尘器和HEPA过滤器至少一次（希望多次）-因此，如果您不想押注于室内密封性非常好，则这是一个很好的安全措施。


### 但是我们已经有过滤排气了？

是的，但是除了一次性过滤之外，普通的网状活性炭过滤器主要由...网状材料组成。而且活性炭颗粒量很少，不适合在3D打印机中24/7使用。

仅仅通过网状过滤器运行普通空气，几周内就会耗尽活性炭（碳不能选择只结合有害物质）。长时间暴露在空气中的过滤器也会耗尽活性炭。几乎一切都会消耗活性炭。这就是为什么我们需要更多的原因。


Nevermore拥有一千克（约两磅）的活性炭，而非单位克数。并且它可以与周围环境隔离，所以当它不运行时，它不会消耗活性炭。在打印过程中产生的任何挥发性气体也会被留在过滤器内！而当它运行时，它具有很高的VOC结合能力！至少比普通的焊接烟雾活性炭网过滤器高出百倍。

这是一款适合低维护需求的人群（但仍希望安全使用）的过滤器。

### 我也曾与塑料制品打过交道，一切都很好！

如果你独自生活——不影响其他人——并且这样认为，那么这款过滤器不适合你！
毕竟，你完全可以每天抽两包烟或者成为俄罗斯的反对派政治家，尽管这可能对你的健康并不理想。在个人层面上，我们永远无法确定具体的健康影响是什么（如果有的话）——有史以来年龄最大的人曾一直抽烟，直到她118岁左右……

但是在谈论我们所知道的事情时，我们可以肯定地说：

世界卫生组织的国际癌症研究机构（IARC）会根据已知的对人类致癌物证据，将化学物质分为四类（致癌物、可能致癌物、可能致癌物或不可归类为对人类致癌物）。

大多数化学物质属于最后一类，但在已知的致癌物组中，我们发现了一些3D打印机副产物： 
	     
 o 苯 ABS打印过程中的主要烟雾之一。3ppm被认为是安全的，而在小空间内，每小时ABS打印产生高达280ppm的VOCs。已被证明会导致不同类型的白血病，并且被怀疑会导致其他多种癌症。例如，长期暴露于40ppm浓度下的女性鞋厂工人患乳腺癌死亡的风险增加了一百倍。1类致癌物。

 o 苯乙烯 ABS烟雾中的主要污染物，最近从可能致癌物升级到可能致癌物，因为越来越多的证据表明它与不同类型白血病风险接近三倍有关。

       o 丁二烯
 ABS打印的另一个组成部分，也是苯乙烯长时间没有被贴上致癌物标签的原因（因为这两者都是ABS副产物，所以很长时间无法判断某种癌症是由于丁二烯还是苯乙烯引起）。丁二烯还是已知的心血管疾病原因和/或促成因素，因此长时间吸入可能会提前几年发生心脏病发作或中风。

其他已知事实：

       • 处理塑料最容易产生颗粒/VOCs 的环节是加热挤压。
       • 注塑成型、真空成型和其他常见的工业方法由于较少的直接空气/氧气接触/气流下熔融塑料表面积而产生较少的空气污染物。
     • 3D打印挤压使这一VOCs创造过程达到另一个水平，因为你是逐层挤压薄材料，没有限制任何挤出的熔融材料接触氧气或气流。因此，按每公斤产品计算，这是最具颗粒和VOCs生成能力的塑料加工过程。
       • 家用3d打印机通常在没有工业通风或工业湿法洗涤设备的地方使用。事实上，一项最近的研究显示，在使用加热挤压工艺的塑料回收厂内，VOC致癌物水平大多在安全范围内。然而，在那些安全作业厂房周边的住宅区，由于住宅通风要求较低，VOC浓度高达42倍安全限值，并由塑料厂排放的废气组成。研究表明，在这些地区居民终身患癌风险明显增加，甚至包括工厂内的工人。

这只是一些已知事实的简短列表，且只针对最常见的ABS烟雾。其他材料会产生不同的VOCs。例如，PETG会释放甲苯、乙醛、甲醛，这些都是已知的卫生危害物质。普通PLA和不含添加剂的尼龙通常更安全，但仍然会释放较低浓度的丙酮、甲基丙烯酸甲酯和异丁醇（PLA）以及丙二醇和环戊酮（尼龙）。并非所有烟雾都一样。




<!-- CONTRIBUTING -->
## 贡献

请多提建议！我希望能够整合VOC传感器，使过滤器更智能化（在可接受的VOC水平下以低噪音模式运行，然后在结束时加速运行以在开门前更彻底地清洁空气）。

<!-- LICENSE -->
## License

Distributed under GNU General Public License version 3.0 (GPLv3)



<!-- CONTACT -->
## Contact

0ndsk4#5933  - (http://discord.com/user/0ndsk4#5933) <BR>
Nevermore: [https://github.com/0ndsk4/VoronUsers/tree/0ndsk4/printer_mods/0ndsk4/Nevermore_Air_Filter](https://github.com/0ndsk4/VoronUsers/tree/0ndsk4/printer_mods/0ndsk4/Nevermore_Air_Filter)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [The Voron Dev Team](https://vorondesign.com/)






<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[product-screenshot]: images/screenshot.png

