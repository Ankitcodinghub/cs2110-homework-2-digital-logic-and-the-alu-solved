# cs2110-homework-2-digital-logic-and-the-alu-solved
**TO GET THIS SOLUTION VISIT:** [CS2110 Homework 2-Digital Logic and the ALU Solved](https://www.ankitcodinghub.com/product/cs2110-homework-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92761&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2110 Homework 2-Digital Logic and the ALU Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
1 Overview

1.1 Purpose

You have learned about digital logic, including transistors, gates, and combinational logic. Gates (AND, OR, etc.) can be built using transistors, and Combinational Logic circuits (decoder, MUX, etc.) can be built using gates. Note how the concepts build up from transistors to gates to combinational logic. We have provided you with a tool called Circuitsim (available through Docker) that allows you to simulate building circuits, without actually using physical hardware.

The purpose of this assignment is for you to become proficient building gates out of transistors, and com- binational logic circuits out of gates, using Circuitsim. You will put these components together to create an ALU (arithmetic logic unit) circuit, which will allow you to perform several specified math and logic operations using digital logic.

1.2 Task

You will complete three Circuitsim files, and build an ALU from the ground up, starting with transistors, and then gates, and then the remainder of your combinational logic. Please read this entire document for detailed instructions, including which digital logic components you are allowed to use or prohibited from using for each part of the assignment.

This document also contains tutorials on using Circuitsim and creating subcircuits, among other topics. The steps to complete this assignment include:

1. Create the standard logic gates (NAND, NOR, NOT, AND, OR) 2. Create an 8-input multiplexer and an 8-output decoder

3. Create a 1-bit full adder

4. Create an 8-bit full adder using the 1-bit full adder

5. Use your 8-bit full adder and other components to construct an 8-bit ALU

1.3 Criteria

You will submit three Circuitsim files that you produce to Gradescope: gates.sim, plexers.sim, and alu.sim. Your circuits must work properly and produce the desired results in order to receive credit. For the ALU portion, we will give partial credit for each operation that works properly.

Be sure to avoid using components that are disallowed for each phase of this assignment.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
2 Optional Tutorial

Note: This tutorial is optional and to help you get acquainted with CircuitSim before you start this homework. If you’re comfortable with this software, feel free to skip to section 2. CircuitSim is an interactive circuit simulation package. We will be using this program for the next couple of homework assignments. This is a tutorial to help you get acquainted with the software. CircuitSim is a powerful simulation tool designed for educational use. This gives it the advantage of being a little more forgiving than some of the more commercial simulators. However, it still requires some time and effort to be able to use the program efficiently. With this in mind, we present you with the following assignment:

2.1 Part 1 — Read Resources

Read through the following resources

• CircuitSim Wires Documentation https://ra4king.github.io/CircuitSim/docs/wires/

• Tutorial 1: My First Circuit https://ra4king.github.io/CircuitSim/tutorial/tut-1-beginner 2.2 Part 2 — Complete Tutorial 2

Complete Tutorial 2 https://ra4king.github.io/CircuitSim/tutorial/tut-2-xor

Instead of saving your file as xor.sim, save your file as part1.sim. As well, make sure you label your two

inputs a and b, and your output as c, as well as rename your subcircuit to xor. 2.3 Part 3 — Complete Tutorial 3

Complete Tutorial 3 https://ra4king.github.io/CircuitSim/tutorial/tut-3-tunnels-splitters Name the subcircuit umbrella, the input in, and the output out. Save your file as part2.sim.

3 Instructions

For this assignment, you will be using CircuitSim. The version is included in the 2110 Docker container. If you are having issues with Docker, it can also be found on canvas under Files -&gt; Tools -&gt; CircuitSim.jar.

3.1 Requirements

For the first part of this assignment (the logic gates), you may use only those components found in the Wiring tab (being the input/output pins, constants, probes, clocks, splitters, tunnels, and transistors), along with any of the sub-circuits that you create or that already exist.

For the second part of this assignment (the multiplexer and decoder), you may use only those components found in the Wiring and Gates tabs along with any of the sub-circuits that you create or that already exist.

For the rest of this assignment, you may use only those components found in the Wiring and Gates tabs (except for the XOR/XNOR gates) as well as any of the sub-circuits that you create or that already exist. The term sub-circuit refers to any circuits that you have constructed in this part of the homework. If you’re unsure on how to utilize a sub-circuit, check out Section 5. For the ALU specifically, you may use the Plexer tab as well.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Use of anything not listed above will result in heavy deductions. Your need to have everything in their correctly named sub-circuit. More information on sub-circuits is given below.

Use tunnels where necessary to make your designs more readable, but do not overdo it! For gates, muxes, adders and decoders you can often get clean circuits just by placing your components well rather than using tunnels everywhere.

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
3.2 Part 1: 1-Bit Logic Gates

ALLOWED COMPONENTS: Wiring Tab and Circuits Tab

All of the circuits in this file are in the gates.sim file.

For this part of the assignment, you will create a transistor-level implementation of the NAND, NOT, NOR,

AND, and OR logic gates.

Remember for this section that you are only allowed to use the components listed in the Wiring section, along with any of the logic gates you are implementing in CircuitSim. For example, once you implement the NOT gate you are free to use that subcircuit in implementing other logic gates. Implementing the gates in the order of the subcircuit tabs can be the easiest option.

As a brief summary of the behavior of each logic gate: NAND (Inputs: A, B – Output: OUT)

</div>
</div>
<div class="layoutArea">
<div class="column">
NOR (Inputs: A, B – Output: OUT)

AND (Inputs: A, B – Output: OUT)

OR (Inputs: A, B – Output: OUT)

NOT (Input: IN – Output: OUT)

</div>
<div class="column">
A B ANANDB

001 011 101 110

A B ANORB

001 010 100 110

A B AANDB

000 010 100 111

A B AORB

000 011 101 111

A NOTA

01 10

</div>
</div>
<div class="layoutArea">
<div class="column">
Hint: Start by creating the NAND and NOT gates from transistors. Then use this gate as a subcircuit for implementing the others.

All of the logic gates must be within their named sub-circuits.

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
3.3 Part 2: Plexers

ALLOWED COMPONENTS: Wiring Tab, Circuits Tab, and Gates Tab

All of the circuits in this file are in the plexers.sim file.

The multiplexer you will be creating has 8 1-bit inputs (labeled appropriately as A, B, C, …, H), a single 3-bit selection input (SEL), and one 1-bit output (OUT). The multiplexer uses the SEL input to choose a specific input line for forwarding to the output.

</div>
</div>
<div class="layoutArea">
<div class="column">
For example:

<pre>SEL = 000 ==&gt; OUT = A
SEL = 001 ==&gt; OUT = B
SEL = 010 ==&gt; OUT = C
SEL = 011 ==&gt; OUT = D
SEL = 100 ==&gt; OUT = E
SEL = 101 ==&gt; OUT = F
SEL = 110 ==&gt; OUT = G
SEL = 111 ==&gt; OUT = H
</pre>
The decoder you will be creating has a single 3-bit selection input (SEL), and eight 1-bit outputs (labeled A, B, C, …, H). The decoder uses the SEL input to raise a specific output line, as seen below.

</div>
</div>
<div class="layoutArea">
<div class="column">
For example:

<pre>SEL = 000 ==&gt; A = 1, BCDEFGH = 0
SEL = 001 ==&gt; B = 1, ACDEFGH = 0
SEL = 010 ==&gt; C = 1, ABDEFGH = 0
SEL = 011 ==&gt; D = 1, ABCEFGH = 0
SEL = 100 ==&gt; E = 1, ABCDFGH = 0
SEL = 101 ==&gt; F = 1, ABCDEGH = 0
SEL = 110 ==&gt; G = 1, ABCDEFH = 0
SEL = 111 ==&gt; H = 1, ABCDEFG = 0
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
3.4 Part 3: Adders &amp; ALUs

ALLOWED COMPONENTS: Wiring Tab, Circuits Tab, and Gates Tab BANNED COMPONENTS: XOR Gate, XNOR Gate

NOTE: For the ALU specifically, you may use the Plexer tab as well. (Section 2.4.3) All of the circuits in this file are in the alu.sim file.

3.4.1 1-Bit Adder

The full adder has three 1-bit inputs (A, B, and CIN), and two 1-bit outputs (SUM and COUT). The full adder adds A + B + CIN and places the sum in SUM and the carry-out in COUT.

For example:

<pre>A = 0, B = 1, CIN = 0 ==&gt; SUM = 1, COUT = 0
A = 1, B = 0, CIN = 1 ==&gt; SUM = 0, COUT = 1
A = 1, B = 1, CIN = 1 ==&gt; SUM = 1, COUT = 1
</pre>
Hint: Making a truth table of the inputs will help you.

3.4.2 8-Bit Adder

For this part of the assignment, you will daisy-chain 8 of your 1-bit full adders together in order to make an 8-bit full adder.

This circuit should have two 8-bit inputs (A and B) for the numbers you’re adding, and one 1-bit input for CIN. The reason for the CIN has to do with using the adder for purposes other than adding the two inputs.

There should be one 8-bit output for SUM and one 1-bit output for COUT.

</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
3.4.3 8-Bit ALU

ALLOWED COMPONENTS: Wiring Tab, Ciruits Tab, Gates Tab, and Plexer Tab

BANNED COMPONENTS: XOR Gate, XNOR Gate (see note regarding the ExclusiveNOR oper- ation)

You will create an 8-bit ALU with the following operations, using the 8-bit full adder you created in for 2.4.2:

</div>
</div>
<div class="layoutArea">
<div class="column">
000. Addition

001. Subtraction 010. ExclusiveNOR 011. isEqual

100. isMultipleOf8 101. MultiplyBy15 110. DivideBy2 111. AbsoluteValue

</div>
<div class="column">
[A+B] [A-B]

[A xnor B] [A==B] [A%8==0] [15*A] [A//2] [abs(A)]

</div>
</div>
<div class="layoutArea">
<div class="column">
Notice that MultiplyBy15, isMultipleOf8, DivideBy2, and AbsoluteValue only operate on the A input. They should NOT rely on B being a particular value.

For this ALU, we will be using a multiplexer. This ALU has two 8-bit inputs for A and B and one 3-bit input for OP, the op-code for the operation in the list above. It has one 8-bit output named OUT.

For the ExclusiveNOR operation, you are NOT allowed to use the exclusive OR or the exclusive NOR gate provided on CircuitSim. NOTE: this rule recursively extends to any component that your ALU uses, so you will need to ensure that no other part of the ALU uses the XOR or XNOR gates. This includes subcircuits like the 1-bit adder.

For the DivideBy2 operation, we ask you to consider this as floor division as shown in the // simply meaning to round down if the division would result in a fraction. For example: if the input is 5, your output should be 2.

For the MultiplyBy15 operation, although there is potential for overflow, we don’t need to worry about it in this homework.

For isMultipleOf8 and isEqual operations, return 00000001 if the condition is true, and 00000000 other- wise.

The provided autograder will check the op-codes according to the order listed above (Addition (000), Sub- traction (001), etc.) and thus it is important that the operations are in this exact order.

Hint: ExclusiveNOR Truth Table (Inputs: A, B – Output: OUT)

A B AXNORB

001 010 100 111

</div>
</div>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
3.5 Running the Autograder

To run the autograder, type the following command into your terminal while in the homework 2 directory:

<pre>        java -jar hw02-tester.jar
</pre>
Make sure all the tests have been passed. Keep in mind that even if you get full credit from the autograder, we reserve the right to test for more cases.

4 Deliverables

Please upload the following files onto the assignment on Gradescope:

</div>
</div>
<div class="layoutArea">
<div class="column">
1. gates.sim 2. plexers.sim 3. alu.sim

</div>
<div class="column">
<pre>NOT, NAND, NOR, AND, OR
Decoder, MUX
1-Bit Adder, 8-Bit Adder, 8-Bit ALU
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Be sure to check your score to see if you submitted the right files, as well as your email frequently until the due date of the assignment for any potential updates.

No partial credit will be given for incorrect outputs for Part 1, Part 2, and the adder-portion of Part 3. For the ALU, partial credit will be awarded on a per-operation basis, wherein each operation must perform successfully to be awarded credit. Because of this, we urge you to check your score before the due date.

5 Sub-Circuit Tutorial

As you build circuits that are more and more sophisticated, you will want to build smaller circuits that you can use multiple times within larger circuits. Sub-circuits behave like classes in Object-Oriented languages. Any changes made in the design of a sub-circuit are automatically reflected wherever it is used. The di- rection of the IO pins in the sub-circuit correspond to their locations on the representation of the sub-circuit.

To create a sub-circuit:

1. Go to the “Circuits” menu and choose “New circuit”

2. Name your circuit by right-clicking on the “New circuit” item and selecting “Rename”

</div>
</div>
<div class="layoutArea">
<div class="column">
10

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
11

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
To use a sub-circuit:

1. Click the “Circuits” tab next to the “Misc” tab

</div>
</div>
<div class="layoutArea">
<div class="column">
2. Select the circuit you wish to use and place it in your design

</div>
</div>
<div class="layoutArea">
<div class="column">
12

</div>
</div>
</div>
