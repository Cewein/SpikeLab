# Spiking Network Lab

An interactive 2D environment for building, growing, pruning, training and
inspecting spiking neural networks in the browser. The networks are free
directed graphs: any neuron can connect to any neuron, including itself. You
watch spikes travel along synapses with their real transmission delays.

Simulation, plasticity, feature extraction, readout training and rendering all
run on the GPU through WebGPU (WGSL compute and render pipelines). There is no
CPU simulator. Every glow and every moving pulse on the canvas is a spike that
the GPU recorded.

## References

- R1: K. O. Stanley and R. Miikkulainen (2002). *Evolving Neural Networks through Augmenting Topologies.* Evolutionary Computation 10(2).
- R2: W. Gerstner, W. M. Kistler, R. Naud and L. Paninski (2014). *Neuronal Dynamics*, §1.3.
- R3: E. M. Izhikevich (2003). *Simple Model of Spiking Neurons.* IEEE Trans. Neural Networks 14(6).
- R4: W. Maass, T. Natschläger and H. Markram (2002). *Real-Time Computing Without Stable States.* Neural Computation 14(11).
- R5: G. Bi and M. Poo (1998). *Synaptic Modifications in Cultured Hippocampal Neurons.* J. Neuroscience 18(24).
- R6: E. O. Neftci, H. Mostafa and F. Zenke (2019). *Surrogate Gradient Learning in Spiking Neural Networks.* IEEE Signal Processing Magazine 36(6).
- N2: G. Bellec, D. Salaj, A. Subramoney, R. Legenstein and W. Maass (2018). *Long short-term memory and Learning-to-learn in networks of spiking neurons.* NeurIPS.
- WebGPU and WGSL: W3C specifications and the MDN WebGPU documentation.
