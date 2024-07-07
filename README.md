
1 Haider 
Title: Tunable Memory Protection for Secure Neural Processing Units
Authors: Sunho Lee, Seonjin Na, Jungwoo Kim, Jongse Park, Jaehyuk Huh
Affiliation: School of Computing, KAIST
Emails: {myshlee417, sjna, jwkim, jspark}@casys.kaist.ac.kr, jhhuh@kaist.ac.kr

Abstract:
One of the key security supports for neural processing units (NPUs) is the hardware-based memory protection to provide confidentiality and integrity of NPU data. However, adopting the memory encryption and integrity protection techniques developed for CPUs do not fully utilize the NPU characteristics, incurring a significant performance degradation. To address the performance challenges, this paper proposes new improvements of memory protection for NPUs based on the unique property of NPU computation. The design first proposes a context-based memory protection which imposes the hardware memory protection only for the critical memory region of NPUs. Second, it allows adjusting the counter granularity for NPU memory to reduce the overheads of common counter-mode encryption. In addition, it exploits the read-only property of machine learning parameters, and adds a trusted communication channel between the CPU and NPU. Our evaluation with a simulated NPU shows that the performance overhead of memory protection for NPUs can be significantly reduced from the state-of-the-art CPU-oriented design, improving the performance by 13.5%.

Publication Details:
- Title: Tunable Memory Protection for Secure Neural Processing Units
- Authors: Sunho Lee, Seonjin Na, Jungwoo Kim, Jongse Park, Jaehyuk Huh
- Affiliation: School of Computing, KAIST
- Publication: 2022 IEEE 40th International Conference on Computer Design (ICCD)
- DOI: 10.1109/ICCD56317.2022.00025
- Conference: 2022 IEEE 40th International Conference on Computer Design (ICCD)
- ISBN: 978-1-6654-6186-3/22/$31.00
- Copyright: ©2022 IEEE

2. Gagandeep 
Title: A Predictive Multi-task Scheduling Algorithm For Preemptible Neural Processing Units
Author(s): M. Rhu, N. Gimelshein, J. Clemons, A. Zulfiqar, and S. W. Keckler
Affiliation(s): Department of Electrical and Computer Engineering, The University of Texas at Austin, Austin, TX, USA
Abstract: This paper presents a predictive multi-task scheduling algorithm for preemptible neural processing units (NPUs). The algorithm aims to improve the efficiency of NPUs by predicting the execution time of neural network tasks and scheduling them preemptively to maximize system throughput. The proposed algorithm considers task characteristics such as execution time, priority, and dependencies to make informed scheduling decisions. Experimental results demonstrate the effectiveness of the algorithm in improving system throughput and fairness in multi-task workloads.
Publication Details: IEEE Transactions on Parallel and Distributed Systems, vol. 32, no. 1, pp. 221-234, Jan. 2021.

3. Sunil
Title: Temperature-Aware Memory Mapping and Active Cooling of Neural Processing Units
Author(s): Vahidreza Moghaddas, Hammam Kattan, Tim B¨ucher, Mikail Yayla, Jian-Jia Chen, and Hussam Amrouch
Affiliation(s): TU Dortmund University, University of Stuttgart, Lamarr Institute for Machine Learning and Artificial Intelligence, AI Processor Design - Technical University of Munich, Munich Institute of Robotics and Machine Intelligence
Abstract: The abstract discusses the challenges posed by on-chip power densities in Neural Processing Units (NPUs) and the use of on-chip superlattice thermoelectric cooling devices to reduce memory temperatures. It also highlights the impact of memory voltage scaling on error sensitivity and leakage power consumption in NPUs.
Publication Details: The document was published in a conference or journal, as indicated by the references to other works such as [10], [11], [12], [13], [14], [15], [16] in the bibliography.

4. Mohammad Omer
Title: Eyeriss: An Energy-Efficient Reconfigurable Accelerator for Deep Convolutional Neural Networks
Author(s): Yu-Hsin Chen, Tushar Krishna, Joel S. Emer, Vivienne Sze
Affiliation(s): Department of Electrical Engineering and Computer Science, Massachusetts Institute of Technology, Cambridge, MA, USA; School of Electrical and Computer Engineering, Georgia Institute of Technology, Atlanta, GA, USA; Nvidia Corporation, Westford, MA, USA
Abstract: The abstract discusses the challenges of energy efficiency in processing Convolutional Neural Networks (CNNs) and the importance of optimizing data movement in the system. It highlights the need for a compute scheme that supports high parallelism and energy-efficient data movement, utilizing techniques like data reuse, reconfigurability, and data statistics exploitation.
Publication Details: IEEE Journal of Solid-State Circuits, Vol. 52, No. 1, January 2017

5. Prince shah 
Title: Deep Learning on Mobile Devices With Neural Processing Units
Author(s): Tianxiang Tan, Guohong Cao
Affiliation(s): Tianxiang Tan - TikTok, Mountain View, CA, USA; Guohong Cao - The Pennsylvania State University, State College, PA, USA
Abstract: This paper explores the utilization of neural processing units (NPUs) for deep learning tasks on mobile devices. The computational intensity of deep neural networks poses challenges for running them on battery-powered mobile devices. NPUs offer a solution by providing efficient processing capabilities for AI applications on smartphones and tablets, enhancing performance while conserving power.
Publication Details:
- Title: Deep Learning on Mobile Devices With Neural Processing Units
- Authors: Tianxiang Tan, Guohong Cao
- Affiliations: Tianxiang Tan - TikTok, Mountain View, CA, USA; Guohong Cao - The Pennsylvania State University, State College, PA, USA
- Published in: IEEE Computer Society
- Year: 2023
- Pages: 10
- DOI: 10.1109/INFOCOM48880.2022.9796929

6.Harmandeep kaur - 2310206
Title: WidePipe: High-Throughput Deep Learning Inference System on a Cluster of Neural Processing Units
Author(s): Lixian Ma, En Shao, Yueyuan Zhou, Guangming Tan
Affiliation(s): State Key Laboratory of Computer Architecture, Institute of Computing Technology, CAS, China, Beijing; University of Chinese Academy of Sciences, China, Beijing
Abstract: The wide application of machine learning technology has led to the emergence of ML-as-a-Service (MLaaS), a serverless computing paradigm for deploying trained models rapidly. Designing an inference system capable of handling large traffic for low latency and heterogeneous neural networks poses a challenge. In this paper, the authors propose and implement WidePipe, a high-throughput inference system that leverages reinforcement learning to co-adapt resource allocation and batch size according to device status. Experimental results on a large cluster with 1000 neural processing units demonstrate that WidePipe achieves significantly higher throughput compared to current systems, meeting service-level objectives for response time.
Publication Details: WidePipe: High-Throughput Deep Learning Inference System on a Cluster of Neural Processing Units by Lixian Ma, En Shao, Yueyuan Zhou, Guangming Tan. Published in State Key Laboratory of Computer Architecture, Institute of Computing Technology, CAS, China, Beijing, and University of Chinese Academy of Sciences, China, Beijing.
