# Comp-Neuro-SpikingNN
Google colab tutorial of spiking neural network simulation with spike time dependent plasticity that I created for my final project in computational neuroscience. 
The liquid state machine resevior recieves a spike train that represents encoded audio from from an auditory nerve simulation, and the synaptic weights update
in the LSM with STDP which is similar to the type of plasticity used in the brain. 
In this tutorial I only completed the audio encoder, LSM with STDP simulation, and the visualization of the the networks connectivity before and after exposure to audio stimulus. 
In the future a neural network readout layer can be used to test the quality of the representations in the LSM activity. 

the visualization and connectivity pattern is partly inspired from Ricardo de Azambuja's publication and repos on using LSMs with short term plasticity for robotics 
but I implemented the LSM with Brian2 instead of bee, used 2D connectivity for simplicity of visualization, and I implemented STDP instead of STP to mimic the type of long
term potentiation and long term depression seen in human synapses and associated with memory.
