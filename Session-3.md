# Architecture Of Linux OS-
Linux architecture consist of inner most Hardware layer, kernel, shell, and 
outer application layer.


![image](https://github.com/vishakhadhonde9/Linux-/assets/97825776/62c5a20a-77ad-4d78-a9a2-d91f573ca34b)



## 1) Application Layer:
- Users interact with the system through varies applications such as office, games, etc.
- These applications run in outer layer of architecture.

## 2) Shell:
- Shell provides environment to run any application.
- It provides interface to the user to interact with hardware.
- Shell act as command interpreter.
- It convert high level language into computer level language.
* Shell can be of:
  i) Graphical Shell
  ii) Command line Shell
- Examples: k shell, bash shell, sh shell, etc.

## 3) Kernel:
- Kernel is core component of Linux architecture.
- Manages hardwares (CPU, Memory and devices).
- It controls process management, memory management and device management.
- It tracks all active processes running on systems.
- In Linux, we use Monolithic kernel.

## 4) Hardware: 
All the hardware components such as motherboard, CPU, hard disk, etc. are comes under 
this layer. 


# Monolithic kernel vs microlithic kernel-

## Monolithic Kernel-
- It manages system's resources between system applications and system hardware.
- which are required for system applications are already installed.
- Large in size and provides high execution speed.
- All prerequisites are already installed required to install new packeges.
- It offers memory management, file management and process scheduling.

## Microservices-
- In microlithic kernel, only required dependencies are pre-installed.
- lightweight in size
- Application softwares running on microlithic architecture have ability to install its
own dependencies by itself.
- It is slow in execution.





