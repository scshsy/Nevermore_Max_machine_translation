
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
**测试版文件和CAD模型都已经在线上了。** 


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
			 
	有几个原因，可能会影响你选择什么类型的过滤器最合适。
			  
	1. 我们很懒。微型滤芯很小，可能不会持续很长时间。有些人两周后就会再次闻到打印材料的气味。
           而即使更换很快很容易，但仍然是个烦恼！Max有20倍的活性炭。20倍的活性炭可以持续更长的时间。
	
	2. 我们需要更好。随着活性炭深度越深，碳过滤效果就会越好。在微型滤芯的小气流区域，深层的滤芯迅速会阻塞气流。
	你是否曾想过为什么Micro XL滤芯只比标准滤芯长10mm？气流下降得_this_快。微型滤芯的表面积略高于1000 mm2。
	一个健硕的Max滤芯在内圈内增加了十倍以上，在外圈内增加了50倍。这意味着同样的风扇可以在_less_压力降低的情况
	下移动_更_多的空气。 
	
	3. 我们需要捕捉颗粒物：3D打印机挤出会产生VOC和颗粒物。微型滤芯侧重于VOC，因为这是最恶臭并具有直接毒性效应
	的物质，一旦溢出打印室就很难捕捉。但同时，PM颗粒物是世界上导致死亡的主要原因之一，不能忽视不计。我之前曾主
	张在微型滤芯的基础上与普通房间规模的HEPA过滤器一起使用，但Max内置HEPA过滤器系统。每次通过过滤器时，你的打
	印机制造的99％以上的颗粒物将被清除，并且你不会让肮脏的空气进入你的房间或肺部
	 
	4. 我们需要降温:3D打印和3D打印过滤需要不同的东西。例如，我们希望拥有60摄氏度的加热室，以减少ABS的翘曲。
	同时，随着温度的增加，VOCs获得更多的热能，并从碳中脱附。传感器测试表明，打开使用时间较长的活性炭过滤器会
	_increase_室内VOCs。任何高于50°C的温度总的来说都不利于不良物质留在活性炭上。虽然微型滤芯已被证明可以在加
	热床下的80°C的进气温度下工作，但它肯定会大大缩短碳更换的时间！将过滤器单元放在打印机的外部可以让活性炭比
	打印机稍微降温几度。这对于延长使用寿命有很大帮助。
	   
	5. 我们需要高科技：更多的空间来放置更酷的装置。你曾经想过何时更换活性炭吗？在Max上，你可以在进风口和排风
	口上都添加VOC传感器，以及测量过滤器的效果！由于Dr Dave提供的数据，有些传感器可以可靠地检测我们努力捕捉的
	芳香VOC（很多传感器几乎不能检测挤出VOC，因为它们是为其他应用而设计的）。我选择将项目分为基本版（只包括HEPA+活性炭+风扇），
	但完全可升级到专业版，包括VOC传感器（温度、湿度、过滤效率）、LED/屏幕/控制板、伺服碳密
	封（最佳活性炭寿命，无室内VOC碳耗）和4010排气（负压+通风控制）。

	7. 降低噪音：让我们直面现实吧。高功率的5015会产生一些噪音。两个会产生更多。通过增加活性炭过滤器的尺寸，
	减小压力降，我们可以使过滤器风扇以更慢的速度运行，同时仍然获得相同的空气流量。我们可以以更高的转速运行风扇，并且快速清洁室内空气。
			    
			 被说服了吗？那么Max就是适合你的！	
			  
			
<!-- GETTING STARTED -->
## 开始

准备好要构建一个Nevermore Max了吗？太棒了！与第一个版本相比，新的Max组装起来要简单得多！

<div id="BOM"></div>

### 组装清单和采购指南
有关采购指南、详细信息和材料清单，请查看：[BOM](BOM.md)

