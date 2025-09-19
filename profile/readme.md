Welcome to RGD-Software !

## Rarefied gas dynamics
Rarefied gas dynamics studies gas and plasma flows with low densities where the mean free path is significant compared to the flow characteristic spatial dimension, making the use of kinetic equations necessary and surface interactions crucial. The central characteristic number relevant to these processes is the Knudsen number  
```math
Kn = \frac{\lambda}{D},
```
a ratio of the mean free path of the particles $\lambda$ to a characteristic spatial scale $D$,
which defines flow regimes from continuum flow to free molecule flow, where molecular behavior dominates.

Very often this research activity leads to scientific software to simulate, analyze, predict and/or optimize scenarios involving rarefied gas dynamics. This GitHub organization tries to collect and promote software repositories related to RGD.

## RGD Symposium
The community of rarefied gas dynamics gathers at the [**International Symposium on Rarefied Gas Dynamics**](https://www.rarefiedgasdynamics.org/) - a biennial academic conference. These symposia are a forum for the presentation of recent advances in the field of rarefied gas dynamics. Research presented encompasses applications of space, materials, and propulsion, as well as the basic physics of molecular interactions, gas surface interactions, kinetic theory, astronomical observations, gas transport, multi-phase flows, combustion, non-equilibrium hypersonic gas dynamics, and plasma processing. The first symposium was held in 1958 in Nice, France. Since that time, the symposia have been organized in various countries in North America, Europe, Asia, and Australia.

The Symposium invites scientists from several disciplines to discuss basic science and technological applications in the following areas:
 * Boltzmann and related equations: mathematical properties of the Boltzmann equation, proofs of existence of solutions in particular cases, model kinetic equations
 * Monte Carlo methods and numerical solutions
 * Moment methods
 * Experimental methods
 * Gas-surface interactions
 * Aerospace. Examples include high speed flows, shock waves, nozzle expansions, high altitude aerodynamics.
 * Jets and plumes
 * Internal flows and vacuum systems
 * Reactive gas dynamics
 * Rarefied plasmas
 * MEMs and NEMs
 * Granular flows
 * Porous media


## Rarefied Gas Dynamics Codes

### Continuum methods (Euler, Navier-Stokes)

#### Multi-dimensional solvers
* [Eilmer](https://github.com/gdtk-uq/gdtk)
* [hyFoam, hy2Foam](https://github.com/hystrath/hyStrath) | [hyFoam, hy2Foam RGD-Software fork](https://github.com/rgd-software/hyStrath)

#### 0-D, 1-D solvers
* [Cantera](https://github.com/Cantera/cantera)
* [ChemicalReactions.jl](https://github.com/LeoBasov/chemical-kinetics.jl)
* [L1D, Pitot, ESTCN, NENZF1d](https://github.com/gdtk-uq/gdtk)

#### Reaction rates, relaxation times
* [Cantera](https://github.com/Cantera/cantera)
* [Kappa](https://github.com/lkampoli/kappa)
* [Mutation++](https://github.com/mutationpp/Mutationpp)
* [VT-relaxation](https://github.com/knstmrd/VT-relaxation)

#### Thermodynamical data
* [Cantera](https://github.com/Cantera/cantera)
* [Kappa](https://github.com/lkampoli/kappa)
* [Mutation++](https://github.com/mutationpp/Mutationpp)

#### Transport coefficients
* [Cantera](https://github.com/Cantera/cantera)
* [Kappa](https://github.com/lkampoli/kappa)
* [Mutation++](https://github.com/mutationpp/Mutationpp)

#### Equilibrium compositions
* [Cantera](https://github.com/Cantera/cantera)
* [equilibrium-c](https://github.com/uqngibbo/equilibrium-c)
* [Mutation++](https://github.com/mutationpp/Mutationpp)

### Moment methods
* [fenicsR13](https://github.com/lamBOOO/fenicsR13) | [fenicsR13 RGD-Software fork](https://github.com/rgd-software/fenicsR13)

### Direct Simulation Monte Carlo (DSMC), Particle-in-Cell (PIC)

#### Large-scale codes
* [dsmcFoam+](https://github.com/hystrath/hyStrath) | [dsmcFoam+ RGD-Software fork](https://github.com/rgd-software/hyStrath)
* [Pantera PIC-DSMC](https://github.com/vonkarmaninstitute/pantera-pic-dsmc) | [Pantera PIC-DSMC RGD-Software fork](https://github.com/rgd-software/pantera-pic-dsmc)
* [PICLAS](https://github.com/piclas-framework/piclas) | [PICLAS RGD-Software fork](https://github.com/rgd-software/piclas)
* [SPARTA](https://github.com/sparta/sparta) | [SPARTA RGD-Software fork](https://github.com/rgd-software/sparta)
* [Starfish](https://github.com/particleincell/Starfish)

#### Smaller-scale/research codes
* [Merzbild.jl](https://github.com/merzbild/Merzbild.jl)
* [ParticLas](https://github.com/OttTs/ParticLas.jl)
* [Python octree-DSMC code](https://github.com/LeoBasov/dsmc-python)