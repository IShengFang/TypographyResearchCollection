[[hackmd]](https://hackmd.io/s/B1BZCZpPX)[[github]](https://github.com/IShengFang/TypographyResearchCollection) [[github pages]](https://ishengfang.github.io/TypographyResearchCollection/)

Typography is the cross between technology and liberal arts. 
This page is a research collection that includes computer graphics, computer vision, machine learning that related to typography.

## Font Stye Transfer and Glyph Generation
### NN Approach
- **A Learned Representation for Scalable Vector Graphics**
    - [[paper]](https://arxiv.org/abs/1904.02632)
    - Raphael Gontijo Lopes, David Ha, Douglas Eck, Jonathon Shlens
    - ICCV 2019
    - ICLR workshop 2019

![](https://user-images.githubusercontent.com/544269/61917345-9c587780-af87-11e9-96a7-cf406aaa4f97.png)
    
- **DeepGlyph**
    - [[websites]](https://deepglyph.app/)
    
<iframe width="560" height="315" src="https://www.youtube.com/embed/T70k-0qgccs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    
- **Separating Style and Content for Generalized Style Transfer**
    - [[paper]](http://openaccess.thecvf.com/content_cvpr_2018/html/Zhang_Separating_Style_and_CVPR_2018_paper.html)[[code]](https://github.com/zhyxun/Separating-Style-and-Content-for-Generalized-Style-Transfer)
    - Yexun Zhang, Ya Zhang, Wenbin Cai
    - CVPR 2018

**Networks**
![](https://raw.githubusercontent.com/zhyxun/Separating-Style-and-Content-for-Generalized-Style-Transfer/master/images/network.png)

**results**
![](https://raw.githubusercontent.com/zhyxun/Separating-Style-and-Content-for-Generalized-Style-Transfer/master/images/area2.png)
![](https://raw.githubusercontent.com/zhyxun/Separating-Style-and-Content-for-Generalized-Style-Transfer/master/images/area4.png)

    
- **Deep Learning for Classical Japanese Literature**
    - [[paper]](https://arxiv.org/abs/1812.01718)[[GitHub]](https://github.com/rois-codh/kmnist)
    - Tarin Clanuwat, Mikel Bober-Irizar, Asanobu Kitamoto, Alex Lamb, Kazuaki Yamamoto, David Ha
    - NeurIPS 2018
    - Kuzushiji-MNIST,Kuzushiji-49 and Kuzushiji-Kanji

**Kuzushiji-MNIST**
![](https://raw.githubusercontent.com/rois-codh/kmnist/master/images/kmnist_examples.png)
**Kuzushiji-Kanji**
![](https://raw.githubusercontent.com/rois-codh/kmnist/master/images/kkanji_examples.png)

- **Multi-Content GAN for Few-Shot Font Style Transfer**
    - [[code]](https://github.com/azadis/MC-GAN)[[paper]](https://arxiv.org/abs/1712.00516)[[blog]](https://bair.berkeley.edu/blog/2018/03/13/mcgan/)
    - Azadi, Samaneh, Matthew Fisher, Vladimir Kim, Zhaowen Wang, Eli Shechtman, and Trevor Darrell.
    - CVPR2018

![](https://bair.berkeley.edu/static/blog/mcgan/given-new-titles.jpg)
![](https://bair.berkeley.edu/static/blog/mcgan/ft51_1_fake_B.gif)

- **zi2zi: Master Chinese Calligraphy with Conditional Adversarial Networks**
    - [[blog]](https://kaonashi-tyc.github.io/2017/04/06/zi2zi.html) [[code]](https://github.com/kaonashi-tyc/zi2zi)
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

![](https://ai2-s2-public.s3.amazonaws.com/figures/2017-08-08/f4de25085605e82bd635666cd5676a7075e77520/2-Figure2-1.png)

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
- **Chinese Handwriting Recognition Competition 2013**https://raw.githubusercontent.com/kaonashi-tyc/Rewrite/master/images/single_font_progress.gif
    - [[paper]](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&ved=2ahUKEwipwtmZ3NXdAhUJyrwKHYBuAp4QFjACegQIAxAC&url=http%3A%2F%2Fblog.sciencenet.cn%2Fhome.php%3Fmod%3Dattachment%26id%3D48833&usg=AOvVaw3z6eOWVROK6CCdPly6Te5n)
    - http://www.nlpr.ia.ac.cn/databases/handwriting/Download.html

![](https://i.imgur.com/jZcj4oo.png)

- **Deep Learning for Classical Japanese Literature**
    - [[paper]](https://arxiv.org/abs/1812.01718)[[GitHub]](https://github.com/rois-codh/kmnist)
    - Tarin Clanuwat, Mikel Bober-Irizar, Asanobu Kitamoto, Alex Lamb, Kazuaki Yamamoto, David Ha
    - NeurIPS 2018
    - Kuzushiji-MNIST,Kuzushiji-49 and Kuzushiji-Kanji

**Kuzushiji-MNIST**
![](https://raw.githubusercontent.com/rois-codh/kmnist/master/images/kmnist_examples.png)
**Kuzushiji-Kanji**
![](https://raw.githubusercontent.com/rois-codh/kmnist/master/images/kkanji_examples.png)


## Other Application
- **FontCode: Embedding Information in Text Documents Using Glyph Perturbation**
    - [[paper]](http://www.cs.columbia.edu/cg/fontcode/fontcode.pdf)[[project page]](http://www.cs.columbia.edu/cg/fontcode/)
    - Chang Xiao, Cheng Zhang, Changxi Zheng 
    - SIGGRAPH 2018

<iframe width="560" height="315" src="https://www.youtube.com/embed/dejrBf9jW24" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
