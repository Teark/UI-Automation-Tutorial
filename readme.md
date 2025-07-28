![未标题-1](docs/assets/未标题-1.jpg)



&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;[1.环境准备](docs/1.环境准备.md)	&emsp;&emsp;&emsp;[2.编写高稳定性的xpath](docs/2.如何写出高稳定性的xpath？.md )&emsp;	&emsp;&emsp;[3.pytest要会这几个](docs/3.pytest会这几个足够了.md )

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;[4.四层结构思想](docs/4.ui自动化四层结构思想.md )	&emsp;&emsp;&emsp;[5.三个demo](docs/5.逐渐深入的3个demo.md)	&emsp;&emsp;&emsp;[6.效果展示](docs/6.效果展示.md)	&emsp;&emsp;&emsp;[7.平台化方案](docs/7.平台化方案.md)

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;[8.关于我们](docs/about.md)









### 🧭 欢迎

来到UI-Automation-Tutorial ！

我们希望 UI-Automation-Tutorial 能够帮助你更好、更方便地做ui自动化测试。UI-Automation-Tutorial 提供一整套方案来做ui自动化，在便捷性、标准化、平台化方面做到史无前例的统一，期待它能帮助个人或公司更便捷的做ui自动化项目。

### 🚀 最新进展 

- [2025.6.13] UI-Automation-Tutorial 合集发布🔥
- [2024.12] 基于seliky的平台化方案落地🔥
- [2024.6] 商业化-seliky支撑着KM的UI自动化业务🔥🔥🔥
- [2023.9] seliky支持了grid分布式🔥🔥
- [2022.5] 商业化-seliky支撑着VCG的自动化、爬虫等业务🔥🔥🔥
- [2021.8] 作者自研了超好用的上传器-upload，可以在seliky中直接与页面交互🔥🔥🔥
- [2021.6] 作者自研了超好看的测试报告-pytest-html5，可以在seliky中无感使用🔥🔥🔥
- [2020.3] seliky借鉴华为aw思路，统一了一系列规范，优化了高亮、稳定、统一xpath、支持robotframework等。🔥🔥
- [2018] seliky雏形诞生，集百家之所长🔥

### 🎈关于Seliky

​	我们踩过了无数的坑，我们不希望后来者继续踩坑，或许我们的选型在 AI 快速发展的当下不是最新的，但一定是最稳的，最适合企业采用的。

时至今日，Selenium依旧是UI自动化领域下载量最多的工具库。尽管后来有很多优秀的ui自动化库，但要在便捷性、兼容性、稳定性、生态方面做到媲美Selenium的几乎没有，尤其是UI自动化很依赖稳定性，选择一个稳定的库尤为重要。

​	seliky是selenium的第三方封装库，通过 pip install seliky 即可安装。

​	seliky早在18年初就走的selenium路线，在二次封装方面集百家之所长于一身，在VCG-视觉时刻项目、开目-ecol等项目中又进一步进行了小完善，目前已经相当稳定。作为ui自动化项目的内核，它发挥的作用不言而喻。

​	除了稳定性外，seliky的精简、优雅与易用程度堪称一绝，你几乎不需要代码基础，就是各种调用，如：点击、输入、上传、拖拽，简直是言出法随，说的官方一点，非常pythonic。

​	还有集成了优美的测试报告。原生的报告过于丑陋，大家熟知的Allure报告过于臃肿以至于还依赖着java环境。作者自研的pytest-html5带来优美又详细测试报告。

​	更不用说它还支持grid这种其它第三方库很少涉足的深度，还有远非其它库能比的真实交互的上传功能，更多精彩，请见seliky。

### 🚩方案

​	目前最佳的ui自动化方案，简而言之为：seliky + pytest，语言用的python。其它插件有pytest-html5以及pytest家族的插件。

### 😣不用担心

​	读者看到这里，可能会有一种 “哪有时间，太难了”  的感觉，但其实不必担心，不是真的要你掌握python，学习成本没有想象中那么大，正如本篇标题所言-“ui自动化2天速通”，只要读者切身实践，3~4天完全能够掌握。

​	假设读者代码基础薄弱，亦或不懂代码不懂自动化，理论情况下只需4天便能掌握该自动化方案。花费时间参考如下（事实上有的测试员一天不到就能熟练上手）：

- 耗时1天：看完并看懂文档 “如何写出高稳定性的xpath？”，能写出高质量xpath即可。

- 耗时1天：看懂并实操文档 “pytest会这几个足够了”，能写出pytest测试代码即可。

- 耗时1天：看完并看懂文档 “ui自动化核心四层结构”，能理解数据流向即可。

- 耗时1天：看完并实操文档 “从头到尾写一遍3个demo”，能运行demo即可。

  

​	在结尾作者附带了平台化方案，根据生涯中的大量调研与实际经验，至少80%的公司是没有自动化岗位的，在有自动化的公司里，又至少有80%的公司是没有做平台化的。事实上，平台化对于自动化项目而言并非必须的，作者依旧给出了2个相当有竞争力的平台化方案。

​	其中方案1 “平台化方案-自研” 适合有自动化氛围的公司，该方案需要公司层面提供前后端开发人力给予支持，或者一个成熟的测试开发工程师单独来搞定；方案2 “平台化方案-集成开源平台” 是可以做到将seliky集成到metersphere（以下简称ms）里面的，可惜的是ms里的ui自动化是收费且很难用的，作者也很希望ms官方能直接采用seliky来替换掉ms里的ui库底层，虽然我们可以对ms做二次开发来支持seliky，但若ms官方能直接改了那才是从根本解决问题。

### 番外📣

- seliky地址：https://github.com/Teark/seliky
- pytest-html5地址：https://github.com/Teark/pytest-html5

这两个项目都是作者的心血制作（均采用pip安装哦），seliky是本篇教程的基石，pytest-html5是作者自研的精美测试报告。它们+pytest组合在一起，才是ui自动化该有的样子嘛~