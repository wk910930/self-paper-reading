# Self Paper Reading

A curated list of deep learning resources for computer vision, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision) and [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision). Many thanks to [Jiwon Kim](https://github.com/kjw0612)' great work!

## Contributing

Please feel free to [pull requests](https://github.com/wk910930/self-paper-reading/pulls) to add papers.

## Table of Contents

- [Papers](#papers)
  - [ImageNet Classification](#imagenet-classification)
  - [Object Detection](#object-detection)
  - [Object Tracking](#object-tracking)
  - [Semantic Segmentation](#semantic-segmentation)
  - [Object Recognition](#object-recognition)
  - [Understanding CNN](#understanding-cnn)
  - [Image Generation](#image-generation)
  - [Reinforcement Learning](#reinforcement-learning)
  - [Visual Question Answering (VQA)](#visual-question-answering)
  - [Other Source](#other-source)
- [Books](#books)
- [Tutorials](#tutorials)
- [Blogs](#blogs)

## Papers

### ImageNet Classification

* Matching Networks for One Shot Learning [[Paper]](https://arxiv.org/abs/1606.04080)
  * Oriol Vinyals, Charles Blundell, Timothy Lillicrap, Koray Kavukcuoglu, Daan Wierstra
* Active Convolution: Learning the Shape of Convolution for Image Classification [[Paper]](https://arxiv.org/abs/1703.09076)
  * Yunho Jeon, Junmo Kim, *CVPR*, 2017
* Aggregated Residual Transformations for Deep Neural Networks [[Paper]](https://arxiv.org/abs/1611.05431) [[Code]](https://github.com/facebookresearch/ResNeXt)
  * [Saining Xie](http://vcl.ucsd.edu/~sxie/), [Ross Girshick](http://www.rossgirshick.info/), [Piotr Dollár](https://pdollar.github.io/index.html), Zhuowen Tu, [Kaiming He](http://kaiminghe.com/)
* Convolutional Neural Fabrics [[Paper]](https://arxiv.org/abs/1606.02492) [[Code]](https://github.com/shreyassaxena/convolutional-neural-fabrics)
  * Shreyas Saxena, Jakob Verbeek
* Locally Scale-Invariant Convolutional Neural Networks [[Paper]](https://arxiv.org/abs/1412.5104) [[Code]](https://github.com/akanazawa/si-convnet)
  * Angjoo Kanazawa, Abhishek Sharma, David Jacobs


### Object Detection

* Mask R-CNN [[Paper]](https://arxiv.org/abs/1703.06870)
  * [Kaiming He](http://kaiminghe.com/), [Georgia Gkioxari](http://people.eecs.berkeley.edu/~gkioxari/), [Piotr Dollár](https://pdollar.github.io/index.html), [Ross Girshick](http://www.rossgirshick.info/), Mask R-CNN, *CVPR*, 2017
* Deformable Convolutional Networks [[Paper]](https://arxiv.org/abs/1703.06211) [[Code]](https://github.com/msracver/Deformable-ConvNets)
  * [Jifeng Dai](http://www.jifengdai.org/), Haozhi Qi, Yuwen Xiong, Yi Li, Guodong Zhang, Han Hu, Yichen Wei, Arxiv tech report, 2017
* A-Fast-RCNN: Hard positive generation via adversary for object detection [[Paper]](http://abhinavsh.info/papers/pdfs/adversarial_object_detection.pdf) [[Code]](https://github.com/xiaolonw/adversarial-frcnn)
  * [Xiaolong Wang](http://www.cs.cmu.edu/~xiaolonw/), Abhinav Shrivastava, Abhinav Gupta, *CVPR*, 2017
* Spatial Memory for Context Reasoning in Object Detection [[Paper]](https://arxiv.org/abs/1704.04224)
  * [Xinlei Chen](https://www.cs.cmu.edu/~xinleic/index.html), [Abhinav Gupta](http://www.cs.cmu.edu/~abhinavg/)
* Learning Features by Watching Objects Move [[Paper]](https://arxiv.org/abs/1612.06370) [[Code]](https://github.com/pathak22/unsupervised-video)
  * [Deepak Pathak](https://people.eecs.berkeley.edu/~pathak/), [Ross Girshick](http://www.rossgirshick.info/), [Piotr Dollár](https://pdollar.github.io/index.html), Trevor Darrell, Bharath Hariharan
* Improving Object Detection With One Line of Code [[Paper]](https://arxiv.org/abs/1704.04503) [[Code]](https://github.com/bharatsingh430/soft-nms)
  * Navaneeth Bodla, Bharat Singh, Rama Chellappa, Larry S. Davis

### Object Tracking

* Deep Feature Flow for Video Recognition [[Paper]](https://arxiv.org/abs/1611.07715) [[Code]](https://github.com/msracver/Deep-Feature-Flow)
  * Xizhou Zhu, Yuwen Xiong, [Jifeng Dai](http://www.jifengdai.org/), Lu Yuan, Yichen Wei

### Semantic Segmentation

* Fully Convolutional Instance-aware Semantic Segmentation [[Paper]](https://arxiv.org/abs/1611.07709) [[Code]](https://github.com/daijifeng001/TA-FCN)
  * Yi Li, Haozhi Qi, [Jifeng Dai](http://www.jifengdai.org/), Xiangyang Ji, Yichen Wei, *CVPR*, 2017 (Spotlight)
* PixelNet: Representation of the pixels, by the pixels, and for the pixels [[Paper]](https://arxiv.org/abs/1702.06506) [[Code]](https://github.com/aayushbansal/PixelNet)
  * [Aayush Bansal](http://www.cs.cmu.edu/~aayushb/), [Xinlei Chen](http://www.cs.cmu.edu/~xinleic/), Bryan Russell, Abhinav Gupta, Deva Ramanan
* Semantic Image Segmentation with Task-Specific Edge Detection Using CNNs and a Discriminatively Trained Domain Transform [[Paper]](https://arxiv.org/abs/1511.03328)
  * [Liang-Chieh Chen](http://liangchiehchen.com), Jonathan T. Barron, George Papandreou, Kevin Murphy, Alan L. Yuille

### Object Recognition

* Discovering objects and their relations from entangled scene representations [[Paper]](https://arxiv.org/abs/1702.05068)
  * David Raposo, Adam Santoro, David Barrett, Razvan Pascanu, Timothy Lillicrap, Peter Battaglia, *ICLR*, 2017
* Learning Spatiotemporal Features with 3D Convolutional Networks [[Paper]](https://arxiv.org/abs/1412.0767) [[Code]](https://github.com/facebook/C3D)
  * [Du Tran](http://www.cs.dartmouth.edu/~dutran/), Lubomir Bourdev, Rob Fergus, Lorenzo Torresani, Manohar Paluri

### Understanding CNN

* Structured Receptive Fields in CNNs [[Paper]](https://arxiv.org/abs/1605.02971)
  * [Jörn-Henrik Jacobsen](https://jhjacobsen.github.io), Jan van Gemert, Zhongyu Lou, Arnold W. M. Smeulders, *CVPR*, 2016
* Understanding image representations by measuring their equivariance and equivalence [[Paper]](https://arxiv.org/abs/1411.5908)
  * [Karel Lenc](http://www.robots.ox.ac.uk/~karel/), Andrea Vedaldi, *CVPR*, 2015
* Dynamic Filter Networks [[Paper]](https://arxiv.org/abs/1605.09673)
  * Bert De Brabandere, Xu Jia, Tinne Tuytelaars, Luc Van Gool, *NIPS*, 2016
* Network Dissection: Quantifying Interpretability of Deep Visual Representations [[Paper]](https://arxiv.org/abs/1704.05796)
  * David Bau, [Bolei Zhou](http://people.csail.mit.edu/bzhou/), [Aditya Khosla](http://people.csail.mit.edu/khosla/), Aude Oliva, Antonio Torralba, *CVPR*, 2017 (Oral)
* On Large-Batch Training for Deep Learning: Generalization Gap and Sharp Minima [[Paper]](https://arxiv.org/abs/1609.04836) [[Code]](https://github.com/keskarnitish/large-batch-training)
  * [Nitish Shirish Keskar](http://users.iems.northwestern.edu/~nitish/), [Dheevatsa Mudigere](https://sites.google.com/site/dheevatsa/home), Jorge Nocedal, Mikhail Smelyanskiy, Ping Tak Peter Tang, *ICLR*, 2017
* Auto-Encoding Variational Bayes [[Paper]](https://arxiv.org/abs/1312.6114)
  * [Diederik P Kingma](http://dpkingma.com), Max Welling
* Intriguing properties of neural networks [[Paper]](https://arxiv.org/abs/1312.6199)
  * Christian Szegedy, Wojciech Zaremba, Ilya Sutskever, Joan Bruna, Dumitru Erhan, [Ian Goodfellow](http://www.iangoodfellow.com/), Rob Fergus
* Convolutional Sequence to Sequence Learning [[Paper]](https://arxiv.org/abs/1705.03122)
  * Jonas Gehring, Michael Auli, David Grangier, Denis Yarats, Yann N. Dauphin 

### Image Generation

* Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks [[Paper]](https://arxiv.org/abs/1703.10593) [[Code]](https://github.com/junyanz/CycleGAN)
  * [Jun-Yan Zhu](http://people.eecs.berkeley.edu/~junyanz/), Taesung Park, Phillip Isola, [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros/)
* Adversarial Feature Learning [[Paper]](https://arxiv.org/abs/1605.09782) [[Code]](https://github.com/jeffdonahue/bigan)
  * [Jeff Donahue](http://jeffdonahue.com), Philipp Krähenbühl, Trevor Darrell

### Reinforcement Learning

* Playing Atari with Deep Reinforcement Learning [[Paper]](https://arxiv.org/abs/1312.5602)
  * [Volodymyr Mnih](https://www.cs.toronto.edu/~vmnih/), Koray Kavukcuoglu, David Silver, Alex Graves, Ioannis Antonoglou, Daan Wierstra, Martin Riedmiller

### Visual Question Answering

* Inferring and Executing Programs for Visual Reasoning [[Paper]](https://arxiv.org/abs/1705.03633) [[Code]](https://github.com/facebookresearch/clevr-iep)
  * Justin Johnson, Bharath Hariharan, Laurens van der Maaten, Judy Hoffman, [Li Fei-Fei](http://vision.stanford.edu/feifeili/), [C. Lawrence Zitnick](http://larryzitnick.org/), [Ross Girshick](http://www.rossgirshick.info/)

### Other Source

* [Newly published papers (< 6 months) which are worth reading](https://github.com/terryum/awesome-deep-learning-papers#new-papers)
  * [terryum](https://github.com/terryum)
* [Recent Submissions: Computer Vision and Pattern Recognition](https://arxiv.org/list/cs.CV/recent)
  * [arXiv.org](https://arxiv.org/)
* [DeepMind](https://deepmind.com/research/publications/)
  * DeepMind's publications

## Books

* Free Online Books
  * [Deep Learning](http://www.deeplearningbook.org) by [Ian Goodfellow](http://www.iangoodfellow.com/), Yoshua Bengio, and Aaron Courville
  * [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/) by Michael Nielsen
  * [Deep Natural Language Processing](https://github.com/oxford-cs-deepnlp-2017/lectures) by Hilary Term 2017 at the University of Oxford

## Tutorials

* [UFDL](http://deeplearning.stanford.edu/wiki/index.php/UFLDL_Tutorial), Unsupervised Feature Learning and Deep Learning
* [Distill](http://distill.pub), a modern medium for presenting research
* [GAN](https://arxiv.org/abs/1701.00160), Generative Adversarial Networks, *NIPS* 2016 Tutorial
* [Edward](http://edwardlib.org/tutorials/), Edward provides a testbed for rapid experimentation and research with probabilistic models

## Blogs

* [Andrej Karpathy's blog](http://karpathy.github.io)
* [Colah's blog](http://colah.github.io)
* [WILDML](http://www.wildml.com)
* [Google Research Blog](https://research.googleblog.com)
