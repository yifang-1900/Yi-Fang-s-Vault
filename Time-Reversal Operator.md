#eternal [[Antiunitary Operator]]

Represent the time-reversal operator by $\Theta$, to be distinguished from $\theta$, a general antiunitary operator.

Consider a time-reversed state $\Theta\ket{\alpha}$. More appropriately, $\Theta\ket{\alpha}$ should be called the motion-reversed state.

Look at the time evolution of the time-reversed state and try to deduce the fundamental property of the time reversal operator:

A system is in state $\ket{\alpha}$ at $t=0$. At a slightly later time $t=\delta t$, the system is found in a the state $\ket{\alpha,\ t_{0}=0,\ t=\delta t}=(1-\frac{iH\delta t}{\hbar})\ket{\alpha}$. Let the time-reversed state $\Theta\ket{\alpha}$ evolve, we then have, at $t=\delta t$, $$(1-\frac{iH\delta t}{\hbar})\Theta\ket{\alpha}.$$
If motion obeys symmetry under time reversal ([[qq_not quite understand]]), we expect the preceding state ket to be the same as $$\Theta\ket{\alpha, t_{0}=0; t=-\delta t}$$ That is, we consider a ket at ealier time $t=-\delta t$ then reverse $P$ and $J$, i.e., $$(1-\frac{iH\delta t}{\hbar})\Theta\ket{\alpha}=\Theta(1-\frac{iH(-\delta t)}{\hbar})\ket{\alpha}$$$$iH\Theta\ket{\alpha}=-\Theta iH\ket{\alpha}$$
Notice that $i$ cannot be cancelled in general. The $\Theta$ in front of the $i$ on the RHS might make the coefficient behind it to be a complex conjugate.

Suppose that $\Theta$ were unitary. It would be legitimate to cancel the imaginary number $i$. We would have $H\Theta=-\Theta H$. Consider an energy eigenket $\ket{n}$ with energy eigenvalue $E_{n}$.  $$H\Theta \ket{n}=-\Theta H\ket{n}=-\Theta E_{n}\ket{n}=-E_{n}\Theta\ket{n}$$It is nonsensical even for an elementary case of free particle. How can a free particle have negative energy just because it has a reversed motion? 

If time reversal is to be a useful symmetry, we are not allowed to cancel the i's and $\Theta$ is antiunitary. The identity becomes  $iH\Theta\ket{\alpha}=i\Theta H\ket{\alpha}$. and we have $$\Theta H = H\Theta$$
[[qq_more example]] 

This equation expresses the fundamental property of the Hamiltonian under time reversal.[[qq_examine other commutation relation]]

(Trivial) identity of antiunitary operator: $$\braket{\beta|\otimes|\alpha}=\braket{\tilde{\alpha}|\Theta\otimes^{\dagger}\Theta^{-1}|\tilde{\beta}}$$ where $\otimes$ is a linear operator.

For Hermitian observables $A$, $$\braket{\beta|A|\alpha}=\braket{\tilde{\alpha}|\Theta A\Theta^{-1}|\tilde{\beta}}$$
We say that $A$ is even or odd under time reversal according to $$\Theta A \Theta^{-1}= \pm A$$.For a Hermitian observable, the identity above gives information about the matrix elements: $$\braket{\beta|A|\alpha}=\pm\braket{\tilde{\beta}|A|\tilde{\alpha}}^{*}$$If $\ket{\alpha} =\ket{\beta}$, we can think about it as the diagonal elements or the expectation values: $$\braket{\alpha|A|\alpha}=\pm\braket{\tilde{\alpha}|A|\tilde{\alpha}}$$ [[qq_no complex conjugation]]

Example: momentum operator $p$
We choose reasonably that $p$ is odd under time-reversal, i.e., $\Theta p\Theta^{-1}=-p$, or $\Theta p = -p\Theta$. Moreover, $$p\Theta\ket{p'} = -\Theta p\Theta^{-1}\Theta\ket{p'}=-\Theta p\ket{p'}=(-p')\Theta \ket{p'}$$ We can say that $\Theta \ket{p'}=\ket{-p}$. 

Notice that time-reversed state is motion-reversed state, so $$\Theta x \Theta^{-1}=x,\ \ \Theta \ket{x'}=\ket{x'}$$
[[qq_Notice that there are phase DOF]].
