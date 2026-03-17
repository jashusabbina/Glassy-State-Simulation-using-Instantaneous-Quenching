# Obtaining Computer-Generated Glassy States via Instantaneous Quenching

##  Project Overview

This project focuses on obtaining glassy states by minimizing the potential energy of a 2D system of interacting particles using computational methods. The system undergoes structural relaxation through an optimization algorithm.

##  Objective

To find a local minimum of the potential energy using the Steepest Descent algorithm, resulting in a stable "glassy state" or inherent structure.

##  Key Concepts

* Lennard-Jones Potential
* Particle Interaction (Attraction & Repulsion)
* Energy Minimization
* Structural Relaxation
* Gradient Descent (Steepest Descent Algorithm)

##  Methodology

1. Initialize a system of particles in 2D space
2. Compute forces using Lennard-Jones potential
3. Move particles along negative energy gradient (−∇U)
4. Update positions iteratively
5. Stop when force magnitude is below threshold

##  Mathematical Model

* Lennard-Jones potential models inter-particle forces
* Includes:

  * Repulsive force (short distance)
  * Attractive force (long distance)
* Parameters:

  * ε (epsilon): interaction strength
  * σ (sigma): distance at zero potential

##  Results

* Achieved stable low-energy configuration
* Observed displacement of particles
* Compared initial vs final configurations
* Generated plots for visualization

##  Challenges

* Choosing optimal step size (α)
* Slow convergence in narrow energy valleys
* Debugging force calculations

##  Conclusion

The Steepest Descent algorithm successfully minimized system energy and produced a stable glassy configuration. While simple, it demonstrates the structural relaxation process effectively.

##  Technologies Used

* Python / MATLAB
* NumPy
* Matplotlib
* Google Colab

##  Project Structure

* `glassy_states.ipynb` → Main simulation
* `output.png` → Graphs & results
* `README.md` → Documentation

##  Reference

Project based on simulation of Lennard-Jones systems and energy minimization techniques. 
