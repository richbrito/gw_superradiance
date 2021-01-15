# Data

Data has been computed assuming that the dimensionless black hole spin is given by chi=chi_f, eq. 12 in [arXiv:1810.03812](https://arxiv.org/pdf/1810.03812.pdf).

### Data for amplitudes A as defined in eq.(19) of  [arXiv:1810.03812](https://arxiv.org/pdf/1810.03812.pdf): 

- first column: M\mu, second column: amplitude A
  - Z22_direct.dat -> l_gw=2,m_gw=2 GW mode, using direct integration method to compute homogeneous solutions to Teukolsky's equation
  - Z32_direct.dat ->  l_gw=3,m_gw=2 GW mode, using direct integration method to compute homogeneous solutions to Teukolsky's equation
  - Z22_MST.dat -> l_gw=2,m_gw=2 GW mode, using MST method to compute homogeneous solutions to Teukolsky's equation
  - Z32_MST.dat ->  l_gw=3,m_gw=2 GW mode, using MST method to compute homogeneous solutions to Teukolsky's equation


### Data for GW flux. Note that this already includes the summation over positive and negative m_gw..

- first column: M\mu, second column: dE/dt/(M_s/M)^2
  - fluxGWl2m2.dat -> dE/dt/(M_s/M)^2 for the l_gw=2,m_gw=2 GW mode, using direct integration method
  - fluxGWl3m2.dat  -> dE/dt/(M_s/M)^2 for the l_gw=3,m_gw=2 GW mode, using direct integration method
