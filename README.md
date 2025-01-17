

---

# 4-Bit Arithmetic and Logic Unit (ALU) Simulation using NI Multisim  

### **Overview**  
This project showcases a functional **4-bit Arithmetic and Logic Unit (ALU)** designed and simulated using **NI Multisim**. The ALU performs key arithmetic and logic operations, making it a crucial component for digital systems. Its modular and interactive design highlights practical digital electronics concepts in an engaging way.  

### **Key Features**  
1. **Arithmetic Operations**:  
   - **Addition and Subtraction** of two 4-bit binary numbers.  
   - The **Mode Switch** (`Mode`):  
     - `Mode = 0`: Executes **Addition**.  
     - `Mode = 1`: Executes **Subtraction** (using 2's complement).  

2. **Logic Operations**:  
   - Performs **AND**, **OR**, and **XOR** operations on the same two 4-bit binary inputs.  
   - Operations are selected using **2 Multiplexer Selection Lines** (`sel1`, `sel2`).  

3. **User-Friendly Visual Output**:  
   - Results are projected using **indicator bulbs**, providing real-time, intuitive visualization of the operations.  

4. **Interactive and Modular Design**:  
   - Each operation is modularly implemented, allowing for easy debugging and scalability.  
   - The combination of multiplexers and logical gates ensures a robust implementation.  

### **Simulation Process**  
Follow these steps to simulate the project and interact with the ALU:  
1. **Load the Circuit**: Open the design file in **NI Multisim**.  
2. **Input Binary Numbers**:  
   - Use the switches provided to input two 4-bit binary numbers.  
   - For each number, toggle the switches to `1` (high) or `0` (low) to represent the desired binary value.  
3. **Select an Operation**:  
   - Use the **Mode switch** to toggle between Addition (`Mode = 0`) and Subtraction (`Mode = 1`).  
   - Use the **Selection Lines (`sel1`, `sel2`)** to choose the desired logical operation:  
     - `sel1 = 0`, `sel2 = 0`: Perform **AND**.  
     - `sel1 = 0`, `sel2 = 1`: Perform **OR**.  
     - `sel1 = 1`, `sel2 = 0`: Perform **XOR**.  
4. **View Outputs**:  
   - The **Arithmetic Output** (Sum or Difference) and the selected **Logic Operation Output** will be displayed using the indicator bulbs.  
   - Carry, overflow, or complement-related values (if any) will also be shown.  
5. **Experiment and Verify**:  
   - Test various combinations of inputs and control signals to observe the ALU's behavior.  
   - Use the real-time bulb indicators to understand the operation results instantly.  

### **Project Insights**  
- The **Arithmetic Logic Unit (ALU)** is the heart of many computational devices, making this project an excellent way to showcase core digital electronics concepts.  
- **Real-World Relevance**: The integration of arithmetic and logical operations mirrors the operations performed in CPUs.  
- **Hands-On Experience**: The simulation offers a practical understanding of concepts like **MUX-based control**, **logic gate operations**, and **binary arithmetic**.  

### **Why This Project Stands Out**  
- This project demonstrates **practical problem-solving skills** by combining digital electronics and simulation tools.  
- The interactive design and clear visual output make the ALU not just functional but also intuitive and user-friendly.  
- Ideal for interviews, technical showcases, or academic presentations, this project reflects a deep understanding of digital system design.  

---

