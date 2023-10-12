# Typography Research Collection
[[hackmd]](https://hackmd.io/s/B1BZCZpPX)[[github]](https://github.com/IShengFang/TypographyResearchCollection) [[github pages]](https://ishengfang.github.io/TypographyResearchCollection/)

Typography is the cross between technology and liberal arts. 
This page is a research collection that includes computer graphics, computer vision, machine learning that related to typography.

## Font Stye Transfer and Glyph Generation
### NN Approach

- **DS-Fusion: Artistic Typography via Discriminated and Stylized Diffusion**
    - Maham Tanveer, Yizhi Wang, Ali Mahdavi-Amiri, Hao Zhang
    - ICCV2023
    - [[project page]](https://ds-fusion.github.io/)[[paper]](https://arxiv.org/abs/2303.09604)[[code]](https://github.com/tmaham/DS-Fusion) [[demo]](https://huggingface.co/spaces/tmaham/DS-Fusion-Express)

![](https://ds-fusion.github.io/static/images/ds-fusion.png)

- **Word-As-Image for Semantic Typography**
    - Shir Iluz*, Yael Vinker*, Amir Hertz, Daniel Berio, Daniel Cohen-Or, Ariel Shamir
        - *Denotes equal contribution
    - SIGGRAPH 2023 - Honorable Mention Award
    - [[project page]](https://wordasimage.github.io/Word-As-Image-Page/)[[paper]](https://arxiv.org/abs/2303.01818)[[code]](https://github.com/WordAsImage/Word-As-Image)[[demo]](https://huggingface.co/spaces/SemanticTypography/Word-As-Image)

![](https://github.com/Shiriluz/Word-As-Image/raw/main/images/teaser.png)

- **DeepVecFont-v2: Exploiting Transformers to Synthesize Vector Fonts with Higher Quality**
    - Yuqing Wang, Yizhi Wang, Longhui Yu, Yuesheng Zhu, Zhouhui Lian
    -  CVPR 2023
    -  [[paper(CVPR)]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_DeepVecFont-v2_Exploiting_Transformers_To_Synthesize_Vector_Fonts_With_Higher_Quality_CVPR_2023_paper.pdf)[[code]](https://arxiv.org/abs/2303.14585) 
    
![](https://github.com/yizhiwang96/deepvecfont-v2/raw/main/statics/chinese_font_demo_syn_1.gif)

- **DeepVecFont: Synthesizing High-quality Vector Fonts via Dual-modality Learning**
    - Yizhi Wang, Zhouhui Lian
    - SIGGRAPH Asia 2021
    - [[project page]](https://yizhiwang96.github.io/deepvecfont_homepage/)[[code]](https://github.com/yizhiwang96/deepvecfont)[[paper]](https://arxiv.org/abs/2110.06688)

![](https://yizhiwang96.github.io/deepvecfont_homepage/imgs/teaser.svg)

- **StrokeStyles: Stroke-based Segmentation and Stylization of Fonts**
    - Daniel Berio, Frederic Fol Leymarie, Paul Asente, Jose Echevarria
    - ACM Transactions on GraphicsVolume 41Issue 3Article No.: 28pp 1–21
    - [[paper]](https://dl.acm.org/doi/10.1145/3505246)



- **DG-Font: Deformable Generative Networks for Unsupervised Font Generation**
    - Yangchen Xie, Xinyuan Chen, Li Sun, Yue Lu
    - [[paper(CVPR)]](https://openaccess.thecvf.com/content/CVPR2021/html/Xie_DG-Font_Deformable_Generative_Networks_for_Unsupervised_Font_Generation_CVPR_2021_paper.html)[[paper(arxiv)]](https://arxiv.org/abs/2104.03064)[[code]](https://github.com/ecnuycxie/DG-Font)
    - CVPR2021

![](https://i.imgur.com/QLnHf6k.png)

- **Multiple Heads are Better than One:Few-shot Font Generation with Multiple Localized Experts**
    - Song Park, Sanghyuk Chun, Junbum Cha, Bado Lee, Hyunjung Shim
    - [[paper]](https://arxiv.org/abs/2104.00887)[[code]](https://github.com/clovaai/mxfont)
    - ICCV 2021

![](https://i.imgur.com/Pd1y67r.png)

- **Font Style that Fits an Image -- Font Generation Based on Image Context**
    - [[paper]](https://arxiv.org/abs/2105.08879)[[code]](https://github.com/Taylister/FontFits)
    - Taiga Miyazono, Brian Kenji Iwana, Daichi Haraguchi, and Seiichi Uchida
    - arxiv 2021

![](https://raw.githubusercontent.com/Taylister/FontFits/main/smaple/generated_example.png)

- **Few-shot Font Generation with Localized Style Representations and Factorization**
    - Song Park*, Sanghyuk Chun*, Junbum Cha, Bado Lee, Hyunjung Shim1
        - *: equal contribution
    - [[project page]](https://cvml.yonsei.ac.kr/projects/few-shot-font-generation) [[paper]](https://arxiv.org/abs/2009.11042)[[code]](https://github.com/clovaai/lffont)
    - AAAI 2021

![](https://i.imgur.com/ZMjQCap.png)
![](https://i.imgur.com/lkEBLBG.png)



- **Handwritten Chinese Font Generation with Collaborative Stroke Refinement**
    - [[paper]](https://arxiv.org/abs/1904.13268)[[WACV2021]](https://openaccess.thecvf.com/content/WACV2021/html/Wen_Handwritten_Chinese_Font_Generation_With_Collaborative_Stroke_Refinement_WACV_2021_paper.html)[[code(dead)]](https://github.com/s024/fontml-research)
    - Chuan Wen, Jie Chang, Ya Zhang, Siheng Chen, Yanfeng Wang, Mei Han, Qi Tian
    - WACV 2021

![](https://i.imgur.com/7sDYLGj.png)
![](https://i.imgur.com/93RSv38.png)


- **RD-GAN: Few/Zero-Shot Chinese Character Style Transfer via Radical Decomposition and Rendering**
    - Yaoxiong Huang, Mengchao He, Lianwen Jin, Yongpan Wang
    - [[paper(ECVA)]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/4880_ECCV_2020_paper.php)
    - ECCV 2020

![](https://i.imgur.com/536F0HD.png)

- **Few-shot Compositional Font Generation with Dual Memory**
    - Junbum Cha, Sanghyuk Chun, Gayoung Lee, Bado Lee, Seonghyeon Kim, Hwalsuk Lee.
    - [[paper]](https://arxiv.org/abs/2005.10510) [[code]](https://github.com/clovaai/dmfont)
    - ECCV 2020 
![](https://raw.githubusercontent.com/clovaai/dmfont/master/assets/teaser.jpg)


![](https://i.imgur.com/JKD8brf.png)
![](https://i.imgur.com/1cD2G3p.png)

- **CalliGAN: Style and Structure-aware Chinese Calligraphy Character Generator**
    - [[paper]](https://arxiv.org/abs/2005.12500)[[code]](https://github.com/JeanWU/CalliGAN)
    - Shan-Jean Wu, Chih-Yuan Yang and Jane Yung-jen Hsu
    - AI for Content Creation Workshop CVPR 2020.

![](https://i.imgur.com/itv9IMn.png)


- **A Learned Representation for Scalable Vector Graphics**
    - [[paper]](https://arxiv.org/abs/1904.02632)
    - Raphael Gontijo Lopes, David Ha, Douglas Eck, Jonathon Shlens
    - ICCV 2019
    - ICLR workshop 2019
    
![](https://user-images.githubusercontent.com/544269/61917345-9c587780-af87-11e9-96a7-cf406aaa4f97.png)
    
- **Large-scale Tag-based Font Retrieval with Generative Feature Learning**
    - [[paper]](https://arxiv.org/abs/1909.02072)[[page]](https://www.cs.rochester.edu/u/tchen45/font/font.html)
    - Tianlang Chen, Zhaowen Wang, Ning Xu, Hailin Jin, Jiebo Luo
    - ICCV 2019

- **DynTypo: Example-based Dynamic Text Effects Transfer**
    - [[paper]](http://www.icst.pku.edu.cn/zlian/docs/2019-04/20190418093151169110.pdf)
    - Yifang Men, Zhouhui Lian, Yingmin Tang, Jianguo Xiao
    - CVPR 2019
    - <iframe width="560" height="315" src="https://www.youtube.com/embed/FkFQ6bV1s-o" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    
    
- **Typography with Decor: Intelligent Text Style Transfer**
    - Wenjing Wang, Jiaying Liu, Shuai Yang, and Zongming Guo
    - CVPR2019
    - [[project page]](https://daooshee.github.io/Typography2019/) [[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Typography_With_Decor_Intelligent_Text_Style_Transfer_CVPR_2019_paper.pdf) [[code]](https://github.com/daooshee/Typography-with-Decor)
 
    ![](https://hackmd.io/_uploads/rkvrLQrWa.png)

- **DeepGlyph**
    - [[websites]](https://deepglyph.app/)
    - <iframe width="560" height="315" src="https://www.youtube.com/embed/T70k-0qgccs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- **Coconditional Autoencoding Adversarial Networks for Chinese Font Feature Learning**
    - [[paper]](https://arxiv.org/abs/1812.04451)
    - arxiv 2018
    - Zhizhan Zheng, Feiyun Zhang

- **TET-GAN: Text Effects Transfer via Stylization and Destylization**
    - [[paper]](https://www.aaai.org/ojs/index.php/AAAI/article/view/3919)
    - Shuai Yang, Jiaying Liu, Wenjing Wang, Zongming Guo
    - AAAI2019

![](https://i.imgur.com/k31pWcZ.png)

- **SCFont: Structure-Guided Chinese Font Generation via Deep Stacked Networks** 
    - [[paper]](https://aaai.org/ojs/index.php/AAAI/article/view/4294)
    - Yue Jiang, Zhouhui Lian*, Yingmin Tang, Jianguo Xiao
    - AAAI 2019

![](https://i.imgur.com/NzY6mF3.png)

- **Separating Style and Content for Generalized Style Transfer**
    - [[paper]](http://openaccess.thecvf.com/content_cvpr_2018/html/Zhang_Separating_Style_and_CVPR_2018_paper.html)[[code]](https://github.com/zhyxun/Separating-Style-and-Content-for-Generalized-Style-Transfer)
    - Yexun Zhang, Ya Zhang, Wenbin Cai
    - CVPR 2018
    - Networks
    ![](https://raw.githubusercontent.com/zhyxun/Separating-Style-and-Content-for-Generalized-Style-Transfer/master/images/network.png)
    - results
    ![](https://raw.githubusercontent.com/zhyxun/Separating-Style-and-Content-for-Generalized-Style-Transfer/master/images/area2.png)
    ![](https://raw.githubusercontent.com/zhyxun/Separating-Style-and-Content-for-Generalized-Style-Transfer/master/images/area4.png)

    
- **Deep Learning for Classical Japanese Literature**
    - [[paper]](https://arxiv.org/abs/1812.01718)[[GitHub]](https://github.com/rois-codh/kmnist)
    - Tarin Clanuwat, Mikel Bober-Irizar, Asanobu Kitamoto, Alex Lamb, Kazuaki Yamamoto, David Ha
    - NeurIPS 2018
    - Kuzushiji-MNIST,Kuzushiji-49 and Kuzushiji-Kanji
    - Kuzushiji-MNIST
    ![](https://raw.githubusercontent.com/rois-codh/kmnist/master/images/kmnist_examples.png)
    - Kuzushiji-Kanji
    ![](https://raw.githubusercontent.com/rois-codh/kmnist/master/images/kkanji_examples.png)

- **Multi-Content GAN for Few-Shot Font Style Transfer**
    - [[code]](https://github.com/azadis/MC-GAN)[[paper]](https://arxiv.org/abs/1712.00516)[[blog]](https://bair.berkeley.edu/blog/2018/03/13/mcgan/)
    - Azadi, Samaneh, Matthew Fisher, Vladimir Kim, Zhaowen Wang, Eli Shechtman, and Trevor Darrell.
    - CVPR2018
    ![](https://bair.berkeley.edu/static/blog/mcgan/given-new-titles.jpg)
    ![](https://bair.berkeley.edu/static/blog/mcgan/ft51_1_fake_B.gif)

- **Learning to Write Stylized Chinese Characters by Reading a Handful of Examples**
    - [[paper]](https://www.ijcai.org/proceedings/2018/0128.pdf)
    - Danyang Sun∗, Tongzheng Ren∗, Chongxuan Li, Hang Su†, Jun Zhu†
    - IJCAI 2018
    - SA-VAE

![](https://i.imgur.com/9i5bFS0.png)


- **DCFont: An End-To-End Deep Chinese Font Generation System**
    - [[paper]](http://www.icst.pku.edu.cn/zlian/docs/20181024110234919639.pdf)
    - Juncheng Liu, Zhouhui Lian, Jianguo Xiao
    - SIGGRAPH Asia 2017
    
![](https://i.imgur.com/rQYFZRU.png)


- **zi2zi: Master Chinese Calligraphy with Conditional Adversarial Networks**
    - [[blog]](https://kaonashi-tyc.github.io/2017/04/06/zi2zi.html) [[code(TensorFlow)]](https://github.com/kaonashi-tyc/zi2zi) [[code(pytorch)(xuan-li)]](https://github.com/xuan-li/zi2zi-pytorch) [[code(pytorch)( EuphoriaYan)]](https://github.com/EuphoriaYan/zi2zi-pytorch)
    - Yuchen Tian
    - 2017
    
    ![](https://kaonashi-tyc.github.io/assets/intro.gif)

- **Rewrite: Neural Style Transfer For Chinese Fonts**
    - [[code]](https://github.com/kaonashi-tyc/Rewrite)
    - Yuchen Tian
    - 2016
    
    ![](https://raw.githubusercontent.com/kaonashi-tyc/Rewrite/master/images/single_font_progress.gif)

- **Automatic generation of large-scale handwriting fonts via style learning**
    - [[paper]](https://dl.acm.org/citation.cfm?id=3005371)
    - Zhouhui Lian, Bo Zhao, and Jianguo Xiao
    - SIGGRAPH ASIA 2016

![](https://ai2-s2-public.s3.amazonaws.com/figures/2017-08-08/a9c74b454bfaedceb0c06a3d82f133e4c9c0257e/3-Figure4-1.png)

- **A Book from the Sky 天书: Exploring the Latent Space of Chinese Handwriting**
    - [[blog]](http://genekogan.com/works/a-book-from-the-sky/)
    - [Gene Kogan](http://genekogan.com/)

![](http://genekogan.com/images/a-book-from-the-sky/banner.png)

- **Letter Spirit: An Emergent Model of the Perception and Creation of Alphabetic Style**
    - [[paper]](https://pdfs.semanticscholar.org/e03a/21a4dfaa34b3d43ab967a01d7d9f6f7adccf.pdf)
    - Douglas Hofstadter, Gary McGraw
    - 1993

### Other Approach
- **Automatic Generation of Typographic Font from a Small Font Subset**
    - [[paper]](https://arxiv.org/abs/1701.05703)
    - Tomo Miyazaki, Tatsunori Tsuchiya, Yoshihiro Sugaya, Shinichiro Omachi, Masakazu Iwamura, Seiichi Uchida, Koichi Kise
    - 2017
    
    ![](https://pbs.twimg.com/media/C22YtOvWEAA8XsT.jpg)

- **FlexyFont: Learning Transferring Rules for Flexible Typeface Synthesis**
    - [[paper]](https://doi.org/10.1111/cgf.12763)
    - H. Q. Phan, H. Fu, and A. B. Chan
    - 2015 Computer Graphics Forum
    
    ![](https://ai2-s2-public.s3.amazonaws.com/figures/2017-08-08/616f7c6bf71946430db5561cfa4045a022f29f7f/4-Figure4-1.png)

- **Awesome Typography: Statistics-Based Text Effects Transfer**
    - [[paper]](https://arxiv.org/pdf/1611.09026.pdf)[[code]](https://github.com/williamyang1991/Text-Effects-Transfer)
    - Shuai Yang, Jiaying Liu, Zhouhui Lian and Zongming Guo
    - CVPR 2017
    
    ![](https://pbs.twimg.com/media/CydToymWgAAbddo.jpg)

- **Easy generation of personal Chinese handwritten fonts**
    - [[paper]](https://ieeexplore.ieee.org/document/6011892/)
    - Baoyao Zhou, Weihong Wang, and Zhanghui Chen
    - 2011 ICME(IEEE International Conference on Multimedia and Expo)
    
    ![](https://ai2-s2-public.s3.amazonaws.com/figures/2017-08-08/4760fce6c4ce72b17abe9595f1e635b6ecef70fc/3-Figure2-1.png)

- **Automatic shape morphing for Chinese characters**
    - [[paper]](https://dl.acm.org/citation.cfm?id=2407748)
    - Zhouhui Lian, and Zhouhui Lian
    - SIGGRAPH Asia 2012 
    - ![](https://ai2-s2-public.s3.amazonaws.com/figures/2017-08-08/f4de25085605e82bd635666cd5676a7075e77520/2-Figure2-1.png)

## Struture Learning
- **Analyzing 50k fonts using deep neural networks**
    - [[blog]](https://erikbern.com/2016/01/21/analyzing-50k-fonts-using-deep-neural-networks.html)
    - [Erik Bernhardsson](https://erikbern.com/about.html)
    - 2016
    
    ![](https://erikbern.com/assets/animated_font.gif)

- **Learning a Manifold of Fonts**
    - [[paper]](http://vecg.cs.ucl.ac.uk/Projects/projects_fonts/papers/siggraph14_learning_fonts.pdf)[[project(demo)]](http://vecg.cs.ucl.ac.uk/Projects/projects_fonts/projects_fonts.html)
    - Neill D.F. Campbell, and Jan Kautz
    - SIGGRAPH 2014
    
    ![](http://vecg.cs.ucl.ac.uk/Projects/projects_fonts/images/projects/font_hamburgefon_large.png)


## DataSet
- **Chinese Handwriting Recognition Competition 2013**
    - [[paper]](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&ved=2ahUKEwipwtmZ3NXdAhUJyrwKHYBuAp4QFjACegQIAxAC&url=http%3A%2F%2Fblog.sciencenet.cn%2Fhome.php%3Fmod%3Dattachment%26id%3D48833&usg=AOvVaw3z6eOWVROK6CCdPly6Te5n)[[download]](http://www.nlpr.ia.ac.cn/databases/handwriting/Download.html)

![](https://i.imgur.com/jZcj4oo.png)

- **Deep Learning for Classical Japanese Literature**
    - [[paper]](https://arxiv.org/abs/1812.01718)[[GitHub]](https://github.com/rois-codh/kmnist)
    - Tarin Clanuwat, Mikel Bober-Irizar, Asanobu Kitamoto, Alex Lamb, Kazuaki Yamamoto, David Ha
    - NeurIPS 2018
    - Kuzushiji-MNIST,Kuzushiji-49 and Kuzushiji-Kanji
    - Kuzushiji-MNIST
    ![](https://raw.githubusercontent.com/rois-codh/kmnist/master/images/kmnist_examples.png)
    - Kuzushiji-Kanji
    ![](https://raw.githubusercontent.com/rois-codh/kmnist/master/images/kkanji_examples.png)


## Other Application
- **FontCode: Embedding Information in Text Documents Using Glyph Perturbation**
    - [[paper]](http://www.cs.columbia.edu/cg/fontcode/fontcode.pdf)[[project page]](http://www.cs.columbia.edu/cg/fontcode/)
    - Chang Xiao, Cheng Zhang, Changxi Zheng 
    - SIGGRAPH 2018
    - <iframe width="560" height="315" src="https://www.youtube.com/embed/dejrBf9jW24" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
