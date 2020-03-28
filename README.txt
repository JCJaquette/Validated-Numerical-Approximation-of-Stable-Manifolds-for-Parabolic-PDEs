This folder contains the MATLAB codes associated with the paper: 
"Validated Numerical Approximation of Stable Manifolds for Parabolic Partial Differential Equations" 
by JB van den Berg, J Jaquette, and J Mireles James.

These codes require the INTLAB interval arithmetic library: 
http://www.ti3.tu-harburg.de/rump/intlab/


a_bundles_a1_proof  Obtains an approximate equilibria and good coordinates.
Main                Implements a computer assisted proof for Theorem 6.3, using a linear change of coordinates. 
Main_NL             Implements a computer assisted proof for Theorem 7.1, using a nonlinear change of coordinates. 
Plot_Manifold       Produces Figure 1 of the paper. 
Error_Continuation & Error_Continuation_NL ...
                    Produces Figure 3 of the paper. (See note at the beginning of these files for how to run the script properly.) 

..........................................................................

A rough correspondence for some of the files & proposition are as follows:

bound_P_alt     -	Proposition 4.4
bound_P         -	Theorem 4.2 (not used in practice)
bound_P2        -	Theorem 4.11
check_R         -	Proposition 3.13 & Remark 3.14
create_C        -	Proposition 2.4
create_D        -   Proposition 2.4
create_F        -	Proposition 5.4 & Remark 5.5
create_G        -	Algorithm 3.11
create_gamma	-	Definition 3.3
create_H_hat	-	Definition 2.6
create_H        -	Definition 2.6
create_J        -	Definition 5.8
create_K        -	Proposition 4.7 & Remark 4.8
create_lambda0	-	Theorem B.1
create_mu_deriv2    Remark 4.8
create_S        -	Proposition 4.6


data_SH         -	Section 6.2 
data_SH_Z1      -	Section 6.2.4
data_SH_Z2      -	Section 6.2.3 

data_SH_nonlinear       -   Section 7 
data_SH_nonlinear_Z1    -   Section 7.4
data_SH_nonlinear_Z2    -   Section 7.3

norm_X           -   Section 6.
norm_ell_to_X    -   Section 6.   
norm_X_to_ell    -   Section 6.
norm_X_to_X      -   Section 6.

plot_G          -	Condition 3.4 (not used for a computer assisted proof)
Q_2derivative	-	Theorem 4.10 & Proposition A.4
Q_basic         -	Section 3 & Proposition A.4 
Q_Contraction	-	Section 5 & Proposition A.4 
T_2derivative	-	Theorem 4.10 & Proposition A.3			
T_basic         -	Theorem 3.7
T_Contraction	-	Theorem 5.7 & Proposition A.3	


ValidateManifold    -   Theorem 5.11
DisplayResults      -   Theorem 5.11
Error_Continutation -   Section 6.3
Error_Continutation_NL  -   Section 6.3

Copyright (C) 2018  JB van den Berg, J Jaquette, and J Mireles James.

This program is free software: you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.