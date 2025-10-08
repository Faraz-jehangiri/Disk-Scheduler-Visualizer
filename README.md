# Disk Scheduler Visualizer

A **Python-based Disk Scheduling Visualizer** built using **PyQt5** and **Matplotlib**. This project demonstrates how different disk scheduling algorithms work by visualizing head movement, seek time, and algorithm comparison in an interactive and intuitive interface.

---

## 🧠 Overview

The Disk Scheduler Visualizer allows users to input a sequence of disk requests and specify the initial head position. It then simulates multiple disk scheduling algorithms and displays their performance visually through graphs and seek time calculations.

---

## ⚙️ Features

* Supports six major disk scheduling algorithms:

  * **FCFS (First Come First Serve)**
  * **SSTF (Shortest Seek Time First)**
  * **SCAN (Elevator Algorithm)**
  * **CSCAN (Circular SCAN)**
  * **LOOK**
  * **CLOOK (Circular LOOK)**
* Option to simulate a single algorithm or compare all algorithms at once
* Displays a **Matplotlib** graph representing head movement
* Calculates and displays **total seek time** for each algorithm
* User-friendly **PyQt5** GUI for smooth interaction

---

## 🧰 Technologies Used

* **Python 3**
* **PyQt5** – for building the GUI
* **Matplotlib** – for data visualization and plotting

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/Faraz-jehangiri/Disk-Scheduler-Visualizer.git
   ```
2. Navigate into the project directory:

   ```bash
   cd Disk-Scheduler-Visualizer
   ```
3. Install required dependencies:

   ```bash
   pip install pyqt5 matplotlib
   ```
4. Run the project:

   ```bash
   python main.py
   ```

---

## 📊 Output Example

* Input your disk request sequence and head position
* Choose an algorithm or “Compare All”
* View a **graphical plot** of disk head movement and the **total seek time** below it

---

## 📘 Learning Outcome

This project was developed as part of an **Operating Systems** course to better understand disk scheduling concepts and their real-time performance differences. It provides a clear visualization of how each algorithm optimizes head movement and access time.

---

## 🧑‍💻 Author

**Faraz Jehangiri**
Computer Science Student | Sir Syed University of Engineering & Technology
[LinkedIn Profile](https://linkedin.com/in/your-link-here) | [GitHub](https://github.com/Faraz-jehangiri)

---

## 🪪 License

This project is licensed under the **MIT License** – you’re free to use, modify, and distribute it with attribution.
