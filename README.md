
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
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#About-The-Nevermore">About: Why a Nevermore Max?</a>
      <ul>
        <li><a href="#Why">Why Nevermore?</a></li>
		<li><a href="#But-we-already-have-a-filtered-exhaust">But we already have a filtered exhaust?</a></li>
		<li><a href="#I-have-worked-with-plastics-and-I-am-fine">I've worked with plastics, and I'm fine!</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#BOM">BOM and Sourcing Guide</a></li>
        <li><a href="#installation">Installation</a></li>
		<li><a href="#Built-with">Built with</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About Nevermore Max



Why a Max when the Micro works well? The little bugger is an easy print, nimble, looks great... Why bother making a large unit chewing filament?
			 
	 Well - there are a few reasons, that may or may not affect your decision on what filter is best for you.
			  
	1. We're **LAZY**. A micro cartridge is small and may not last very long. Some will 
	have filament smell again in two weeks.   And while the change is quick and easy,
	its still a chore! A Max has 20x the carbon. 20x the carbon lasts...longer.  
	
	2. We need **BETTER**. Carbon filtration gets better and better the deeper the carbon 
	bed. At the small airflow area of a micro, a deep bed quickly chokes air flow. 
	Ever wondered why a Micro XL cartridge is only 10mm longer than a standard cartridge? 
	Air flow degrades _that_ fast. The surface area of a micro cartridge is just 
	above 1000 mm2. A hefty max filter increases that over ten times at the inside 
	perimeter, and 50 times on the outside perimeter. This means the same powered
	fan could move _much_ more air at _less_ pressure drop.  
	
	3. We catch **PARTICLES**: 3D printer extrusion creates both VOCs and particles. 
	The micro focuses on VOCs, as thats what give off the worst smell and has direct 
	toxic effects, and are difficult to catch once outside of the print chamber. 
	Yet again, PM particles are among the leading causes of death in the world and 
	shouldn't be ignored. I've advocated using a regular room-size HEPA for particles 
	in conjunction with a micro before, but with the Max a HEPA filtration system is
	 built in. 99+ per cent of particles created by your printer will be removed 
	 every pass and you wont add dirty air to your room or lungs.  
	 
	4. We need **COOLER**: 3D printing and 3D printing filtration require different things.
	For instance, we _love_ to have a 60C chamber for less ABS warping. At the same
	time, with increasing heat, the VOCs get more heat energy and desorb from the 
	carbon. Sensor testing has shown that turning on a well used carbon filter can 
	_increase_ chamber VOCs. Anything above 50C is generally not good for bads stuff to
	stay attached to the carbon. And while the micro has been shown to work even at 
	80C intake air under a heated bed, it most definitely decreases the time between 
	carbon changes a lot! Having the filter unit outside of the printer allows for the
	carbon to be a few degrees cooler than the printer. That does much for longevity.  
	   
	5. We haz to needz **TECHz**: More space for cooler gadgets. Ever wondered when 
	its time to swap carbon? Well, on the max you could add VOC sensors to both intake
	and exhaust and measure how well the filter is doing its job! Thanks to Dr Dave
	there are even data on which sensors reliably detect the aromatic VOCs we strive
	to catch (a lot of sensors hardly detect extrusion VOCs at all as they are intended
	for other applications). I've chosen to divide the project into a Basic version
	with just HEPA+carbon+fan, but entirely upgradeable to the Pro version 
	including VOC sensors (temp, humidity, filter efficiency), LED/Screen
	/Controller board, servo carbon sealing for (optimal carbon longevity with no
	room VOC carbon depletion) and a 4010 exhaust (negative pressure+vent 
	control).  

	7. Less **NOISE**: Lets face it. A high powered 5015 creates some noise. Two creates
	even more. By increasing the size of the carbon filter, decreasing pressure drop,
	we can run the filter fan slower while still getting the same air flow. We can 
	run the fan at a higher rpm:s and clean the chamber in a jiffy as well.  
			    
			  Convinced? Well, then the Max is for you!	
			  
			
<!-- GETTING STARTED -->
## Getting Started

You're ready to build a Nevermore? Cool! The New Max is a lot simpler to assemble compared to the first version!

<div id="BOM"></div>

### BOM and Sourcing Guide
For the sourcing guide, details and material list please check this out: [BOM](BOM.md)

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

