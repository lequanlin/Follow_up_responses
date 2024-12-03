# Follow_up_responses

Here we present some supplementary experiment results on the balation study of GFE and some relevant information.

## Ablation - More hops

### Supplementary material 1

To build on our previous analysis, where we experimented with GFE using "GCN1" and "GCN2", we conducted additional experiments by increasing the number of GCN layers from 3 to 5. The results, presented in Supplementary Material 1, indicate that the number of GCN layers has minimal impact on generative quality and may even improve model accuracy.

![supp_hop](https://github.com/user-attachments/assets/5a3fd1b6-1646-43cc-977b-e8e87292b1c0)


## Ablation - SAGE

### Supplementary material 2 

To further back up our explination, we provide some experiment results from [[Understanding convolution on graphs via energies]](https://arxiv.org/pdf/2206.10991).

Although Actor is not included, the three datasets (Texas, Wisconsin, Cornell) are all heterophilic datasets.
We can observe from the results that MLP is sometimes more powerful than traditional GNNs, such as SAGE, GCN, and GAT, on heterophilc graphs.
The current GFE architecture is similar to H2GCN, which is generally better than MLP.

![GNN-Diff](https://github.com/user-attachments/assets/5c8d6e14-0066-4dd4-a96d-91cf2342cfdf)


### Supplementary material 3


![supp_sage](https://github.com/user-attachments/assets/66c6577f-c039-4f89-bb20-875c15b0eb5b)
