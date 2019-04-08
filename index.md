<font size="14">**The Blog of Covariant g minor**</font>

<font size="6">**The ground state of the helium atom (this is for test)**</font>

<font size = "3"></span>

The Hamiltonian of a helium atom can be written as

$$H=\frac{p_1^2}{2}+\frac{p_2^2}{2}-\frac{Z^*}{r_1}-\frac{Z^*}{r_1}+\frac{1}{|\bold{r_1}-\bold{r_2}|}$$

in which we have used atomic unit and neglected the motion of the nucleus. The wavefunction for the space part of the ground state of the helium atom can be written as

$$\psi_0(\text{r$_1$},\text{r$_2$})=\psi_{1s}(\text{r$_1$};Z^*)\psi_{1s}(\text{r$_2$};Z^*)$$

in which $$\psi_{1s}(\text{r};Z^*)$$ has a form of

$$\psi_{1s}(\text{r};Z^*)=\sqrt{\frac{1}{4\pi}}{Z^*}^{3/2}2e^{-Z^*r}$$

where $$Z^*$$ is the effective number of charges of the nucleus. The energy of such state can be given by

$$E_0 =E_0(Z^*)=  \int_{\infty} \psi_0(\text{r$_1$},\text{r$_2$})^*H\psi_0(\text{r$_1$},\text{r$_2$})dV_1dV_2 = -2\times \frac{1}{2}{Z^*}^2+ \int_\infty \psi_0(\text{r$_1$},\text{r$_2$})^*(\frac{1}{|\text{r$_1$}-\text{r$_2$}|}-\frac{2-Z^*}{r_1}-\frac{2-Z^*}{r_2})\psi_0(\text{r$_1$},\text{r$_2$})dV_1dV_2  =(Z^*)^2-\frac{27}{8}Z^*.$$

By the variation theory, we should have

$$\frac{\partial E_0}{\partial Z^*}=0$$

which yields that $$Z^*=\frac{27}{16}$$ from which we can infer that $$E_0= -2.85$$ a.u. which correspond to $$- 77.52$$ eV.



Under perturbation theory, the zeroth order is given by
$$H^{(0)}=-2\times\frac{1}{2}\times 2^2=-4$$

and the first correction order is given by

$$H^{(1)}=\int_\infty \psi_0(\text{r$_1$},\text{r$_2$})^*\frac{1}{|\text{r$_1$}-\text{r$_2$}|}\psi_0(\text{r$_1$},\text{r$_2$})dV_1dV_2$$

with $$Z^*=2$$. After some calculations, the result is $$H^{(1)}=\frac{5}{4}$$. Thus the energy of the ground state can be calculated as (to the first order) $$E_0=H^{(0)}+H^{(1)}=\frac{11}{4}$$ a.u. which corresponds $$-74.8$$ eV.

