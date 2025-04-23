# Distributed_Compute_Net
ClientServer/  ArraySum/  MatMul/  Laplace/     :  A project that combines a client-server file transfer system with serial, OpenMP, and distributed implementations for solving array summation, matrix multiplication, and 2D Laplace equation problems.

# ComputeNet
ComputeNet is a comprehensive project that combines a client-server file transfer system with serial, OpenMP, and distributed implementations for solving array summation, matrix multiplication, and 2D Laplace equation problems. The project is designed to highlight performance scaling, communication, and efficient resource utilization across machines.
***

**1. Client-Server File Sharing**  
  
_ A simple yet effective TCP-based client-server model.

_ The server maintains a list of files (e.g., .pdf, .docx, .txt) available for download.

_ The client requests and downloads files from the server.

_ Downloaded files are verified by opening them after the transfer.
***

**2. Scientific Computation Modules**  
<br>
Each computational module supports:

_ Serial implementation – For correctness verification.

_ Parallel implementation (OpenMP) – For performance scaling on a single machine.

_ Distributed implementation (Sockets + optional OpenMP) – For computation across multiple machines.  
<br>

**A. Array Summation**  
<br>
_ Sums a large 1D array using the three modes.

_ Used to benchmark the overhead and speedup in distributed environments.  
<br>

**B. Matrix Multiplication**  
<br>
_ Performs large matrix multiplication.

_ 2D contour plots included to visualize correctness and computational patterns.

_ Shows how distributed systems can handle data beyond single-machine memory limits.  
<br>

**C. 2D Laplace Equation Solver**  
<br>
_ Solves Laplace’s equation on a grid with Dirichlet boundary conditions:

_ Top = 5V, Bottom = -5V, Left & Right = 0V.

_ Simulates the electric potential inside a capacitor.

_ Includes contour plots to visualize potential distribution.



