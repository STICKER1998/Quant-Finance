<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>


AB Test
================================
1. AB Test的定义
AB测试是为WEB或者APP界面或流程制作两个或者多个版本，。。。
2.AB Test的优势
AB Test 全量怎么和实验效果不一致？
## 2.AB Test的本质
AB测试的作用：为了检验新功能的效果；
我们假设新功能是无害的，设计AB实验来检验真正的效果；
AB测试的本质：假设检验；


### 1.背景
某电商公司非常注重自己的落地页设计，希望能够改进设计来提高转化率。往年公司的全年转化率在13%左右，现在希望能够使用新页面来提高转换率，希望能够达到15%的转换率。

### 2.A/B测试基本流程
了解了基本的背景之后，就可以进入AB测试。



#### 确定实验目标及衡量指标
在本案例中实验目标是通过AB测试确定新落地页是否可以提升2%的转化率。衡量指标为页面转化率。
#### 设计实验方案
实验变量，实验时间，实验样本量，划分实验组和对照组。
#### 执行实验并收集数据
#### 数据分析和结果评估


### 3.设计A/B test实验
> [!NOTE]
> **AB Test 基本步骤**
> - 提出假设
> - 确定实验分组
> - 计算实验样本量及试验周期
> - 上线AB测试并收集数据
> - 数据分析及假设检验
> - 得出结论及建议

#### 3.1 提出假设
单位检验 or 双尾检验

本案例原则上应该要选择右侧单尾检验，但是我们并不能确定新页面的性能一定比当前页面更好，所以选择双尾检验。

- 如果备择假设H1是$$\neq$$，则是双尾检验；
- 如果备择假设H1是$\ge$，则是双尾检验；
- 如果备择假设H1是$\neq$，则是双尾检验；