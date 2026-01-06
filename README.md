<h1>Hydrogen Wavefunction Computation and Orbital Generation</h1>
<h2>Method</h2>

* Electron wave function $\psi_{n, l, m_{l}}(r, \theta, \phi)$ was obtained by computing $R_{n, l}(r)$ (radial) and $Y_{l, m_l}(\theta, \phi)$ (angular) components individually.
* Probability density function for orbital with certain quantum numbers $n, l, m_l$ was resolved using $|\psi(r, \theta, \phi)|^2$ and was then sampled in 3D space around origin
spherically.
* Normalised probability values were then plotted as granular points until probability integral gave sufficiently high number (>0.97).
* Sign of $\psi(r, \theta, \phi)$ was used to assign colour gradient and transparency to points, blue being `+` and red being `-`.
* For $m \neq 0$, linear combination was done for $+m$ and $-m$ angular wave functions to obtain complete wavefunction for symmetric orbitals.
* Normalization was handled for radial and angular components, and verified by integration.

<h2>Tools and Libraries</h2>

* Python (3.12.12)
* Plotly (5.24.1)
* Matplotlib
* NumPy

<h2>Renders</h2>

![alt text](https://github.com/astrobits1/hydro-orb-gen/raw/master/output/op1.png)
![alt text](https://github.com/astrobits1/hydro-orb-gen/raw/master/output/op2.png)
![alt text](https://github.com/astrobits1/hydro-orb-gen/raw/master/output/op3.png)
![alt text](https://github.com/astrobits1/hydro-orb-gen/raw/master/output/1s.png)
![alt text](https://github.com/astrobits1/hydro-orb-gen/raw/master/output/2pz.png)
![alt text](https://github.com/astrobits1/hydro-orb-gen/raw/master/output/3dxz.png)
![alt text](https://github.com/astrobits1/hydro-orb-gen/raw/master/output/3dx2y2.png)
![alt text](https://github.com/astrobits1/hydro-orb-gen/raw/master/output/4f3.png)
![alt text](https://github.com/astrobits1/hydro-orb-gen/raw/master/output/5g2.png)
![alt text](https://github.com/astrobits1/hydro-orb-gen/raw/master/output/5g4.png)
![alt text](https://github.com/astrobits1/hydro-orb-gen/raw/master/output/5g5.png)

<h3>Bonus: Hypothetical higher orbital render (10l) </h3>

![alt text](https://github.com/astrobits1/hydro-orb-gen/raw/master/output/10l6.png)
![alt text](https://github.com/astrobits1/hydro-orb-gen/raw/master/output/10l7.png)
![alt text](https://github.com/astrobits1/hydro-orb-gen/raw/master/output/op4.png)
