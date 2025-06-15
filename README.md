# CUDA-learn
CUDA-Programming-Course-12Weeks/
│
├── README.md
├── requirements.md               # Tools & setup instructions
├── environment/                  # Dockerfile or Conda env setup (optional)
│
├── week01_intro_to_cuda/
│   ├── vector_add.cu
│   ├── README.md
│   └── notes.md
│
├── week02_memory_and_kernels/
│   ├── matrix_multiplication_naive.cu
│   ├── memory_allocation.cu
│   ├── README.md
│   └── notes.md
│
├── week03_profiling_and_performance/
│   ├── image_negative.cu
│   ├── profiling_results.txt
│   ├── README.md
│   └── notes.md
│
├── week04_shared_memory_optimization/
│   ├── matrix_multiplication_optimized.cu
│   ├── README.md
│   └── notes.md
│
├── week05_streams_and_concurrency/
│   ├── batch_image_processing.cu
│   ├── images/                   # Sample input/output images
│   ├── README.md
│   └── notes.md
│
├── week06_unified_memory/
│   ├── histogram_equalization.cu
│   ├── README.md
│   └── notes.md
│
├── week07_atomic_operations/
│   ├── parallel_histogram.cu
│   ├── README.md
│   └── notes.md
│
├── week08_fft/
│   ├── audio_fft_visualizer.cu
│   ├── README.md
│   └── notes.md
│
├── week09_thrust/
│   ├── thrust_kmeans.cu
│   ├── README.md
│   └── notes.md
│
├── week10_opencv_cuda/
│   ├── video_filter.cu
│   ├── webcam_filter.cpp
│   ├── README.md
│   └── notes.md
│
├── week11_deep_learning/
│   ├── custom_cuda_layer.cu
│   ├── pytorch_module/
│   │   ├── custom_layer.cpp
│   │   └── bindings.py
│   ├── README.md
│   └── notes.md
│
├── week12_capstone/
│   ├── README.md
│   ├── performance_report.md
│   ├── ray_tracer/
│   ├── object_tracker/
│   └── conway_simulation/
│
└── utils/
    ├── timers.h
    ├── profiler_helpers.cu
    └── README.md
