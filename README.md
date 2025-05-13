# cs39001-assignment-7-solved
**TO GET THIS SOLUTION VISIT:** [CS39001 Assignment 7 Solved](https://www.ankitcodinghub.com/product/cs39001-assignment-7-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92938&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS39001 Assignment 7 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
Class

Arithmetic Logic

Shift

Memory

Branch

</div>
<div class="column">
Instruction

Add

Comp

Add immediate

Complement Immediate

AND

XOR

Shift left logical

Shift right logical

Shift left logical variable

Shift right logical

Shift right arithmetic

Shift right arithmetic variable Load Word

Store Word

Unconditional branch

Branch Register

Branch on less than 0

Branch on flag zero

Branch on flag not zero Branch and link

Branch on Carry

Branch on No Carry

</div>
<div class="column">
Usage

add rs,rt comp rs,rt addi rs,imm compi rs,imm and rs,rt

xor rs,rt

shll rs, sh

shrl rs, sh shllv rs, rt shrl rs, rt

shra rs, sh shrav rs, rt

lw rt,imm(rs) sw rt,imm,(rs) b L

br rs bltz rs,L bz rs,L bnz rs,L bl L

bcy L bncy L

</div>
<div class="column">
Meaning

</div>
</div>
<div class="layoutArea">
<div class="column">
Date: 22/10/21

</div>
</div>
<div class="layoutArea">
<div class="column">
rs ← (rs) + (rt)

rs ← 2’s Complement (rs)

rs ← (rs) + imm

rs ← 2’s Complement (imm)

rs ← (rs) ∧ (rt)

rs ← (rs) ⊕ (rt)

rs ← (rs) left-shifted by sh

rs ← (rs) right-shifted by sh

rs ← (rs) left-shifted by (rt)

rs ← (rs) right-shifted by (rt)

rs ← (rs) arithmetic right-shifted by sh rs ← (rs) right-shifted by (rt)

rt ← mem[(rs) + imm]

mem[(rs) + imm] ← (rt)

goto L

goto (rs)

if(rs) &lt; 0 then goto L

if (rs) = 0 then goto L

if(rs) ̸= 0 then goto L

goto L; 31 ← (PC)+4

goto L if Carry = 1

goto L if Carry = 0

</div>
</div>
<div class="layoutArea">
<div class="column">
Our processor KGP-RISC has the above Instruction Set Architecture (ISA). Assume that the processor has a 32 bit word, with all the registers and memory elements having 32 bit data. The address line of the memory is also 32 bits.

We are to develop first the op-code format for the above instruction set, identify the data path element and design the data path along with the control signals. Subsequently, we shall first develop a single-cycle instruction execution unit for KGP-RISC.

Proceed step-by-step as follows:

<ol>
<li>For the above Instruction set, evolve a suitable instruction format. Clearly specify the fields of the opcode and mention how each of the above instruc- tions are to be encoded. Keep in mind, while deciding the op-code, you should keep provisions for adding more instructions to the ISA.</li>
<li>Identify the Data path elements and draw an architecture for the Arith- metic Logic Unit. Clearly differentiate between the data lines and control lines in your architecture diagram.1</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol start="3">
<li>Draw the complete data path along with the control signals for a single cycle execution unit for the above ISA.</li>
<li>Write the truth table for the controller signals as a function of the opcode and the function code in the instruction format. Note that for a single cycle implementation of the controller there is no state and the design is purely combinational.</li>
<li>Develop the complete RTL Verilog code for the processor. Your design should have separate and modular codes for the data-path and control- path.As an indicative guideline, your submission should consist of the following verilog files:
(a) KGPRISC.v (b) datapath.v (c) controller.v

(d) registerfile.v

(e) ALU.v

(f) InstructionMemory.v (g) DataMemory.v

Note these are indicative names of the modules, and you can make alter- ations as you deem necessary. You can also add to it depending on the architecture you need for supporting the ISA of KGPRISC.
</li>
<li>Please write suitable test-benches for verifying these components, either individually or few modules together. What is mandatory is the top-level testbench file. Your testbench should correspond to an assembly level program for your favorite algorithm. For example, you can choose to im- plement Computegcd, or SortNumbers, etc. The input to these algorithms can be numbers stored in the data-memory, and accessed by appropriate instructions by your processor.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
