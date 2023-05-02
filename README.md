Download Link: https://assignmentchef.com/product/solved-cpe526-homework1-simulating-multiple-architectures
<br>
Consider a code converter circuit that converts BCD 84-2-1 to BCD 8421.

B3B2B1B0          E3E2E1E0

0 0 0 0                    0 0 0 0

0 0 0 1                    1 1 1 1

0 0 1 0                    1 1 1 1

0 0 1 1                    1 1 1 1

0 1 0 0                    0 1 0 0

0 1 0 1                    0 0 1 1

0 1 1 0                    0 0 1 0

<ul>

 <li>1 1 1              0 0 0 1</li>

 <li>0 0 0                 1 0 0 0</li>

</ul>

1 0 0 1                    0 1 1 1

1 0 1 0                    0 1 1 0

1 0 1 1                    0 1 0 1

1 1 0 0                    1 1 1 1

1 1 0 1                    1 1 1 1

1 1 1 0                    1 1 1 1

1 1 1 1                    1 0 0 1







B<sub>3</sub>B<sub>2</sub>B<sub>1</sub>B<sub>0</sub> represents the 4-bit BCD 84-2-1 input and E<sub>3</sub>E<sub>2</sub>E<sub>1</sub>E<sub>0 </sub>represents the 4-bit BCD 8421 output. For invalid BCD 84-2-1 inputs, all 1s are output as an error indication. You will find a zip file in Canvas that contains the following:

<ol>

 <li>A VHDL entity declaration for the converter.</li>

 <li>An algorithmic behavioral architectural body for the converter.</li>

 <li>A data flow behavioral architectural body for the converter.</li>

 <li>A structural architectural body for the converter.</li>

 <li>A test bench entity that ties the entity to a pulse generator that generates all possible combinations of the inputs.</li>

 <li>Three configuration files</li>

</ol>

i.Test bench for the behavioral architecture

ii.Test bench for the dataflow architecture

iii.Test bench for the structural architecture

These files are also available at ece.uah.edu/~gaede/cpe526/homework_files/hw1

Perform the following steps

<ol>

 <li>Create a project in modelsim which has all these files</li>

 <li>Compile all of the files</li>

 <li>Simulate all three configurations to verify correctness.</li>

 <li>Save your wave and list files.</li>

</ol>

Turn in your wave and list files making a zip file and then uploading it to the drop box in Canvas.