🚀 **Reinforcement Learning-Based Workflow Scheduling**

This project implements intelligent workflow scheduling in a cloud computing environment using Q-Learning and Deep Q-Network (DQN). The system is built using CloudSim for simulation and Python (TensorFlow/Keras) for reinforcement learning implementation.

📌 **Objective**

To optimize task-to-VM allocation in cloud environments by minimizing execution time, reducing resource cost, and improving overall efficiency compared to traditional scheduling algorithms.

🧠 **Approach**

a. Designed RL agents to dynamically select the best VM for incoming tasks.

b. Defined state space using VM utilization, task length, and resource availability.

c. Designed reward function based on execution time, cost, and energy efficiency.

d. Compared performance with:

   1. Round Robin
    
   2. Min-Min
    
   3.  Max-Min

📊 **Results**

⬆️ 25% improvement in task execution efficiency

⬇️ 20% reduction in overall workflow time (makespan)

⬇️ 15% reduction in resource cost

Improved throughput and energy efficiency over baseline algorithms

⚙️ **Tech Stack**

CloudSim, Python, TensorFlow / Keras, NumPy, Matplotlib

🧪 **Experimental Results**

Tested under varying workload sizes

Simulated heterogeneous cloud environments

Evaluated metrics:

      1. Makespan
      
      2. Throughput
      
      3. Energy consumption
      
      4. Resource utilization
      
      5. Cost efficiency

**DQN showed superior performance in large-scale and highly dynamic environments compared to tabular Q-Learning.**
