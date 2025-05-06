# solved-lab-task-5-csc322
**TO GET THIS SOLUTION VISIT:** [SOLVED:Lab Task 5 CSC322](https://www.ankitcodinghub.com/product/solvedlab-task-5-solution/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;3498&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;SOLVED:Lab Task 5 CSC322&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
Ahhh, tax time again. Millions of innocent Americans are filling in their 1040. Don’t we all just love the IRS. If I were king, things would be a whole bunch simpler, with a simple computer program to compute tax. Here’s how my IRS program will work:

The loyal subject is repeated prompted to enter either an amount of income (a positive value) or an amount of deduction (a negative value). This continues until a zero value is entered. The positive values are summed to form the income, and the negative values are summed to form the deduction.

The taxable income is computed as the income less the deduction, except in the case that the deduction is greater than than the income in which case the taxable income is zero.

A tax group is calculated from the taxable income:Greater or equal to $500000 = Stinking rich

Greater or equal to $200000 = Quite rich

Greater or equal to $100000 = Miami poor

Greater or equal to $50000 = Average

Greater or equal to $20000 = Realistic

Less than $20000 = Poor

The tax group is saved as an uppercase letter, one of S, Q, M, A, R, P.

The tax is computed using one of three rates:The stinking rich and quite rich get taxed at the high rate of 25%.

The Miami poor get taxed at the medium rate of 10%.

The average and realistic get taxed at the low rate of 3%.

The poor pay no tax.

Additionally, the maximal tax is $50000.

The tax information is displayed.

Here what a sample run should look like (with the keyboard input shown in italics) …Enter next amount : 125000

Enter next amount : -250

Enter next amount : -3000

Enter next amount : 15000

Enter next amount : 88000

Enter next amount : -200

Enter next amount : 0

Income = $228000.00

Deductions = $ 3450.00

Taxable Income = $224550.00

Tax group = Q

Tax owed = $ 50000.00

Luckily, someone has already done the analysis and design, resulting in the following structure chart and algorithm …

1. Input income and deduction

1.1 Repeatedly until 0.0 is entered

1.1.1 Prompt user

1.1.2 Input value

1.1.3 If positive

1.1.3.1 Add to income

1.1.4 If negative

1.1.4.1 Add (absolute) to deduction

2. Compute taxable income

2.1 If income = deduction taxable is income – deduction, else

2.2 Taxable is 0.0

3. Compute tax group

3.1 If taxable = 500000

3.1.1 Group is S, else

3.2 If taxable = 200000

3.2.1 Group is Q, else

3.3 If taxable = 100000

3.3.1 Group is M, else

3.4 If taxable = 50000

3.4.1 Group is A, else

3.5 If taxable = 20000

3.5.1 Group is R, else

3.6 Group is P

4. Compute tax

4.1 Depending on the group

4.1.1 For S and Q

4.1.1.1 Tax is 25% of taxable

4.1.2 For M

4.1.2.1 Tax is 10% of taxable

4.1.3 For A and R

4.1.3.1 Tax is 3% of taxable

4.1.4 For P

4.1.4.1 Tax is 0.0

4.1.5 For other groups

4.1.5.1 Error!

4.2 If tax 50000 then

4.2.1 tax = 50000

5. Display tax information

5.1 Display income

5.2 Display deduction

5.3 Display taxable

5.4 Display group

5.5 Display tax

You must …

Implement the program in C. (2.0%) Internal nodes of the structure chart must be implemented as separate functions. The implementation must follow the design.

This program already has a macro that determines whether or not an unsigned int is odd by examining the least significant binary digit. It is missing the macros for determining if the Nth least significant bit is set (counting N from the least significant bit, starting from 0), and for determining if all bits are on in a range of positions.

You must add those macros (1.0%)

A couple of sample runs are …

BitOps

Enter an integer : 31

31 is odd

Enter an integer and a bit number : 31 3

31 has bit 3 on

Enter an integer, start and end bit numbers : 31 2 4

31 has all those bits on

BitOps

Enter an integer : 30

30 is even

Enter an integer and a bit number : 30 6

30 has bit 6 off

Enter an integer, start and end bit numbers : 30 4 6

30 has not all those bits on
