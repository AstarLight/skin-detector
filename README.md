# skin-detector
用opencv写的一个皮肤检测器，里面封装了以下6种主流的皮肤检测算法：

1. RGB color space
2. Ycrcb之cr分量+otsu阈值化
3. YCrCb中133<=Cr<=173 77<=Cb<=127
4. HSV中 7<H<20，s>48,v>50
5. 基于椭圆皮肤模型的皮肤检测
6. opencv自带肤色检测类AdaptiveSkinDetector

想知道效果好不好，那赶紧自己跑一下看看效果吧！



具体说明可以参考我的博客：http://www.cnblogs.com/skyfsm/p/7868877.html
