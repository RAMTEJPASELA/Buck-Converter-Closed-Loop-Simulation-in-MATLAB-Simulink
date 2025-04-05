# ⚡ Operation and Control of a DC-DC Buck Converter Using PID-Based Closed-Loop Regulation in MATLAB Simulink

## 📌 Introduction  

Building upon the previously developed [**open-loop buck converter model**](https://github.com/RAMTEJPASELA/Buck-Converter-Open-Loop-Simulation-in-MATLAB-Simulink/blob/main/README.md), this project focuses on the implementation of a **closed-loop control system using a PID (Proportional–Integral–Derivative) controller**. While the open-loop system successfully demonstrated key theoretical concepts such as **inductor volt-second balance**, **capacitor charge balance**, and **small-ripple approximation**, it lacked the ability to regulate output voltage under dynamic conditions such as **load fluctuations** (or) **changes in input supply**.

In practical applications especially in **electric vehicles**, **aerospace systems**, and **renewable energy technologies**—maintaining a **stable output voltage** despite external disturbances is critical. Open-loop operation lacks in such cases because it provides **no feedback mechanism** to correct deviations. This motivates the need for a **closed-loop control system**, where real-time output voltage is monitored and compared against a reference. The **PID controller** adjusts the duty cycle accordingly to minimize the error, ensuring accurate and robust voltage regulation.

## 🎯 Objectives  

The primary objective of this project is to **design and implement a closed-loop DC-DC buck converter using a PID controller in MATLAB Simulink**. This enhancement builds upon the previously modeled open-loop system and introduces dynamic voltage regulation through feedback control. The specific goals include:

✅ **Integrate a PID controller** into the buck converter to achieve real-time regulation of the output voltage.  
✅ **Maintain output voltage stability** in the presence of input voltage disturbances and varying load conditions.  
✅ **Demonstrate the real-world relevance** of closed-loop control for applications in electric vehicles, aerospace, and renewable energy technologies.  
✅ **Obtain optimal PID controller parameters** using the **transfer function of the buck converter**, ensuring a balance between fast response and minimal steady-state error.


