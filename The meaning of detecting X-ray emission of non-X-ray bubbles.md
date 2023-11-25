![Alt text](Attachments/The_scale_of_X-ray_emission_and_the_physics_behind/NGC4151.png)

# The meaning of detecting X-ray emission in Seyfert galaxies?
## 一. 为什么研究radio-quiet Seyfert galaxies的X-ray emission?
### 1. Seyfert galaxies有什么特殊之处？
<font color="blue">Chatgpt --</font>
Seyfert星系在X射线研究中的受欢迎程度主要源于其相对较亮的X射线辐射、X射线吸收特征、活跃的核心黑洞以及多波段观测的可能性。这使得它们成为研究AGN和宿主星系相互作用的理想天体。
### 2. 为什么要求radio-quiet?
<font color="blue">Wang, et al, 2009, ApJ --</font>
Radio-loud的星系中，X-ray emission主要来自强大射电喷流的X射线对应物(counterpart)。在radi-quiet的Seyfert星系中，有与之类似的东西，在窄线区域 (NLR) 尺度上发现的较小喷流。
<font color="red">Me --</font>
Seyfert星系是radio-quiet的。所以这两个问题好像是同一个。。因为想研究radio-quiet的AGN，所以选择了Seyfert星系，这也是一个理由。
### 3. 其X-ray emission反映了什么？
#### * 什么东西产生了X-ray emission？
<font color="blue">Bianchi, et al, 2006, A&A --</font>
对源的光谱分析表明，soft X-ray emission最可能的来源是the gas photoionized by nuclear continuum。 最清晰的证据来自 Mrk 3 的 190 ks 组合 RGS 光谱，它显然是在photoionized gas中产生的，其中共振散射(resonant scattering)起到了重要作用。
#### * 这种东西对于研究AGN有什么意义？
<font color="blue">Wang, et al, 2009, ApJ --</font>
利用高分辨率成像研究这些喷流和排放线气体，为了解向中央引擎提供燃料的星际介质（ISM）以及活动星系核与主星系之间的相互作用提供了有价值的探针。
<font color="red">Me --</font>
感觉还是没连起来，soft X-ray emission的存在只能(possible)说明这里应该有一团气体，由于中心向外发射的光子，被光致电离了，从而产生了X-ray emission。。这难道就是中心AGN对星系的作用吗？传说中的AGN反馈？
## 二. 为什么选择NGC4151？
### 1. NGC4151有什么特色？
<font color="blue">Wang, et al, 2009, ApJ --</font>
* 被认为是最近的典型Seyfert 1星系；
* 有线性射电喷流，～3.5‘’（～230pc）；
* 有双锥的NLR，沿NE（东北方向）和SW（西南方向）延展，～10‘’；
* 射电喷流与NLR的方向不同；
* HST观测到块状的ionized gas；
* Chandra ACIS iamges观测到延展的soft X-ray emission，与r>1.5‘’处的光学禁线发射密切相关；
### 2. 以往观测缺少了什么？为什么需要新观测？
<font color="blue">Wang, et al, 2009, ApJ --</font>
* X-ray emission与radio jet之间的关联
	* pile-up and resolution
## 三. 观测了什么？
<font color="blue">Wang, et al, 2009, ApJ --</font>
* 观测：
	* 比较源图像和PSF图像
	* 比较不同方向的表面亮度分布
* 目的：
	* 寻找亮核周围的低亮度发射，看是否存在延展发射
* 结论：
	* 存在延展发射，且主要沿NE和SW方向，
	<font color="red">Me --</font>
	与光学上盘的方向近乎垂直

<div style="border-top: 1px dashed #888;"></div>

* 观测：
	* 叠加X-ray emission和[O iii]发射线图像比较形态
	* 计算NLR clouds中的[O iii]/soft X-ray ratio
* 目的：
	* <font color="blue">Bianchi, et al, 2006, A&A --</font>
	使用HST和Chandra调查了附近8个Seyfert 2星系的NLR，发现kpc尺度的soft X_ray emission与[O iii] emission的范围和形态一致。提出由AGN连续体光电离的相同气体可以同时产生具有观察到的比率的X-ray和[O iii]发射。这些源~3-11。（请注意，这些比率是~kpc区域的平均值，因为ACIS图像不允许将X射线发射与HST 图像中看到的小团块进行比较。）
