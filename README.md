# NN Execution Time Prediction

This repository contains neural network models for predicting execution time of Spark applications, based on the paper:

**Tariq, H., & Das, O. (2023). Execution Time Prediction Model that Considers Dynamic Allocation of Spark Executors.**  
Published in: *EPEW/ASMTA 2023, Lecture Notes in Computer Science (LNCS)*.  
DOI: https://doi.org/10.1007/978-3-031-43185-2_23

---

## 📢 Citation

If you use this code or build upon it, please cite the original paper:

```
@inproceedings{tariq2023execution,
  title={Execution Time Prediction Model that Considers Dynamic Allocation of Spark Executors},
  author={Tariq, Hina and Das, Olivia},
  booktitle={Computer Performance Engineering (EPEW/ASMTA)},
  series={Lecture Notes in Computer Science},
  volume={14231},
  pages={340--352},
  year={2023},
  publisher={Springer},
  doi={10.1007/978-3-031-43185-2_23}
}
```

---

## Structure

- `km_nn_blackbox.txt`: NN model using blackbox features for KMeans.
- `km_nn_whitebox.txt`: NN model using whitebox features for KMeans.
- `query26_nn_blackbox.txt`: NN model using blackbox features for Query-26.
- `query26_nn_whitebox.txt`: NN model using whitebox features for Query-26.
- `q52_NN_black box.ipynb`: Blackbox NN model for Query-52
- `q52_NN_whitebox.ipynb`: Whitebox NN model for Query-52
- `q70_NN_black box.ipynb`: Blackbox NN model for Query-70
- `q70_NN_whitebox.ipynb`: Whitebox NN model for Query-70
- `kmeansdata.csv`: Input data for KMeans models.
- `query26_train_blackbox.csv`: Blackbox feature data for Query-26.
- `query26_train_whitebox.csv`: Whitebox feature data for Query-26.
- `query52train.csv`: Blackbox feature data for Query-52.
- `query52train1.csv`: Whitebox feature data for Query-52.
- `query70train.csv`: Blackbox feature data for Query-70.
- `query70train1.csv`: Whitebox feature data for Query-70.


## How to Run

1. Open a Jupyter notebook inside the `NN` folder.
2. Run the notebook to view predictions and plots.


