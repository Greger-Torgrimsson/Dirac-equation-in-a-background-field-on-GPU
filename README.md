jaxBWplaneWaveGH.ipynb contains a code for computing the probability of nonlinear Breit-Wheeler pair production in (1+1)D. "planeWave" in the name refers to the high-energy photon, not the background field. The method and code are described in

G. Torgrimsson,
``Solving the Dirac equation on a GPU for strong-field processes in multidimensional background fields''
to appear


jaxSchwingerGH.ipynb is an updated code which is much faster.  


This notebook solves the Dirac equation in an electric field, E(t,x), E(t,x,y) or E(t,x,y,z), and computes the probability of Schwinger pair production, using the method described in:

G. Torgrimsson,
``Momentum correlation in pair production by spacetime dependent fields from scattered wave functions''
arXiv:2509.17770

The code has been tested on Colab with 3 different runtime types: CPU for 1+1, T4 GPU for 2+1, and A100 GPU for 3+1.
