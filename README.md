## Neural Network Acceleration Study Season #3
This is a repository of the study "neural network acceleration". The goal of this study is to understand the acceleration of nerual networks on various devices. The topic of acceleration includes neural acceleration (such as inference on `CPU`, `GPU`, `NPU`, `ASIC`, `FPGA`,`NDP`), neural accelerator (`RTL`, `HLS`), and designing lightweight neural network (`Quantization`, `Pruning`, etc).Our materials are open to this github and youtube. This study is supported by Facebook community, "AI Robitcs Korea".

#### CPU/GPU, NPU, and distributed computing
- Fast acceleration of inference/training on general processor (CPU/GPU)
- Distributed computing for large training system
- Heterogeneous system architecture (HSA) device

#### ASIC and FPGA
- Low-power inference acceleration using RTL/HLS design
- High computing performance interfence/training accelerator

#### Lightweight neural network
- Quantization (Fixed-point, LUT, log, etc)
- Pruning (Fine/Course-grain, Channel-wise, etc)


## Paper List (16)
### CPU/GPU/NPU/DSP based Acceleration (3)
	1. Efficient Execution of Quantized Deep Learning Models: A Compiler Approach, arxiv, 2020
	2. AMC: AutoML for Model Compression and Acceleration on Mobile Devices, ECCV, 2018
	3. Integer Quantization for Deep Learning Inference: Principles and Empirical Evaluation, arxiv, 2020
	
### Dedicated neural network accelerator (3)
	1. Integrating NVIDIA Deep Learning Accelerator (NVDLA) with RISC-V SoC on FireSim, EMC2, 2019
	2. ACG-Engine: An Inference Acelerator for Content Generative Neural Networks, ICCAD, 2020
	3. Timeloop: A Systematic Approach to DNN Accelerator Evaluation, ISPASS, 2019


### Designing lightweight neural network (5)
	1. THE LOTTERY TICKET HYPOTHESIS: FINDING SPARSE, TRAINABLE NEURAL NETWORKS, ICLR, 2019
	2. Quantizing deep convolutional networks for efficient inference: A whitepaper, GOOGLE, 2018
	3. Learned Step Size Quantization, ICLR, 2020
	4. HAQ: Hardware-Aware Automated Quantization with Mixed Precision, CVPR, 2019
	5. AUTOQ: AUTOMATED KERNEL-WISE NEURAL NETWORK QUANTIZATION, ICLR, 2020
	
	
## Presentation with Video
### Week1 (September 09, 2020)
**THE LOTTERY TICKET HYPOTHESIS: FINDING SPARSE, TRAINABLE NEURAL NETWORKS**
	Presenter: Jeongah-Shin (jeongah.arie@gmail.com)
	PPT: 
	Video: 

**Integrating NVIDIA Deep Learning Accelerator (NVDLA) with RISC-V SoC on FireSim**

	Presenter: Constant Park (sonicstage12@naver.com)
	PPT: 
	Video: 

## Contributors
**Main Contributor**: Constant Park (sonicstage12@naver.com)

**Presenters**: Constant Park (sonicstage12@naver.com), Jeongah-Shin (jeongah.arie@gmail.com), 김용우 (yongwoo.kim@smu.ac.kr), 강준구 (gjk6626@gmail.com), 이제민 (leejaymin@etri.re.kr), 금나연 (nayounkeum@gmail.com), 김영범 (eddy979793@gmail.com)
