/************************************************************************
%%%%%%%%%%%%%%%%%%%%%% DESCRIPTION %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
 * A posteriori error estimates for the Richards equation
 * authors: K. Mitra, M. Vohralik 
 * link: 
 * usage: script for FreeFem++ 
 * file: Main_aposteriori.edp  
 * author: Koondanibha Mitra
 * based on scripts by Fréderic Hecht, Zuqi Tang, and Benjamin Stamm
 * expanding the code:  I. Smears and M. Vohralík, ESAIM Math. Model. Numer. Anal. (2020)
 * Aug 2021 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%*/

The codes are in FreeFem++. There are three codes for the following test cases
Test 1: Nonlinear but nondegenerate problem with known exact solution.
Test 2: Nonlinear and degenerate problem  in the total pressure formulation of the Richards equation with known exact solution.
Test 3: Realistic case, nonlinear, degenerate with heterogeneous and anisotropic absolute permeability, mixed boundary conditions (Neumann + Dirichlet), discontinuous initial condition, non-uniform mesh, and no known exact solution.

Comments:
The most general code is Test 1, since it includes all code parts in the pressure formulation, including exact error computating. The realistic case (Test 3) uses more general meshes and absolute permeability functions.
