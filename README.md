# 🚀 CUDA Programming Course – Beginner to Pro (12 Weeks)

Welcome to the **CUDA Programming Course** designed to take you from a complete beginner to a professional GPU programmer through a hands-on, project-based learning approach.

---

## 📆 Course Timeline (12 Weeks)

Each week includes core CUDA concepts, curated notes, and a hands-on project. Build a strong foundation and optimize real-world applications step by step.

---

### ✅ Week 1: Introduction to CUDA
- **Topics:** CUDA architecture, threads, grids, blocks
- **Project:** Vector Addition (CPU vs GPU)
- 📁 `week01_intro_to_cuda/`

---

### ✅ Week 2: Memory & Kernel Fundamentals
- **Topics:** Global/shared memory, kernel syntax, memory management
- **Project:** Naive Matrix Multiplication
- 📁 `week02_memory_and_kernels/`

---

### ✅ Week 3: Profiling & Performance
- **Topics:** `nvprof`, Nsight Systems, timing kernels
- **Project:** Image Negative Converter with profiling
- 📁 `week03_profiling_and_performance/`

---

### ✅ Week 4: Shared Memory Optimization
- **Topics:** Shared memory usage, coalescing, loop unrolling
- **Project:** Optimized Matrix Multiplication
- 📁 `week04_shared_memory_optimization/`

---

### ✅ Week 5: Streams and Concurrency
- **Topics:** CUDA streams, async execution
- **Project:** Batch Image Processing Pipeline
- 📁 `week05_streams_and_concurrency/`

---

### ✅ Week 6: Unified and Pinned Memory
- **Topics:** Unified memory, pinned memory, `cudaMallocManaged`
- **Project:** Histogram Equalization using Unified Memory
- 📁 `week06_unified_memory/`

---

### ✅ Week 7: Atomics and Reductions
- **Topics:** Atomic operations, reduction patterns
- **Project:** Parallel Histogram with Atomics
- 📁 `week07_atomic_operations/`

---

### ✅ Week 8: FFT on GPU
- **Topics:** cuFFT library, FFT in audio/image
- **Project:** Real-Time Audio Spectrum Visualizer
- 📁 `week08_fft/`

---

### ✅ Week 9: High-Level CUDA with Thrust
- **Topics:** Thrust parallel algorithms (`transform`, `reduce`)
- **Project:** K-means Clustering using Thrust
- 📁 `week09_thrust/`

---

### ✅ Week 10: OpenCV + CUDA
- **Topics:** CUDA-accelerated OpenCV filters
- **Project:** Real-Time Webcam Filter
- 📁 `week10_opencv_cuda/`

---

### ✅ Week 11: Deep Learning + CUDA
- **Topics:** cuDNN, PyTorch custom CUDA ops
- **Project:** Custom Convolution Kernel for CNN Inference
- 📁 `week11_deep_learning/`

---

### 🏁 Week 12: Capstone Project
- Choose one of the following:
  - CUDA Ray Tracer
  - Real-Time Object Tracking
  - Conway’s Game of Life (Large-scale)
- 📁 `week12_capstone/`

---

## 📁 Repo Structure
```bash
CUDA-Programming-Course-12Weeks/
├── week01_intro_to_cuda/
├── week02_memory_and_kernels/
├── ...
├── week12_capstone/
├── utils/
├── requirements.md
├── environment/
└── README.md
