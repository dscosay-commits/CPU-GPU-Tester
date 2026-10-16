# CPU-GPU-Tester
test how powerful your PC is 
# 🖥️ CPU & GPU System Tester (`sys-bench-py`)

A lightweight, no-nonsense Python utility designed to put your hardware through the wringer, check your system vitals, and audit running processes—all without needing a bloated corporate software suite.

## 🚀 Features

* **Multi-Core CPU Stress Test**: Leverages Python's `multiprocessing` to max out your cores with heavy floating-point math.
* **GPU Detection**: Auto-detects Nvidia GPUs via `nvidia-smi` (or gracefully accepts that your integrated graphics are trying their best)[cite: 1].
* **RAM & Disk Speed Profiler**: Measures total/available memory and calculates real-time disk read/write speeds[cite: 1].
* **Simulated FPS Test**: Pushes your processor with a custom matrix loop to calculate theoretical peak and average frame rates[cite: 1].
* **Temp Process Audit**: Scans active background processes to flag anything sketchy running directly out of the `Temp` folder[cite: 1].

---

## ⚠️ Warning
*Running this script may cause your laptop fan to sound like a jet engine preparing for takeoff. We are not responsible if your CPU achieves sentience out of sheer panic.*

---

## 🛠️ Requirements

Make sure you have `psutil` installed before running the script:

```bash
pip install psutil
