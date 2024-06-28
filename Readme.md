# RAFT Consensus Implementation in EigenLayer ##
The following is a generalized implementation of RAFT Consensus for use within EigenLayer AVSs. This allows for operators to reach agreement about some genralized request for data. This will be the primary consensus method for how operators within LayerLens reach agreement evaluation tasks for foundational models. RAFT consensus is a known consensus method used in a plethora of ditributed systems all over the world. 

## Use within LayerLens
The Atlas Protocol, which is the broader protocol defining how nodes within LayerLens evaluate and reach agreement upon data for new evaluation requests, utilizes Raft Consensus to assign new evaluation tasks to individual operators, select localized leaders for clusters, and aggregrate final scores for each model-evalaution dataset pair. 


## Generalized for AVSs
This code can be adopted for use within any AVS that requires operators to reach agreement upon some individual datapoint. Examples inlcude: price oracles, layer-2 protocols, DA protocols, and more. 