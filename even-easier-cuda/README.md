An Even Easier Introduction to CUDA - Accompanying Notebook
Open In Colab

This notebook accompanies Mark Harris's popular blog post An Even Easier Introduction to CUDA and can be run directly in Google Colaboratory.

Learning Objectives
In this notebook you will learn the basics of writing massively parallel CUDA kernels to run on NVIDIA GPUs. By the time you complete it you will be able to:

Launch massively parallel CUDA Kernels on an NVIDIA GPU
Organize parallel thread execution for massive dataset sizes
Manage memory between the CPU and GPU
Profile your CUDA code to observe performance gains
Prerequisites
This notebook does not require you to write novel code, but to best understand its details, you should already have familiarity with:

Writing, compiling and running C or C++ code
Followup Materials
If you enjoyed this notebook and want to learn more, the NVIDIA DLI offers several in depth CUDA Programming courses.

For those of you just starting out, please consider Fundamentals of Accelerated Computing with CUDA C/C++ which provides dedicated GPU resources, a more sophisticated programming environment, use of the NVIDIA Nsight Systems™ visual profiler, dozens of interactive exercises, detailed presentations, over 8 hours of material, and the ability to earn a DLI Certificate of Competency.

Similarly, for Python programmers, please consider Fundamentals of Accelerated Computing with CUDA Python.

For more intermediate and advance CUDA programming materials, please check out the Accelerated Computing section of the NVIDIA DLI self-paced catalog.
