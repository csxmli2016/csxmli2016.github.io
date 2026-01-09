---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% assign Xiaoming_Li = "**Xiaoming Li**" %}
{% assign Xinyu_Hou = "[Xinyu Hou](https://scholar.google.com/citations?user=90lIt2QAAAAJ)" %}
{% assign Chen_Change_Loy = "[Chen Change Loy](https://scholar.google.com.sg/citations?user=559LF80AAAAJ&hl=en)" %}

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<div style="text-align: justify; line-height: 1.6; margin-bottom: 20px;" markdown="1">

I am an incoming Associate Professor with [PRLab](https://prlab-nju.com/nju/) at [the School of Intelligence Science and Technology](https://is.nju.edu.cn/), Nanjing University (Suzhou Campus).
Currently, I am a research fellow at <a href="https://www.mmlab-ntu.com/" target="_blank">MMLab@NTU</a>, Nanyang Technological University, Singapore, working with Prof. <a href="https://www.mmlab-ntu.com/person/ccloy/" target="_blank">Chen Change Loy</a>.
I obtained my joint Ph.D degrees from Harbin Institute of Technology and The Hong Kong Polytechnic University, under the supervision of Prof. <a href="https://scholar.google.com/citations?hl=zh-CN&user=rUOpCEYAAAAJ&view_op=list_works" target="_blank">Wangmeng Zuo</a> and Prof. <a href="https://www4.comp.polyu.edu.hk/~cslzhang/" target="_blank">Lei Zhang</a>.
My research interests lie in high-fidelity image restoration (face/text) and controllable image generation.
</div>



<div style="background-color: #fff9e6; border: 1px solid #ffe58f; border-radius: 0.5rem; padding: 1.25rem; margin: 1.25rem 0;">
  <h3 style="margin-top: 0; color: #d46b08; font-size: 1.1rem;">
    <i class="fas fa-flag"></i> Openings / 招生信息
  </h3>
  <hr style="border: 0; border-top: 1px solid #ffe58f; margin: 0.75rem 0;">
  
  <p style="margin-bottom: 0.75rem; line-height: 1.6;">
    We are <strong>actively looking</strong> for passionate and talented students to join our research group at <strong>Nanjing University (Suzhou)</strong>. If you are interested in working on <strong>image restoration</strong> and <strong>image/video generation/editing</strong>, please send me an email with your CV.
  </p>
  
  <p style="margin-bottom: 0.75rem; line-height: 1.6;">
    我们课题组长期欢迎有志于<strong>图像/视频复原/编辑、生成模型</strong>等方向的优秀同学加入！有意向的同学请发送简历至我的邮箱。
  </p>

  <div style="line-height: 1.6;" markdown="1">
  **招收对象**
  * **本科生：** 南京大学及其他高校大一至大三学生，需保证至少一年的进组科研时间或者完成一个完整工作，表现优秀者提供科研补助。
  * **研究生：** 硕士/~~博士~~研究生，欢迎计算机、数学等相关专业背景。
  * **研究人员：** 全职/兼职研究助理 (RA)。
  </div>
  <!--
  **2. 硕士研究生说明**
  * 招收对象为愿意全身心投入做好科研、学习专业知识的学生。
  * 需对编程能力有自信，喜欢阅读源码。
  * 如成功保研，建议大四在课题组内完成毕设，提前熟悉背景并在入学前尝试投稿。
  **3. 博士研究生说明**
  * 优先考虑以第一作者身份在 CCF A 类会议或期刊发表过至少一篇论文的同学。
  * 具有生成式大模型相关研究经验者优先考虑。
  * -->
  <!--<p style="margin-bottom: 0; font-weight: bold;">
    目前，课题组正在招收 <span style="color: #cf1322;">2026年秋季</span> 入学的硕士研究生和博士研究生。欢迎感兴趣的同学积极投递简历！
  </p>-->
</div>




# 🔥 News

<div style="max-height: 16rem; overflow-y: auto; padding-right: 1rem;" markdown="1">

- *2025.12*: &nbsp; One paper is accepted in IJCV.
- *2025.11*: &nbsp; 获得 中国图象图形学学会自然科学二等奖，排名3/5.

</div>



# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2026</div><img src='images/AITTI.jpg' alt="sym" width="100%" style="cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge"></div></div>
<div class='paper-box-text' markdown="1">

**AITTI: Learning Adaptive Inclusive Token for Text-to-Image Generation**

International Journal of Computer Vision, 2026

Xinyu Hou, **<u>Xiaoming Li</u>**, Chen Change Loy

[<i class="fas fa-file-pdf"></i> **PDF**](https://arxiv.org/pdf/2406.12805) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-github"></i> **Code**](https://github.com/itsmag11/AITTI)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/refstar.jpg' alt="sym" width="100%" style="cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge" ></div></div>
<div class='paper-box-text' markdown="1">

**RefSTAR: Blind Facial Image Restoration with Reference Selection, Transfer, and Reconstruction**

The Association for the Advancement of Artificial Intelligence, 2026

Zhicun Yin, Junjie Chen, Ming Liu, Zhixin Wang, Fan Li, Renjing Pei, **<u>Xiaoming Li</u>**, Rynson WH Lau, Wangmeng Zuo

[<i class="fas fa-file-pdf"></i> **PDF**](https://arxiv.org/pdf/2507.10470) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-github"></i> **Code**](https://github.com/yinzhicun/RefSTAR)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div>
<!--<img src='images/marconetplus.jpg' alt="sym" width="100%" style="cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge" >-->
<video src='images/marconetplusC.mp4' muted autoplay loop playsinline onclick="openModal(this.src)" title="Click to enlarge" style="width: 100%; cursor:zoom-in;"></video>
</div></div>
<div class='paper-box-text' markdown="1">

**Enhanced Generative Structure Prior for Chinese Text Image Super-Resolution**

IEEE Transactions on Pattern Analysis and Machine Intelligence, 2025

**<u>Xiaoming Li</u>**, Wangmeng Zuo, Chen Change Loy

[<i class="fas fa-file-pdf"></i> **PDF**](https://arxiv.org/pdf/2508.07537) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-github"></i> **Code**](https://github.com/csxmli2016/MARCONetPlusPlus)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/omegance_demo.gif' alt="sym" width="100%" style="cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge" ></div></div>
<div class='paper-box-text' markdown="1">

**Omegance: A Single Parameter for Various Granularities in Diffusion-Based Synthesis**

International Conference on Computer Vision, 2025

Xinyu Hou, Zongsheng Yue, **<u>Xiaoming Li</u>**, Chen Change Loy

[<i class="fas fa-file-pdf"></i> **PDF**](https://openaccess.thecvf.com/content/ICCV2025/papers/Hou_Omegance_A_Single_Parameter_for_Various_Granularities_in_Diffusion-Based_Synthesis_ICCV_2025_paper.pdf) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-github"></i> **Code**](https://github.com/itsmag11/Omegance) &nbsp;&nbsp;&nbsp;
[<i class="fas fa-home"></i> **Project Page**](https://itsmag11.github.io/Omegance/)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/wplus.jpg' alt="sym" width="100%" style="cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge" ></div></div>
<div class='paper-box-text' markdown="1">

**When stylegan meets stable diffusion: a w+ adapter for personalized image generation**

IEEE International Conference on Computer Vision and Pattern Recognition, 2024

**<u>Xiaoming Li</u>**, Xinyu Hou, Chen Change Loy

[<i class="fas fa-file-pdf"></i> **PDF**](http://openaccess.thecvf.com/content/CVPR2024/papers/Li_When_StyleGAN_Meets_Stable_Diffusion_a_W_Adapter_for_Personalized_CVPR_2024_paper.pdf) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-github"></i> **Code**](https://github.com/csxmli2016/w-plus-adapter) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-home"></i> **Project Page**](https://csxmli2016.github.io/projects/w-plus-adapter/)



</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/wideangle.jpg' alt="sym" width="100%" style="cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge" ></div></div>
<div class='paper-box-text' markdown="1">

**Combining Generative and Geometry Priors for Wide-Angle Portrait Correctionn**

European Conference on Computer Vision, 2024

Lan Yao, Chaofeng Chen, **<u>Xiaoming Li</u>**<sup><i class="fas fa-envelope" style="vertical-align: baseline;" title="Corresponding author"></i></sup>, Zifei Yan, Wangmeng Zuo

[<i class="fas fa-file-pdf"></i> **PDF**](https://arxiv.org/pdf/2410.09911) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-github"></i> **Code**](https://github.com/Dev-Mrha/DualPriorsCorrection)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2023</div><img src='images/dmdnet.jpg' alt="sym" width="100%" style="cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge" ></div></div>
<div class='paper-box-text' markdown="1">

**Learning Dual Memory Dictionaries for Blind Face Restoration**

IEEE Transactions on Pattern Analysis and Machine Intelligence, 2023

**<u>Xiaoming Li</u>**, Shiguang Zhang, Shangchen Zhou, Lei Zhang, Wangmeng Zuo

[<i class="fas fa-file-pdf"></i> **PDF**](https://arxiv.org/pdf/2210.08160) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-github"></i> **Code**](https://github.com/csxmli2016/DMDNet)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/marconet.jpg' alt="sym" width="100%" style="cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge" ></div></div>
<div class='paper-box-text' markdown="1">

**Learning Generative Structure Prior for Blind Text Image Super-resolution**

IEEE International Conference on Computer Vision and Pattern Recognition, 2023

**<u>Xiaoming Li</u>**, Wangmeng Zuo, Chen Change Loy

[<i class="fas fa-file-pdf"></i> **PDF**](http://openaccess.thecvf.com/content/CVPR2023/papers/Li_Learning_Generative_Structure_Prior_for_Blind_Text_Image_Super-Resolution_CVPR_2023_paper.pdf) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-github"></i> **Code**](https://github.com/csxmli2016/MARCONet)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/f2n.jpg' alt="sym" width="100%" style="cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge" ></div></div>
<div class='paper-box-text' markdown="1">

**From Face to Natural Image: Learning Real Degradation for Blind Image Super-Resolution**

European Conference on Computer Vision, 2022

**<u>Xiaoming Li</u>**, Chaofeng Chen, Xianhui Lin, Wangmeng Zuo, Lei Zhang

[<i class="fas fa-file-pdf"></i> **PDF**](https://arxiv.org/pdf/2210.00752) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-github"></i> **Code**](https://github.com/csxmli2016/ReDegNet)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/SAFM.jpg' alt="sym" width="100%" style="cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge" ></div></div>
<div class='paper-box-text' markdown="1">

**Semantic-shape Adaptive Feature Modulation for Semantic Image Synthesis**

IEEE International Conference on Computer Vision and Pattern Recognition, 2022

Zhengyao Lv, **<u>Xiaoming Li</u>**, Zhenxing Niu, Bing Cao, Wangmeng Zuo

[<i class="fas fa-file-pdf"></i> **PDF**](https://openaccess.thecvf.com/content/CVPR2022/papers/Lv_Semantic-Shape_Adaptive_Feature_Modulation_for_Semantic_Image_Synthesis_CVPR_2022_paper.pdf) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-github"></i> **Code**](https://github.com/cszy98/SAFM)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2021</div><img src='images/psfrgan.jpg' alt="sym" width="100%" style="cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge" ></div></div>
<div class='paper-box-text' markdown="1">

**Progressive semantic-aware style transformation for blind face restoration**

IEEE International Conference on Computer Vision and Pattern Recognition, 2021

Chaofeng Chen, **<u>Xiaoming Li</u>**, Lingbo Yang, Xianhui Lin, Lei Zhang, Kwan-Yee K Wong

[<i class="fas fa-file-pdf"></i> **PDF**](http://openaccess.thecvf.com/content/CVPR2021/papers/Chen_Progressive_Semantic-Aware_Style_Transformation_for_Blind_Face_Restoration_CVPR_2021_paper.pdf) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-github"></i> **Code**](https://github.com/chaofengc/PSFRGAN)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2021</div><img src='images/sean.jpg' alt="sym" width="100%" style="cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge" ></div></div>
<div class='paper-box-text' markdown="1">

**Learning Semantic Person Image Generation by Region-Adaptive Normalization**

IEEE International Conference on Computer Vision and Pattern Recognition, 2021

Zhengyao Lv, **<u>Xiaoming Li</u>**, Xin Li, Fu Li, Tianwei Lin, Dongliang He, Wangmeng Zuo

[<i class="fas fa-file-pdf"></i> **PDF**](http://openaccess.thecvf.com/content/CVPR2021/papers/Lv_Learning_Semantic_Person_Image_Generation_by_Region-Adaptive_Normalization_CVPR_2021_paper.pdf) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-github"></i> **Code**](https://github.com/cszy98/SPGNet)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2020</div><img src='images/dfdnet.gif' alt="sym" width="100%" style="cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge" ></div></div>
<div class='paper-box-text' markdown="1">

**Blind Face Restoration via Deep Multi-scale Component Dictionaries**

European Conference on Computer Vision, 2020

**<u>Xiaoming Li</u>**, Chaofeng Chen, Shangchen Zhou, Xianhui Lin, Wangmeng Zuo, Lei Zhang

[<i class="fas fa-file-pdf"></i> **PDF**](https://arxiv.org/pdf/2008.00418) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-github"></i> **Code**](https://github.com/csxmli2016/DFDNet)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2020</div>
<video src='images/asffnet.mp4' width="100%" muted autoplay loop playsinline onclick="openModal(this.src)" title="Click to enlarge" style="cursor:zoom-in;"></video>
</div></div>
<div class='paper-box-text' markdown="1">

**Enhanced Blind Face Restoration With Multi-Exemplar Images and Adaptive Spatial Feature Fusion**

IEEE International Conference on Computer Vision and Pattern Recognition, 2020

**<u>Xiaoming Li</u>**, Wenyu Li, Dongwei Ren, Hongzhi Zhang, Meng Wang, Wangmeng Zuo

[<i class="fas fa-file-pdf"></i> **PDF**](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Enhanced_Blind_Face_Restoration_With_Multi-Exemplar_Images_and_Adaptive_Spatial_CVPR_2020_paper.pdf) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-github"></i> **Code**](https://github.com/csxmli2016/ASFFNet512)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2018</div><img src='images/gfrnet.jpg' alt="sym" width="100%" style="cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge" ></div></div>
<div class='paper-box-text' markdown="1">

**Learning Warped Guidance for Blind Face Restoration**

European Conference on Computer Vision, 2018

**<u>Xiaoming Li</u>**, Ming Liu, Yuting Ye, Wangmeng Zuo, Liang Lin, Ruigang Yang

[<i class="fas fa-file-pdf"></i> **PDF**](http://openaccess.thecvf.com/content_ECCV_2018/papers/Xiaoming_Li_Learning_Warped_Guidance_ECCV_2018_paper.pdf) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-github"></i> **Code**](https://github.com/csxmli2016/GFRNet)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2018</div><img src='images/shiftnet.jpeg' alt="sym" width="100%" style="cursor: pointer;" onclick="openModal(this.src)" title="Click to enlarge" ></div></div>
<div class='paper-box-text' markdown="1">

**Shift-Net: Image Inpainting via Deep Feature Rearrangement**

European Conference on Computer Vision, 2018

Zhaoyi Yan, **<u>Xiaoming Li</u>**, Mu Li, Wangmeng Zuo, Shiguang Shan

[<i class="fas fa-file-pdf"></i> **PDF**](http://openaccess.thecvf.com/content_ECCV_2018/papers/Zhaoyi_Yan_Shift-Net_Image_Inpainting_ECCV_2018_paper.pdf) &nbsp;&nbsp;&nbsp;
[<i class="fab fa-github"></i> **Code**](https://github.com/Zhaoyi-Yan/Shift-Net)

</div>
</div>


<!--
# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->


# 📖 Educations
- *2019.01 - 2022.09*, The Hong Kong Polytechnic University, Joint PhD, Suprevisor: [Prof. Lei Zhang](https://www4.comp.polyu.edu.hk/~cslzhang/). 
- *2016.09 - 2021.09*, Harbin Institute of Technology, PhD, Supervisor: [Prof. Wangmeng Zuo](https://scholar.google.com/citations?user=rUOpCEYAAAAJ). 
- *2013.09 - 2016.07*, Harbin Institute of Technology, Master. 
- *2009.09 - 2013.07*, Harbin Institute of Technology, Bachelor. 


<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
- -->

# 💻 Internships
- *2019.11 - 2021.11*, [Alibaba DAMO Academy](https://damo.alibaba.com/).




---
<p style="text-align: center; color: #888; font-size: 1rem; margin-top: 0.5rem;">
The website template is adapted from <a href="https://github.com/RayeRen/rayeren.github.io" target="_blank" style="color: #777; text-decoration: underline;">RayeRen</a>.
Last updated: January 2, 2026
</p>


<!-- 
############################################################################################################################################
定义script的function
############################################################################################################################################
-->

<div id="myModal" onclick="closeModal()" style="display:none; position:fixed; z-index:9999; top:0; left:0; width:100%; height:100%; background-color:rgba(0,0,0,0.9); cursor:zoom-out;">
  <div id="modalContent" style="margin:auto; display:block; max-width:90%; max-height:90%; position:relative; top:50%; transform:translateY(-50%); text-align:center;">
  </div>
</div>



<a href="https://clustrmaps.com/site/1bd1m" title="Visit tracker"><img src="//www.clustrmaps.com/map_v2.png?d=QOUn4w5djX3sOmVRx_qPmV2YK0mxkbPUBhLlp8-cTH4&cl=ffffff" style="display: none;"></a>
