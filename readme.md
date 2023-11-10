// 用一个模型去学习颗粒的形状特征
颗粒是一堆点的集合。

generater 生成一个颗粒（点的集合）
descripter， 判别生成器生成的颗粒是不是和真实的颗粒一样


// 用一个模型去学习猫的图像，

mask = np.rand(640, 640, 3)
生成器就能够去一张猫的图片，
判别器就能去判断 这个图片是不是猫，是不是生成的猫


mask———generater———output


output———————discripter——————feature
label————————discripter——————feature

生成器