# QEC_GNN
Quantum error correction using graph neural networks


Convert_data
- gen_data: MCMC decoder
- new_datacreator: From MCMC-decoder transform syndrome matrices to node feature- and edge list etc. 
- convert_datapytorch: Create graphs from edge list, node features etc.
- clean_data: Remove graphs such that all remaining graphs are unique
