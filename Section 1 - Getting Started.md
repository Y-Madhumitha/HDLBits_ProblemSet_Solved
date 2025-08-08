## Problem Statement 1 - Build a circuit with no inputs and one output. That output should always drive 1 (or logic high).

The problem gave us a partially written Verilog module:

<img src="https://drive.google.com/uc?export=view&id=1C4KsiXbKwuPFiSa7jibyBiEAiKOlY5lf" width="450"><br>

Our task is to make the output one always have a constant value of logic high (1). To do this, we just need to add a continuous assignment under the comment line. In Verilog, a continuous assignment is written using the assign keyword, followed by the signal name, the equal sign, and the value we want to drive.

Here, the constant value is written as 1'b1. 
So, the completed code becomes: <b>assign one = 1'b1;</b>

This ensures that the output one will always be logic high throughout simulation or synthesis. Finally, the full working code looks like this:

<img src="https://drive.google.com/uc?export=view&id=1Dyh-YRr9cTLX0nRv0hnZVISYQSt9tIhY" width="450">

---

## Problem Statement 2 - Build a circuit with no inputs and one output that outputs a constant 0

The problem gave us a partially written Verilog module:

 <img src="https://drive.google.com/uc?export=view&id=1WAQoogaFQtXusW5A0dkNsF-MqCwosMX1" width="450"><br>

Our task is to make the output zero always have a constant value of logic low (0). To do this, we just need to add a continuous assignment under the comment line. In Verilog, a continuous assignment is written using the assign keyword, followed by the signal name, the equal sign, and the value we want to drive.

Here, the constant value is written as 1'b0. 
So, the completed code becomes: <b>assign zero = 1'b0;</b>

This ensures that the output zero will always be logic low throughout simulation or synthesis. Finally, the full working code looks like this:

<img src="https://drive.google.com/uc?export=view&id=1ykAGGC0OFsVYCedfE-6Hw0kXfT-jTzYp" width="450">
