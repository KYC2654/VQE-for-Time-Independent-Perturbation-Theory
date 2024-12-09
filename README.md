# VQE-for-Time-Independent-Perturbation-Theory
In Quantum 137B, we had to find a "good" basis for the Hamiltonian such that the perturbation Hamiltonian is diagonalized, after which we could  more easily conduct Time-Independent Perturbation Theory. However, I found this p[process tedious, and I wanted to create an automated process to find a good basis for Hamiltonians to conduct Time-Independent Perturbation Theory. Wanting to apply my knowledge gained from quantum computing, I decided to attempt appling the Variational Quantum Eigensolver algorithm to this problem. (Why not?) This project still has much to develop, and it was not as easy to code up as I initially thought. Nevertheless, I am having lots of fun with this and would like to see if it will actually lead to something remotely useful for skipping my homework. (Even though I spent more time on this than my homework anyway). There are still many issues with finding consistent eigenvalues and eigenvector results for the test case in re-runs. This could be due to the Random Initialization of Parameters, Noise, etc..

As I continue to work on the project, I plan to apply data analysis methods over many optimization trials, or even use gradient-based optimizers. I also plan to incorporate Error Mitigation code to, hopefully, improve the precision of the results. 
