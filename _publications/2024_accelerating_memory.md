---
title: "Accelerating memory and I/O intensive HPC applications using hardware compression"
collection: publications
category: manuscripts
permalink: /publication/2024_accelerating_memory
excerpt: ''
date: 2024-07-07
venue: 'Journal of Parallel and Distributed Computing'
paperurl: 'https://saleh1204.github.io/files/2024_Accelerating memory and IO intensive HPC applications using hardware compression.pdf'
citation: 'Saleh AlSaleh, Muhammad E.S. Elrabaa, Aiman El-Maleh, Khaled Daud, Ayman Hroub, Muhamed Mudawar, Thierry Tonellot,Accelerating memory and I/O intensive HPC applications using hardware compression,Journal of Parallel and Distributed Computing,Volume 193,2024,104955,ISSN 0743-7315,https://doi.org/10.1016/j.jpdc.2024.104955.'
---
Recently, accelerator-based compression/decompression was proposed to hide the storage latency of high-performance computing (HPC) applications that generate/ingest large data that cannot fit a node's memory. In this work, such a scheme has been implemented using a novel FPGA-based lossy compression/decompression scheme that has very low-latency. The proposed scheme completely overlaps the movement of the application's data with its compute kernels on the CPU with minimal impact on these kernels. Experiments showed that it can yield performance levels on-par with utilizing memory-only storage buffers, even though data is actually stored on disk. Experiments also showed that compared to CPU- and GPU-based compression frameworks, it achieves better performance levels at a fraction of the power consumption.
Keywords: High performance computing; Reconfigurable computing; FPGA accelerators; Data compression; Memory intensive applications; Hardware co-design
