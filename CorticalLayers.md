##Cortical Layers

Within every region of the neocortex there is a consistent 6-layered structure. The structure consists of inputs, outputs and internal processing. The inputs and outputs connect to other regions, the thalamas and other sub-cortical structures. The internal processing essentially learns and classifies input patterns. It outputs patterns to regions above and below the cortical hierarchy. The coalition of these patterns form semantic strucuture of feedforward information from the world and feedback information from memory. This form of information processing is unlike anything else. It is vastly flexibile and general purpose.

There are two major types of neurons in the cortex: stellate and pyramidal. The majority of them are pyramidal. They both have a specific morphology for pattern recognition. They can recognize hundreds of unique neural activity patterns of their neighbors. Their dendrites grow down, left/right (and up for pyramidal neurons). The key property of these neurons is that they operate in complete ignorance. When they grow their dendrites they don't know who they're going to connect to. They don't know what any pattern means. All they do is just form synapses with whatever neighboring axons they can find and re-enforce their synaptic connections with Spike-Timing-Dependent-Plasticity.

Leaving the details aside for now, here is the general structure of the cortical layers and their dominant cell types. (Triangles = pyramidal, Circles = stellate)

![cortex_layers](https://github.com/sebjwallace/HTM-theory/blob/master/layersinfo.png)

Although every cell has the same processing mechanism, they operate differently depending on who they're connected to. For example, neurons in layer 4 who connect to each other have a different function from the cells in layer 6 that connect to layers 3, 5 and input axons.

Starting with the feedforward inputs from other regions, the thalamas, etc. the primary input layer is layer 4. On the way to layer 4 the layer 6 cells form synapses to the input axons. Layer 4 performs the first classification of inputs then feeds onto layers 2/3 for further classification. From layers 2/3 the output feeds to other regions.

Feedback inputs from higher regions enter into layer 1 where the inputs are distributed across all the columns. Ignoring layer 5 (which is involved with motor output) the feedback pathway is just as simple the feedforward pathway. The inputs routed from layer 1 pass through layers 2/3 onto layer 6. As layer 6 has synaptic connections with feedforward inputs, it combines the classifications from layers 2/3 with the classifications of the lower regions layers 2/3 axons. Layer 6 then feeds back to the lower region for feedback input.

Further details on the functions of these layers will be illustrated later. For now this is the general schematic.

![cortex_layers_map](https://github.com/sebjwallace/HTM-theory/blob/master/layersmap.png)
