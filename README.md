# Latency-dataset-for-Once-For-All-Network

This repository provides a latency dataset for Mobilenetv3 blocks within the Once-for-All (OFA) Network. The latency data was obtained using the Vitis profiler, with the Ultra96-v2 FPGA board. Quantization Precision: int8

## Usage
### Latency profiling with Vitis Profiler

To run latency profiling in the FPGA board using Vitis profiler, run:

'python3 -m vaitrace_py <fpga_inference_code.py> <*.xmodel>'

### Batch Latency Profiling

To run latency profiling of 10 model simultaneously in the PEtalinux environment:
1. Grant execute permissions:

'sudo chmod +x search_folder.sh'


2. Execute the script

'./search_folder.sh'
