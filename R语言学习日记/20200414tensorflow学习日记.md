# 20200414学习日记

##### 1.听老师画大饼（8点到9点）

统计的前途是光明的，我们的前途是光明的，万物核心统计学？我不会随便让学生做工作的？

稀疏主成分，LSTM可以理解成一个分段函数？这都是啥啊？我得回去看一下LSTM模型，这能理解成分段函数？

##### 2.tensorflow与pytorch

昨晚弄明白了**神经网络（NN）**和**深度学习（DL）**的关系，是深度学习可以看成复杂多层的神经网络

而深度学习里，又有**卷积神经网络（CNN）**和**循环神经网络（RNN）**等划分，其中我之前接触的LSTM又是一种特殊的循环神经网络

而tensorflow和pytorch又是两个分庭抗礼的，被发明出来解决机器学习问题的工具，都是python里的库，下午一直在装tensorflow

先是3.8的python太高了不行，好，那我转anaconda，用3.7的python

然后又是tensorflow2.1版本的太高了，好像是电脑旧了又不行，好，那我卸了装1.15版

然后又是tensorflow又有cpu版和gpu版，显卡的计算能力3.5以上才可以用gpu版，又去查我的显卡型号和计算能力，只有2.1，用cpu版的tensorflow

终于在python里可以使用tensorflow了，可是一把这个tensorflow加载到R里，又是漫天飘红的报错，心好累，说tensorflow not found，你是瞎了吗？我那么大一个tensorflow在这个pip list里写着，连版本都记的一清二楚，你说not found？

##### 3.R里的tensorflow

先对package进行一些操作，tensorflow总是报错，我实在是想不到解决办法，我重新装一下试试

```R
help(函数名)    #查看某个函数属于哪个package
remove.packages("mgcv")  #卸载package
library()     #查看共安装了哪些package
```

重装无效，cnm了

我做到了！我做到了！我，做到了！

cnmd傻逼tensorflow终于可以在R里运行了

可是为什么呢？我以前明明不用library(tensorflow)以及install_tensorflow()就可以啊？

就一个library(keras)就行了的啊，我以前做中远数据分析的时候一模一样的代码都可以的欸

不管了，能用就行

舒服了，优秀如我，恐怖如斯恐怖如斯，毕业在望成名在即

![](F:\github-md\R语言学习日记\lstm_test.png)

