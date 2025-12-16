---
title: "Exploring Efficient FPGA Acceleration of High-Order 3D Iterative Stencil Loops on Large Data Grids"
collection: publications
category: manuscripts
permalink: /publication/2025_fpga_3d_stencil
excerpt: ''
date: 2024-12-11
venue: 'Arabian Journal for Science and Engineering'
paperurl: 'https://saleh1204.github.io/files/2025_Exploring_Efficient_FPGA_Acceleration_of_High-Order_3D_Iterative_Stencil_Loops_on_Large_Data_Grids.pdf'
citation: 'Ibrahim, A., Elrabaa, M.E.S., Alsaleh, S. et al. Exploring Efficient FPGA Acceleration of High-Order 3D Iterative Stencil Loops on Large Data Grids. Arab J Sci Eng (2025). https://doi-org.ezaccess.libraries.psu.edu/10.1007/s13369-025-10919-y'
---
An efficient methodology for FPGA acceleration of high-order 3D iterative stencil loops over large 3D-grids was developed. Spatial (tiling) and temporal (combined iterations) blocking are used to circumvent the FPGAs’ limitations and maximize throughput. Implemented as a fully asynchronous SW-HW pipeline, it can compute high-order stencils on 3D grid without any limitations on the grid size or the number of iterations. An 8th-order, 25-point 3D stencil was used to demonstrate the methodology and possible optimizations of performance, resource utilization, and power efficiency. Results show that throughput is only limited by the FPGA off-chip memory bandwidth. Comparisons with published results for the same stencil showed that the developed methodology can achieve a throughput equivalent to ~ 43-Haswell cores (22 nm technology) or ~ 13 Milan-x cores (7 nm technology) running at 2.3 and 2.45 GHz, respectively. Compared to an A100 NVIDIA GPU implementation of the same stencil, it achieved ~ 41% better power efficiency (Watts per GB/s). The methodology was extended to support multiple FPGAs. With two FPGA boards, the total latency was reduced by ~ 27%.
