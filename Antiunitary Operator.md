#eternal 


Unitary operator: $\braket{uA|Av}=\braket{u|v}$.

Definition of antiunitary operator:

The transformation $$\ket{\alpha} \rightarrow \ket{\tilde{\alpha}}=\theta\ket{\alpha},\ \ \ket{\beta} \rightarrow \ket{\tilde{\beta}}=\theta\ket{\beta}$$is said to be **antiunitary** if $$\braket{\tilde{\beta}|\tilde{\alpha}}=\braket{\beta|\alpha}^{*},\ \  \theta(c_{1}\ket{\alpha}+c_{2}\ket{\beta})=c_{1}^{*}\theta\ket{\alpha}+c_{2}^{*}\theta\ket{\beta}$$The second condition defines the antiunitary operator. We claim here that an antiunitary operator can be written as $$\theta=UK,$$where $U$ is a unitary operator and $K$ is the complex cinjugate operator that forms the comclex conjugate of any coefficent that multiplies a ket.

Start with $K$. $$Kc\ket{\alpha}=c^{*}K\ket{\alpha}$$
and $$K\ket{\alpha}=K\sum_{\alpha'}\ket{\alpha'}\braket{\alpha'|\alpha}=\sum_{\alpha'}\braket{\alpha|\alpha'}K\ket{\alpha'}$$
Notice that if the explicit representation of the basis does not include imaginary number $i$, then $K\ket{\alpha'}=\ket{\alpha'}$. For example, the eigenstates of $S_{y}$ represented in $S_{z}$ basis.

If we define the operator this way, the second condition is satisfied: $$\theta(c_{1}\ket{\alpha}+c_{2}\ket{\beta})=UK(c_{1}\ket{\alpha}+c_{2}\ket{\beta})=U(c_{1}^{*}K\ket{\alpha}+c_{2}^{*}K\ket{\beta})=c_{1}^{*}UK\ket{\alpha}+c_{2}^{*}UK\ket{\beta}=c_{1}^{*}\theta\ket{\alpha}+c_{2}^{*}\theta\ket{\beta}$$ 
Let's check the first condition: $$\ket{\alpha} \rightarrow \ket{\tilde{\alpha}}=UK\sum_{\alpha'} \ket{\alpha'}\braket{\alpha'|\alpha}=\sum_{\alpha'}\braket{\alpha|\alpha'}UK\ket{\alpha'},$$ $$\braket{\tilde{\beta}|\tilde{\alpha}}=\sum_{\alpha''}\sum_{\alpha'} \braket{\alpha|\alpha'}\braket{\alpha''|\beta}\bra{\alpha''}K^{\dagger}U^{\dagger}UK\ket{\alpha'}$$   ^784abf
Notice that $\alpha'$ and $\alpha''$ denote the basis vectors. If we choose a basis which is unchanged under $K$, then It's obvious that $\bra{\alpha''}U^{\dagger}U\ket{\alpha'}=\braket{U\alpha''|U\alpha'}=\braket{\alpha''|\alpha'}$ since $U$ is unitary. We hope that $\{\alpha'\}$ is a set of  orthogonal basis vectors so we can have $$\braket{\tilde{\beta}|\tilde{\alpha}}=\sum_{\alpha'} \braket{\alpha|\alpha'}\braket{\alpha'|\beta}=\braket{\alpha|\beta}=\braket{\beta|\alpha}^{*}$$

For the physical interest, infact we are only interested in two types of transformation: unitary and antiunitary operators. ^5aa9a8