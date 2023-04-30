Download Link: https://assignmentchef.com/product/solved-cs2310-lab-7-arrays
<br>
Please test the correctness of your <strong><u>program in 2) and 3)</u></strong> using PASS.

<ol>

 <li>Write a program which define and initialize an array of 10 integers:</li>

</ol>

int num[10]={5,10,2,5,8, 8, 7,9, 1,5};

Using the elements in the array,  print a bar chart with lengths equal to corresponding element in the array:

*****

**********

**

*****

********

********

*******

*********

*

*****

<em>Hint: You should use </em><em>nested-for loops</em><em>. </em>

<em> The outer-for repeatedly retrieve the value a[i] where 0&lt;=i&lt;10 and the inner-for loop is used to print ‘*’ n times, followed by </em><em>endl</em>

<ol start="2">

 <li>Write a program which read two sets of integer elements (10 elements for each set) and find the intersection of two entered sets.<em> (According to the definition of “set”, elements are guaranteed to be unique within set)</em></li>

</ol>

<strong><u>Expected Output:</u></strong>

<strong> </strong>

<table width="0">

 <tbody>

  <tr>

   <td width="303"><strong>Example-1 </strong></td>

   <td width="303"><strong>Example-2 </strong></td>

  </tr>

  <tr>

   <td width="303">Enter 10 Elements of Set A: <u>1 2 3 4 5 6 7 8 9 10</u>Enter 10 Elements of Set B:<u>11 12 13 14 15 16 17 18 19 20</u> The Intersected Element of Set A and B are not Found.</td>

   <td width="303">Enter 10 Elements of Set A: <u>1 2 3 4 5 6 7 8 9 10</u>Enter 10 Elements of Set B:<u>1 2 3 4 5 6 7 8 9 10</u>The Intersected Elements of Set A and B are:1 2 3 4 5 6 7 8 9 10</td>

  </tr>

  <tr>

   <td width="303"><strong>Example-3 </strong></td>

   <td width="303"><strong>Example-4 </strong></td>

  </tr>

  <tr>

   <td width="303">Enter 10 Elements of Set A: <u>1 2 3 4 5 6 7 8 9 10</u>Enter 10 Elements of Set B:<u>1 3 5 7 9 11 13 15 17 19</u>The Intersected Elements of Set A and B are: 1 3 5 7 9</td>

   <td width="303">Enter 10 Elements of Set A:<u>-1 -2 -3 -4 -5 -6 -7 -8 -9 -10</u>Enter 10 Elements of Set B:<u>-1 -3 -5 -7 -9 -11 -13 -15 -17 -19</u>The Intersected Elements of Set A and B are:-1 -3 -5 -7 -9</td>

  </tr>

 </tbody>

</table>

<em> Computer Programming                                                                                                                     </em>

<ol start="3">

 <li>Write a program which read the first name of a person as an array of characters:</li>

</ol>

char Name[100]; cin &gt;&gt; Name;

Derive whether name is palindrome or not.

l     A palindrome is a word or any sequence of characters which reads the same backward or forward.

l     Entered words should be case sensitive. (i.e. ‘A’ and ‘a’ are considered different)




l    You can use the strlen() function to find the length of a string

(by #include &lt;string.h&gt;). For example, if the entered name is ”CityU” then strlen(Name) will return 5.




<strong><u>Expected Output:</u></strong>

<strong> </strong>

<table width="0">

 <tbody>

  <tr>

   <td width="303"><strong>Example-1 </strong></td>

   <td width="303"><strong>Example-2 </strong></td>

  </tr>

  <tr>

   <td width="303">Enter the First Name: <u>madam</u> madam is palindrome</td>

   <td width="303">Enter the First Name:<u>Madam</u>Madam is not palindrome</td>

  </tr>

  <tr>

   <td width="303"><strong>Example-3 </strong></td>

   <td width="303"><strong>Example-4 </strong></td>

  </tr>

  <tr>

   <td width="303">Enter the First Name:<u>ANNA</u>ANNA is palindrome</td>

   <td width="303">Enter the First Name: <u>mark</u> mark is not palindrome</td>

  </tr>

 </tbody>

</table>