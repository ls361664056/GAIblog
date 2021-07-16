# GAIblog, update constantly :)
中文版，GAMEAI学习paper清单推荐和记录,不断更新，欢迎交流  
Some Recommanded and Marked paper for GAMEAI learning  
### mail adress：361664056@qq.com  
[1] Rasmussen, Carl Edward, and Malte Kuss. "Gaussian Processes in Reinforcement Learning." In NIPS, vol. 4, p. 1. 2003.  
  
这篇论文主要提及了**高斯过程在强化学习中的实现**，并没有涉及深度神经网络，**需要比较良好的概率论和线性代数基础**才能读懂。文中提到的**使用高斯过程去拟合状态价值函数**的方法还是很值得一看的，同时也对经典的**山路车问题**做了比较详细的描述  
This paper mainly mentions **the realization of Gaussian process in reinforcement learning**, and does not involve deep neural networks. It **requires a relatively good basis in probability theory and linear algebra** to understand it. The method of **using the Gaussian process to fit the state value function** mentioned in the article is still worth a look. At the same time, it also gives a more detailed description of the classic **mountain bike(car) problem**.  
  
[2]Goumiri, Imene R., Benjamin W. Priest, and Michael D. Schneider. "Reinforcement Learning via Gaussian Processes with Neural Network Dual Kernels." In 2020 IEEE Conference on Games (CoG), pp. 1-8. IEEE, 2020.  
这篇paper可以看成是上一篇paper的延伸版，在利用高斯过程在预采样的状态值初始化动态系统变量与价值函数时采取了更高的维度和较少的点。也对不同的核函数**CK，NTK**进行了分析，不过对核函数的应用这一块并没很看懂，第二部分的概率论也一度让我很崩溃，但是到了第三部分开始会更加流畅。最重要的思想个人感觉还是**利用高斯过程生成的状态会比0或完全随机来的更有效率**  
This paper can be regarded as an extended version of the previous paper. It takes a higher dimension and fewer points when initializing the value function and dynamics of the system with the pre-sampled state value using the Gaussian process. The paper also analyzed different kernel functions **CK and NTK**, but I didn't understand the application of kernel functions very well. The probability theory of the second part also broke me a lot, but the third part started to be smoother. The most important thought is personal feeling that the state generated by the Gaussian process will be more efficient than 0 or completely random.
