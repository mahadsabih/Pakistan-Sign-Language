# Pakistan-Sign-Language
## Introduction
This project focuses on building a real-time Pakistan Sign Language (PSL) interpretation system using Field-Programmable Gate Arrays (FPGAs). The project aims to bridge the communication gap faced by individuals with hearing loss in Pakistan, where there is a shortage of human interpreters. By utilizing the parallel processing power of FPGAs, the system provides a cost-effective and efficient solution for interpreting sign language in real-time, especially in professional settings like education and healthcare.

## Technologies
This project incorporates a variety of technologies to ensure efficient real-time sign language interpretation:

YOLOv5: A deep learning model for detecting signs and gestures.
PyTorch: for training and testing YOLOv5
Conda: For environment management
Python: For scripting and controlling the FPGA and YOLOv5 model.
OpenCV: For image processing.
FPGA (Field-Programmable Gate Array): Hardware acceleration for real-time processing.
Verilog/VHDL: For FPGA programming.
ONNX (Open Neural Network Exchange): For deploying the YOLOv5 model on the FPGA.
## Results

The real-time Pakistan Sign Language (PSL) interpretation system was tested using a variety of sign gestures captured through a camera connected to the FPGA. Below are the key results:

- **Real-Time Sign Detection**: The system successfully detects PSL signs with an average accuracy of **XX%** and a processing latency of **YY milliseconds**.
- **Efficient Hardware Utilization**: The FPGA-based implementation showed a significant improvement in processing speed compared to traditional CPU/GPU setups, with a **Z% reduction** in inference time.
- **Scalability**: The system is capable of scaling to multiple gestures and signs, providing flexibility for real-world applications.
- **Visualization**: Detected signs are rendered on screen in real-time, with corresponding translations displayed as text in Urdu and English.




