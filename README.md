# cs317-project---regular-expression-to-finite-automata-solved
**TO GET THIS SOLUTION VISIT:** [CS317 Project – Regular Expression to Finite Automata Solved](https://www.ankitcodinghub.com/product/cs317-project-regular-expression-to-finite-automata-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95911&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS317 Project – Regular Expression to Finite Automata Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

Introduction

</div>
</div>
<div class="layoutArea">
<div class="column">
For this programming project, you will construct a regular expression engine using C (preferable) or Java to implement your program. If you use Java, your program must run without any external libraries (default java libraries only). Graders must be able to easily compile and run your code. The “engine” involves creating Nondeterministic Finite Automata (NFA) from user supplied regular expressions in postfix notation (see below).

Regular Expressions

Regular expression semantics:

<ul>
<li>Σ = {a, b, c, d, e} and expressions are over Σ* this includes ε. For ease of processing we will
write E for ε.
</li>
<li>r1|r2 is union (this is r1 È r2, either expression r1 or r2, the | is easier to type/process)</li>
<li>r1r2 is concatenation (expression r1 followed by r2 also written r1◦r2). For ease of processing
we will write r1&amp;r2 for concatenation.
</li>
<li>r* Kleene closure (expression r zero or more times)</li>
<li>(r) parenthesized expression (postfix notation will not use parenthesizes)
Operators are listed in increasing order of precedence, lowest is |. Your program should check for well formed regular expressions and give appropriate error messages if the input is incorrect.

Postfix Regular Expressions

Most people who use HP calculators are used to postfix notation for arithmetic expressions. For example, the infix expression

(3 + (4 * 8)) + ((6 + 7)/5) is expressed as

348*+67+5/+

in postfix notation. In prefix form, this expression would be

++3*48/+675

Both prefix and postfix notation are nice because parentheses are not needed since they do not have the operator-operand ambiguity inherent to infix expressions. Postfix expressions are also easy to parse (which is why we are discussing them here). Later in the course, when we discuss context- free languages, we will revisit the problem of parsing infix expressions. Using the same idea for regular expressions, the infix regular expression

((aÈb)*aba*)*(aÈb)(aÈb) can be represented as

((a|b)*◦a◦b◦a*)*◦(a|b)◦(a|b)

where ◦ is added for concatenation. This can be changed to

ab|*a&amp;b&amp;a*&amp;*ab|&amp;ab|&amp;

in postfix notation. Notice we removed the need for parentheses but added the &amp; operator for concatenation. Your program will work with regular expressions in their postfix form.
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
10/1/2020

</div>
</div>
<div class="layoutArea">
<div class="column">
Postfix Regular Expression to NFA

We will convert a postfix regular expression into an NFA using a stack, where each element on the stack is an NFA. The input expression is scanned from left to right. When this process is completed, the stack should contain exactly one NFA. We construct NFAs based on the inductive rules below.

Converting regular expressions into FAs

§ Rule 1: There is a FA that accepts any symbol of Σ and there is a FA that accepts ε.

o IfxisinΣthengiveaFAthatacceptsx

o GiveaFAthatacceptsε.

§ Rule 2: Given FA1 that accepts regular expression r1 and FA2 that accepts regular expression

r2 then make FA3 that accepts r1 È r2. Add a new start state s and make a ε-transition from this state to the start states of FA1 and FA2. Add a new final state f and make a ε-transition to this state from each of the final states of FA1 and FA2.

§ Rule 3: Given FA1 that accepts regular expression r1 and FA2 that accepts regular expression r2 then make FA3 that accepts r1◦ r2. Add a ε-transition from the final state of r1 to the start state of r2. The start state of FA3 is the start state of FA1 and the final state of FA3 is the final state of FA2. You will have to think about it, but I do not think you will have multiple final states in FA1.

§ Rule 4: Given FA1 that accepts regular expression r then make a FA2 that accepts r*. Add a new start state s and make a ε-transition from this state to the start state of FA1. Make a ε- transition from the final state of F1 to the new start state s. The final states of FA1 are no longer final and s is the final state of FA2.

Input/Output Conventions

Input: Your program should read from a text file that contains a list of regular expression in postfix form (the infix form will not be included). The file will be setup so that there is one regular expression per line. See the posted test file.

Input symbols: a, b, c, d, e, |, &amp;, * and E (for ε). We will skip the empty set.

If you want to include capital S for Σ you may but I will not test your program on this since Σ = (a È b È c È d È e).

Output: You can use any internal data structures that you want to represent the NFA you are building. When your program is done please print the NFA out as a table or as a list of transitions. Make sure the grader knows which you have picked. For example, input a*b| (which is postfix for a*Èb might produce the NFA below. Only print a table or a list of transitions as output.

</div>
</div>
<div class="layoutArea">
<div class="column">
(q1, a) → q2

(q2, ε) → q3 ε ε q1 (q3,ε)→q1,q7 q qεq a q q q2 (q4,b)→q5 6 3 1 2 7 q3

</div>
<div class="column">
ε

</div>
</div>
<div class="layoutArea">
<div class="column">
ab q2

q3

q1,q7 q5

q7 q3, q4

</div>
</div>
<div class="layoutArea">
<div class="column">
(q5, ε) → q7

S (q6, ε) → q3, q4 F (q7, ε)

</div>
<div class="column">
ε q4 εqε

</div>
</div>
<div class="layoutArea">
<div class="column">
q4 b 5 q5 q6 S

</div>
</div>
<div class="layoutArea">
<div class="column">
q7 F

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
10/1/2020

</div>
</div>
<div class="layoutArea">
<div class="column">
Postfix Regular Expressions

These are samples of regular expression in both infix and postfix form. Only the postfix list would be in an input file for your program.

1. aÈb a|b ab|

2. aÈε a|E aE|

3. ab ab ab&amp;

4. a* a* a*

5. (aÈb)* (a|b)* ab|*

6. a*Èb a*|b a*b|

7. (aÈb)*b (a|b)*b ab|*b&amp;

8. aba*(aÈb)b aba*(a|b)b ab&amp;a*&amp;ab|&amp;b&amp;

9. ((aÈb)*aba*)*(aÈb)(aÈb) ((a|b)*aba*)*(a|b)(a|b) ab|*a&amp;b&amp;a*&amp;*ab|&amp;ab|&amp; 10. (aba*(aÈb))*b (aba*(a|b))*b ab&amp;a*&amp;ab|&amp;*b&amp;

11. ((aba*(aÈb))*b)* ((aba*(a|b))*b)* ab&amp;a*&amp;ab|&amp;*b&amp;*

12. ((aba*(aÈb))*b)*(aÈb)*b ((aba*(a|b))*b)*(a|b)*b ab&amp;a*&amp;ab|&amp;*b&amp;*ab|*&amp;b&amp;

Basic Code Outline

while (not end of postfix expression) {

c = next character in postfix expression; if (c == ’&amp;’) {

nFA2 = pop();

nFA1 = pop();

push(NFA that accepts the concatenation of L(nFA1) followed by L(nFA2));

} else if (c == ’|’) { nFA2 = pop();

nFA1 = pop();

push(NFA that accepts L(nFA1) | L(nFA2)); } else if (c == ’*’) {

nFA = pop();

push(NFA that accepts L(nFA) star); } else

</div>
</div>
<div class="layoutArea">
<div class="column">
}

</div>
<div class="column">
push(NFA that accepts a single character c);

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
10/1/2020

</div>
</div>
<div class="layoutArea">
<div class="column">
Data Structure Idea

Below is one suggestion on how to implement your code, but you do not have to use this. For example, in C you might have

1. A structure that represents an NFA containing the number for the start state, the number for the accept state and a pointer to a list of transitions

NFA

</div>
</div>
<div class="layoutArea">
<div class="column">
start state accept state transition list

</div>
<div class="column">
integer

integer

pointer to a list of transitions for the NFA

</div>
</div>
<div class="layoutArea">
<div class="column">
2. A second structure that represents transitions containing a number for the first state, a number for the second state, the symbol that goes from the first state to the second and last, and a pointer to a list of transitions. This could represent (q1, a) → q2.

Transition

</div>
</div>
<div class="layoutArea">
<div class="column">
state 1

state 2 symbol transition list

</div>
<div class="column">
integer

integer

integer too if a = 1, b = 2, c = 3, etc. pointer to a list of transitions for the NFA

</div>
</div>
<div class="layoutArea">
<div class="column">
With this type of data structure what you need to push and pop from the stack is the NFA structure because the list of transitions for the NFA is connected to it and can have any length including null.

</div>
</div>
</div>
