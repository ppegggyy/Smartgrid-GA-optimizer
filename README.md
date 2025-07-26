# Smart Grid Optimization using Genetic Algorithms and Parallel Computing

This project applies a parallelized Genetic Algorithm (GA) approach to optimize energy distribution in a smart grid system, especially during disaster scenarios. It focuses on minimizing operational costs, transmission losses, and unmet demand under real-time constraints.

## 📁 Files Included

- `smartgrid_optimizer.ipynb` – Core notebook containing Serial & Parallel GA implementations
- `smartgrid_dataset_5000.csv` – Synthetic dataset used for training
- `node_info.csv`, `source_info.csv` – Additional node/source metadata

## ⚙️ Features

- Serial & Parallel GA implementation (via ThreadPoolExecutor)
- Fitness function incorporating cost, loss, and constraint penalties
- Performance comparison vs. greedy baseline
- Parameter sensitivity analysis
- Manual fitness score example

## 📊 Metrics

- Execution time: Serial vs. Parallel GA
- Fitness convergence curves
- Resource utilization logs

## 🧠 Technologies Used

- Python 3.x
- NumPy, Pandas, Matplotlib
- Scikit-learn (optional preprocessing)
- ThreadPoolExecutor (parallelism)

## 👤 Contributors

- Subrna Thakurathi (Leader)
- Prayash KC
- Biraj Prajapati
- Sagar Lama
- Swikriti Oli

## 📜 License

MIT License (or adjust as needed)
