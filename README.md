# Open-Quantum-Dynamics-Simulation
This repository contains my personal simulations of open quantum systems using QuTiP. My current focus is on light–matter interactions, particularly exploring the conditions required for strong coupling between quantum dots and optical fields, along with studying noise sources and practical fabrication challenges.

Many of these codes were originally written for my own exploration. I am now gradually rewriting them in a tutorial-style format, adding detailed explanations of the theory, simulation methods, and interpretation of results.

The simulations typically reproduce existing theoretical proposals rather than presenting new research. I try to reference the papers that were used for writing the codes at the end of each notebook. The primary goal is to deepen my own understanding while building a collection of open-source educational resources.

Since this is an ongoing personal learning project, some implementations may contain mistakes or approximations. I continuously refine and debug the codes as I learn more.

Notebooks in this repo:

1. **qd_cavity_QED.ipynb**: This notebook simulates an InAs/GaAs self-assembled quantum dot (QD) embedded in a photonic-crystal nanocavity, modelled as a two-level emitter (TLS) strongly coupled to a single quantised cavity mode. The system is treated as an open quantum system: coherent Jaynes–Cummings dynamics plus incoherent Lindblad dissipation.
2. **open_JC_model_lindblad**: This is the extension of the previous notebook, but now I have considered possible sources of noise. I have simulated individual effect of these noises and also the combined effect. This notebook builds up the model layer by layer, visualises each physical effect, and finally quantifies photon indistinguishability _M_ as a function of all relevant parameters.
3. **qd_placement_cavity_qed.ipynb**: This notebook explores the connection between strong coupling and quantum dot placement in photonic cavities. I have tried to simulate favorable conditions for preparing quantum dot for maximum efficiency.
4. **qd_photon_emission_cavity.ipynb**: This notebook simulates photon emission from a quantum dot in cavity. A semiconductor quantum dot (QD) embedded in a photonic cavity is one of the most controllable and well-characterised light–matter interfaces in solid-state physics. This notebook provides rigorous, numerically validated simulations of three cornerstone phenomena: _Purcell Effect_, _Vacuum Rabi Splitting_, _Photon indistinguishability_.
5. **nanomechanical_qubit_simulation**: This notebook provides a QuTiP simulation of the nanomechanical qubit proposed in [Phys. Rev. X 11, 031027 (2021)](https://arxiv.org/abs/2008.10524). The system consists of a suspended carbon nanotube hosting a double quantum dot whose single-electron charge states are coupled to the second flexural mechanical mode of the nanotube. Main purpose of this notebook is to reproduce the simulation results proposed in the original work.
