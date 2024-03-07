## 1. FUNCTIONAL SIMULATION

### 1.1 About iverilog and gtkwave
- Icarus Verilog is an implementation of the Verilog hardware description language.
- GTKWave is a fully featured GTK+ v1. 2 based wave viewer for Unix and Win32 which reads Ver Structural Verilog Compiler generated AET files as well as standard Verilog VCD/EVCD files and allows their viewing.
  
### 1.2 Installing iverilog and gtkwave

- **For Ubuntu**

 Open your terminal and type the following to install iverilog and GTKWave
 ```
 $   sudo apt get update
 $   sudo apt get install iverilog gtkwave
 ```

![310466210-817a18ee-9914-4c1f-8700-d14f62b4bcc3](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/96ec3449-b87f-4e17-94c1-aefcb5f18fa3)

- **To clone the repository and download the netlist files for simulation, enter the following commands in your terminal.**

 ```
 $ git clone https://github.com/Animeshhhh15/VSDSQUADRON-MINI-.git
 $ cd 
```

![310466383-6ede157a-d64b-4a23-b87d-1cb4efc3f139](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/92aee8e2-f6a7-40a9-8ad8-2050b43caf43)


- **To simulate and run the Verilog code, enter the following commands in your terminal.**

```
$ iverilog -o hello hello.v hello_tb.v
$ ./hello
```
![WhatsApp Image 2024-03-06 at 4 05 59 PM](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/3f7c9757-ea44-4196-9444-e7ab64cd46cd)





- **To see the output waveform in gtkwave, enter the following commands in your terminal.**

`$ gtkwave hello.vcd`

![310466967-ca8c05ff-d87b-4688-b930-af33990e8631](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/96ca6529-7cf8-496a-9766-84746c4e7d03)


### 1.3 The output waveform

![310527452-806fe8ea-4c44-42b3-b028-0f9b32e10f1c](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/e6580c42-f0ac-4b8a-bff2-d5c3aafc5f03)


![310528512-92e741a5-0c62-44a0-9809-61e44b5e6184](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/d189a333-546f-4699-8ed7-cfca9df3f8d6)



