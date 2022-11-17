# Why FT is used
In order to know why we have to use some transform, we have to know a basic idea about ***orthogonal basis*** （正交基in Chinese）. 

It means: x·x = 0; y·y = 0; x·y = 1

For example, in Cartesian coordinate system, (0,1) and (1,0) can be regarded as a pair of ***orthogonal basis***. 

**In Fourier Transform, cos  $\omega$ and sin  $\omega$ is used.**

## Fourier Series and FT
1. Fourier Series: 

> Based on ***periodic signals***. (This point is very important!!!)   
> Periodic signals can be presented by the sum of cosines and sines.
> Note that: cos and sin are a pair of orthogonal basis.

2. FT

> If the signal is not periodic signal, before using Fourier Transform (or borrow some concepts in Fourier Series), we consider this signal is a periodic signal with infinite period.
> Then we can apply the orthogonal basis cos and sin.
> 
> ......(It is too hard to write notes in English, I quit)  
> 用中文继续说吧，就是cos和sin是一组正交基，同时记住欧拉公式的表示形式，其中θ表示为  $\omega$t,通过这样的表示，在和f(t)相乘，做积分，得到了FT的公式。  
>   $\omega$ 就解决了这个问题  
> 说的好乱啊，这样把，直接上链接，不会了可以回去再看看：https://www.youtube.com/watch?v=0LuyxzqI3Hk
> 具体内容13min往后看就行
