What I learned in JavaScript
[[HTML]][[CSS]][[Linux]]

**  

defer = <script src\="script.js" defer\></script\>  so it loads after the whole page is parsed.

Bubbling in event listeners move up the tree, inner towards outer element

Capturing in event listeners moves from outer element to inner element

e.stopPropagation() stops event from continuing through the capture or bubble phases

You can have an event run an event once and then remove itself from the propagation

{ once: True }

.removeRemoveEventListener

  

CODE OUTPUT

\\’ single quote

\\” double quote

\\\\ backslash

\\n newline

\\r carriage return

\\t tab

\\b backspace

\\f form feed

  

 defer inside the script of the HTML 

  

 prompt()

  

 window object 40:40

  

Immediately invoked function expression 42:15

  

VARIABLES

Review Variables

Nice work! This lesson introduced you to variables, a powerful concept you will use in all your future programming endeavors.

Let’s review what we learned:

-   Variables hold reusable data in a program and associate it with a name.
    
-   Variables are stored in memory.
    
-   The var keyword is used in pre-ES6 versions of JS.
    
-   let is the preferred way to declare a variable when it can be reassigned, and const is the preferred way to declare a variable with a constant value.
    
-   Variables that have not been initialized store the primitive data type undefined.
    
-   Mathematical assignment operators make it easy to calculate a new value and assign it to the same variable.
    
-   The + operator is used to concatenate strings including string values held in variables
    
