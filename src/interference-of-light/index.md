---
nav:
    title: 光的干涉
    path: /interference-of-light
---

## 波的叠加原理

> 波的叠加区域内各点振动的物理量等于各列波在该点引起的物理量的矢量和。光的干涉实质上是波的叠加和波的干涉！

两个单色点光源的叠加公式推导:

单色点光源$S_1$和$S_2$, 发出频率相同、振动方向相同的球面简谐波, 初相位分别为$\varphi_{01}$和$\varphi_{02}$

叠加区域任意一点**P**的复振幅为

<!-- 这里的公式渲染有问题 -->

$$
\widetilde{E}_1 = A_1e^{kd_1 - \varphi_{01}} = A_1e^{i\theta_1} \\
\widetilde{E}_2 = A_2e^{kd_2 - \varphi_{02}} = A_2e^{i\theta_2}
$$

根据叠加原理, **P**的复振幅为

$$
\widetilde{E} = \widetilde{E}_1 + \widetilde{E}_2 = A_1e^{i\theta_1} + A_2e^{i\theta_2}
$$

**P**光强为

$$
I = A^2_1 + A^2_2 + A_1A_2\cos(\theta_2 - \theta_1)
$$

或

<!-- 下面公式的根号渲染有问题 -->

$$
I = I_1 + I_2 + 2\sqrt{I_1I_2}\cos\delta
$$

```tsx
import React from 'react';
import { PrincipleOfWaveSuperimposing } from 'visible-physics';

export default () => <PrincipleOfWaveSuperimposing />;
```

## 杨氏双缝干涉实验

## 牛顿环干涉实验

## 迈克尔逊干涉仪实验
