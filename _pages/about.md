---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm an undergraduate student in Zhejiang University, major in Computer Science and minor in ACEE

My research focuses on **Vision-Language models** and extends in two directions:

- Diffusion (text2image, image edit)
- Robotics (vla)

<div style="display: flex; justify-content: center; align-items: center; flex-direction: column;">
  <svg width="500" height="330" style="border: 1px solid transparent;">
    <!-- VL Circle -->
    <circle cx="250" cy="120" r="100" fill="rgba(244,143,177,0.2)" stroke="rgb(244,143,177)" stroke-width="4"/>
    <text x="180" y="70" fill="rgb(244,143,177)" style="font-size: 18px; font-weight: bold;">Vision-Language</text>
    <text x="210" y="100" fill="black" style="font-size: 10px;">Sugar, NeurIPS’24</text>
    <text x="225" y="115" fill="black" style="font-size: 10px;">PhysBench</text>
    <!-- Robotics Circle -->
    <circle cx="170" cy="220" r="100" fill="rgba(255,202,100,0.2)" stroke="rgb(255,202,100)" stroke-width="4"/>
    <text x="100" y="210" fill="rgb(255,202,100)" style="font-size: 18px; font-weight: bold;">Robotics</text>
    <text x="115" y="250" fill="black" style="font-size: 10px;">VLT</text>
    <!-- Education Circle -->
    <circle cx="330" cy="220" r="100" fill="rgba(129,212,250,0.2)" stroke="rgb(129,212,250)" stroke-width="4"/>
    <text x="320" y="205" fill="rgb(129,212,250)" style="font-size: 18px; font-weight: bold;">Diffusion</text>
    <!-- Intersection Text -->
    <text x="325" y="230" fill="black" style="font-size: 10px;">AnyEdit</text>
    <text x="320" y="245" fill="black" style="font-size: 10px;">Meissonic</text>
  </svg>
</div>


### Publications

<a href="https://www.flaticon.com/free-icons/korea" title="korea icons"></a>

<style>
    table {
        width: 100%;
        border-collapse: collapse;
    }
    td {
        padding: 5pt;
        vertical-align: middle;
    }
    .first-column {
        width: 25%;
        padding:5pt;
        text-align: center;
        vertical-align:middle
    }
    .second-column {
        width: 75%;
        padding:5pt;
        text-align: left;
        vertical-align:middle
    }
    .blue-bold {
        color: navy; /* 使用深蓝色 */
        font-weight: bold; /* 加粗 */
        font-size: 16px;
    }
    /* 隐藏表格边框 */
    table, th, td {
        border: none;
    }
    /* 去除链接下划线 */
    a {
        text-decoration: none; 
    }
