# Reinforcement Learning-Based Workflow Scheduling

This project implements intelligent workflow scheduling within a cloud computing environment using advanced Deep Reinforcement Learning (DRL). It leverages **Q-Learning** and **Deep Q-Network (DQN)** agents to dynamically allocate incoming tasks to virtual machines, optimizing performance metrics in real-time.

<img width="1408" height="768" alt="image" src="https://github.com/user-attachments/assets/44ce8d18-87bf-40cb-85a8-3fba0816b3d8" />


## 📌 Objective

To optimize task-to-VM allocation in heterogeneous cloud environments. The main goals are minimizing overall execution time (makespan), reducing operational resource cost, and improving overall energy efficiency, particularly when compared to traditional, static scheduling algorithms.

## 🛠️ Tech Stack

* **Simulation Environment:** CloudSim
* **AI Frameworks:** Python, TensorFlow / Keras
* **Data Processing:** NumPy
* **Visualization:** Matplotlib

## 🧠 Approach

1.  **Agent Design:** Developed RL agents (Q-Learning and DQN) to learn optimal VM selection policies for diverse task workloads.
2.  **State Space Definition:** Defined the environment state using real-time factors including VM utilization (CPU/Memory load), incoming task length, and current resource availability.
3.  **Reward Function:** Designed a complex reward function that balances competing objectives: execution time reduction, resource cost management, and energy consumption efficiency.
4.  **Baseline Comparison:** Evaluated performance against standard scheduling benchmarks:
    * Round Robin (RR)
    * Min-Min (Smallest task first)
    * Max-Min (Largest task first)

## 📊 Results & Performance

* **25% Improvement** in task execution efficiency.
* **20% Reduction** in overall workflow time (makespan).
* **15% Reduction** in resource cost.
* Improved system throughput and energy efficiency over all baseline algorithms.

**Key Technical Finding:** The **DQN** agent demonstrated superior scalability and robustness, outperforming tabular Q-Learning in large-scale, highly dynamic, and complex simulated environments.

## 🧪 Experimental Analysis

The project was tested extensively under the following conditions:
* **Variable Workloads:** Varying sizes, arrival rates, and task characteristics.
* **Heterogeneous Clouds:** Simulated cloud environments with diverse VM configurations (CPU speed, memory size).
* **Key Evaluated Metrics:**
    * Makespan
    * Throughput
    * Energy Consumption
    * Resource Utilization
    * Cost Efficiency

## Author
Yash Yadav
