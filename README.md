# Hi, I'm Usamah 👋

**Machine Learning Engineer at [Arm](https://www.arm.com)**, working on inference:
kernels, compilers, and getting models onto real hardware.

🏅 **PyTorch Ambassador**, one of 31 worldwide and the UK representative
(The Linux Foundation, 2025 to 2026).

---

### 🔧 What I work on

- **LLM and deep learning inference optimisation** on Arm CPUs and NPUs, across
  DLRM-class recommendation and Llama-class language workloads
- **Compiler and runtime work**: lowering neural network graphs through TOSA onto
  Ethos-U (via the Vela compiler), VGF, and other hardware backends
- **Compute kernels**: KleidiAI, oneDNN, FBGEMM
- **Benchmarking and profiling**: NVIDIA Nsight, PyTorch Profiler, JAX profiling tools
- **End-to-end examples**: taking real customer models all the way onto silicon,
  from requirements through to a working deployment

### 🌱 Open source

| Project | Contribution |
| --- | --- |
| [pytorch/pytorch](https://github.com/pytorch/pytorch) | int4-to-bf16 KleidiAI kernels merged into core ([PR #158250](https://github.com/pytorch/pytorch/pull/158250)): Llama-3.1-8B decode throughput 23.8 → 43.4 tokens/s on Neoverse V2, with roughly 50% less inference memory |
| [pytorch/executorch](https://github.com/pytorch/executorch) | Arm backend: migrated the pass manager to exported program, enabled TOSA and Ethos-U model flows, added a VGF image classification flow, standardised the executor runner |
| [pytorch/FBGEMM](https://github.com/pytorch/FBGEMM) | Arm kernel contributions |
| [nasa/fprime](https://github.com/nasa/fprime) | Contributions to NASA's flight software framework |

### 📌 Selected projects

- **[cnn](https://github.com/usamahz/cnn)** a convolutional neural network written
  in C from scratch
- **[autonomous-vehicles](https://github.com/usamahz/autonomous-vehicles)** computer
  vision for autonomous driving perception
- **[multi-task-loss](https://github.com/usamahz/multi-task-loss)** multi-task
  perception experiments
- **On-device object detection** an Android app running YOLO, Mask R-CNN and SSD
  on edge, optimised with TensorFlow Lite

### 🛠️ Tech

```text
Languages    Python · C++ · C · Rust · SQL
Frameworks   PyTorch · TensorFlow · JAX · ONNX · ExecuTorch
Inference    TensorRT · CUDA · cuDNN · oneDNN · KleidiAI · FBGEMM · TOSA · Ethos-U
Profiling    NVIDIA Nsight · PyTorch Profiler · Valgrind · gprof · Py-Spy
Infra        Docker · Kubernetes · GCP · AWS · MLflow · CI/CD · Linux · HPC
Robotics     ROS · Gazebo · RViz · SLAM · FreeRTOS
```

### 🧭 Background

Before Arm I was a **Robotics Software Engineer at Dyson**, where I shipped CNN
perception models onto robots operating globally, built a 360 degree vision SLAM
system fusing 26 sensors, and wrote embedded C and FreeRTOS for products. Before
that I built ML pipelines on HPC clusters for a European Space Agency and CGI UK
funded Earth observation programme, classifying satellite imagery for forest fire
detection. MSc with Distinction, University of Leicester.

### 🔗 More

Portfolio and full background at [usamahzaheer.com](https://usamahzaheer.com).

### 📫 Connect

[LinkedIn](https://linkedin.com/in/usamahzaheer) · usamahzaheer2@gmail.com · Cambridge, UK
[LinkedIn](https://linkedin.com/in/usamahzaheer) · usamahzaheer2@gmail.com · Cambridge, UK