</style>
<table>
    <tr>
        <td class="first-column">
                <img src="../images/physbench.png" width="80%"/>
        </td>
        <td class="second-column">
            <span class="blue-bold">PhysBench: Benchmarking and Enhancing Vision-Language Models for Physical World Understanding</span>
            <div>
                <strong>Wei Chow<sup>*</sup></strong>,
                Jiageng Mao<sup>*</sup>, 
                Boyi Li, 
                Daniel Seita, 
                Vitor Guizilini, 
                Yue Wang
            </div>
            <div>
                <a href="https://eval.ai/web/challenges/challenge-page/2379/overview">
                    <img src="https://img.shields.io/badge/🔺-EvalAI-gray.svg?"></a>
            </div> 
        </td>
    </tr>
    <tr>
        <td class="first-column">
                <img src="../images/sugar.png" width="80%"/>
        </td>
        <td class="second-column">
            <span class="blue-bold">Unified Generative and Discriminative Training for Multi-modal Large Language Models</span>
            <div>
                <strong>Wei Chow</strong>,
                Juncheng Li, 
                Kaihang Pan, 
                Qifan Yu, 
                Hao Fei, 
                Zhiqi Ge, 
                Shuai Yang, 
                Siliang Tang, 
                Hanwang Zhang, 
                Qianru Sun
            </div>
            <div>
                <a href="https://neurips.cc/virtual/2024/poster/93174"><img src="https://img.shields.io/badge/NeurIPS 2024-poster-blue" alt="Poster"></a>
            </div> 
        </td>
    </tr>
    <tr>
        <td class="first-column">
                <img src="../images/paper1.png" width="100%"/>
        </td>
        <td class="second-column">
            <span class="blue-bold">One Graph Model for Cross-domain Dynamic Link Prediction</span>
            <div>
                Xuanwen Huang<sup>*</sup>
                <strong>Wei Chow<sup>*</sup></strong>,
                Yize Zhu,
                Yang Wang,
                Ziwei Chai,
                Chunping Wang,
                Lei Chen,
                Yang Yang
            </div>
            <div>
                <a href="https://arxiv.org/pdf/2402.02168.pdf"><img src="https://img.shields.io/badge/arXiv-2402.02168-b31b1b.svg" alt="arXiv"></a>
            </div> 
        </td>
    </tr>
    <tr>
        <td class="first-column">
                <img src="../images/paper2.png" width="80%"/>
        </td>
        <td class="second-column">
            <span class="blue-bold">Exploring Correlations of Self-supervised Tasks for Graphs</span>
            <div>
                Taoran Fang,
                <strong>Wei Chow</strong>,
                Yifei Sun,
                Kaiqiao Han,
                Lvbin Ma,
                Yang Yang
            </div>
            <div>
                <a href="https://arxiv.org/pdf/2405.04245"><img src="https://img.shields.io/badge/ICML 2024-poster-blue" alt="Poster"></a>
                <a href="https://github.com/zjunet/GraphTCM"><img src="https://img.shields.io/github/stars/zjunet/GraphTCM?style=social&amp;logo=github" width="75pt"></a>
            </div> 
        </td>
    </tr>
    <tr>
        <td class="first-column">
                <img src="../images/anyedit.png" width="80%"/>
        </td>
        <td class="second-column">
            <span class="blue-bold">AnyEdit: Unified High-Quality Image Edit with Any Idea</span>
            <div>
                Qifan Yu<sup>*</sup>, 
                <strong>Wei Chow<sup>*</sup></strong>, 
                Zhongqi Yue, 
                Kaihang Pan,
                Yang Wu, 
                Xiaoyang Wan, 
                Juncheng Li, 
                Siliang Tang, 
                Hanwang Zhang, 
                Yueting Zhuang
            </div>
            <div>
                <a href="https://arxiv.org/abs/2411.15738"><img src="https://img.shields.io/badge/arXiv-2411.15738-b31b1b.svg" alt="arXiv"></a>
                <a href="https://dcd-anyedit.github.io/"><img src="https://img.shields.io/badge/website-gold" alt="project website"></a>
            </div> 
        </td>
    </tr>
    <tr>
        <td class="first-column">
                <img src="../images/paper4.png" width="80%"/>
        </td>
        <td class="second-column">
            <span class="blue-bold">Meissonic: Revitalizing Masked Generative Transformers for Efficient High-Resolution Text-to-Image Synthesis</span>
            <div>
                Jinbin Bai, 
                Tian Ye, 
                <strong>Wei Chow</strong>, 
                Enxin Song, 
                Qing-Guo Chen, 
                Xiangtai Li,
                Zhen Dong, 
                Lei Zhu, 
                Shuicheng Yan
            </div>
            <div>
                <a href="https://arxiv.org/abs/2410.08261"><img src="https://img.shields.io/badge/arXiv-2410.08261-b31b1b.svg" alt="arXiv"></a>
                <a href="https://github.com/viiika/Meissonic"><img src="https://img.shields.io/github/stars/viiika/Meissonic?style=social&amp;logo=github" width="75pt"></a>
                <a href="https://huggingface.co/MeissonFlow/Meissonic">
    				<img src="https://img.shields.io/badge/🤗-Model-blue.svg"></a>
                <a href="https://huggingface.co/spaces/MeissonFlow/meissonic">
    				<img src="https://img.shields.io/badge/🤗-Space-purple.svg"></a>
            </div> 
        </td>
    </tr>
</table>










<span style="text-transform:lowercase;">$^*$equal contribution</span>




### Course Project

