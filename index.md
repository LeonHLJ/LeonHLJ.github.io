<script type="text/javascript">
<!--
// Toggle Display of BibTeX
function toggleBibtex(articleid) {
  var bib = document.getElementById(articleid);
  // Toggle 
    if(bib.style.display == "none") {
      bib.style.display = "";
    }
    else {
      bib.style.display = "none";
    }
}
-->
</script>

<script type="text/javascript">

  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', 'UA-40926388-1']);
  _gaq.push(['_trackPageview']);

  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();

</script>

## Welcome to Linjiang Huang's Homepage

### Personal Information
- Email: linjiang.huang@cripac.ia.ac.cn
- [Scholar Page](https://scholar.google.com.hk/citations?hl=zh-CN&user=j5rBSw0AAAAJ)

---

### Biography
- Now, I am pursuing my Ph.D. degree in the Institute of Automation Chinese Academy of Sciences ([CASIA](http://www.ia.cas.cn/)) under the supervision of Prof. [Liang Wang](http://sourcedb.ia.cas.cn/cn/iaexpert/201010/t20101013_2986122.html).

- In 2017, I received the Master degree from Huazhong University of Science and Technology ([HUST](http://www.hust.edu.cn/)) in Department of Mechanical Science and Engineering.

- In 2014, I received the Bachelor degree from Huazhong University of Science and Technology ([HUST](http://www.hust.edu.cn/)) in Department of Mechanical Science and Engineering.

My research interests include computer vision, deep learning, particularly action recognition and detection in videos.

---

### Publications
Part-level Graph Convolutional Network for Skeleton-Based Action Recognition,

**Linjiang Huang**, Yan Huang, Wanli Ouyang, Liang Wang

American Association for AI National Conference (**AAAI Oral**), 2020.

[<a href="javascript:toggleBibtex('PL_GCN_abstract')" target="_self">Abstract</a>]
<div class="blockcontent" id="PL_GCN_abstract" style="display:none"> 
  <p style="font-size:16px">
          Recently, graph convolutional networks have achieved remarkable performance for skeleton-based action recognition. In this work, we identify a problem posed by the GCNs for skeleton-based action recognition, namely part-level action modeling. To address this problem, a novel Part-Level Graph Convolutional Network (PL-GCN) is proposed to capture part-level information of skeletons. Different from previous methods, the partition of body parts is learnable rather than manually defined. We propose two part-level blocks, namely Part Relation block (PR block) and Part Attention block (PA block), which are achieved by two differentiable operations, namely graph pooling operation and graph unpooling operation. The PR block aims at learning high-level relations between body parts while the PA block aims at highlighting the important body parts in the action. Integrating the original GCN with the two blocks, the PL-GCN can learn both part-level and joint-level information of the action. Extensive experiments on two benchmark datasets show the state-of-the-art performance on skeleton-based action recognition and demonstrate the effectiveness of the proposed method.
      </p>
</div>

---

Relational Prototypical Network for Weakly Supervised Temporal Action Localization,

**Linjiang Huang**, Yan Huang, Wanli Ouyang, Liang Wang

American Association for AI National Conference (**AAAI Oral**), 2020.

[<a href="javascript:toggleBibtex('RPN_abstract')" target="_self">Abstract</a>]
<div class="blockcontent" id="RPN_abstract" style="display:none"> 
  <p style="font-size:16px">
          In this paper, we propose a weakly supervised temporal action localization method on untrimmed videos based on prototypical networks. We observe two challenges posed by weakly supervision, namely action-background separation and action relation construction.
Unlike the previous method, we propose to achieve action-background separation only by the original videos. To achieve this, a clustering loss is adopted to separate actions from backgrounds and learn intra-compact features, which helps in detecting complete action instances. Besides, a similarity weighting module is devised to further separate actions from backgrounds. To effectively identify actions, we propose to construct relations among actions for prototype learning. A GCN-based prototype embedding module is introduced to generate relational prototypes. Experiments on THUMOS14 and ActivityNet1.2 datasets show that our method outperforms the state-of-the-art methods.
      </p>
</div>

---

Part-aligned Pose-guided Recurrent Network for Action Recognition,

**Linjiang Huang**, Yan Huang, Wanli Ouyang, Liang Wang

Pattern Recognition (**PR**), 2019.

[<a href="https://www.sciencedirect.com/science/article/abs/pii/S0031320319301098">PDF</a>]
[<a href="javascript:toggleBibtex('P2RN_abstract')" target="_self">Abstract</a>]
[<a href="javascript:toggleBibtex('P2RN_bib')" target="_self">Bibtex</a>]
<div class="blockcontent" id="P2RN_abstract" style="display:none"> 
  <p style="font-size:16px">
          Action recognition using pose information has drawn much attention recently. However, most previous approaches treat human pose as a whole or just use pose to extract robust features. Actually, human body parts play an important role in action, and so modeling spatio-temporal information of body parts can effectively assist in classifying actions. In this paper, we propose a Part-aligned Pose-guided Recurrent Network (P$^2$RN) for action recognition. The model mainly consists of two modules, i.e., part alignment module and part pooling module, which are used for part representation learning and part-related feature fusion, respectively. The part-alignment module incorporates an auto-transformer attention, aiming to capture spatial configuration of body parts and predict pose attention maps. While the part pooling module exploits both symmetry and complementarity of body parts to produce fused body representation. The whole network is a recurrent network which can exploit the body representation and simultaneously model spatio-temporal evolutions of human body parts. Experiments on two publicly available benchmark datasets show the state-of-the-art performance and demonstrate the power of the two proposed modules.
      </p>
</div>
<div class="blockcontent" id="P2RN_bib" style="display:none"> 
<pre>
@article{huang2019part,
  title={Part-aligned pose-guided recurrent network for action recognition},
  author={Huang, Linjiang and Huang, Yan and Ouyang, Wanli and Wang, Liang},
  journal={Pattern Recognition},
  volume={92},
  pages={165--176},
  year={2019},
  publisher={Elsevier}
}
</pre>
</div>

---

Hierarchical Graph Convolutional Network for Skeleton-Based Action Recognition,

**Linjiang Huang**, Yan Huang, Wanli Ouyang, Liang Wang

International Conference on Image and Graphics (**ICIG**), 2019.

[<a href="https://link.springer.com/chapter/10.1007/978-3-030-34120-6_8">PDF</a>]
[<a href="javascript:toggleBibtex('HiGCN_abstract')" target="_self">Abstract</a>]
[<a href="javascript:toggleBibtex('HiGCN_bib')" target="_self">Bibtex</a>]
<div class="blockcontent" id="HiGCN_abstract" style="display:none"> 
  <p style="font-size:16px">
          Skeleton-based action recognition has drawn much attention recently. Previous methods mainly focus on using RNNs or CNNs to process skeletons. But they ignore the topological structure of the skeleton which is very important for action recognition. Recently, Graph Convolutional Networks (GCNs) achieve remarkable performance in modeling non-Euclidean structures. However, current graph convolutional networks lack the capacity of modeling hierarchical information, which may be sub-optimal for classifying actions which are performed in a hierarchical way. In this work, a novel Hierarchical Graph Convolutional Network (HiGCN) is proposed to deal with these problems. The proposed model includes several Hierarchical Graph Convolutional Layers (HiGCLs). Each layer consists of an attention block and a hierarchical graph convolutional block, which are used for salient feature enhancement and hierarchical representation learning, respectively. To represent hierarchical information of human actions, we propose a graph pooling method, which is differentiable and can be plugged into GCN in an end-to-end manner. Extensive experiments on two benchmark datasets show the state-of-the-art performance of our method.
      </p>
</div>
<div class="blockcontent" id="HiGCN_bib" style="display:none"> 
<pre>
@inproceedings{huang2019hierarchical,
  title={Hierarchical Graph Convolutional Network for Skeleton-Based Action Recognition},
  author={Huang, Linjiang and Huang, Yan and Ouyang, Wanli and Wang, Liang},
  booktitle={International Conference on Image and Graphics},
  pages={93--102},
  year={2019},
  organization={Springer}
}
</pre>
</div>
