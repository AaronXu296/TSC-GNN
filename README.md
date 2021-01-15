# TSC-GNN
Detail of experiment of TSC-GNN

## Performance comparison on averaged travel time

The following table shows the performance comparison on averaged travel time.

|         | Grid-6×6-Bi | Grid-6×6-Uni |
| ------- | ----------- | ------------ |
| TSC-GNN | 176.27      | 174.88       |
| CoLight | 180.27      | 181.75       |
| Fixedtime | 209.68      | 209.68       |
| MaxPressure | 194.96      | 186.07       |
| GCN | 272.14      | 205.40       |
| CGRL | 2884.23      | 1532.75       |
| OneModel | 242.63      | 181.75 81    |
| Individual RL | 261.60      | 314.82       |
| Neighbor RL | 248.11      | 181.75240.68       |


<img src="https://github.com/AaronXu296/TSC-GNN/blob/main/con_bi.png" width = "400" height = "200" alt="Grid-6×6-Bi" align=center /><img src="https://github.com/AaronXu296/TSC-GNN/blob/main/con_uni.png" width = "400" height = "200" alt="" align=center />

<img src="https://github.com/AaronXu296/TSC-GNN/blob/main/ablation-bi.png" width = "400" height = "200" alt="" align=center /><img src="https://github.com/AaronXu296/TSC-GNN/blob/main/ablation-uni.png" width = "400" height = "200" alt="" align=center />

Note: VGAN in the figure is the model name before TSC-GNN is renamed