<style>
    table {
        width: 100%;
        border-collapse: collapse;
    }
    td {
        padding: 5pt;
        vertical-align: middle;
    }
    .first-column {
        width: 25%;
        padding:5pt;
        text-align: center;
        vertical-align:middle
    }
    .second-column {
        width: 75%;
        padding:5pt;
        text-align: left;
        vertical-align:middle
    }
    .blue-bold {
        color: navy; /* 使用深蓝色 */
        font-weight: bold; /* 加粗 */
        font-size: 16px;
    }
    /* 隐藏表格边框 */
    table, th, td {
        border: none;
    }
</style>
<table>
    <tr>
        <td class="first-column">
                <img src="../images/secondhand.png" width="100%"/>
        </td>
        <td class="second-column">
            <a href="https://github.com/weichow23/Second-hand_housing_transaction"><span class="blue-bold">Analysis on the relationship between second-hand housing transactions and business districts in Hangzhou's main urban area</span></a>
            <div>
                [2024 Spring in ZJU] Real Estate Finance and Economics
            </div>
        </td>
    </tr>
    <tr>
        <td class="first-column">
                <img src="../images/photo.png" width="100%"/>
        </td>
        <td class="second-column">
            <a href="https://github.com/weichow23/Computational-Photography"><span class="blue-bold">Interactive digital montage</span></a>
            <div>
                [2024 Spring in ZJU] Computational Photography
            </div>
        </td>
    </tr>
    <tr>
        <td class="first-column">
                <img src="../images/mathm.png" width="100%"/>
        </td>
        <td class="second-column">
            <a href="https://github.com/weichow23/math-modeling-proj"><span class="blue-bold">Optimal matching of tutors and students</span></a>
            <div>
                [2022 Fall in ZJU] Math Modeling
            </div>
        </td>
    </tr>
</table>
### Academic Service

##### Challenge Organizer

[DEMON: Demonstrative Instruction Following Challenge](https://dcdmllm.github.io/DEMON-challenge/) (MM'2024)

##### Reviewer

WWW'25, CVPR'25

### Experience

<table style="width:100%; border:none; border-collapse:collapse;"> 
  <tr>
    <td style="width:10%; vertical-align:middle; text-align:center;">
      <img src="../images/zju.png" alt="" style="width:70px;" />
    </td>
    <td style="width:90%; vertical-align:top; font-size:12px;">
      <span style="font-size:16px; font-weight:bold;">Zhejiang University</span><br>
      2021.08 ~ 2025.06 (expected)<br>
        GPA: GPA: 92.9/100 (rank <b>1/301</b>)<br>
      B.Eng. in Computer Science and Technology, Minor in Advanced Class of Engineering Education (Honors)<br>
    	supervisored by Professor <a href="https://person.zju.edu.cn/juncheng">Juncheng Li</a>
      </td>
  </tr>
  <tr>
    <td style="width:6%; vertical-align:middle; text-align:center;">
      <img src="../images/hku.png" alt="" style="width:60px;" />
    </td>
    <td style="width:90%; vertical-align:top; font-size:12px;">
   <span style="font-size:16px; font-weight:bold;">University of Hong Kong</span> <br>
      2023.06 - 2023.12<br>
      Research Assistant in <a href="https://mmlab.ie.cuhk.edu.hk/people.html">MMLab</a> supervisored by Professor <a href="http://luoping.me/">Luo Ping</a>
    </td>
  </tr>
   <tr>
    <td style="width:3%; vertical-align:middle; text-align:center;">
      <img src="../images/ntu.png" alt="" style="width:56px;" />
    </td>
    <td style="width:90%; vertical-align:top; font-size:12px;">
   <span style="font-size:16px; font-weight:bold;">Nanyang Technological University</span> <br>
      2023.12 - 2024.6<br>
      Intern supervisored by Professor <a href="https://mreallab.github.io/index.html">Hanwang Zhang</a>
    </td>
  </tr> 
  <tr>
    <td style="width:6%; vertical-align:middle; text-align:center;">
      <img src="../images/usc.png" alt="" style="width:65px;" />
    </td>
    <td style="width:90%; vertical-align:top; font-size:12px;">
   <span style="font-size:16px; font-weight:bold;">University of Southern California</span> <br>
      2024.06 - Present<br>
      Intern supervisored by Professor <a href="https://yuewang.xyz/">Yue Wang</a>
    </td>
  </tr> 
</table>





### Misc.

In my free time, I like curving seal 🗿, playing tennis 🎾, cooking 🍳and taking photography 📷

