# 🧠 Virtual Memory Management Simulation using Page Replacement Algorithms

This project simulates **Virtual Memory Management** in an operating system using popular **page replacement algorithms** — FIFO, LRU, and Optimal.  
It helps visualize how page faults occur and how each algorithm affects memory performance.

---

## 📌 Objective
To simulate and compare the performance of different **page replacement algorithms** for virtual memory management and identify which one minimizes page faults.

---

## 🧩 Features
- Implements **FIFO**, **LRU**, and **Optimal** algorithms.
- Displays **step-by-step memory frame changes**.
- Calculates **total page faults** and **hit ratio**.
- Provides a clear performance comparison between algorithms.
- Works in both **Python script** and **Jupyter Notebook** formats.

---

## ⚙️ Technologies Used
- **Language:** Python 3  
- **Libraries:** No external libraries required (uses core Python)
- **Environment:** Jupyter Notebook / VS Code

---

## 🚀 How to Run

### 🧾 Option 1: Run in Jupyter Notebook
1. Open Jupyter Notebook  
2. Create a new notebook or upload `virtual_memory_simulation.ipynb`  
3. Run all cells  
4. View page replacement steps and fault summary

### 🧩 Option 2: Run as Python Script
```bash
python virtual_memory_simulation.py

🧠 Example Output
Pages: [7, 0, 1, 2, 0, 3, 0, 4, 2, 3, 0, 3, 2]

--- FIFO Simulation ---
FIFO -> Page: 7 | Memory: [7]
FIFO -> Page: 0 | Memory: [7, 0]
FIFO -> Page: 1 | Memory: [7, 0, 1]
...
Total Page Faults (FIFO): 9

📊 Comparison Summary
Algorithm	Total Page Faults	Efficiency
FIFO	9	⭐⭐☆☆☆
LRU	7	⭐⭐⭐⭐☆
Optimal	6	⭐⭐⭐⭐⭐

🧾 Report Summary

Title: Simulation of Virtual Memory Management using Page Replacement Algorithms

Objective: To analyze and compare FIFO, LRU, and Optimal page replacement techniques.

Result: Optimal algorithm yields the least number of page faults.

Conclusion: Efficient page replacement reduces memory load and improves system performance.

🧑‍💻 Author

Manmeet Kaur
🎓 MCA | 💻 Python & OS Enthusiast
📍https://github.com/meet-2621


