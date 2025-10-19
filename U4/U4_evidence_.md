# 🧩 Unit 4: Risk Identification and Modelling – Case Study  

## 🎓 Seminar Title  
**Risk Identification and Modelling – Case Study**

---

## 📚 Reference Paper  
Jbair, M., Al-Awadi, A., Al-Hammadi, F. and Al-Nashif, Y. (2022) *Threat Modelling in Cyber-Physical Energy Systems*, *International Journal of Critical Infrastructure Protection*, 39, pp. 1–14.

---

## 🧠 Workshop Activity – Questions and Answers  

### **Q1.** What are the key elements and interdependencies in a cyber-physical system (CPS) that must be captured in a comprehensive threat model, and why are they critical for accurate risk analysis?

According to *Jbair et al. (2022)*, effective CPS threat modelling must capture **physical components**, **communication channels**, **control logic**, and **human–machine interactions**. These elements represent the layered architecture of energy systems where digital operations directly influence physical processes.  

Interdependencies — such as links between sensors, controllers, and actuators — are vital because they show how a single point of failure can cascade through the entire system.  
For example, if a compromised sensor feeds manipulated data into a SCADA subsystem, both operational safety and power stability could be jeopardised.  

Recognising these dependencies helps analysts predict not just isolated incidents but also **propagating attack chains**, a core concept in modern cyber-physical risk assessment (*Humayed et al., 2017*).

---

### **Q2.** How can threat modelling help identify attack entry points and system vulnerabilities in cyber-physical energy systems, and what are the challenges in doing so effectively?

Threat modelling provides a structured method to map **entry points** such as communication interfaces, control ports, wireless links, and third-party integrations.  
Techniques like **Data Flow Diagrams (DFDs)** and **STRIDE** enable analysts to visualise how data moves across systems and where potential breaches could occur (*Microsoft, 2023*).  

In CPS, this reveals how attackers might exploit insecure protocols (e.g., Modbus TCP, DNP3) to manipulate control logic or inject false data.  
Challenges include system complexity, legacy components, and real-time constraints where patching or downtime may not be feasible (*Knowles et al., 2015*).  

The increased interconnectivity between IT and operational systems further expands the attack surface, demanding collaboration across **engineering and cybersecurity disciplines**.

---

### **Q3.** In the context of CPS threat modelling, how can scenario-specific metrics and risk assessment methodologies be used to prioritise vulnerabilities and guide the development of targeted security countermeasures?

Scenario-specific metrics enable quantification of risk through impact and likelihood scores, tailored to contextual factors such as **energy distribution disruption**, **fault propagation rate**, or **detection latency**.  

Frameworks like **NIST SP 800-30** and **ISO/IEC 27005** can be adapted for CPS by integrating these parameters (*NIST, 2012; ISO, 2018*).  
Assigning weights to such metrics helps prioritise high-impact vulnerabilities — for example, an unauthenticated control interface poses a greater operational risk than a passive monitoring node.  

*Jbair et al. (2022)* emphasise that these structured assessments not only enhance technical precision but also enable **efficient resource allocation** and design of **targeted mitigation strategies** such as redundant control paths, anomaly detection, or automated isolation protocols.

---

## 💬 Reflection  

This case study reinforced the importance of **holistic threat modelling** in cyber-physical environments.  
I learned that genuine resilience depends not only on defending digital assets but also on understanding **physical interconnections** and **operational dependencies**.  

By analysing CPS systems, I recognised that cybersecurity must integrate **engineering perspectives**—an insight I can directly apply within my workplace to improve protection of critical infrastructure.  

This exercise enhanced my **analytical thinking** and ability to connect **quantitative metrics** with **real-world operational outcomes**, bridging theory and practice.

---

## 🔖 References  

- Humayed, A., Lin, J., Li, F. and Luo, B. (2017) ‘Cyber-physical systems security — A survey’, *IEEE Internet of Things Journal*, 4(6), pp. 1802–1831.  
- ISO (2018) *ISO/IEC 27005:2018 — Information Security Risk Management.* Geneva: International Organization for Standardization.  
- Jbair, M., Al-Awadi, A., Al-Hammadi, F. and Al-Nashif, Y. (2022) ‘Threat modelling in cyber-physical energy systems: A risk-driven perspective’, *International Journal of Critical Infrastructure Protection*, 39, pp. 1–14.  
- Knowles, W., Prince, D., Hutchison, D., Disso, J. and Jones, K. (2015) ‘A survey of cyber security management in industrial control systems’, *International Journal of Critical Infrastructure Protection*, 9, pp. 52–80.  
- Microsoft (2023) *STRIDE Threat Modelling Framework.* Redmond: Microsoft Security Docs.  
- NIST (2012) *SP 800-30 Rev. 1 — Guide for Conducting Risk Assessments.* Gaithersburg, MD: U.S. Department of Commerce.  

---
