---
title: "File Fragment Type Classification Using Light-Weight Convolutional Neural Networks"
collection: publications
category: conferences
permalink: /publication/2024_file_fragment
excerpt: ''
date: 2024-10-24
venue: 'IEEE Access'
paperurl: 'https://saleh1204.github.io/files/2024_File_Fragment_Type_Classification_using_Light-Weight_Convolutional_Neural_Networks.pdf'
citation: 'M. Felemban, M. Ghaleb, K. Saaim, S. AlSaleh and A. Almulhem, "File Fragment Type Classification Using Light-Weight Convolutional Neural Networks," in IEEE Access, vol. 12, pp. 157179-157191, 2024, doi: 10.1109/ACCESS.2024.3486180'
---
In digital forensics, file carving is used to extract files without relying on the underlying file system metadata. This process can be challenging if the file is fragmented. Therefore, it is important first to identify the type of file fragment. There exist several techniques to identify the type of file fragments without relying on metadata, for example, using headers and footers to identify the fragment type. Recently, convolutional neural network (CNN) models have been used to build classification models to achieve this task. Existing models for file fragment type classification often require significant computational resources due to their large number of parameters, leading to slower inference times and higher memory consumption. To address these challenges, we propose light-weight file fragment type classification models based on separable CNNs that maintain comparable accuracy while reducing computational demands. Our proposed light-weight file fragment type classification model leverages depthwise separable convolutions to improve the efficiency of feature extraction while reducing computational overhead. This approach leads to improved classification performance by focusing on the most relevant features within file fragments, achieving comparable accuracy to state-of-the-art models with significantly fewer parameters. The evaluation results demonstrate the model’s effectiveness, with a 79% accuracy on the FFT-75 dataset using nearly 100K parameters and 164M FLOPs —representing a 4x reduction in model size and a 6x improvement in speed over the best-performing existing classifier. Our results demonstrate that these light-weight models are effective for real-time digital forensic applications where computational efficiency is critical.
