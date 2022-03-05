# QOSFChallenge
-----------------
Task 3 Solution
-----------------

------------------
1. The Main Task
------------------
There are two solutions to the problem: |1001> and |1100>:

X | O | O  
&mdash;&mdash;&mdash;&mdash;  
X | X | O   ==> |1001>  
&mdash;&mdash;&mdash;&mdash;  
O | O | X  



X | O | O  
&mdash;&mdash;&mdash;&mdash;  
X | X | X   ==> |1100>  
&mdash;&mdash;&mdash;&mdash;  
O | O | O  

I chosed the Grover Algorithm to solve the problem. The main solution is in task3/task3.ipynb. 

------------------
2. The Bonus Task
------------------

In a similar matter, solutions to the problem are: |00101>, |00110>, |01100>, |10001>, |10100>, |11000>.

I again used the Grover Algorithm to solve the problem. The bonus solution is in task3/task3_bonus.ipynb. 

References
-----------
1. https://qiskit.org/textbook/ch-algorithms/grover.html
2. https://quantumcomputing.stackexchange.com/questions/15945/implementing-grovers-oracle-with-multiple-solutions-in-qiskit
3. Oracles created with help of https://qiskit.org/documentation/apidoc/classicalfunction.html