* 结论：
	* 光学[O iii]子结构与X-ray形态地惊人对应，特别是NE和SW方向
	* 不同NLR clouds中的[O iii]/soft X-ray ratio不同，较高的比率说明此处的电离度较低，较低的比率说明此处的电离度较高，意味着有higher X-ray emission。这可能与流出的射电等离子体(radio plasma)有关，因为
	<font color="blue">Harris & Krawczynski 2006, ARA&A --</font> many radio jets have X-ray counterparts originating from non-thermal and thermal processes.
	还有大部分NLR clouds的比率接近10，相当恒定的[O iii]/X-ray比率表明即使在大半径下也有几乎均匀的电离参数，需要接近$r^{−2}$的密度依赖性，正如对来自中心核的风所预期的那样。

<div style="border-top: 1px dashed #888;"></div>

* 观测：
	* 考虑不同的发射机制
		* Synchrotron Emission：
			* the X-ray intensity would be consistent with a single powerlaw extrapolation or a broken power-law concaving downward.
			拟合幂律谱
			* the minimum energy argument (or equipartition) generally adopted for synchrotron sources
			![Alt text](Attachments/The_scale_of_X-ray_emission_and_the_physics_behind/the_minimum_energy_argument.png)
		* Inverse Compton(IC) Emission：
			* the synchrotron self-Compton (SSC) emission
				* 高能电子发生同步辐射产生光子，光子与这些高能电子又发生相互作用，产生更高能量的光子
				* 光子能量密度：$u_{\rm sync}=2L_{\rm sync}R/4cV$，假设均匀发射球体来得到体积，其中$L_{\rm sync}$是射电光度，R是球体半径，c是光速，V是体积。
			* 宇宙微波背景(CMB)的IC scattering
				* CMB光子获得高能电子的能量
				* 光子能量密度$u_{\rm CMB}=4\times 10^{−13}~\rm ergs~cm^{−3}$。
				<font color="red">Me --</font> 没有给引用，估计是定值。
			* <font color="blue">Blumenthal & Gould, 1970 --</font>
			estimate the magnetic field from the ratio between the X-ray and the radio fluxes.
			<font color="red">Me --</font> 没有找到具体公式。
			* <font color="blue">Mernier, et al, 2019, MNRAS --</font>
			![Alt text](Attachments/The_scale_of_X-ray_emission_and_the_physics_behind/X_ray_to_radio1.jpg)
			![Alt text](Attachments/The_scale_of_X-ray_emission_and_the_physics_behind/X_ray_to_radio2.jpg)
			<font color="red">Me --</font> 在另一篇文章里找到了，感谢JT。
		* Thermal Bremsstrahlung Emission：
			* <font color="blue">Kruszewski, 1971(引用最高那篇) --</font>
			光学偏振测量中推导出$n_{\rm e}$。 
			<font color="red">Me --</font> 脑袋里常常充满疑惑，因为我没找到对应公式
* 目的：
	* 理解X-ray emission与radio knots的关联
	* 寻找X-ray emission的可能机制
* 结论：
	* 观察到的X-ray intensities比radio synchrotron spectra还要高几个数量级。 这不能归因于radio或X-ray flux density测量的不确定性，这表明简单的synchrotron model不足以用于解释X-ray emission。
	* IC emission中提到的前两种情况，光子能量密度都远低于NGC 4151核区中AGN和星光组合的光子能量密度。因此主要考虑后面这种情况。如果想运用IC emission来解释X-ray emission，需要的磁场比均分磁场(通过同步辐射得到)大3个数量级——不可能，为了降低磁场的影响，需要具有相对论体射流速度的射束模型，但现实也不符合，因此该模型无法解释X-ray emission。
	<font color="red">Me --</font> 为什么磁场大不可能，让人疑惑
	* 热发射所需$n_{\rm e}$小于光学偏振测量中推导出的值，因此很有可能

<div style="border-top: 1px dashed #888;"></div>

* 观测：
	* 假设光学核发射的峰值源自活动星系核，将X射线、光学和射电核对齐。观察其图像。
* 目的：
	* 寻找三者的联系
* 结论：
	* 喷流-云交互场景(jet–cloud interaction scenario)
	radio knots（例如，[Fe ii]/Paβ）处的[Fe ii]发射有所增强——这与喷射云相互作用的点一致。
	knots的压力小于喷流的压力——符合Kraft 等人 (2009) 提出的冲击场景的最低要求
	对喷流的估计，认为其相对重且慢——与流体动力学模拟中喷流的特性非常匹配，热主导的、缓慢且密集的Seyfert喷流遇到稠密的气体云。
## 四. 为什么值得进一步观测？
* 符合喷流-云交互场景
* 前人的经验：强有力的证据表明射电喷流与Seyfert星系中NLR尺度上的ISM会发生相互作用。