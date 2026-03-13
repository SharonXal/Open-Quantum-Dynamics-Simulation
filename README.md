# Open-Quantum-Dynamics-Simulation
Develop simulations using QuTip for simulating open quantum systems. 

I have initially focused on light-matter interactions. I wanted to investigate, as a hobbie, what are the conditions for strong coupling of QD and light and what are the sources of noise and fabrication challenges. 

I have written many codes for open quantum simulations, but my goal with this codebase is to upload them in tutorial style. So currently, I am working towards re-writing existing codes with detailed theory and analysis.

Currently the codebase contains three notebooks. The notebooks are:

1. **qd_cavity_QED.ipynb**: This notebook simulates an InAs/GaAs self-assembled quantum dot (QD) embedded in a photonic-crystal nanocavity, modelled as a two-level emitter (TLS) strongly coupled to a single quantised cavity mode. The system is treated as an open quantum system: coherent Jaynes–Cummings dynamics plus incoherent Lindblad dissipation.
2. **open_JC_model_lindblad**: This is the extension of the previous notebook, but now I have considered possible sources of noise. I have simulated individual effect of these noises and also the combined effect. This notebook builds up the model layer by layer, visualises each physical effect, and finally quantifies photon indistinguishability _M_ as a function of all relevant parameters.
3. **qd_placement_cavity_qed.ipynb**: This notebook explores the connection between strong coupling and quantum dot placement in photonic cavities. I have tried to simulate favorable conditions for preparing quantum dot for maximum efficiency.
4. **qd_photon_emission_cavity.ipynb**: This notebook simulates photon emission from a quantum dot in cavity. A semiconductor quantum dot (QD) embedded in a photonic cavity is one of the most controllable and well-characterised light–matter interfaces in solid-state physics. This notebook provides rigorous, numerically validated simulations of three cornerstone phenomena: _Purcell Effect_, _Vacuum Rabi Splitting_, _Photon indistinguishability_.
