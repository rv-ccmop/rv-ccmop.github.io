---
layout: default
---
   
**CCMOP** is a [**runtime verification**](https://en.wikipedia.org/wiki/Runtime_verification) (RV) tool for C/C++ program. 
To our knowledge,  **CCMOP** is the **first** runtime verification tool that implements an aspect-oriented programming (AOP) based RV approach and supports the RV of general properties for C++ programs. **CCMOP** supports the RV of the properties specified in extended regular expressions (ERE) and finite state machines (FSM).

* * *

*   [**Introduction**](introduction)

*   [**Manual**](manual)

*   [**Tutorial**](tutorial)

*   [**Evaluation results and reproduction**](evaluation)


* * *

# [](#header-1)**Features**
*   `Parametric`: **CCMOP** supports the parametric RV for C/C++ programs.

*   `Applicability`: **CCMOP** can support real-world C/C++ programs.

*   `Efficient`: The runtime overhead of **CCMOP** is acceptable, and the average runtime overhead is less than 10x compared to the original C/C++ programs. See more details in [**Evaluation results and reproduction**](evaluation).

*   `Source-level Instrumentation`: **CCMOP** provides an AOP framework implemented by source-level instrumentation carried out on abstract syntax trees (ASTs).

*   `Transparent Compilation`: **CCMOP** provides a transparent compilation framework that avoids the tedious compilation configuration.

* * *
# [](#header-1)**Demonstration Vedio**

<video width="860" height="485" controls>
  <source src="resources/demo.mkv" type="video/mp4">
</video>


* * *

# [](#header-1)**Contacts**

Please feel free to contact us if you have any questions about **CCMOP**.

*   <font color="#0000FF" size="4">Yongchao Xing (xingyc0979@nudt.edu.cn)</font>

*   <font color="#0000FF" size="4"> Zhenbang Chen (zbchen@nudt.edu.cn)</font>

* * *
<span id="jump1">[1]</span>. Yongchao Xing, Zhenbang Chen, Shibo Xu, Yufeng Zhang. CCMOP: A Runtime Verification Tool for C/C++ Programs[C] International Conference on Runtime Verification. Cham: Springer Nature Switzerland, 2023: 339-350.([PDF](https://zbchen.github.io/files/rv2023.pdf))

* * *