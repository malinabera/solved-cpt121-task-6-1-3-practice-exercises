Download Link: https://assignmentchef.com/product/solved-cpt121-task-6-1-3-practice-exercises
<br>
Task 6.1.3 Practice Exercises

Inheritance and subclass basics

<ol>

 <li>In the following pair of classes identify the superclass and subclass: <strong>a) </strong>Employee / Manager

  <ol>

   <li>Polygon / Triangle</li>

   <li>Vehicle / Car</li>

   <li>GeometricObject / Rectangle</li>

   <li>Integer / Number</li>

   <li>Object/Person</li>

  </ol></li>

 <li>If class C extends class B and class B extends class A then which of the following statement is true?

  <ol>

   <li>an instance of C can use all public methods of classes A, B and C</li>

   <li>an instance of A can use all public methods of classes A, B and C</li>

  </ol></li>

 <li>Extend the Account class to create a new subclass called ChequeAccount for modelling a cheque account which incorporates the following functionality:

  <ul>

   <li>Cheque accounts can use an overdraft facility, so the new class will need instance variables for the overdraft limit and the amount overdrawn.</li>

   <li></li>

  </ul></li>

</ol>

<table>

 <tbody>

  <tr>

   <td width="49"></td>

   <td width="179"></td>

   <td width="200"></td>

   <td width="300"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td></td>

   <td rowspan="2"></td>

  </tr>

  <tr>

   <td></td>

  </tr>

 </tbody>

</table>

<ul>

 <li>The overdraft should not be used unless the current balance is insufficient to cover a</li>

</ul>

withdraw.

<ul>

 <li>Cheque account holders may be charged for withdrawals or transfers, so the new class will also need a new instance variable for the number of transactions that have been made.</li>

 <li>A new constructor will be required that accepts the account id, name, initial balance and overdraft limit. This constructor should use the super() facility to initialize the account id, name and balance.</li>

 <li>This constructor should set the amount overdrawn to 0 and the transaction count to 0.</li>

 <li>Define another (overloaded) constructor which only accepts the account name, id and balance for the new ChequeAccount (for customers who do not wish to use the overdraft facility yet)</li>

 <li>This constructor should set the overdraft limit to 0, amount overdrawn to 0 and transaction count to 0</li>

 <li>Decide whether accessors and/or mutators will be required for the three new instance variables.</li>

</ul>

<ol start="4">

 <li>Write a program which creates two CAccount objects and trace where the details supplied for each object will be stored upon construction. Describe how the various values supplied when creating the find their way into the corresponding superclass and subclass-level instance variables?</li>

</ol>


