 # A-Text_to_Image-zoo </span>
[Yutong ZHOU](https://github.com/Yutong-Zhou-cv) in [Interaction Laboratory, Ritsumeikan University.](https://github.com/Rits-Interaction-Laboratory) ლ(╹◡╹ლ) 

## <span id="head-content"> *Content* </span>
* - [x] [1. Description](#head1)

* - [x] [2. Quantitative Evaluation Metrics](#head2)
  * [Inception Score (IS)](#head-IS)
  * [Fréchet Inception Distance (FID)](#head-FID)  
  * [R-precision](#head-R)
  * [L<sub>2</sub> error](#head-L2)
  
* - [x] [3. Datasets](#head3)  
  * [Caltech-UCSD Bird (CUB)](#head-CUB)
  * [Oxford-102 Flower](#head-Flower)
  * [MS-COCO](#head-COCO)
* - [ ] [4. Paper With Code](#head4)
  * - [ ] [2020](#head-2020)
  * - [ ] [2019](#head-2019)
  * - [x] [2018](#head-2018)
  * - [x] [2017](#head-2017)
  * - [x] [2016](#head-2016)
* [*Contact Me*](#head5)

 ## <span id="head1"> *1.Description* </span>

* In the last few decades, the fields of Computer Vision (CV) and Natural Language Processing (NLP) have been made several major technological breakthroughs in deep learning research. Recently, researchers appear interested in combining semantic information and visual information in these traditionally independent fields. 
A number of studies have been conducted on the text-to-image synthesis techniques that transfer input textual description (keywords or sentences) into realistic images.

* **A-Text_to_Image-zoo**: This is a survey on Text-to-Image Generation/Synthesis. 

* Papers, codes and datasets for the text-to-image task are available here.

 ## <span id="head2"> *2.Quantitative Evaluation Metrics* </span>

* <span id="head-IS"> Inception Score (IS) </span> [[Paper](https://arxiv.org/pdf/1606.03498.pdf)] [[Python Code (Pytorch)](https://github.com/sbarratt/inception-score-pytorch)] [[Python Code (Tensorflow)](https://github.com/taki0112/GAN_Metrics-Tensorflow)]

* <span id="head-FID"> Fréchet Inception Distance (FID) </span> [[Paper](https://papers.nips.cc/paper/7240-gans-trained-by-a-two-time-scale-update-rule-converge-to-a-local-nash-equilibrium.pdf)] [[Python Code (Pytorch)](https://github.com/mseitzer/pytorch-fid)] [[Python Code (Tensorflow)](https://github.com/taki0112/GAN_Metrics-Tensorflow)]

* <span id="head-R"> R-precision </span> [[Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_AttnGAN_Fine-Grained_Text_CVPR_2018_paper.pdf)]

* <span id="head-L2"> L<sub>2</sub> error </span> [[Paper](https://papers.nips.cc/paper/7290-text-adaptive-generative-adversarial-networks-manipulating-images-with-natural-language.pdf)]

## <span id="head3"> *3.Datasets* </span>

* <span id="head-CUB"> **Caltech-UCSD Bird(CUB)** </span>

  Caltech-UCSD Birds-200-2011 (CUB-200-2011) is an extended version of the CUB-200 dataset, with roughly double the number of images per class and new part location annotations.
  * **Detailed information (Images):**  ⇒ [[Paper](http://www.vision.caltech.edu/visipedia/papers/CUB_200_2011.pdf)] [[Website](http://www.vision.caltech.edu/visipedia/CUB-200-2011.html)]
    * Number of different categories: 200 (**Training**: 150 categories. **Testing**: 50 categories.)
    * Number of bird images: 11,788
    * Annotations per image: 15 Part Locations, 312 Binary Attributes, 1 Bounding Box, Ground-truth Segmentation
  * **Detailed information (Text Descriptions):**  ⇒ [[Paper](https://openaccess.thecvf.com/content_cvpr_2016/papers/Reed_Learning_Deep_Representations_CVPR_2016_paper.pdf)] [[Website](https://drive.google.com/file/d/0B0ywwgffWnLLZW9uVHNjb2JmNlE/view)]
    * Descriptions per image: 10 Captions
* <span id="head-Flower"> **Oxford-102 Flower** </span>

  Oxford-102 Flower is a 102 category dataset, consisting of 102 flower categories. The flowers are chosen to be flower commonly occurring in the United Kingdom. The images have large scale, pose and light variations. 
  * **Detailed information (Images):**  ⇒ [[Paper](http://www.robots.ox.ac.uk/~vgg/publications/2008/Nilsback08/nilsback08.pdf)] [[Website](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html)]
    * Number of different categories: 102 (**Training**: 82 categories. **Testing**: 20 categories.)
    * Number of flower images: 8,189
  * **Detailed information (Text Descriptions):**  ⇒ [[Paper](https://openaccess.thecvf.com/content_cvpr_2016/papers/Reed_Learning_Deep_Representations_CVPR_2016_paper.pdf)] [[Website](https://drive.google.com/file/d/0B0ywwgffWnLLcms2WWJQRFNSWXM/view)]
    * Descriptions per image: 10 Captions
* <span id="head-COCO"> **MS-COCO** </span>

  COCO is a large-scale object detection, segmentation, and captioning dataset.
  * **Detailed information (Images & Text Descriptions):**  ⇒ [[Paper](https://arxiv.org/pdf/1405.0312.pdf)] [[Website](https://cocodataset.org/#overview)]
    * Number of images: 120k (**Training**: 80k. **Testing**: 40k.)
    * Descriptions per image: 5 Captions

## <span id="head4"> *4.Paper With Code* </span>

* <span id="head-2020"> **2020**  </span>
    * (WIREs Data Mining and Knowledge Discovery 2020) **A survey and taxonomy of adversarial neural networks for text-to-image synthesis**, Jorge Agnese et al. [[Paper](https://onlinelibrary.wiley.com/doi/epdf/10.1002/widm.1345)] 
    * (TPAMI 2020) **Semantic Object Accuracy for Generative Text-to-Image Synthesis**, Tobias Hinz et al. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9184960)] [[Code](https://github.com/tohinz/semantic-object-accuracy-for-generative-text-to-image-synthesis)]
    * (ACM Trans 2020) **End-to-End Text-to-Image Synthesis with Spatial Constrains**, Min Wang et al. [[Paper](https://dl.acm.org/doi/pdf/10.1145/3391709)]
    * (IEEE Access 2020) **TiVGAN: Text to Image to Video Generation With Step-by-Step Evolutionary Generator**, Doyeon Kim et al. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9171240)]
    * (CVPR 2020) **RiFeGAN: Rich Feature Generation for Text-to-Image Synthesis From Prior Knowledge**, Jun Cheng et al. [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cheng_RiFeGAN_Rich_Feature_Generation_for_Text-to-Image_Synthesis_From_Prior_Knowledge_CVPR_2020_paper.pdf)] 
    * (CVPR 2020) **ManiGAN: Text-Guided Image Manipulation**, Bowen Li et al. [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_ManiGAN_Text-Guided_Image_Manipulation_CVPR_2020_paper.pdf)] [[Code](https://github.com/mrlibw/ManiGAN)]
    * (CVPR 2020) **CookGAN: Causality based Text-to-Image Synthesis**, Bin Zhu et al. [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhu_CookGAN_Causality_Based_Text-to-Image_Synthesis_CVPR_2020_paper.pdf)]
    * (CVPR 2020 - Workshop) **SegAttnGAN: Text to Image Generation with Segmentation Attention**, Yuchuan Gou et al. [[Paper](https://arxiv.org/pdf/2005.12444.pdf)]
    * (IVPR 2020) **PerceptionGAN: Real-world Image Construction from Provided Text through Perceptual Understanding**, Kanish Garg et al. [[Paper](https://arxiv.org/pdf/2007.00977.pdf)]
    * (ACMMM 2020) **Describe What to Change: A Text-guided Unsupervised Image-to-Image Translation Approach**, Yahui Liu et al. [[Paper](https://arxiv.org/pdf/2008.04200.pdf)]
    * (arXiv preprint 2020) **TIME: Text and Image Mutual-Translation Adversarial Networks**, Bingchen Liu et al. [[Paper](https://arxiv.org/pdf/2005.13192.pdf)] 
    * (arXiv preprint 2020) **DF-GAN: Deep fusion generative adversarial networks for Text-to-Image synthesis**, Ming Tao et al. [[Paper](https://arxiv.org/pdf/2008.05865.pdf)] [[Code](https://github.com/tobran/DF-GAN)] 
    
* <span id="head-2019"> **2019**  </span>
    * (IEEE TCSVT 2019) **Bridge-GAN: Interpretable Representation Learning for Text-to-image Synthesis**, Mingkuan Yuan et al. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8902154)] [[Code](https://github.com/PKU-ICST-MIPL/Bridge-GAN_TCSVT2019)]
    * (AAAI 2019) **Perceptual Pyramid Adversarial Networks for Text-to-Image Synthesis**, Minfeng Zhu et al. [[Web](https://www.aaai.org/ojs/index.php/AAAI/article/view/4844)]
    * (AAAI 2019) **Adversarial Learning of Semantic Relevance in Text to Image Synthesis**, Miriam Cha et al. [[Web](https://www.aaai.org/ojs/index.php/AAAI/article/view/4553)]
    * (CVPR 2019) **DM-GAN: Dynamic Memory Generative Adversarial Networks for Text-to-Image Synthesis**, Minfeng Zhu et al. [[Paper](https://arxiv.org/pdf/1904.01310.pdf)] [[Code](https://github.com/MinfengZhu/DM-GAN)]
    * (CVPR 2019) **Object-driven Text-to-Image Synthesis via Adversarial Training**, Wenbo Li et al. [[Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Object-Driven_Text-To-Image_Synthesis_via_Adversarial_Training_CVPR_2019_paper.pdf)] [[Code](https://github.com/jamesli1618/Obj-GAN)]
    * (CVPR 2019) **MirrorGAN: Learning Text-to-image Generation by Redescription**, Tingting Qiao et al. [[Paper](https://arxiv.org/pdf/1903.05854.pdf)] [[Code](https://github.com/qiaott/MirrorGAN)]
    * (CVPR 2019) **Text2Scene: Generating Abstract Scenes from Textual Descriptions**, Fuwen Tan et al. [[Paper](https://arxiv.org/pdf/1809.01110.pdf)] [[Code](https://github.com/uvavision/Text2Scene)]
    * (CVPR 2019) **Semantics Disentangling for Text-to-Image Generation**, Guojun Yin et al. [[Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Yin_Semantics_Disentangling_for_Text-To-Image_Generation_CVPR_2019_paper.pdf)] [[Website](https://gjyin91.github.io/projects/sdgan.html)]
    * (ICCV 2019) **Semantics-Enhanced Adversarial Nets for Text-to-Image Synthesis**, Hongchen Tan et al. [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Tan_Semantics-Enhanced_Adversarial_Nets_for_Text-to-Image_Synthesis_ICCV_2019_paper.pdf)] 
    * (ICCV 2019) **Dual Adversarial Inference for Text-to-Image Synthesis**, Qicheng Lao et al. [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Lao_Dual_Adversarial_Inference_for_Text-to-Image_Synthesis_ICCV_2019_paper.pdf)] 
    * (ICCV 2019) **Tell, Draw, and Repeat: Generating and Modifying Images Based on Continual Linguistic Instruction**, Alaaeldin El-Nouby et al. [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/El-Nouby_Tell_Draw_and_Repeat_Generating_and_Modifying_Images_Based_on_ICCV_2019_paper.pdf)] [[Code](https://github.com/Maluuba/GeNeVA)]
    * (NIPS 2019) **Learn, Imagine and Create: Text-to-Image Generation from Prior Knowledge**, Tingting Qiao et al. [[Paper](https://papers.nips.cc/paper/8375-learn-imagine-and-create-text-to-image-generation-from-prior-knowledge.pdf)] [[Code](https://github.com/qiaott/LeicaGAN)]
    * (NIPS 2019) **Controllable Text-to-Image Generation**, Bowen Li et al. [[Paper](https://papers.nips.cc/paper/8375-learn-imagine-and-create-text-to-image-generation-from-prior-knowledge.pdf)] [[Code](https://github.com/mrlibw/ControlGAN)]
    * (arXiv preprint 2019) **GILT: Generating Images from Long Text**, Ori Bar El et al. [[Paper](https://arxiv.org/pdf/1901.02404.pdf)] [[Code](https://github.com/netanelyo/Recipe2ImageGAN)]
    * (arXiv preprint 2019) **CPGAN: Content-Parsing Generative Adversarial Networks for Text-to-Image Synthesis**, Jiadong Liang et al. [[Paper](https://arxiv.org/abs/1912.08562v2)] 
    
* <span id="head-2018"> **2018**  </span>
    * (TPAMI 2018) **StackGAN++: Realistic Image Synthesis with Stacked Generative Adversarial Networks**, Han Zhang et al. [[Paper](https://arxiv.org/pdf/1710.10916.pdf)] [[Code](https://github.com/hanzhanggit/StackGAN-v2)]
    * (BMVC 2018) **MC-GAN: Multi-conditional Generative Adversarial Network for Image Synthesis**, Hyojin Park et al. [[Paper](https://arxiv.org/pdf/1805.01123.pdf)] [[Code](https://github.com/HYOJINPARK/MC_GAN)]
    * (CVPR 2018) **AttnGAN: Fine-grained text to image generation with attentional generative adversarial networks**, Tao Xu et al. [[Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_AttnGAN_Fine-Grained_Text_CVPR_2018_paper.pdf)] [[Code](https://github.com/taoxugit/AttnGAN)]
    * (CVPR 2018) **Photographic Text-to-Image Synthesis with a Hierarchically-nested Adversarial Network**, Zizhao Zhang et al. [[Paper](https://arxiv.org/pdf/1802.09178.pdf)] [[Code](https://github.com/ypxie/HDGan)]
    * (CVPR 2018) **Inferring Semantic Layout for Hierarchical Text-to-Image Synthesis**, Seunghoon Hong et al. [[Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Hong_Inferring_Semantic_Layout_CVPR_2018_paper.pdf)] 
    * (CVPR 2018) **Image Generation from Scene Graphs**, Justin Johnson et al. [[Paper](https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0764.pdf)] [[Code](https://github.com/google/sg2im)]
    * (NIPS 2018) **Text-adaptive generative adversarial networks: Manipulating images with natural language**, Seonghyeon Nam et al. [[Paper](http://papers.nips.cc/paper/7290-text-adaptive-generative-adversarial-networks-manipulating-images-with-natural-language.pdf)] [[Code](https://github.com/woozzu/tagan)]
    * (ICLR 2018 - Workshop) **ChatPainter: Improving Text to Image Generation using Dialogue**, Shikhar Sharma et al. [[Paper](https://arxiv.org/pdf/1802.08216.pdf)] 
    * (ACMMM 2018) **Text-to-image Synthesis via Symmetrical Distillation Networks**, Mingkuan Yuan et al. [[Paper](https://dl.acm.org/doi/pdf/10.1145/3240508.3240559)]
    * (WACV 2018) **C4Synth: Cross-Caption Cycle-Consistent Text-to-Image Synthesis**, K. J. Joseph et al. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8658689)]
    * (arXiv preprint 2018) **Text to Image Synthesis Using Generative Adversarial Networks**, Cristian Bodnar. [[Paper](https://arxiv.org/pdf/1805.00676.pdf)] 
    * (arXiv preprint 2018) **Text-to-image-to-text translation using cycle consistent adversarial networks**, Satya Krishna Gorti et al. [[Paper](https://arxiv.org/pdf/1808.04538.pdf)] 
    
* <span id="head-2017"> **2017**  </span>
    * (ICCV 2017) **StackGAN: Text to photo-realistic image synthesis with stacked generative adversarial networks**, Han Zhang et al. [[Paper](https://arxiv.org/pdf/1612.03242.pdf)] [[Code](https://github.com/hanzhanggit/StackGAN)]
    * (ICIP 2017) **I2T2I: Learning Text to Image Synthesis with Textual Data Augmentation**, Hao Dong et al. [[Paper](https://arxiv.org/pdf/1703.06676.pdf)] [[Code](https://github.com/zsdonghao/im2txt2im)]
    * (MLSP 2017) **Adversarial nets with perceptual losses for text-to-image synthesis**, Miriam Cha et al. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8168140)]
   

* <span id="head-2016"> **2016**  </span>
    * (ICML 2016) **Generative Adversarial Text to Image Synthesis**, Scott Reed et al. [[Paper](http://proceedings.mlr.press/v48/reed16.pdf)] [[Code](https://github.com/reedscot/icml2016)]
    * (NIPS 2016) **Learning What and Where to Draw**, Scott Reed et al. [[Paper](https://arxiv.org/pdf/1610.02454.pdf)] [[Code](https://github.com/reedscot/nips2016)]


## <span id="head5"> *Contact Me* </span>

* If you have any question, please feel free to contact Yutong ZHOU (E-mail: <zhou@i.ci.ritsumei.ac.jp>).
