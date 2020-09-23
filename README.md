<div align="center">

## Beginners C\+\+ \- Lesson 1


</div>

### Description

Welcome fellow programmers!! This is part one of the course which will show you the basics of programming C++ from scratch using the any platform. If you already know how to use the C++ already, you might want to read later lessons when available. So, lets begin.

Found at http://pa.pulze.com/
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Found on the World Wide Web](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/found-on-the-world-wide-web.md)
**Level**          |Beginner
**User Rating**    |4.4 (96 globes from 22 users)
**Compatibility**  |C\+\+ \(general\)
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__3-1.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/found-on-the-world-wide-web-beginners-c-lesson-1__3-417/archive/master.zip)





### Source Code


<p><b style="FONT-WEIGHT: bold">Instructor</b>:&nbsp;&nbsp; Paul C. Benedict,
Jr. (<u><span style="COLOR: #0000ff">PCC PaulB</span></u>)<br>
<b style="FONT-WEIGHT: bold">Keyword:</b>&nbsp;&nbsp;&nbsp; <u><span style="COLOR: #0000ff">Online
Classroom</span></u><br>
<b style="FONT-WEIGHT: bold">Resources: </b><u><span style="COLOR: #0000ff">PC
Development Forum</span></u></p>
<p>&nbsp;</p>
<h3>Color coded text:</h3>
<p><b style="FONT-WEIGHT: bold">&nbsp;&nbsp;&nbsp; black&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
New things to Remember</b><br>
<span style="COLOR: #0000ff"><b style="FONT-WEIGHT: bold">&nbsp;&nbsp;&nbsp;
blue&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; C++
keywords (do, while)</b></span><br>
&nbsp;&nbsp;&nbsp; <span style="COLOR: #008800"><b style="FONT-WEIGHT: bold">green&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
C++ preprocessor directives (#include, #define)</b></span></p>
<p><br>
</p>
<h1><u><i>Section 1.1</i></u></h1>
<p>Welcome fellow programmers!!&nbsp; This is part one of the course which will
show you the basics of programming C++ from scratch using the any platform.&nbsp;
If you already know how to use the C++ already, you might want to read later
lessons when available. So, lets begin.</p>
<p>Being developed by mathematicians, C++ is naturally a math-oriented
programming language.&nbsp; It should be very natural since we have all done
math to some extent.&nbsp; The only difficult part is learning the syntax of the
C++ language.&nbsp; Syntax is the use of the language, just like all spoken
languages have.&nbsp; To write a program that works, you must have correct
syntax or it will not run.</p>
<p>What the programmer, that's you, write is what is called <b style="FONT-WEIGHT: bold">source
code</b>.&nbsp; Its the source of your program which turns into code, what you
run.&nbsp; What makes this transition is called the &quot;compiler&quot;.&nbsp;
The compiler is a program which turns your source into code.&nbsp; This program
is automatically part of programs such as <b style="FONT-WEIGHT: bold">Borland
C++</b> and <b style="FONT-WEIGHT: bold">Microsoft Visual C++</b>.&nbsp; On a
side note, do not get confused with &quot;C++&quot; and &quot;Visual C++&quot; -
C++ is a programming language, and Visual C++ is a product which compiles C++.&nbsp;
I get alot of questions about this, so I figured I would clear this up now.</p>
<p>Now lets go more in-depth into making a program.&nbsp; There are four steps:</p>
<p>&nbsp;&nbsp;&nbsp; 1. Write out your source code (in a .CPP file)<br>
&nbsp;&nbsp;&nbsp; 2. Compile your program<br>
&nbsp;&nbsp;&nbsp; 3. Link your program<br>
&nbsp;&nbsp;&nbsp; 4. Run your program</p>
<p>We have already discussed steps 1 and 2.&nbsp; Step 3, <b style="FONT-WEIGHT: bold">linking</b>
your program is new to us.&nbsp; You see, there are many programs out there that
are already written for you, which means you don't have to write them.&nbsp;
After the compiler compiles your program, it links your program to other
pre-written programs, and creates an <b style="FONT-WEIGHT: bold">executable
file</b> (.EXE).&nbsp; This executable file is what is used to run the program.</p>
<p>Now a <b style="FONT-WEIGHT: bold">.cpp</b> file is just like any other text
file.&nbsp; You can write this in notepad if you would, but usually you would
use the product's <b style="FONT-WEIGHT: bold">Integrated Development
Environment (IDE)</b>.&nbsp; This IDE is &quot;integrated&quot; because it
incorporates a text editor, the compiler, the linker, help files, and tools.</p>
<br>
<p>&nbsp;</p>
<h1><u><i>Section 1.2</i></u></h1>
<p>In this lesson, we are here to learn the syntax of the C++ language to allow
us to delve deeper into the depths of C++ Windows programming in the next
lesson.&nbsp; The most fundamental part of a language are <b style="FONT-WEIGHT: bold">types</b>,
<b style="FONT-WEIGHT: bold">variables</b>, and <b style="FONT-WEIGHT: bold">expressions</b>.&nbsp;
The first statement we are going to learn is the assignment expression:</p>
<p><i>&nbsp;&nbsp;&nbsp; variable = expression;</i></p>
<p>For example:</p>
<p>&nbsp;&nbsp;&nbsp; x = 3 + 5;</p>
<p>This allows us to assign a value of 3 + 5, which is 8 to the variable <i>x</i>.&nbsp;
An expression which is always on the right-side gets evaluated by the compiler
and is assigned to a variable on the left.&nbsp; Please note that expressions
can only be on the right side, otherwise the compiler will yell at you &quot;Hey
you, what's going on?&quot;&nbsp; :-)</p>
<p>The = means assign the value of the right to the left hand side.&nbsp;
Remember that you need a variable on the left hand side of the<i> </i>=, not an
expression.&nbsp; The compiler evaluates the expression on the right hand side,
deduces what you mean, and assigns it to the left hand side.&nbsp; In our
example, the compiler evaluates the expression on the right side of the = to
mean 8 and assigns it to the variable <i>x</i> on the left side.</p>
<p>The entire line of our example,<i> x = 3 + 5;</i> is called a <b style="FONT-WEIGHT: bold">statement</b>.&nbsp;
If you are a BASIC programmer, you know that you must put everything on one
line.&nbsp; In C and C++, your statement can span multiple lines.&nbsp; If we
wanted, we could write our statement to look like this:</p>
<p>&nbsp;&nbsp;&nbsp; x = 3<br>
&nbsp;&nbsp;&nbsp; +<br>
&nbsp;&nbsp;&nbsp; 5<br>
&nbsp;&nbsp;&nbsp; ;</p>
<p>To the compiler, this makes absolutely no difference.&nbsp; It sees the
statement as the same as if you wrote it on one line (which made it much more
readable to us humans) :-)&nbsp; <u>Please note that for every statement you
write, it is ended in a semi-colon <i>;</i></u>.&nbsp; This is very critical,
otherwise the compiler will keep on looking at this as one expression and it
will look like complete junk to it.&nbsp; Forgetting the semi-colon is bad
syntax, and therefore you are not speaking the language correctly.</p>
<p>It is always required that you declare the type of the variable.&nbsp; This
is because so the compiler knows how much memory to set aside for your variable.&nbsp;
If you do not specify a type, it will automatically be an <span style="COLOR: #0000ff"><b style="FONT-WEIGHT: bold">int</b></span>.</p>
<br>
<p>&nbsp;</p>
<h1><u><i>Section 1.3</i></u></h1>
<p>Now we are going to learn how to do assignments full with variables.&nbsp;
The first thing we must understand about variables are what they are and how to
use them in a program.&nbsp; A variable is a location in your computer's memory
where you can save and retrieve information. The type of data can be anything
you want.&nbsp; The most common data we will be using are integers, floating
point numbers, characters, and strings.</p>
<p>Integers are numbers like -1, 2, 0, 3456.&nbsp; Any number that can
represented on a number line (remember math?) :-)</p>
<p>Floating point numbers are fractional numbers: 1.0, 3.4, 0.72984, 10E-10.&nbsp;
The reason it is called <b style="FONT-WEIGHT: bold">floating point</b> is
because the decimal point can move around through addition.&nbsp; For instance,
.01 * .01 = .0001</p>
<p><b style="FONT-WEIGHT: bold">Characters</b> are a single letter, number, or
symbol.&nbsp; For instance, 'A', 'B', '3', <a href="mailto:'@'">'@'</a>.&nbsp;
Characters are represented in single quotation marks.</p>
<p><b style="FONT-WEIGHT: bold">Strings </b>are a collection of characters.&nbsp;
For instance, &quot;How may I help you?&quot;,&nbsp; &quot;This string is filled
with junk at the end 232312312312&quot;,&nbsp; &quot;(*&amp;^%&quot;.&nbsp;
Strings are denoted by double quotation marks.</p>
<p>Now, here is some code that shows all the types you just learned, except the
string.&nbsp; The string is a little bit more complicated and will be reviewed
later:</p>
<p>&nbsp;&nbsp;&nbsp; int MyNumber = 3;<br>
&nbsp;&nbsp;&nbsp; float Pi = 3.14;<br>
&nbsp;&nbsp;&nbsp; char LetterA = 'A';</p>
<p>What we have above is three declarations.&nbsp; We <b style="FONT-WEIGHT: bold">declare</b>
three variables an assign values to them.&nbsp; We declare the variable &quot;MyNumber&quot;
as type &quot;int&quot;, which means it is an integer.&nbsp; We declare the
variable &quot;Pi&quot; as type &quot;float&quot;, which means it is a floating
point number.&nbsp; We also declare the variable &quot;LetterA&quot; as type
&quot;char&quot;, which means it is a character.</p>
<p>With numerical data types (like <span style="COLOR: #0000ff"><b style="FONT-WEIGHT: bold">int</b></span>
and <span style="COLOR: #0000ff"><b style="FONT-WEIGHT: bold">float</b></span>),
we can perform simple math operations on them:</p>
<p>&nbsp;&nbsp;&nbsp; Addition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
+<br>
&nbsp;&nbsp;&nbsp; Subtraction&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
-<br>
&nbsp;&nbsp;&nbsp; Multiplication&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
*<br>
&nbsp;&nbsp;&nbsp; Division&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
/<br>
&nbsp;&nbsp;&nbsp; Modular Division (Remainder)&nbsp;&nbsp;&nbsp;&nbsp; %</p>
<p>We will not review the four simple math operations, but here is an example of
the four:</p>
<p>&nbsp;&nbsp;&nbsp; int MyNumber = 3;<br>
&nbsp;&nbsp;&nbsp; MyNumber = MyNumber + 2;<br>
&nbsp;&nbsp;&nbsp; MyNumber = MyNumber - 1;<br>
&nbsp;&nbsp;&nbsp; MyNumber = MyNumber * 3;<br>
&nbsp;&nbsp;&nbsp; MyNumber = MyNumber / 2;</p>
<p>In the first statement, the variable <i>MyNumber</i> is taken, adds 2 to it,
and stores it back in <i>MyNumber</i>.&nbsp; Right now, <i>MyNumber</i> now
equals 5.&nbsp; Then we subtract one and store back the result, multiply by
three and store back the result, and then divide by 2 and store back the result.&nbsp;
<i>MyNumber</i> now contains 6.</p>
<p>Please note that the &quot;=&quot; (equal operator) does not mean
&quot;equal&quot;.&nbsp; Read it as &quot;assigns&quot;.&nbsp; This assigns the
value of the right side to the variable on the left side.</p>
<p>The Modular Division operator (or Remainder operator), returns the remainder
of a division:</p>
<p>&nbsp;&nbsp;&nbsp; int Remainder = 7 % 4;</p>
<p>The variable <i>Remainder</i> contains the value of 3 now.&nbsp; How did we
get that?&nbsp; Because 4 goes into 7 one time with a remainder of 3.&nbsp;
Please note that the &quot;%&quot; operator always returns an integer value.</p>
<p><br>
</p>
<h1><u><i>Section 1.4</i></u></h1>
<p>Unlike pure mathematics (the kind of math we do at school), we do not have an
infinite amount of memory to store some numbers.&nbsp; Therefore, computer
scientists came up with ways to store numbers in finite quantities.&nbsp; The
date type <span style="COLOR: #0000ff"><b style="FONT-WEIGHT: bold">int</b></span>,
<span style="COLOR: #0000ff"><b style="FONT-WEIGHT: bold">float</b></span>, and <span style="COLOR: #0000ff"><b style="FONT-WEIGHT: bold">char</b></span>
are all different sizes - and determining which type you use, you must set aside
that number of bytes to hold it.&nbsp; You can use the <span style="COLOR: #0000ff"><b style="FONT-WEIGHT: bold">sizeof</b></span>
operator to find out how much memory (in bytes) a type or variable holds in code
- example: <span style="COLOR: #0000ff"><b style="FONT-WEIGHT: bold">sizeof(int)</b></span>.&nbsp;
In the three most commonly used data types we are examining, these are the
values:</p>
<p>&nbsp;&nbsp;&nbsp; sizeof(int)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; = 4<br>
&nbsp;&nbsp;&nbsp; sizeof(float)&nbsp;&nbsp;&nbsp; = 4<br>
&nbsp;&nbsp;&nbsp; sizeof(char)&nbsp;&nbsp; = 1</p>
<p>On a side note, if you were running <span style="COLOR: #0000ff"><b style="FONT-WEIGHT: bold">sizeof(int)</b></span>
on a 16-bit compiler (ones made before Windows 95), it would return 2.&nbsp;
Notice how <span style="COLOR: #0000ff"><b style="FONT-WEIGHT: bold">sizeof(float)</b></span>
and <span style="COLOR: #0000ff"><b style="FONT-WEIGHT: bold">sizeof(int)</b></span>
return the same size (each occupy four bytes in memory), but the memory is used
much differently.&nbsp; It is all dependent on the data type used.</p>
<p>Now, you are probably wondering, what on earth is a <b style="FONT-WEIGHT: bold">byte</b>?&nbsp;
Well, a byte consists of eight bits of information.&nbsp; As we unwrap this
enigma of words, a bit is the SMALLEST piece of information that the computer
can work with.&nbsp; A bit can only be in the ON or OFF position, like your
computer.&nbsp; This on/off system is called the <b style="FONT-WEIGHT: bold">binary
system</b> because there are only two numbers in the system (unlike our decimal
system which contains ten).&nbsp; We like to represent on as a 1 and off as a 0.&nbsp;
And if we link a bunch of 1's and 0's together, we get a number the computer can
use.&nbsp; Let's see exactly how the computer does this so we can understand the
use of numbers in computers better:</p>
<p>We want to see how the number 8 is represented in computers.&nbsp; First off,
8 exists in our decimal system (power of tens) and we must represent it in the
binary system (power of twos).&nbsp; This is how the number 8 looks like when
broken down into the power of tens:</p>
<p>&nbsp;&nbsp;&nbsp; 10^0 * 8</p>
<p>Above says take 10 to the power (^) of zero, which is 1 and multiply it by 8.&nbsp;
Hence we get the number eight.&nbsp; In the binary system, this is how it would
look:</p>
<p>&nbsp;&nbsp;&nbsp; (2^3 * 1) + (2^2 * 0) + (2^1 * 0) + (2^0 * 0)</p>
<p>Wow!&nbsp; That's alot of writing.&nbsp; Let's examine what is going on:<br>
2 to the 3rd power times 1 is eight.&nbsp; We add that to 2 to the 2nd power
times 0, which is zero.&nbsp; We add that to 2 to the 1st power times 0, which
is zero.&nbsp; Finally, we add that to 2 to the 0 power times 0, which is zero.&nbsp;
Through all that, we get the answer of 8.</p>
<p>Now, if we look at the multiplication in that binary example, you can see we
get 01000.&nbsp; 01000 equals 8 in decimal.&nbsp; You might be wondering why I
took it upon myself to put an extra zero in the front of the binary number.&nbsp;
The reason we do that is because the LEFT most side of a binary number
determines if the number is positive or negative.&nbsp; Remember computers can't
use all the fancy math symbols we do, so we have to have some way of making a
number negative - this is our way.&nbsp; Since eight is a positive number, we
make the left-most bit a zero.</p>
<p><br>
</p>
<h1><u><i>Section 1.5</i></u></h1>
<p>Now what the next thing we are going to learn is binary addition and
subtraction.&nbsp; You might be sitting there wondering why we are doing this.&nbsp;
The reason is because as you get more experienced in programming, most of the
time you will be dealing with bits of a number, and not the number itself.&nbsp;
This is crucial.</p>
<p>Let's say we are working with a byte and wanted to add the numbers 8 and 5
together.&nbsp; This is how it would be done:</p>
<p>&nbsp;</p>
<h2><i>Example 1</i></h2>
<p><br>
&nbsp;&nbsp;&nbsp; 00001000&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; = 8<br>
&nbsp;&nbsp;&nbsp; 00000101&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; = 5nbsp; = 5&nbsp;&nbsp;&nbsp;
----------------------------<br>
&nbsp;&nbsp;&nbsp; 00001101&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; = 13</p>
<p>Like normal math, we add from right to left:<br>
1.&nbsp; The right-most column is 0 + 1 which equals 1<br>
2.&nbsp; Then 0 + 0 equals 0.<br>
3.&nbsp; Next 0 + 1 gives another 1.<br>
4.&nbsp; And next 1 + 0 gives another 1.</p>
<p>As you can see, it's pretty basic.&nbsp; Now let's look at a more complex
example.</p>
<p>&nbsp;</p>
<h2><i>Example 2</i></h2>
<p><br>
&nbsp;&nbsp;&nbsp; 00000001&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; =&nbsp; 1<br>
&nbsp;&nbsp;&nbsp; 00001111&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; = 15<br>
&nbsp;&nbsp;&nbsp; ----------------------------<br>
&nbsp;&nbsp;&nbsp; 00010000&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; = 16</p>
<p>Hey now, this looks very different.&nbsp; Let's examine what is going on.<br>
1. When we add 1 and 1 together, we get 2 which is &quot;10&quot; in binary.&nbsp;
So what we do is bring down the zero and carry the one (just like good ol'
math).<br>
2. Next we have 0 + 1 + the carried 1.&nbsp; That yields two again.&nbsp; So we
drop the zero and carry the one.<br>
3. We continue this until the end.</p>
<p><br>
</p>
<h1><u><i>Section 1.6</i></u></h1>
<p>We must learn how to convert decimal into binary efficiently.&nbsp; The rules
are very simple:<br>
1) Take your number and divide by 2<br>
2) Take the remainder and write it down<br>
3) Take the quotient and make that the number to divide for the next time<br>
4) Repeat step 1 through 3 until the number reaches 0<br>
5) Reverse the list of all your remainders and you have the number in binary</p>
<p>&nbsp;</p>
<h2><i>Example 3</i></h2>
<p><br>
&nbsp;&nbsp;&nbsp; Convert decimal 16 to binary<br>
&nbsp;&nbsp;&nbsp; 16 / 2 = 8, remainder 0<br>
&nbsp;&nbsp;&nbsp; 8 / 2&nbsp;&nbsp; = 4, remainder 0<br>
&nbsp;&nbsp;&nbsp; 4 / 2&nbsp;&nbsp; = 2, remainder 0<br>
&nbsp;&nbsp;&nbsp; 2 /2&nbsp;&nbsp;&nbsp; = 1, remainder 0<br>
&nbsp;&nbsp;&nbsp; 1 / 2&nbsp;&nbsp; = 0, remainder 1</p>
<p>Now look at the remainder list.&nbsp; We have 00001.&nbsp; Obviously, that is
the number 1 in decimal, so like step 5 says, reverse the list and we get 10000.&nbsp;
Make sure you had that front zero to keep the number positive, so it is really
010000.</p>
<p>&nbsp;</p>
<h2><i>Example 4</i></h2>
<p><br>
&nbsp;&nbsp;&nbsp; Convert decimal 11 to binary<br>
&nbsp;&nbsp;&nbsp; 11 / 2 = 5, remainder 1<br>
&nbsp;&nbsp;&nbsp; 5 / 2&nbsp;&nbsp; = 2, remainder 1<br>
&nbsp;&nbsp;&nbsp; 2 / 2&nbsp;&nbsp; = 1, remainder 0<br>
&nbsp;&nbsp;&nbsp; 1 / 2&nbsp;&nbsp; = 0, remainder 1</p>
<p>Now we have 1101.&nbsp; Reverse it and add the front zero to keep the number
positive:&nbsp; 01011</p>
<p>&nbsp;</p>
<h1><u><i>Section 1.7</i></u></h1>
<p>Next up is binary subtraction.&nbsp; If you remember division in math, there
is no such thing.&nbsp; You would invert the second factor and multiply across.&nbsp;
4 divided by 2, is really 4 multiplied by 1/2, which equals 2.&nbsp; In binary
subtraction, this parallels to what we want to do.&nbsp; Take the second number
and invert all the bits (turning all the zeros to ones and all the ones to
zeros) and then add one.&nbsp; This process of inverting and adding one is
called <b style="FONT-WEIGHT: bold">twos complement</b>.</p>
<p>First to understand complementing, let's look at an example:</p>
<p>&nbsp;</p>
<h2><i>Example 5</i></h2>
<p>&nbsp;&nbsp;&nbsp; 00000101 = 5</p>
<p>Here is the number five in binary.&nbsp; Now to find out the complement of
the number, invert all the bits which makes the number &quot;11010&quot; and
then add one:</p>
<p>&nbsp;&nbsp;&nbsp; 11111010&nbsp;&nbsp; = 5 inverted<br>
&nbsp;&nbsp;&nbsp; 00000001&nbsp;&nbsp; = 1<br>
&nbsp;&nbsp;&nbsp; -----------------------<br>
&nbsp;&nbsp;&nbsp; 11111011&nbsp;&nbsp; = -5</p>
<p>Hey now!!!&nbsp; It turns out that two's complement gives us the negative
version of our number, and to prove it, if we add 5 and our -5 together, we
should get zero:</p>
<p>&nbsp;&nbsp;&nbsp; 11111011&nbsp;&nbsp; = -5<br>
&nbsp;&nbsp;&nbsp; 00000101&nbsp;&nbsp; =&nbsp; 5<br>
&nbsp;&nbsp;&nbsp; -----------------------<br>
&nbsp;&nbsp;&nbsp; 00000000&nbsp;&nbsp; = 0</p>
<p>We get zero!!&nbsp; If you noticed, we do not extend the number of bits when
this is done.&nbsp; Since we have a finite number of bits to work with and there
is an <b style="FONT-WEIGHT: bold">overflow</b> (an extra bit), we just discard
it.&nbsp; Now with this knowledge, to subtract two numbers: Take the first
number and add it from the two's complement of the other number.</p>
<p><br>
</p>
<h1><u><i>Section 1.8</i></u></h1>
<p>Now we are going to look at adding, subtracting, positive, and negative
numbers more in-depth.&nbsp; There are two type of integers: <b style="FONT-WEIGHT: bold">signed</b>
and <b style="FONT-WEIGHT: bold">unsigned</b>.&nbsp; A signed integer means that
the number can be either a negative or a positive.&nbsp; An unsigned integer
means that the number can only be zero or positive.&nbsp; Unsigned integers are
useful in absolute situations: the number of apples you have, how much a stamp
costs, etc.&nbsp; This is how you can specify the type:</p>
<p>&nbsp;&nbsp;&nbsp; signed int i = -100;<br>
&nbsp;&nbsp;&nbsp; unsigned int j = 40;</p>
<p>Now, if you don't specify the type of integer, it is automatically a signed
integer.</p>
<p>Now, we learned that that we used the left-most bit in determining if the
number is negative or not.&nbsp; This is ONLY the case when we work with signed
numbers.&nbsp; When the number is unsigned, the left-bit is just part of the
number. In the case of the byte, these are the ranges of a byte:</p>
<p>&nbsp;&nbsp;&nbsp; SIGNED&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; = -128 to 127&nbsp;&nbsp;&nbsp;
(uses bits 0 through 6)<br>
&nbsp;&nbsp;&nbsp; UNSIGNED = 0 to 255&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
(uses bits 0 through 7)</p>
<p>I hope you enjoyed the first of lessons in learning how to programming C++
from ground-zero.&nbsp; There is alot of material to be covered, so pay
attention, practice, and review.</p>
<p><br>
</p>
<h1><u><i>Keywords and Terms to Remember</i></u></h1>
<p>Assign<br>
Binary<br>
Bit<br>
Byte<br>
</p>
<h3><span style="COLOR: #0000ff">char</span></h3>
<p>Compiler<br>
Expression<br>
</p>
<h3><span style="COLOR: #0000ff">float</span></h3>
<p>Floating point<br>
IDE<br>
</p>
<h3><span style="COLOR: #0000ff">int</span></h3>
<p>Linker<br>
Modular<br>
Signed<br>
</p>
<h3><span style="COLOR: #0000ff">sizeof</span></h3>
<p>Source<br>
Statement<br>
Type<br>
Twos complement<br>
Unsigned<br>
Variable</p>
<p><br>
</p>
<h1><u><i>Summary</i></u></h1>
<p>The four steps in making a program is: writing code, compiling, linking, and
then running your program.</p>
<p>What makes up a language is: types, variables, and expressions.</p>
<p>Correct syntax is needed like any other human spoken language.</p>
<p><span style="COLOR: #0000ff"><b style="FONT-WEIGHT: bold">int</b></span>
allows integer data types, <span style="COLOR: #0000ff"><b style="FONT-WEIGHT: bold">float
</b></span>creates real numbers with fractional portions, and <span style="COLOR: #0000ff"><b style="FONT-WEIGHT: bold">char
</b></span>stores characters.</p>
<p>The five main math operators are: plus, minus, multiplication, division, and
modular division (remainder).</p>
<p>The <span style="COLOR: #0000ff"><b style="FONT-WEIGHT: bold">sizeof</b></span>
keyword returns the number of bytes a type or variable occupies.</p>
<p>The binary system is used in computers to represent numbers.</p>
<p>Binary subtraction is the same as addition just with twos complement.</p>

