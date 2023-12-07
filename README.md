# GoogLeNet
my implementation of GoogLeNet (also from the d2l)
# GoogLeNet
也是一个经典网络，但是设计的很奇怪，参数很多都是trial and error得到的  
按着d2l的代码实现了一遍，在fashionMNIST上面训练效果还是可以，比我之前的VGG-16效果要好一点
# 基本构造
主要是使用**Inception块**作为基本的构造单元，但是不同的inception块的参数也是不一样的
![inception-full](https://github.com/blameitonme1/GoogLeNet/assets/113235913/53e68366-75f2-4067-a222-a6e615f9c112)
