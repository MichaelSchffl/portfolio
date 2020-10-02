# Mic's Portfolio

# [Project 1: Calculating probability distribution functions for ions in Jupiter's magnetosphere](https://github.com/MichaelSchffl/Jupiters_energetic_particles)
### short description:
Jupiter's magnetosphere contains many energetic ions [100keV -10 MeV]. It has been a puzzling enigma what physical mechanism drives the acceleration of these ions in certain regions of Jupiter's magnetosphere. In this extensive research project I wanted to look deeper into that problem by calculating distributions of energy and pitch angle of these ions, where the pitch angle is the angle between a magnetic field line and the ion. From this analysis I was able to infer on the underlying physical mechanism and make a guess for the cause of the ion acceleration.

### technical implementations:
* Formatting, processing and read in magnetic field and ion data and set physical parameters
* Data interpolation and linearization, calculating relative extrema
* Develope step detection algorithm that automatically finds strongest increase/decrease in data set
* Sort data sets according to relative position of detected steps
* Calculate distribution functions for different ion species based on earlier calculations
* Error analysis in Poisson statistics
* Data visualization and interpretation and implications for dynamics and processes in Jupiter's magnetosphere

![](/images/Orbit04_maglat_B_dens-1.png)
![](/images/PAs_O_Orbit2_7_10-1.png)

# [Project 2: Hydrogeological simulation using PyGimli](https://github.com/MichaelSchffl/hydrogeophysical_process_simulation)
### short description:
Geoscientist are often interested in simulating hydrogeological processes in the subsurface. In order to simulate these processes the PyGimli library represents a powerful tool to scientifically model geophysical applications. These hydrogeological flows are governed by the Darcy equation, streaming potential, mass flow and other physical aspects. These equations can be solved with the finite-element modeling scheme. In this project, I first created a world with a certain geometry and topography. Then, the hydraulic and streaming potentials were solved with the finite-element scheme. When ejecting a tracer fluid in the created world with certain physical parameters (hydraulic & electrical conductivity, porosity, boundary conditions...), the transport equation can again be solved and be converted in electrical conductivity. The result is a flow simulation that can be visualized with an animation.

### technical implementations:
* Use of the PyGimli library for hydrogeophysical applications
* Creating a unique world geometry with topography and set a mesh. Quality test the mesh
* Implementing Darcy's equation to generate a hydraulic potential and solve the equation with the Finite Elements scheme
* Implementing the streaming potential and calculate it with Finite Elements solver
* Simulate a salt tracer injection at a certain cell position
* Implementing and solving advection-diffusion equation with Finite Volume method within the limits of the Courant-Friedrichs-Lewy condition and simulate the flow of the tracer fluid
* Calculating electrical fluid conductivity from salt concentration and convert to bulk resistivity of the rock using implementation of Archie's law
* Creating an animation of the electrical resistivity simulation over time in the subsurface and save it as .mp4


![](/images/stream.png)
![](/images/el_potential.png)
![](/images/pseudosection.png)  |  ![](/images/summary_roh_anim.gif)


# [Project 3: Implementing Python-based Mini Games](https://github.com/MichaelSchffl/Mini-Games)
Sometimes fiddling around and trying to improve a piece of code as far as possible gives new insights to unknown parts of coding...and it's fun!
* Drawing gameboards with some fake graphics in python
* Regular expressions for user input
* Randomness and permutations
* Main method and functions
