# Open-Quantum-Dynamics-Simulation
Develop simulations using QuTip for simulating open quantum systems. 

I have initially focused on light-matter interactions. I wanted to investigate as a hobbie, what are the conditions for strong coupling of QD and light and what are the sources of noise and fabrication challenges.

Currently the codebase contains three notebooks (I have plans to add more as I do further research). The notebooks are:

1. **qd_cavity_QED.ipynb**: This notebook simulates an InAs/GaAs self-assembled quantum dot (QD) embedded in a photonic-crystal nanocavity, modelled as a two-level emitter (TLS) strongly coupled to a single quantised cavity mode. The system is treated as an open quantum system: coherent Jaynes–Cummings dynamics plus incoherent Lindblad dissipation.
2. **open_JC_model_lindblad**: This is the extension of the previous notebook, but now I have considered possible sources of noise. I have simulated individual effect of these noises and also the combined effect. This notebook builds up the model layer by layer, visualises each physical effect, and finally quantifies photon indistinguishability _M_ as a function of all relevant parameters.
3. **qd_placement_cavity_qed.ipynb**: This notebook explores the connection between strong coupling and quantum dot placement in photonic cavities. I have tried to simulate favorable conditions for preparing quantum dot for maximum efficiency.
