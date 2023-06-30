---
title: Specific heat of phonon
data: 2023-06-27
---
The energy of one phonon is defined as:
$$E = \hbar\omega $$ 
where $\omega$ is the angular frequency of this phonon. 
In quantum statistics, phonon number, _n_, follows Bose-Einstein distribution:
$$n=\frac 1{e^{\frac {\hbar\omega}{k_BT}}-1}$$ 
where $k_B$ is the Boltzmman constant, _T_ is temperature. Therefore, the thermal energy contribution by phonons is expressed as:
$$E_{thermal}=(n+\frac 12)\hbar\omega$$ 
Then the specific heat of, _C_, phonon is derived by:
$$
\begin{equation}
\begin{split}
C&=\frac {\partial E_{thermal}}{\partial T} \\
&=\frac {\partial n}{\partial T}\hbar\omega \\
&=\frac {e^{\frac {\hbar\omega}{k_BT}}}{({e^{\frac {\hbar\omega}{k_BT}}-1)}^2}\frac {\hbar^2\omega^2}{k_BT^2}\\
&=n(n+1)\frac {\hbar^2\omega^2}{k_BT^2}
\end{split}
\nonumber
\end{equation}
$$



