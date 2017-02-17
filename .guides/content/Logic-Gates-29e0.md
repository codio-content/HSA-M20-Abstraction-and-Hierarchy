Since computers only use binary numbers and electrical pulses to represent 0s and 1s, we need a way of making decisions based on one or more electrical signal.  Boolean logic is a form of decision making using binary numbers and an operator.

## AND
![AND Gate](LogicGates/and.png)
True only if both input values are true and false otherwise.
<table>
<tr><td>Input A</td><td>Input B</td><td>Output</td></tr>
<tr><td>0</td><td>0</td><td>0</td></tr>
<tr><td>0</td><td>1</td><td>0</td></tr>
<tr><td>1</td><td>0</td><td>0</td></tr>
<tr><td>1</td><td>1</td><td>1</td></tr>
</table>

## OR
![OR Gate](LogicGates/or.png)
True if either of the input values are true and false if they are both false.
<table>
<tr><td>Input A</td><td>Input B</td><td>Output</td></tr>
<tr><td>0</td><td>0</td><td>0</td></tr>
<tr><td>0</td><td>1</td><td>1</td></tr>
<tr><td>1</td><td>0</td><td>1</td></tr>
<tr><td>1</td><td>1</td><td>1</td></tr>
</table>

## XOR
![OR Gate](LogicGates/xor.png)
True if either of the input values is true and false if neither is true or if both are true.
<table>
<tr><td>Input A</td><td>Input B</td><td>Output</td></tr>
<tr><td>0</td><td>0</td><td>0</td></tr>
<tr><td>0</td><td>1</td><td>1</td></tr>
<tr><td>1</td><td>0</td><td>1</td></tr>
<tr><td>1</td><td>1</td><td>0</td></tr>
</table>

## NOT
![NOT Gate](LogicGates/not.png)
Negates the input to the opposite value.
<table>
<tr><td>Input</td><td>Output</td></tr>
<tr><td>0</td><td>1</td></tr>
<tr><td>1</td><td>0</td></tr>
</table>

There are also variations that combine a gate with a not, here is an example.

## NAND
![NAND Gate](LogicGates/nand.png)
The opposite of an AND gate.
<table>
<tr><td>Input A</td><td>Input B</td><td>Output</td></tr>
<tr><td>0</td><td>0</td><td>1</td></tr>
<tr><td>0</td><td>1</td><td>1</td></tr>
<tr><td>1</td><td>0</td><td>1</td></tr>
<tr><td>1</td><td>1</td><td>0</td></tr>
</table>
