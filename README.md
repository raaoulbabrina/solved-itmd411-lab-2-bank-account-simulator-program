Download Link: https://assignmentchef.com/product/solved-itmd411-lab-2-bank-account-simulator-program
<br>
<strong><em> </em></strong>

<strong>PROJECT     </strong><strong>Bank account simulator program                             </strong>

<strong><u>Objective</u></strong><strong>        </strong>To write a program that performs various bank transactions.

<strong><em>PROJECT DESCRIPTION</em></strong>

Bank of WCC has contacted you to write, compile and execute a complete program that creates bank account information and executes various transaction details for their clients.

Your program will prompt users for options such as creating an initial balance, entering deposits or withdrawals. Also, your program will allow for the printing of account information including interest at various interest rates.

Use loops, user defined methods, conditional and relational logic and the basics of OOP to accomplish the objectives of this program.

<u>Error</u> <u>trapping</u> will be part of your grade so don’t forget to include some basic error trapping logic!  Comment your code thoroughly as well for maximum points.

<strong> </strong><strong><em>Project Detail</em></strong>

For this program you will create <em><u>two</u></em> separate Java files within your pack age, namely <strong>AccountHolder </strong>and <strong>AccountHolderTest</strong>.

The <strong>AccountHolder</strong> file <u>must</u> include the following class <em>field</em> members and data <em>methods </em>to allow for transaction processing.

<table>

 <tbody>

  <tr>

   <td width="197">Field Name</td>

   <td width="197">Field modifier/type</td>

  </tr>

  <tr>

   <td width="197">annualInterestRate</td>

   <td width="197">static / double</td>

  </tr>

  <tr>

   <td width="197">balance</td>

   <td width="197">double</td>

  </tr>

 </tbody>

</table>




<table width="522">

 <tbody>

  <tr>

   <td width="160">*Method Name</td>

   <td width="182">Method (Instance or Static)</td>

   <td width="80">Argument</td>

   <td width="100">Return Type</td>

  </tr>

  <tr>

   <td width="160">AccountHolder</td>

   <td width="182">Constructor</td>

   <td width="80">double</td>

   <td width="100">none</td>

  </tr>

  <tr>

   <td width="160">deposit</td>

   <td width="182">Instance</td>

   <td width="80">double</td>

   <td width="100">void</td>

  </tr>

  <tr>

   <td width="160">withdrawal</td>

   <td width="182">Instance</td>

   <td width="80">double</td>

   <td width="100">void</td>

  </tr>

  <tr>

   <td width="160">monthlyInterest</td>

   <td width="182">Instance</td>

   <td width="80">void</td>

   <td width="100">void</td>

  </tr>

 </tbody>

</table>

*assume all methods are declared public

<em>Of course if you would like to <u>add</u> any extra fields or methods in your class(es) feel free </em>

<em>to do so.</em>

Coding detail for your methods <u>must</u> include the following:

<ol>

 <li>Allow the constructor to accept an argument representing an initial balance for the Account holder. Set your balance member equal to the value passed via the class constructor. Balances cannot start off negative! Include an error message if this is the situation.</li>

 <li>Define in your <strong>monthlyInterest</strong> method body an assignment statement to update the <u>account holders’</u> <strong>balance</strong> to be effected as follows:</li>

</ol>

<strong>balance</strong><strong> += balance * (annualInterestRate / 12.0);</strong>

<ol start="3">

 <li>For your <strong>deposit </strong>&amp;<strong> withdrawal </strong>methods either have your method body either increase or decrease the holder’s <u>current</u> balance accordingly.</li>

</ol>

An added rule to follow here:

Disallow a <u>withdrawal</u> attempts to drive account balance to drop below $50. Deliver a message to the console stating that the balance must hold to at least $50.

For your <strong>AccountHolderTest</strong> file, include any local variables in main to work the application. <u>Include</u> the following transactional detail from your main method for each run below, <em>executed</em> in the <strong><u>following order.</u></strong>

Your main() activities

<ol>

 <li>Allow the interest for the bank to be initially set at <strong>4%</strong>. This can be hard coded in.</li>

 <li>Create an AccountHolder object and <u>prompt</u> the user for an initial account balance and have the initial balance <u>passed into</u> the <strong><u>AccountHolder</u></strong></li>

 <li><u>Prompt</u> the user to enter in a deposit amount.</li>

 <li><u>Prompt</u> the user for a withdrawal amount.</li>

 <li>Display an ending balance for the month, including monthly interest, to the account holder.</li>

</ol>

Snapshot your results above and paste it into Word for credit.  Zip your java files of your project separately as well for credit. Label files accordingly. Ex. Lab1_yourInitials.docx and Lab1_yourInitials.zip. Submit all files to BlackBoard when complete.




