-   In ES6, template literals use backticks \` and ${} to interpolate values into a string.
    
-   The typeof keyword returns the data type (as a string) of a value.
    

### Instructions

To learn more about variables take on these challenges!

-   Create variables and manipulate the values
    
-   Check what happens when you try concatenating strings using variables of different data types
    
-   Interpolate multiple variables into a string
    
-   See what happens when you use console.log() on variables declared by different keywords (const, let, var) before they’re defined. For example:
    

console.log(test1);

const test1 = 'figuring out quirks';

-   Find the data type of a variable’s value using the typeof keyword on a variable.
    
-   Use typeof to find the data type of the resulting value when you concatenate variables containing two different data types.
    

  
  

Example:

 var myString = “FirstLine\\n\\t\\\\SecondLine\\nThirdLine”

  

// Example Concantinating

var ourStr \= "I come first. " + "I come second."

console.log(ourStr)

var joinThis \= " I come last."

console.log(ourStr + joinThis)

joinThis += " Concantinating "

console.log(joinThis)

  

I come first. I come second.

›

I come first. I come second. I come last.

I come last. Concantinating.

  

![](https://lh3.googleusercontent.com/DOQvd52nrHnKq2NRvdeseqw_8IFXQGBb3M35Su1Mq-KHgPk6FEwV19z1DpT86TecMVjYtOBTZ1wd_fBBD_21U6t7sbDvx_iNpU1SBVOH_wXwiXkAPfdct_7L_yoDYVoX3TNcd8ho)

![](https://lh4.googleusercontent.com/GRDn5-g9Jf0FP3cUusErkvuz15kSfAGiWniSlQ-loTmLbc6ayiBje0BAJ5AWvBahci3FRgAuBqvdSS0jVf0bbAtmfUOfwg1qYU56EObYxvDYx-sYaagx1RFp5SUakBKE2mZJxxha)

![](https://lh5.googleusercontent.com/zStCSvqOJMBczvDr4VqLTeI-5Y4u2BmvOYT9PF4o_k11FdcALE3iQy4Vdk_IhHcapEA6gDFfULKNaAi7HtaUu46F9_BkiuHZ85ECVBcisqDYSgiNCPFQ5zas2vq2ZdawP9LUmYHX)

Concatenating Strings with Plus Operator

In JavaScript, when the + operator is used with a String value, it is called the concatenation operator. You can build a new string out of other strings by concatenating them together.

  

Example

  

'My name is Alan,' + ' I concatenate.'

Note: Watch out for spaces. Concatenation does not add spaces between concatenated strings, so you'll need to add them yourself.

  

Example:

  

var ourStr = "I come first. " + "I come second.";

The string I come first. I come second. would be displayed in the console.

  

Build myStr from the strings This is the start. and This is the end. using the + operator.

  

var myStr \= "This is the start. " + "This is the end.";

  

Concatenating Strings with the Plus Equals Operator

We can also use the += operator to concatenate a string onto the end of an existing string variable. This can be very helpful to break a long string over several lines.

  

Note: Watch out for spaces. Concatenation does not add spaces between concatenated strings, so you'll need to add them yourself.

  

Example:

var ourStr = "I come first. ";

ourStr += "I come second.";

  

ourStr now has a value of the string I come first. I come second..

  

Build myStr over several lines by concatenating these two strings: This is the first sentence. and This is the second sentence. using the += operator. Use the += operator similar to how it is shown in the editor. Start by assigning the first string to myStr, then add on the second string.

var myStr \= "This is the first sentence. ";

myStr += "This is the second sentence."

  

Constructing Strings with Variables

Sometimes you will need to build a string, [Mad Libs](https://en.wikipedia.org/wiki/Mad_Libs) style. By using the concatenation operator (+), you can insert one or more variables into a string you're building.

Example:

  

var ourName = "freeCodeCamp";

var ourStr = "Hello, our name is " + ourName + ", how are you?";

  

ourStr would have a value of the string Hello, our name is freeCodeCamp, how are you?.

---

Set myName to a string equal to your name and build myStr with myName between the strings My name is and and I am well!

  

var myName \= "Charlie";

var myStr \= "My name is " + myName + "and I am well!";

  

![](https://lh4.googleusercontent.com/EoqwFWReotmM9n6pbG1dQnG4w3K9P46WomlYpvpbwoviZce7-AjcLk_1r6NmAAYYbZmoZ4J3L566RwsvoNIKcHPne6CXPwmnhfyAJAFN3PG-3JaYlsgymTI_8TZRJMsXxdtA40Nd)

![](https://lh4.googleusercontent.com/8TzuB7Be2WhgT9_LUcM7xkPyAW83s5L7_idl7-zd0A9_Q6gioyY0qfipoROh2hIYdavzpCXDFy9tPNdWBSJlF09tQ9wuyFnvzCqxwokVEQoqD0DVCZU9OzqQHDT5vbv03adHf1oy)

  

.push() adds to the end of an array;

.pop() removes the last value of an array;

.shift() removes first value of the array;

.unshift() adds the first value of an array;

  

running .shift() and then running .unshift() would remove the first value then add a new value to the array.

  

Nesting arrays inside arrays,

var myList \= \[\["Chocolate Bar", 5\], \["Milk", 2\], \["Banana", 5\], \["Cereal", 4\], \["Oranges", 6\]\];

Make sure to put “,” between arrays.

  

![](https://lh4.googleusercontent.com/52axQQGbneUHkb6D91f0ZAkG4ZMnfDgLrR4OH0smCK6X6X2qY4vVzZ3HlTFKf0_ZcZlHO1X8j9r-oBX22WJw_kasApofvEvb5Opd_TdEeXktI9kWHov9UIrEJM6hh8OM7I_8J0hJ)

  

![](https://lh3.googleusercontent.com/Qfar6BKR0Al-2cRoBsSmV7jsM53XfHaCYO9ayksdkZvSC1ki1L11tRUZP95x5xTQ2hfJdFeeJuqlFKLBWAyjg_gbM6lAGZLnDokf_T7r7J33O-zfjwBio33FabpT0NDv5N0ewIXn)

Would print/console.log()

![](https://lh5.googleusercontent.com/r0X9GjtmY6MmtCnxpTTEwoDWLll6nzzi9NsyiDYoKQVbTHwz90SBqWM2vKI08aap4hWbX-Eh04HvYe6rhnD-4k86zaJY6RzsKrVfVcyE-O8ZG1LTf3LX_j_sreeYQNJdPa3m3M_c)

![](https://lh6.googleusercontent.com/dJ_-9lrmxH-7aoI8zBPLZdn9kfI130xO37lOq8UfaVqDhQsqBLq-9LFUU7UwHN_8NIhNPTVmZCf3EF9QbQtM-j6AvnrujJ1TWjLW37wlYU6lOpk_7zWPjPV-zZviAvvF7z2w8FSs)

![](https://lh5.googleusercontent.com/o0Qx5YFGpT4Ax6kAG1TpKJ48NG4TYOCDbx01EBsvmjAFD7ALq4oiNtyke14k2I4SzK9b7wMdgne4obDMu8xgZZq9G0X35PFe2NeArQ7uaYBhwLMOzyw3_pd6hKkf1XWE06RJ5zLn)

![](https://lh3.googleusercontent.com/j8CfFqCZm5EY1-rBmZVM7_o-_gnHa_Qv0ldLbRQF8uekw_om7V1Pb--IWXUqEhchGSC00n91vkelR4BNE_BHEUlNoOvPKY5PhbA84Fjm4FD54t0Exxybj592bagtbVYCodf0phuE)

![](https://lh5.googleusercontent.com/vPameA8SwOtbCjDSbVPoU0yRuE6MNHjyp7wdahAhcK3rD5ovOUmFiETWnXRNlp1lN9ZzYOdqXPN95SRQl5EPfTGhFeqAADXWbuw1vUTLa_ZJoBjbsTG9EvwcuBWgOYPdOHQX2_-2)

![](https://lh4.googleusercontent.com/ixK0f5dHOG4-RA7x4PMTNIztV_qd5Bif4v9HbWbev5jq-FzAO3KYAA-A2AkQ7B1R-DDqYTzpaI0tgpXZiFNLX7vJyeCE5pD94uPLCnwrcqwh9EfcBNys8CxiZouW4Wgz70gAma4W)

![](https://lh5.googleusercontent.com/oeubK2-s9ODNtlkGqFiMUAlb_nfkkOlFypjHmF_YB696YY0dNFtxC8dTRtTssRkvvfh9oRUJChbgDhvWZJlFkcg5HSQiByUkgTdUJMswJoMta9127It7C2E357lnHMx57vroM8rq)

![](https://lh3.googleusercontent.com/p_BZ741kHDRdWXjh0qCF-Z5YVfhQle5w8HQYKAqgeWXMUDom6zu9GAJowi-R1F-R0QKlYcGmpaIRG1YekPvs8Zf_y1zjFkAZqE2iiTXV1VYydY3mKpsvmVBEnUKTgwYb8MGPpYuS)

  

![](https://lh4.googleusercontent.com/nwdM5YNodpNwjedq4KAFrXBW_R-PiNjL0jnkUh0jFR23HnqWGAD9Vr90zRB3r0kYyamNMDSbvxIZ2nT8DEON67476V99AkmtDcSiTsKVbQ9_jn97-jl20plX7-TuBEGqYS0uC0Gf)

  

# Inequality (!=)

The inequality operator ([!=](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Inequality)) checks whether its two operands are not equal, returning a Boolean result. Unlike the [strict inequality](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Strict_inequality) operator, it attempts to convert and compare operands that are of different types.

![](https://lh3.googleusercontent.com/GajZaQos38qWGWwneCyDef2eFaOu2GN_zt_525XhOI8vfGUv2qg-neWptmQ3W9KZAFxTRkJS9OEguW65d51HXX4i5qgPavCaBwtlA0o2CyChx5qXDlMQrqeewwVZ0v9ZN0rY6Zjo)

  

!== Strict inequality (!==)

The strict inequality operator (!==) checks whether its two operands are not equal, returning a Boolean result. Unlike the [inequality](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Inequality) operator, the strict inequality operator always considers operands of different types to be different.

![](https://lh3.googleusercontent.com/RZ0wndwC2vECj-rrJEFecl7dzcO6fHxkXUf6eiryf_kDwnxyDDIOkuupL9LE4xyvEY-u0ru_k7Tympr60YfWRUuDUHs5HxsHwIsSOqTtyggub1wiDQMS34xQ180W8a2-n_yEiRIW)

![](https://lh6.googleusercontent.com/nOb5dmz5zn7RZxqelcvtxXxxU2SKXtA-94xaoYbQm1-FKVIe3pqocyCcSzKf2gLuvN3VnJeauk9ETUvOf8hxksDqQstcA5GOJRcYR0A9YGymKz-mVbd_IggIB5SDkOz2m-3YXhJS)

![](https://lh3.googleusercontent.com/YoWT73Ko_21iN02WDlwgE7cM0bHo_b9QiQ1vzOQtFq3YCxMgqkKIFCCRE7o7-23N4shCRokmIZJURwPm-6H9w5igyH5LK5L6azfE6R_CQ_q2tnBSXUdYr8u8YIKol_scmvuStw2O)

  

![](https://lh6.googleusercontent.com/55WtL-DenatTQ3yIR7S6RqjuxDge4G79HV0HF2Q35huwmZwiijUbGrRFyGrmEfgzuo1xACxT9g862u9i0p8nyd1pYhmBF9re_bBxqE8kA8bA5ig-HKNNhd4_QpdVMSGwlPh1AcIp)

![](https://lh4.googleusercontent.com/v9ka0qASJXfUcG09FEFiAwWl_igmK1rK9UdJnRl_i_Hsh_sMNoDjw7eKB3IqThS9HtmPaENDhWsuCdR3j9U9HuxCDF2cwP9-g_ldJ9wsdjKZS-LDWOjt1UnArOYnYw6gG4UDv2Yq)![](https://lh3.googleusercontent.com/M7kystfWW0PMMFWiIxrScki-KN433jbSCPNut9MFt4ODnyE6QG5TQdlfJYUn6AEZyk-H0j0LOfV6U1Zjxvdnna5HDoH2auThLELX-ODH9PmTafjF7lt1L-1jzzOB9F9V5eH1jLxR)

![](https://lh4.googleusercontent.com/tjE0Q3ytxp-gb9GPSSFc_9iERxkBG4q4ihasvSNJn3F_amHuO7FTSs6b9rQM4yw3lK7bJT36mHDE90ayQMRjf2XEMTDXNUs8n966PX1obIzir-DrpTwl7ds7Fs3t9NdwKtHsGgb5)

![](https://lh3.googleusercontent.com/f4X3DbvildWFCwZXEyNxM7iYwhsZukHCBm9O9Kmy6mzqQ6ZOdITI1vH6Dk2KVXoUxV01kzdaQmUyGLXCnSa3WJT-SD-tvhDPJphxyLCzDKcOIx8znt7L8fhhBiXPXPT4CO_7NH6k)

![](https://lh4.googleusercontent.com/eAXjeZfmr1c8MASgH3LozzdmGGCF5py2c1yvEb2MjAddQzCm-b1bWpM_miCeXx88o-0KDbDIZq6TO1cq3HFIKWCJVHE25-Fwg3aDhyjLjhAyEf91aENxiljFgyO9hhUE4bxInT-S)

Would console.log() 40

  

![](https://lh6.googleusercontent.com/Sb9OtgclyfdQUxhTmmKBegu4Y9MastdNMnD3UhFW9WCfiwJFzaTqbl_FCpGSC4L8tcbe9RziVaWTXwskHn8X9TwurkmetXiBYY1SsSxW1JrVSOL_IidyR318Jz5L0M1MfcG5Fy5W)

![](https://lh5.googleusercontent.com/Vrk9XSzfp-UxXLrd8NyhLfd47E_H6xneT-dC1VW9vT-b6_6JXFZ4kd1NNSArw15rBRxVKvs5jFmuKvucXh3Cb6Jczqvd5EUOy_sCeEdfqiP76denLUOMkCVaihT40ElIY4l3FWjF)

![](https://lh3.googleusercontent.com/yHfHCW9yheXK2hmN3EUx1mX-8pPKrt-d4Qe3zOXGWB5bl6Sq73Ue-IACSy5ddLKou8K6cYwTDUuU7-k9o3_jK1M9HWHnPmYrXmY5JszJJy7QRv2Le7dRBOigXqQ0NSIaWHMECbTP)

![](https://lh3.googleusercontent.com/Xd9Rb7pat0POBdV_Oc8F9LkuESu-0EUM1gR9pbNFP2Zw-H-ueux8hXEKOUE-LUI-BW2Xoq3pEHcYBiKaJYH9kuKSprxILrG0-W7p94qiV--RohXXh59qdPgySO1PTIZYTzZzCshM)

  

![](https://lh6.googleusercontent.com/wdgcvysu0ZHJxHGZUdBl5G_-XVaDMunh94-wocslDTBXq5MKrygDs7A2oMNfnMpfbOpU_hcheIqa5aw-HLMOTSPA48HUPjPje7DigtOxafT8SRAf8kyeYeY-o_V2KgV9Ff_l0XcX)

![](https://lh6.googleusercontent.com/fNEtYVM3h1abaAVOGBjZodtwYDZu5FZ6QlljIUgR72U8j-EhiDNwqZ3-o7aDC6FXAkgA9dojJPQd9enycV313VpsyvrEN8CHYHyKiMZsYPcls9oELOXIlrRXadlDmB8GXoeBNeJ5)

![](https://lh6.googleusercontent.com/FAN0OUz1IWIRkVl0XHCzR8qCL9pqYYVpG67cBhURJHpVh8BuDT3op47bTva133swpzYvDYlb9iXOlqJccrCDXchhVy63cD84mMuxJ3jJKip-xJGRGgbXJXgLZwwfGTSb65Xg2hJJ)

  
  
  
  
  
  

![](https://lh6.googleusercontent.com/Ti_FvGnIsmojZJ2aGDxbRLlKGoEpkv9DuWUn6tNlWxfwxsg8thhXt-ObIx8HndAXrwsR5KuQOohzeVD9wKRC7-wkLeG5Eyc6JMO-NbinJXLKrvFzwei7UWQ1QyrV_7RG3c6J40J6)

![](https://lh5.googleusercontent.com/xp_LmNEZ2UlTzZRP1VxKidCLNBf8uir7K2pIXqAWO6Tv1qbqUQ3HG1kmpC5xMsuoRXzismCuWVMVtL6_uEuVCRIwsaktm64U2jyD03Wdur92u3b4TNT8orFNErnGI3PAKVlFgxao)

  

![](https://lh4.googleusercontent.com/avojPHNEfYLZ0B0x3LdG3XevNWx83UjbBrW4etdD_GVE_x6yvwOstXDAd3KjlycefHlWwdmYbBPtqK0dzJuazXStA1qEfYwuPh-8feJUIlGJ5Hzx8EuerqBs8n-CD8DQOewId4Oe)

  

Use Conditional Logic with If Statements

If statements are used to make decisions in code. The keyword if tells JavaScript to execute the code in the curly braces under certain conditions, defined in the parentheses. These conditions are known as Boolean conditions and they may only be true or false.

When the condition evaluates to true, the program executes the statement inside the curly braces. When the Boolean condition evaluates to false, the statement inside the curly braces will not execute.

Pseudocode

if (condition is true) {

 statement is executed

}

Example

function test (myCondition) {

 if (myCondition) {

 return "It was true";

 }

 return "It was false";

}

test(true);

test(false);

test(true) returns the string It was true, and test(false) returns the string It was false.

When test is called with a value of true, the if statement evaluates myCondition to see if it is true or not. Since it is true, the function returns It was true. When we call test with a value of false, myCondition is not true and the statement in the curly braces is not executed and the function returns It was false.

---

Create an if statement inside the function to return Yes, that was true if the parameter wasThatTrue is true and return No, that was false otherwise.

  

function trueOrFalse(wasThatTrue) {

 // Only change code below this line

 if(wasThatTrue) {

 return "Yes, that was true"

 }

 return "No, that was false"

 // Only change code above this line

}

trueOrFalse(true);

trueOrFalse(false);

Comparison with the Equality Operator

There are many comparison operators in JavaScript. All of these operators return a boolean true or false value.

The most basic operator is the equality operator \==. The equality operator compares two values and returns true if they're equivalent or false if they are not. Note that equality is different from assignment (\=), which assigns the value on the right of the operator to a variable on the left.

function equalityTest(myVal) {

 if (myVal \== 10) {

 return "Equal";

 }

 return "Not Equal";

}

If myVal is equal to 10, the equality operator returns true, so the code in the curly braces will execute, and the function will return Equal. Otherwise, the function will return Not Equal. In order for JavaScript to compare two different data types (for example, numbers and strings), it must convert one type to another. This is known as Type Coercion. Once it does, however, it can compare terms as follows:

  
  
  

1 \== 1

1 \== 2

1 \== '1'

"3" \== 3

In order, these expressions would evaluate to true, false, true, and true.

---

Add the equality operator to the indicated line so that the function will return the string Equal when val is equivalent to 12.

// Setup

function testEqual(val) {

 if (val \== 12) { // Change this line

 return "Equal";

 }

 return "Not Equal";

}

testEqual(10);

Comparison with the Strict Equality Operator

Strict equality (\===) is the counterpart to the equality operator (\==). However, unlike the equality operator, which attempts to convert both values being compared to a common type, the strict equality operator does not perform a type conversion.

If the values being compared have different types, they are considered unequal, and the strict equality operator will return false.

Examples

3 \=== 3

3 \=== '3'

These conditions would return true and false respectively.

In the second example, 3 is a Number type and '3' is a String type.

---

Use the strict equality operator in the if statement so the function will return the string Equal when val is strictly equal to 7

// Setup

function testStrict(val) {

 if (val \=== 7) { // Change this line

 return "Equal";

 }

 return "Not Equal";

}

testStrict(7);

Practice comparing different values

In the last two challenges, we learned about the equality operator (\==) and the strict equality operator (\===). Let's do a quick review and practice using these operators some more.

If the values being compared are not of the same type, the equality operator will perform a type conversion, and then evaluate the values. However, the strict equality operator will compare both the data type and value as-is, without converting one type to the other.

Examples

3 == '3' returns true because JavaScript performs type conversion from string to number. 3 === '3' returns false because the types are different and type conversion is not performed.

Note: In JavaScript, you can determine the type of a variable or a value with the typeof operator, as follows:

typeof 3

typeof '3'

typeof 3 returns the string number, and typeof '3' returns the string string.

---

The compareEquality function in the editor compares two values using the equality operator. Modify the function so that it returns the string Equal only when the values are strictly equal.

// Setup

function compareEquality(a, b) {

 if (a \=== b) { // Change this line

 return "Equal";

 }

 return "Not Equal";

}

compareEquality(10, "10");

Comparison with the Inequality Operator

The inequality operator (!=) is the opposite of the equality operator. It means not equal and returns false where equality would return true and vice versa. Like the equality operator, the inequality operator will convert data types of values while comparing.

Examples

1 != 2

1 != "1"

1 != '1'

1 != true

0 != false

In order, these expressions would evaluate to true, false, false, false, and false.

---

Add the inequality operator != in the if statement so that the function will return the string Not Equal when val is not equivalent to 99

// Setup

function testNotEqual(val) {

 if (val != 99) { // Change this line

 return "Not Equal";

 }

 return "Equal";

}

testNotEqual(10);

Comparison with the Strict Inequality Operator

The strict inequality operator (!==) is the logical opposite of the strict equality operator. It means "Strictly Not Equal" and returns false where strict equality would return true and vice versa. The strict inequality operator will not convert data types.

Examples

3 !== 3

3 !== '3'

4 !== 3

In order, these expressions would evaluate to false, true, and true.

---

Add the strict inequality operator to the if statement so the function will return the string Not Equal when val is not strictly equal to 17

// Setup

function testStrictNotEqual(val) {

 if (val !== 17) { // Change this line

 return "Not Equal";

 }

 return "Equal";

}

testStrictNotEqual(10);

Comparison with the Greater Than Operator

The greater than operator (\>) compares the values of two numbers. If the number to the left is greater than the number to the right, it returns true. Otherwise, it returns false.

Like the equality operator, the greater than operator will convert data types of values while comparing.

Examples

5 \> 3

7 \> '3'

2 \> 3

'1' \> 9

In order, these expressions would evaluate to true, true, false, and false.

---

Add the greater than operator to the indicated lines so that the return statements make sense.

function testGreaterThan(val) {

 if (val \> 100) { // Change this line

 return "Over 100";

 }

 if (val \> 10) { // Change this line

 return "Over 10";

 }

 return "10 or Under";

}

testGreaterThan(10);

Comparison with the Greater Than Or Equal To Operator

The greater than or equal to operator (\>=) compares the values of two numbers. If the number to the left is greater than or equal to the number to the right, it returns true. Otherwise, it returns false.

Like the equality operator, the greater than or equal to operator will convert data types while comparing.

Examples

6 \>= 6

7 \>= '3'

2 \>= 3

'7' \>= 9

In order, these expressions would evaluate to true, true, false, and false.

---

Add the greater than or equal to operator to the indicated lines so that the return statements make sense.

function testGreaterOrEqual(val) {

 if (val \>= 20) { // Change this line

 return "20 or Over";

 }

 if (val \>= 10) { // Change this line

 return "10 or Over";

 }

 return "Less than 10";

}

testGreaterOrEqual(10);

Comparison with the Less Than Operator

The less than operator (<) compares the values of two numbers. If the number to the left is less than the number to the right, it returns true. Otherwise, it returns false. Like the equality operator, the less than operator converts data types while comparing.

Examples

2 < 5

'3' < 7

5 < 5

3 < 2

'8' < 4

In order, these expressions would evaluate to true, true, false, false, and false.

---

Add the less than operator to the indicated lines so that the return statements make sense.

function testLessThan(val) {

 if (val < 25) { // Change this line

 return "Under 25";

 }

 if (val < 55) { // Change this line

 return "Under 55";

 }

 return "55 or Over";

}

testLessThan(10);

Comparison with the Less Than Or Equal To Operator

The less than or equal to operator (<=) compares the values of two numbers. If the number to the left is less than or equal to the number to the right, it returns true. If the number on the left is greater than the number on the right, it returns false. Like the equality operator, the less than or equal to operator converts data types.

Examples

4 <= 5

'7' <= 7

5 <= 5

3 <= 2

'8' <= 4

In order, these expressions would evaluate to true, true, true, false, and false.

---

Add the less than or equal to operator to the indicated lines so that the return statements make sense.

function testLessOrEqual(val) {

 if (val <= 12) { // Change this line

 return "Smaller Than or Equal to 12";

 }

 if (val <= 24) { // Change this line

 return "Smaller Than or Equal to 24";

 }

 return "More Than 24";

}

testLessOrEqual(10);

Comparisons with the Logical And Operator

Sometimes you will need to test more than one thing at a time. The logical and operator (&&) returns true if and only if the operands to the left and right of it are true.

The same effect could be achieved by nesting an if statement inside another if:

if (num \> 5) {

 if (num < 10) {

 return "Yes";

 }

}

return "No";

will only return Yes if num is greater than 5 and less than 10. The same logic can be written as:

if (num \> 5 && num < 10) {

 return "Yes";

}

return "No";

---

Replace the two if statements with one statement, using the && operator, which will return the string Yes if val is less than or equal to 50 and greater than or equal to 25. Otherwise, will return the string No.

function testLogicalAnd(val) {

 // Only change code below this line

 if (val \>= 25 && val <= 50) {

 return "Yes";

 }

 // Only change code above this line

 return "No";

}

testLogicalAnd(10);

Comparisons with the Logical Or Operator

The logical or operator (||) returns true if either of the operands is true. Otherwise, it returns false.

The logical or operator is composed of two pipe symbols: (||). This can typically be found between your Backspace and Enter keys.

The pattern below should look familiar from prior waypoints:

if (num \> 10) {

 return "No";

}

if (num < 5) {

 return "No";

}

return "Yes";

will return Yes only if num is between 5 and 10 (5 and 10 included). The same logic can be written as:

if (num \> 10 || num < 5) {

 return "No";

}

return "Yes";

---

Combine the two if statements into one statement which returns the string Outside if val is not between 10 and 20, inclusive. Otherwise, return the string Inside.

function testLogicalOr(val) {

 // Only change code below this line

 if (val < 10 || val \> 20) {

 return "Outside";

 }

 // Only change code above this line

 return "Inside";

}

testLogicalOr(15);

  

Introducing Else Statements

When a condition for an if statement is true, the block of code following it is executed. What about when that condition is false? Normally nothing would happen. With an else statement, an alternate block of code can be executed.

if (num \> 10) {

 return "Bigger than 10";

} else {

 return "10 or Less";

}

  
  
  
  

---

Combine the if statements into a single if/else statement.

  
  
  
  
  
  

function testElse(val) {

 var result \= "";

 // Only change code below this line

 if (val \> 5) {

 result \= "Bigger than 5";

 } else {

 result \= "5 or Smaller";

 }

 // Only change code above this line

 return result;

}

testElse(4);

  

Introducing Else If Statements

If you have multiple conditions that need to be addressed, you can chain if statements together with else if statements.

if (num \> 15) {

 return "Bigger than 15";

} else if (num < 5) {

 return "Smaller than 5";

} else {

 return "Between 5 and 15";

}

---

Convert the logic to use else if statements.

function testElseIf(val) {

 if (val \> 10) {

 return "Greater than 10";

 } else if (val < 5) {

 return "Smaller than 5";

 } else {

 return "Between 5 and 10";

}

}

testElseIf(7);

  

Logical Order in If Else Statements

Order is important in if, else if statements.

The function is executed from top to bottom so you will want to be careful of what statement comes first.

Take these two functions as an example.

Here's the first:

function foo(x) {

 if (x < 1) {

 return "Less than one";

 } else if (x < 2) {

 return "Less than two";

 } else {

 return "Greater than or equal to two";

 }

}

And the second just switches the order of the statements:

function bar(x) {

 if (x < 2) {

 return "Less than two";

 } else if (x < 1) {

 return "Less than one";

 } else {

 return "Greater than or equal to two";

 }

}

While these two functions look nearly identical if we pass a number to both we get different outputs.

foo(0)

bar(0)

foo(0) will return the string Less than one, and bar(0) will return the string Less than two.

---

Change the order of logic in the function so that it will return the correct statements in all cases.

  

function orderMyLogic(val) {

 if (val < 5) {

 return "Less than 5";

 } else if (val < 10) {

 return "Less than 10";

 } else {

 return "Greater than or equal to 10";

 }

}

orderMyLogic(7);

  

function testSize(num) {

 // Only change code below this line

 if (num < 5) {

 return "Tiny";

 } else if (num <10)

 return "Small";

 else if (num < 15)

 return "Medium";

 else if (num < 20)

 return "Large";

 else {

 return "Huge"

 }

 return "Change Me";

 // Only change code above this line

}

testSize(7);

  

CONDITIONAL STATEMENTS

Logical Operators

Working with conditionals means that we will be using booleans, true or false values. In JavaScript, there are operators that work with boolean values known as logical operators. We can use logical operators to add more sophisticated logic to our conditionals. There are three logical operators:

-   the and operator (&&)
    
-   the or operator (||)
    
-   the not operator, otherwise known as the bang operator (!)
    

When we use the && operator, we are checking that two things are true:

if (stopLight === 'green' && pedestrians === 0) {

 console.log('Go!');

} else {

 console.log('Stop');

}

When using the && operator, both conditions must evaluate to true for the entire condition to evaluate to true and execute. Otherwise, if either condition is false, the && condition will evaluate to false and the else block will execute.

If we only care about either condition being true, we can use the || operator:

if (day === 'Saturday' || day === 'Sunday') {

 console.log('Enjoy the weekend!');

} else {

 console.log('Do some work.');

}

When using the || operator, only one of the conditions must evaluate to true for the overall statement to evaluate to true. In the code example above, if either day === 'Saturday' or day === 'Sunday' evaluates to true the if‘s condition will evaluate to true and its code block will execute. If the first condition in an || statement evaluates to true, the second condition won’t even be checked. Only if day === 'Saturday' evaluates to false will day === 'Sunday' be evaluated. The code in the else statement above will execute only if both comparisons evaluate to false.

The ! not operator reverses, or negates, the value of a boolean:

let excited = true;

console.log(!excited); // Prints false

let sleepy = false;

console.log(!sleepy); // Prints true

Essentially, the ! operator will either take a true value and pass back false, or it will take a false value and pass back true.

Logical operators are often used in conditional statements to add another layer of logic to our code.

1.

In main.js there are two variables mood and tirednessLevel.

Let’s create an if...else statement that checks if mood is 'sleepy' and tirednessLevel is greater than 8.

If both conditions evaluate to true, then console.log() the string 'time to sleep'. Otherwise, we should console.log() 'not bed time yet'.

After you press “Run”, play around with the || operator and the ! operator! What happens if you negate the value of the entire statement with ! and switch to || instead of &&?

  

INTRODUCTION TO JAVASCRIPT

Review

Let’s take one more glance at the concepts we just learned:

-   Data is printed, or logged, to the console, a panel that displays messages, with console.log().
    
-   We can write single-line comments with // and multi-line comments between /\* and \*/.
    
-   There are 7 fundamental data types in JavaScript: strings, numbers, booleans, null, undefined, symbol, and object.
    
-   Numbers are any number without quotes: 23.8879
    
-   Strings are characters wrapped in single or double quotes: 'Sample String'
    
-   The built-in arithmetic operators include +, \-, \*, /, and %.
    
-   Objects, including instances of data types, can have properties, stored information. The properties are denoted with a . after the name of the object, for example: 'Hello'.length.
    
-   Objects, including instances of data types, can have methods which perform actions. Methods are called by appending the object or instance with a period, the method name, and parentheses. For example: 'hello'.toUpperCase().
    
-   We can access properties and methods by using the ., dot operator.
    
-   Built-in objects, including Math, are collections of methods and properties that JavaScript provides.
    

let tool = ‘’;

let tool = '';

// Use short circuit evaluation to assign  writingUtensil variable below:

let writingUtensil = tool || 'pen';

console.log(\`The ${writingUtensil} is mightier than the sword.\`);

**