Instead of ultra thin bolts, m3 lap top screws seems to work as well and are readily available (https://www.ebay.com/itm/185540026013?var=693379492797)

### Installation
The installation guide is under development, the alpha presentation  should take you 90% of the way:
[Installation Guide](https://www.canva.com/design/DAFLeYZF86Y/dYEmVobjTJoAHgrsha3OjA/view?utm_content=DAFLeYZF86Y&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink)

### Built with
The Voron nevermore Air Filter was modelled in [Fusion 360](http://autodesk.com).

<!-- USAGE EXAMPLES -->


### Why

At the end of the day, a fresh single-pass filtered exhaust (at brand new) has perhaps 70% VOC removal efficiency while still exhausting 30% of the nasty into the air you breathe. A recirculation filter achieving four passes at worn-in 50% efficiency could still remove 94% of the bas stuff. Or 99% at six passes!

The number of passes you get all depends on how well you can seal your build chamber. The better sealed the chamber, the less room VOCs will circulate the carbon and deplete the filter too (VOCs from onions, wall paper or farts might not be as unhealthy as melted plastics VOCs, but they block space in the carbon all the same).

Some will have a hard time achieving a good chamber seal, which creates the biggest drawback of recirculation filters - they're air flow neutral. Meaning, as nothing pulls air into the chamber, air can diffuse freely to the outside through any remaining gaps. And that air could be <i>zero per cent</I> cleaned...

To both have the cake and eat it (yes you can!), a Max can incorporate a 4010 exhaust fan, that is used to keep a slight negative pressure inside the chamber - air will still just get pulled _into_ the chamber through any remaining cracks, not leak outside. Don't ramp it up high, its meant to just barely evict air so that the majority of air flow through the filter is still recirculated.

Air evicted through the exhaust will at least have passed through the carbon filter, dust-filter and HEPA filter at least once (hopefully many more times) - so its a good security measure to have if you don't want to bet on your chamber being hermetically sealed.


### But we already have a filtered exhaust?

Yup, but aside from being one-pass, regular mesh carbon filters mainly consists of...mesh. And active carbon sprinkle - miniscule amounts, not meant to be used 24/7 in a 3d printer.

Just running regular  air through a mesh filter will still deplete it in weeks (carbon can't opt to just bind the nasty stuff). Filter exposed to air depletes it too, in time. Friggin' everything depletes carbon. Thats why we need *more*.


<b>The Nevermore</B> has a <i>kilo</i>, or two pounds, of active carbon. Not single-digit grams. And its can be sealed off from the surroundings, so when its not running, its not depleting. Any off-gassing between prints will likewise be kept inside the filter! And when is does run, it has a lot of VOC binding capacity! At least a hundred times more compared to a generic solder fume carbon mesh filter. 

This is the filter for the low maintenence crowd (who still want to be safe).

### I have worked with plastics and I am fine!

If you live alone - not impacting other people – and feel that way, this filter is not for you! <br>
After all, you’re perfectly allowed to smoke two packs a day or become a opposition politician in Russia too, even though it’s probably not optimal for your health. And on an individual level one can never be sure what the health effects will be, if any - the oldest person ever used to smoke until she was 118 years or so…

But speaking of what we do know, we can say for sure that:<BR>

The WHO:s <I>International Agency for Research of Cancer (IARC)</i> classifies chemical compounds based on the known evidence of human carcinogenics, into four classes (<I>carcinogenic, probably carcinogenic, possibly carcinogenic or not classifiable as carcinogenic to humans</i>).<BR><BR>
Most chemicals fall into the last category, but in the known carcinogenic groups we find several known 3d printer byproducts:<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<B>o Benzene</b><BR>
One of the main fumes from ABS printing. 3ppm regarded as safe, whereas up to 280 ppm of VOCs are produced ABS printing every hour in a small space. Proven to cause different leukemias, and suspected of causing a multitude of other cancers. Female workers in a shoe factory exposed to 40ppm for a long time had a hundredfold higher risk of dying from breast cancer, for instance. Class 1 carcinogenic.<br><BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>o Styrene</B><BR>
Main pollutant in ABS fumes, recently upgraded from possible to probable carcinogenic based on mounting evidence of connection with a close to tripled risk of different leukemias.<br><BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<B>o Butadiene</b><BR>
Another component of ABS printing, and the reason why styrene didn’t get the carcinogenic label for so long (as both are ABS byproducts it was long impossible to know if a cancer type was due to butadiene or styrene. Butadiene is also a known cause and/or cofactor in cardiovascular disease, so you might get your heart attack or stroke a few years earlier by breathing it in for a long time.<br><br>
<u>Other knowns:</U><br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• What creates the most particles/VOCs from plastics handling is <i>heated extrusion</i>.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Injection molding, vacuum forming and other common industrial methods creates less air pollutants due to less melted plastic surface per kg with direct air/oxygen access/airflow.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• 3D printing extrusion takes this to another VOC creation level, as you’re extruding thin layer by thin layer, not trapping any of the extruded melted material from access to oxygen or airflow. Thus, per kilogram of product, it’s the most particle and VOC generating plastic process there is.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Home 3d printers are often used in places without industrial ventilation or industrial wet scrubbing. Indeed, a recent study showed that levels of VOC carcinogenics in plastics recycling plants using heated extrusion processes were mostly within safe limits. However, in surrounding residential homes of those safe-to-work plants, VOC levels were up to <B>42 times</b> the safe limits and consisted of the ventilated byproducts from the plastic plants, due to lower ventilation requirements in homes. The study showed a clear increased lifetime cancer risk, even for the workers in the plants.<br><br>

This is a short list of some key knowns, and only address the most common ABS fumes. Other materials have different VOCs. PETG for instance, releases Toluene, Acetaldehyde, Formaldehyde – all of which are known health hazards. Regular PLA and Nylons without additives are usually safer, but still release lower levels of acetone, methyl-methacrylate, and iso-butanol (PLA) and Propylene Glycol and Cyclopentanone (Nylon). Not all fumes are created equal.<br><br>




<!-- CONTRIBUTING -->
## Contributing

Please contribute! I'd like to incorporate VOC sensors, making the filter smart (running on low-noise mode at an acceptable VOC level, then ramp up at the end to clean more thoroughly before doors open).


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

