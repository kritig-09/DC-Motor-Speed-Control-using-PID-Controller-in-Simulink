# DC-Motor-Speed-Control-using-PID-Controller-in-Simulink
This project models DC motor speed control using a PID controller in Simulink. Performance is compared for no control, manual tuning, and optimized PID. Results demonstrate improved rise time, reduced steady-state error, and enhanced stability.

##  Overview
This project focuses on modeling and controlling the speed of a DC motor using a PID (Proportional–Integral–Derivative) controller in Simulink. A closed-loop system is designed to analyze system performance under different control strategies.

---

##  Objectives
- Model a DC motor using transfer function
- Design a closed-loop control system
- Implement PID controller in Simulink
- Compare performance for different PID configurations

---

##  System Model

The DC motor is approximated as a first-order system:

G(s) = 1 / (0.5s + 1)

---

##  PID Controller

The control signal is given by:

u(t) = Kp·e(t) + Ki∫e(t)dt + Kd(de/dt)

Where:
- Kp = Proportional gain  
- Ki = Integral gain  
- Kd = Derivative gain  

---

##  Simulation Cases

###  Case 1: Without PID Control
- Direct input to motor  
- Slow response and steady-state error  

###  Case 2: Manual PID
- Kp = 3, Ki = 2, Kd = 1  
- Improved response  

###  Case 3: Tuned PID
- Kp = 5, Ki = 3, Kd = 1  
- Fast and stable response  

---

##  Results

The comparison shows:

- Without PID → slow and inaccurate  
- Manual PID → moderate improvement  
- Tuned PID → fastest and most stable response  

---

##  Tools Used
- MATLAB  
- Simulink  

---

##  Simulink Model

![Simulink Model](model.png)

---

##  Output Graph

![Output Graph](output.png)

---

##  Project Report

You can view the detailed report here:

[Download Report](report.pdf)

---

##  Key Learnings
- Understanding of closed-loop control systems  
- Effect of Kp, Ki, Kd on system response  
- PID tuning techniques  
- Simulink modeling and analysis  

---

##  Conclusion
PID control significantly improves DC motor performance by reducing error, improving stability, and enhancing system response.

---

##  Author
Kriti Goel
