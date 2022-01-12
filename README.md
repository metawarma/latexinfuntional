$定理 7.3.4(Fourier 变换的卷积定理) 设f,g \in K',f的支集是有界的，F(f)是正则广义函数而且F(f)(\sigma)是Z的乘子，那么$

$F(f*g)=F(f)F(g)$

$证 设\psi=F(\varphi),\varphi \in K,那么由(7.3.13)(7.3.20)(7.3.19)有$

$(F(f*g),\psi)=(2\pi)^{n}(f*g,J\varphi)=(2\pi)^n(g,(f,\tau_{(.)}J\varphi))$

$=(2\pi)^n(g,J(f,\tau_{-(.)}(J\varphi)))$

$=(F(g),F(f,\tau_{-(.)}J\varphi))$

=$\frac{1}{(2\pi)^n}(F(g),F(F(f),F(J_{\tau_{-(.)}}J\varphi)))$

然而

$F(J_{\tau-(.)}J\varphi)=\int e^{ix\sigma}\varphi(t+x)dx=e^{-it\sigma}\psi(\sigma)$

所以

$(F(f),F(J_{\tau-(.)}J\varphi))=\int e^{ix\sigma}F(f)(\sigma)\psi(\sigma)d\sigma$

$由于F(f)为Z的乘子，所以F(f)(.)\psi(.)\in Z，因此$
$(F(f),F(J_{\tau-(.)}J\varphi))=(2\pi)^nF^{-1}(F(f)\psi),$

把他代入我们得到

$(F(f*g),\psi)=(F(g),F(f)\psi)$

然而由于F...

$(F(f*g),\psi)=(F(g),F(f)\psi)$
