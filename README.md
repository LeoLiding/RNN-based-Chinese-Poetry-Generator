# RNN-based-Chinese-Poetry-Generator
基于RNN的古诗自然语言生成器
本项目是在学习深度学习的过程中，对自然语言处理感兴趣而做的古诗模型生成器；

训练集是基于全唐诗，都是繁体字，所以测试过程需要输入繁体进行测试；

训练过程的分词是基于字符进行，而不是传统意义上的词，这也是我得最大发现
因为在古体诗中往往单个字符就可以表达足够的意思，而不用词才能表达；同样高频出现的词往往也可以基于字符生成，效果比较良好；

主要适用于五言 七言以及古体诗

以下是我的部分测试结果

![fdf6b3f0e4061f63bcffd1e07497a72](https://user-images.githubusercontent.com/87323344/232471016-4571628c-452e-4f1a-bf56-4b8fcf2b276b.png)
![221da0b8dd98c5606a26e6e17b030c2](https://user-images.githubusercontent.com/87323344/232471071-47fbb5d7-a4af-49d8-8ecb-ce9a80f55104.png)
