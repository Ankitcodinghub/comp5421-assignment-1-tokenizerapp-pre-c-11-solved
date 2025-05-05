# comp5421-assignment-1-tokenizerapp-pre-c-11-solved
**TO GET THIS SOLUTION VISIT:** [COMP5421 Assignment 1-TokenizerApp_pre-C++11 Solved](https://www.ankitcodinghub.com/product/comp5421-assignment-1-tokenizerapp_pre-c11-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99988&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP5421 Assignment 1-TokenizerApp_pre-C++11 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1 Background

Among all commonly used features of the C++ programming language, the concept of pointers can at first cause confusion for programmers new to C++. With that in mind, introductory C++ courses typically dispense with concept of pointers altogether, focusing on basic C++ programming concepts instead.

In higher-level C++ courses, including this one, however, the concept and use of pointers cannot be completely escaped because pointers have a pervasive presence in the language. That is not to suggest that your C++ programs must necessarily involve the use of pointers. In fact, you can write substantial C++ programs without getting involved directly with pointers, replacing them (if and when needed) with the C++ smart pointers. Nevertheless, the more fluent you are with both smart and dumb (raw) pointers, the better equipped you will be to use them effectively as indispensable C++ tools.

Other C++ features that can at first surprise programmers new to C++ include rvalues, lvalues, references, and, in particular, the following five special member functions of a C++ class:

􏰀 default constructor, copy constructor, and copy assignment, since C++98, and 􏰀 move constructor and move assignment since C++11

– they take advantage of move semantics, a major C++11 feature

Fortunately, any potentially confusing notion related to pointers or the special member functions of a class can quickly become second nature with practice, enabling you to better understand and appreciate “modern” features of “modern C++.”1

2 Objectives

This assignment is designed to get you started with C++ giving you practice with writing classes that involve pre-C++11 topics such as raw arrays, pointers, and memory management.

Those of you who are new to C++ might find this first assignment a bit challenging, but you will also feel a sense of accomplishment in your own work after completing the assignment.

To facilitate the challenge, however, this assignment provides a simple design for the program you will develop, describing it in detail using UML class diagram notations.

1Currently C++20, primarily based on the revolutionary C++11 standard.

Assignment 1, Rev.1, Summer 2021 page 1 of 19

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
3 Splitting Text into Tokens

In this assignment, a text token is a sequence of contiguous characters excluding white-space characters such as space, tab, and newline characters. For example, the words in a sentence are tokens but the tokens in line of text may comprise any characters except white-spaces. Just as alphabet letters, single quotes and hyphens are typically allowed in a word, as in it’s and white-space, all characters are allowed in a token, as in 7Up and o.20%.

4 Your Task

Develop a program to build an index of all the tokens that appear in a given file of text, keeping track of the line numbers of the lines in the input file that contain the tokens.

The program should accept the name of a text file, read the contents of that file line by line, splitting each line into tokens and reflecting each token into a sorted list of tokens encountered so far.

Specifically, given a token that is not currently in the list, the program should insert the token at its sorted position in the list; otherwise, the program should update the list of the line numbers associated with that token by adding the current line number to the list.

Finally, the program should display the resulting index, formatting it similarly to an index at the end of a typical textbook.

5 Reinventing the wheel

Your task includes “reinventing” data structures that will implement a very small set of operations readily provided by the highly optimized C++ standard class templates &lt;string&gt;, list&lt;T&gt; and vector&lt;T&gt;.

Bear in mind that there is absolutely no justifiable reason to reinvent the wheel here other than to gain insight into underlying complexities of dynamic resource management in C++. So please do not get used to this legacy style of coding, as it could cost you points in class or at work.

The remaining assignments in this course will require that you leverage the C++ standard library, using its efficient data structures and algorithms to implement specified requirements.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 2 of 19

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
6 Specification

Your program is required to be structured as indicated by the UML class diagram shown below:

</div>
</div>
<div class="layoutArea">
<div class="column">
Token

1 1

TNode

* 11

</div>
<div class="column">
1 1

1

next node

</div>
<div class="column">
IntList

</div>
</div>
<div class="layoutArea">
<div class="column">
1 prev node

</div>
</div>
<div class="layoutArea">
<div class="column">
a node in a list

</div>
<div class="column">
a node in a list

</div>
</div>
<div class="layoutArea">
<div class="column">
1

+

</div>
</div>
<div class="layoutArea">
<div class="column">
TokenizerApp

</div>
<div class="column">
1

</div>
</div>
<div class="layoutArea">
<div class="column">
*

</div>
<div class="column">
TList

</div>
</div>
<div class="layoutArea">
<div class="column">
The UML class diagram above depicts common data structures that you have studied and probably implemented in your data structures course.

Class Token models the tokens in the input file of text, storing a token’s text in a dynamic array of characters, and outsourcing the management of the list of the line numbers associated with that token to an object of the IntList class.

A self-referential class, TNode models the nodes in a linked list, with each node storing a token and pointers to the next and previous neighboring nodes in the list.

An object of class TList creates, links, and manages a linked list of TNode objects. The small round symbol indicates that class TList completely encloses class TNode as a “member type”, effectively hiding TNode from clients of TList by applying the principle of information hiding.

Class TokenizerApp represents a very simple application of a TList object. Reading from a given input file of text one line at a time, a TokenizerApp object extracts the tokens from the input lines and reflects them into a growing sorted list of tokens.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 3 of 19

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
7 Class IntList

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
IntList

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
− dynarray : int * − capacity : int − used : int

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
+ IntList():

+ IntList(array : const IntList&amp; ):

+ IntList(array : IntList&amp;&amp; ):

+ operator=(const IntList&amp; rhs):IntList&amp; + operator=(IntList&amp;&amp; rhs): IntList&amp;

+ ∼IntList() :

+ empty() : bool

+ full() : bool

+ size() : int

− resize() : void

+ pushBack(x : int) : void

+ contains( x : int) : bool

+ get(position : int, value:int&amp;):bool

+ getCapacity(): int

+ print(sout : &amp;ostream) : void

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
A class representing a simple list of integers Pointer to a dynamically allocated array of integers

Allocated capacity of the array above, starting at 1 and doubling the capacity when needed.

Number of elements currently stored in the array Default Constructor, a list of capacity 1, and used=0 Copy constructor

Move constructor

Copy assignment operator

Move assignment operator

Destructor (and a virtual one in this example) Determines whether used equals zero

Determines whether used equals capacity

Returns used

Double the current capacity of the list

Inserts x after the current last element in the list Determines whether x occurs in the list

Returns false if position is out of range; otherwise, places the value stored at position in the reference parameter value and then re- turns true.

Return the allocated capacity of this list

Prints the numbers in the list to the sout stream, separating them by a comma followed by a space

</div>
</div>
<div class="layoutArea">
<div class="column">
Although the public interface of the IntList class above is minimal and would typically include many other useful operations, its implementation is by no means minimal, involving enough basic C++ concepts and issues to meet the objectives of this assignment.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 4 of 19

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
8 Testing Class IntList

Make sure your IntList class works correctly. For example:

1 2 3 4 5 6 7 8 9

10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32 33 34 35 36 37 38 39 40 41 42

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>#include&lt;iostream&gt;
#include&lt;cassert&gt;
#include "IntList.h"
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>using std::cout;
using std::endl;
</pre>
int main() {

<pre>    std::cout &lt;&lt; "Minimal test for IntList!\n";
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>IntList list{};
cout &lt;&lt; "list-1 -&gt; " &lt;&lt; list &lt;&lt; endl;
assert(list.getCapacity() == 0);
</pre>
<pre>list.pushback(19);
cout &lt;&lt; "list-2 -&gt; " &lt;&lt; list &lt;&lt; endl;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>assert(list.getCapacity() == 1);
assert(list.size() == 1);
</pre>
<pre>list.pushback(32);
cout &lt;&lt; "list-3 -&gt; " &lt;&lt; list &lt;&lt; endl;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>assert(list.getCapacity() == 2);
assert(list.size() == 2);
</pre>
<pre>list.pushback(21);
cout &lt;&lt; "list-4 -&gt; " &lt;&lt; list &lt;&lt; endl;
assert(list.getCapacity() == 4);
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>assert(list.size() == 3);
</pre>
<pre>list.pushback(7);
cout &lt;&lt; "list-5 -&gt; " &lt;&lt; list &lt;&lt; endl;
assert(list.getCapacity() == 4);
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>assert(list.size() == 4);
</pre>
<pre>list.pushback(18);
cout &lt;&lt; "list-6 -&gt; " &lt;&lt; list &lt;&lt; endl;
assert(list.getCapacity() == 8);
assert(list.size() == 5);
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>    cout &lt;&lt; "IntList Test Successful" &lt;&lt; endl;
</pre>
return 0; }

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 5 of 19

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
8.1 Output

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Minimal test for IntList!
list-1 -&gt;
list-2 -&gt; 19
list-3 -&gt; 19 32
</pre>
<pre>list-4 -&gt; 19 32 21
list-5 -&gt; 19 32 21 7
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>list-6 -&gt; 19 32 21 7 18
IntList Test Successful
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
9 Class Token

</div>
</div>
<div class="layoutArea">
<div class="column">
− text : char *

− number list: IntList

</div>
</div>
<div class="layoutArea">
<div class="column">
Token

</div>
</div>
<div class="layoutArea">
<div class="column">
A class representing a token

Pointer to a dynamically allocated array of characters (never using C-string pointers again!)

Manages the list of numbers associated with this token

explicit normal constructor, creates a new token using the supplied C-string and line number

Default Constructor, creates an empty C-string Copy constructor

Move constructor

Copy assignment operator

Move assignment operator

Destructor (and a virtual one in this example)

Returns -1, 0, or 1 as “the” this token’s text is less than, equal to, or grater than aToken’s text.

Returns a constant pointer to this token’s text

Adds line num to the end of this token’s number list

Returns the length of this token’s text

Prints this token’s text followed by its number list.

Returns the k’th character (zero-based) of this token’s text. Returns the null character (\0) if k is out-of-range

</div>
</div>
<div class="layoutArea">
<div class="column">
addLineNumber

+ getLineNumber()const : int;

</div>
</div>
<div class="layoutArea">
<div class="column">
Returns this tokens line number, which is stored at position 0 of this token’s list of line numbers

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 6 of 19

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<ul>
<li>+ &nbsp;Token(cstr : const char *, line num : int );</li>
<li>+ &nbsp;Token():</li>
<li>+ &nbsp;Token(token : const Token&amp; ):</li>
<li>+ &nbsp;Token(token : Token&amp;&amp; ):</li>
<li>+ &nbsp;operator=(rhs : const Token&amp; ):Token&amp;</li>
<li>+ &nbsp;operator=(rhs: Token&amp;&amp; ): Token&amp;</li>
<li>+ &nbsp;∼Token() :</li>
<li>+ &nbsp;compare(aToken : const Token&amp; )const : int</li>
<li>+ &nbsp;getText() : const char *</li>
<li>+ &nbsp;(line num : int) : void</li>
<li>+ &nbsp;size() : int</li>
<li>+ &nbsp;print(sout : &amp;ostream) : void</li>
<li>+ &nbsp;getChar(k : int ) const : char</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
9.1 Requirements

<ul>
<li>􏰀 &nbsp;Your implementation of class Token’s member functions may use only the C++ library functions provided by the &lt;cstring&gt; header file, which operate on arrays of characters terminating with the null byte character (\0). For example, you can use the strcpy() and strcat() functions to copy and append a string to a character array, respectively. For another example, you can use the strlen() function to determine the length of a C-string, and you can use the strcmp() to compare two C-strings (which is all you need to implement member function compare).</li>
<li>􏰀 &nbsp;You can also use the functions in &lt;cctype&gt; to manipulate single characters, such as the functions toupper, tolower, isdigit, islower, etc.</li>
<li>􏰀 &nbsp;You may not use the C++ &lt;string&gt; class in this assignment only.</li>
</ul>
10 Testing Class Token

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>#include&lt;iostream&gt;
#include&lt;cassert&gt;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>#include "Token.h"
using std::cout;
</pre>
<pre>using std::endl;
int main()
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>{
    std::cout &lt;&lt; "Testing Class Token\n";
    Token t1{ "Hello", 1 };
    cout &lt;&lt; t1 &lt;&lt; endl;
    t1.addLineNumber(11);
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>t1.addLineNumber(13);
t1.addLineNumber(74);
t1.addLineNumber(92);
cout &lt;&lt; t1 &lt;&lt; endl;
</pre>
return 0;

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
}

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8 9

10 11 12 13 14 15 16 17 18 19 20

</div>
</div>
<div class="layoutArea">
<div class="column">
10.1 output

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>Testing Class Token
Token ctor with the string: Hello
</pre>
<pre>          Hello, 1
          Hello, 1 11 13 74 92
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 7 of 19

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
11 Class TNode

Since TNode objects are created and used solely by the TList class, it makes sense to have class TList host TNode as a private member type, completely isolating it from the outside world:

1 2 3 4 5 6 7 8 9

10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
//TList.h

<pre>class TList {
// a private "member type"
struct TNode
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>{
    Token theToken = Token{ };  // node data
    TNode* prev;                // previous node in list
    TNode* next;                // next node in list
    TNode(const Token&amp; token = Token{ }, TNode* p = nullptr,
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>    TNode* n = nullptr)
    : theToken{ token }, prev{ p }, next{ n }{}
</pre>
<pre>TNode(Token&amp;&amp; token, TNode* p = nullptr, TNode* n = nullptr)
    : theToken{ std::move(token) }, prev{ p }, next{ n }{}
</pre>
<pre>TNode&amp; operator=(const TNode&amp;) = delete;        // copy assignment
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>    TNode&amp; operator=(TNode&amp;&amp;)      = delete;        // move assignment
</pre>
<pre>    ~TNode() = default;
};
</pre>
public:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>// ... public members of TList
</pre>
<pre>private:
// ... private members of TList
};
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Typically, nodes (such as TNode objects) in a linked list are seldom responsible for allocation and deallocation of resources they represent; their raison d’etre is to keep the items in the list linked.

Notice that we choose to represent a node in our linked list in terms of a struct rather than a class for no special reason other than to remind us that the only difference between struct and class is that by default the members of a struct are public whereas by default the members of a class are private.

However, notice that although “any code” using a TNode object can freely access all of that object’s members, the member type TNode itself is a private member of the TList class, and as such the member type TNode is visible only to members of TList.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 8 of 19

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
12 Class TList

This class models a linked list of tokens, implementing a doubly linked list of nodes of type TNode. Typically, a TNode objects stores three values, of which two point to neighboring TNode objects, if any. The third value represents a data object, either directly or indirectly, as depicted in Figures 1 and 2 below, respectively.

previous node next node

Figure 1: A node in a doubly linked list storing a Token object directly

The node structure in Figure 1 illustrates a major difference between Java and C++, indicating

the fact that C++ allows object variables to have names and hold values:

1 2 3 4 5

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
Token object

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>class Token{/* ... */};
</pre>
int main() {

<pre>   Token t{"abc", 11}; // a token = a C-string together with an assiciated number
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
6 7 8 9

10 11 12

</div>
</div>
<div class="layoutArea">
<div class="column">
Notice that t is an actual Token object stored on the run-time stack.

In Java, t would just be a reference variable, not yet referencing anything. For the variable t to

reference an actual Token object in Java, you write t = new Token(“abc”, 11);, for example. In C++, you can, of course, use the operator new to create unnamed objects to point at, but

you don’t have to!

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Token* pt = new Token("abc", 11);     // old C++ style
Token* qt  {new Token{"xyz", 22}};   // modern C++ style
// use pt and qt
delete pt;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
delete qt;

return 0; }

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
But if you do use the operator new to create unnamed objects as in lines 6 and 7, you MUST delete both pt and qt before they exit their scope. Recall that deleting pointers such as pt and qt releases (frees, deallocates) the objects pointed at by pt and qt and NOT the variables pt and qt themselves.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 9 of 19

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
One way to represent Figure 1 above in both C++ and Java is as follows:

Token object

previous node next node

A node in a doubly linked list storing a pointer to Figure 2: a Token object rather than directly storing the

Token object itself as in Figure 1.

Since Java seems to be a primary programming language for most students in this course, you will use the structure in Figure 1 in your TNode class so that you can quickly adapt to using object variables in C++ without necessarily using the new operator.

</div>
</div>
<div class="layoutArea">
<div class="column">
Thus, an instance of the TList class may be depicted as follows: a pointer to the header node

</div>
<div class="column">
a pointer to the trailer node trailerPtr

trailer node

</div>
</div>
<div class="layoutArea">
<div class="column">
headerPtr

header node

</div>
<div class="column">
Token objects

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
TO

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
TO

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
TO

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
TO

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
unused

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
unused

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Figure 3: A doubly linked list storing four Token objects denoted by the symbol TO.

</div>
</div>
<div class="layoutArea">
<div class="column">
Recall (from COMP 5511 or equivalent background on data structures) that implementation of list operations in a doubly linked list can be greatly simplified by using two extra nodes referred to as the header and trailer nodes (also called sentinel nodes and dummy nodes).

Notice that the prev and Token components of the header node, and similarly, the next and Token components of the trailer node, are ignored by the list representation depicted in Figure 3; however, they are all default constructed.

For an empty list, the header and trailer nodes point at each other, as depicted in Figure 4. For a non-empty list, the header node points at the first node and the trailer node points at the last node, as depicted in Figure 3.

</div>
<div class="column">
pointers to the header and trailer nodes

</div>
</div>
<div class="layoutArea">
<div class="column">
headerPtr

</div>
<div class="column">
trailerPtr

</div>
</div>
<div class="layoutArea">
<div class="column">
fixed (dummy) nodes

Figure 4: An empty list

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 10 of 19

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
The primary advantage of using the dummy nodes is that they facilitate implementation of list operations by eliminating a host of special cases (e.g., empty list, first node, last node, list with a single node, etc.) and potential programming pitfalls.

Here are the specifics:

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 11 of 19

</div>
</div>
</div>
<div class="page" title="Page 12">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
TList

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
− headerPtr : TNode *

− trailerPtr : TNode * − theSize : int

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
+ TList():

+ TList(list : const TList&amp; ):

+ TList(list : TList&amp;&amp; ):

+ operator=(rhs : const TList&amp; ):TList&amp; + operator=(rhs: TList&amp;&amp; ): TList&amp;

+ ∼TList() :

+ empty()const : bool

+ front( ) const : const Token&amp;

+ back( ) const : const Token&amp;

+ addSorted ( aToken : const Token&amp;) :void + removeFront( ) : bool

+ removeBack( ) : bool

+ size() const : int

+ print(sout : ostream&amp;) const : void

+ search(aToken : const Token&amp;) const : bool

− lookup (aToken : const Token&amp;) const : TNode*

− init( ) : void

− addBefore(p : TNode*, t : const Token&amp;) : void − remove(nodePtr : TNode*) : void

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
A class representing a doubly linked list

A pointer to the sentinel header node at the front of the list

A pointer to the sentinel trailer node at the back of the list

Stores the number of nodes in this list Default constructor, creates an list Copy constructor

Move constructor

Copy assignment operator

Move assignment operator

Destructor (and a virtual one in this example)

Determines whether this list is empty

Retruns the token at the front of this list

Retruns the token at the back of this list

Adds aToken at its sorted position into the list so as to maintain the ascending order of the list

If the list is nonempty, removes the node at the front of the list and returns true; otherwise, returns false

If the list is nonempty, removes the node at the end of the list and returns true; otherwise, returns false

Returns theSize Prints the entire list

Determines whether aToken is in the list.

Determines whether aToken is in the list. If false, it returns trailerPtr; otherwise, it either returns a pointer to the node that is equal to aToken, or returns a pointer to the node that would appar after aToken, if aToken already existed in the list (see page 19)

Initializes this list to an empty list at construction Inserts a new node before the node p points to Removes the node nodePtr points to

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 12 of 19

</div>
</div>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
13

</div>
<div class="column">
Hints on TList’s default ctor

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>// a private helper method
</pre>
<pre>void TList::init()
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
{

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>// initialize to an empty list
</pre>
<pre>this-&gt;theSize = 0;
headerPtr = new TNode{};        // headerPtr will always point to this
</pre>
<pre>                                // allocated fixed header node
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8 9

10 11 12 13 14 15 16 17 18 19 20

</div>
<div class="column">
<pre>trailerPtr = new TNode{};
</pre>
<pre>headerPtr-&gt;next = trailerPtr;
trailerPtr-&gt;prev = headerPtr;
</pre>
</div>
<div class="column">
<pre>// trailerPtr will always point to this
// allocated fixed header node
</pre>
<pre>// header node’s next points to the trailer node
// trailer node’s prev points to the header node
</pre>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
}

<pre>// default constructor
</pre>
<pre>TList::TList()
{
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
init(); }

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
14

ascending order of the tokens in the list, forcing it to exclude them from its public interface.

TList provides only one insertion method, namely, addSorted(aToken), which inserts aToken in its sorted position in the list.

There are couple reasons why they are given here:

<ul>
<li>􏰀 &nbsp;To show you how easy it is to insert a node before or after any given node in a doubly linked list that uses a pair of sentinel nodes to sandwich the actual list.</li>
<li>􏰀 &nbsp;To suggest a way to quickly test your TList at early stages of its development; after all, the first thing we want to do when constructing a list is to try to put some items into it! So feel free to include the functions below as private or protected members of TList, if you can use them in some way in your implementation.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Hints on inserting a new node into a TList object

The three functions listed below are not specified by class TList because TList must maintain

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 13 of 19

</div>
</div>
</div>
<div class="page" title="Page 14">
<div class="layoutArea">
<div class="column">
14.1 Hints on inserting a new node before or after any node

1 2 3 4 5 6 7 8 9

10 11 12 13 14

1 2 3 4

1 2 3 4

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>// insert a new node pointed by p before a given node pointed to by q
</pre>
<pre>void TList::addBefore(TNode* q, const Token&amp; aToken)
{
</pre>
<pre>        ++this-&gt;theSize;
        TNode* p = new TNode{ aToken };
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>// link p between q-&gt;prev and q
</pre>
<pre>p-&gt;next = q;
p-&gt;prev = q-&gt;prev;
</pre>
<pre>// now that p can see q-&gt;prev and q,
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
}

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>// we let q-&gt;prev and q see p to complete the insertion
</pre>
<pre>q-&gt;prev = (q-&gt;prev)-&gt;next = p;
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
14.2 Hints on inserting a token at the front of a list

However, the simplicty of the

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>void TList::addFront(const Token&amp; tok)  // add new token to front of list
{
</pre>
<pre>    addBefore(headerPtr-&gt;next, tok);
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
}

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
14.3 Hints on inserting a token at the back of the list

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>void TList::addBack(const Token&amp; tok)   // add new token to end of list
{
</pre>
<pre>    addBefore(trailerPtr, tok);
}
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
14.4 Did you notice advantages of using the dummy header and trailer nodes?

􏰀 No tests for checking if the list is empty

􏰀 No need to know the location (front, back, or in the middle, or anywhere) in the list where

a new node is to be inserted 􏰀 No if statements!

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 14 of 19

</div>
</div>
</div>
<div class="page" title="Page 15">
<div class="layoutArea">
<div class="column">
15 Heads Up

Transitioning from the classical C++ to modern C++, future course assignments will prohibit the use of character arrays as well as the use of functions supported in the &lt;cstring&gt; header file.

16 Test Drive with Tokenizer App 16.1 Tokenizer.h

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>#ifndef TOKENIZERAPP_H_
#define TOKENIZERAPP_H_
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>#include "TList.h"
</pre>
<pre>class TokenizerApp
{
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>private:
  TList tokenList{};
</pre>
<pre>public:
    void loadTokenList(const char* filename);
    TokenizerApp(const char* filename);
    void print(ostream&amp; sout)const;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
}; #endif

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
16.2 Tokenizercpp.cpp

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>#include &lt;ostream&gt;
#include &lt;fstream&gt;
#include &lt;sstream&gt;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>#include "TList.h"
#include "TokenizerApp.h"
</pre>
<pre>void TokenizerApp::loadTokenList(const char* filename)
{
</pre>
<pre>    ifstream fin(filename);
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
if (!fin) {

<pre>    cout &lt;&lt; "could not open input file: " &lt;&lt; filename &lt;&lt; endl;
</pre>
exit(1); }

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>int linenum = 0;
string line;
getline(fin, line);  // attempt to read a line
while (fin)
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 15 of 19

</div>
</div>
</div>
<div class="page" title="Page 16">
<div class="layoutArea">
<div class="column">
{

++linenum;

<pre>    istringstream sin(line); // convert the line just read into an input stream
</pre>
</div>
</div>
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>string word;
while (sin &gt;&gt; word)  // extract the tokens and add them to tokenList
{
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
tokenList. (Token(word.c_str(), linenum)); }

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
addSorted

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>        getline(fin, line);
    }
</pre>
<pre>    fin.close();
}
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>TokenizerApp::TokenizerApp(const char* filename)
{
</pre>
<pre>    loadTokenList(filename);
}
</pre>
<pre>void TokenizerApp::print(ostream&amp; sout)const
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>{
    tokenList.print(sout);
</pre>
}

</div>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
16.3 main.cpp

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>#include&lt;iostream&gt;
#include "TokenizerApp.h"
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>using std::cout;
using std::endl;
</pre>
int main() {

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>const char* filename = "input_text_file.txt";
// this file is located in the visual studio storing
// all the .cpp and .h file for this project.
// or
// const char* filename = "C:\\COMP5421\\A1\\input_text_file.txt";
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>TokenizerApp tokApp(filename);
tokApp.print(cout);
cout &lt;&lt; endl;
</pre>
return 0;

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
}

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 16 of 19

</div>
</div>
</div>
<div class="page" title="Page 17">
<div class="layoutArea">
<div class="column">
16.4 Input

1 2 3 4 5 6 7 8 9

10 11 12 13

1 2 3 4 5 6 7 8 9

10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Do you like green eggs and ham?
</pre>
<pre>I do not like them, Sam-I-am.
I do not like green eggs and ham!
</pre>
<pre>Would you like them here or there?
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>I would not like them here or there.
I would not like them anywhere.
</pre>
<pre>I do so like green eggs and ham!
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Thank you! Thank you,
Sam-I-am!
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
16.5 Output

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
-&gt; -&gt; -&gt;

</div>
<div class="column">
Do 1

I 3 4 8 9 11

Sam-I-am! 13

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>-&gt;
-&gt;
-&gt;
-&gt;
-&gt;
-&gt;
</pre>
</div>
<div class="column">
<pre>Sam-I-am. 3
    Thank 12 12
</pre>
<pre>    Would 6
      and 1 4 11
</pre>
<pre>anywhere. 9
       do 3 4 11
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
-&gt; -&gt; -&gt; -&gt; -&gt;

</div>
<div class="column">
<pre> eggs 1 4 11
green 1 4 11
</pre>
<pre> ham! 4 11
 ham? 1
 here 6 8
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>-&gt;
-&gt;
-&gt;
-&gt;
-&gt;
-&gt;
</pre>
</div>
<div class="column">
<pre> like 1 3 4 6 8 9 11
  not 3 4 8 9
</pre>
or 6 8

so 11 them 6 8 9

them, 3

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
-&gt; -&gt; -&gt; -&gt; -&gt;

</div>
<div class="column">
<pre>there. 8
there? 6
</pre>
<pre> would 8 9
   you 1 6
</pre>
you! 12

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
-&gt; you, 12

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 17 of 19

</div>
</div>
</div>
<div class="page" title="Page 18">
<div class="layoutArea">
<div class="column">
17 Deliverables

Create a a new folder that contains the files listed below, then compress (zip) your folder, and submit the compressed (zipped) folder as instructed in the course outline.

<ol>
<li>Header files: IntList.h, Token.h, TList.h, and TokenizerApp.h. TNode.h is optional.</li>
<li>Implementation files: TNode.cpp is optional.

IntList.cpp, Token.cpp, TList.cpp, and TokenizerApp.cpp, and main.cpp.</li>
<li>Input file input file A1.txt</li>
<li>Output file output file A1.txt (copy output from cmd window and paste it into this
file)
</li>
<li>A README.txt text file (see the course outline).</li>
</ol>
18 Grading scheme

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Functionality

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
􏰀 Correctness of execution of your program,

􏰀 Proper implementation of all specified requirements, 􏰀 Efficiency

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
60%

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
OOP style

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<ul>
<li>􏰀 &nbsp;Encapsulating only the necessary data inside your objects,</li>
<li>􏰀 &nbsp;Information hiding,</li>
<li>􏰀 &nbsp;Proper use of C++ constructs and facilities.</li>
<li>􏰀 &nbsp;No global variables</li>
<li>􏰀 &nbsp;No use of the operator delete.</li>
<li>􏰀 &nbsp;No C-style memory functions such as malloc, alloc, realloc,
free, etc.
</li>
</ul>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
20%

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Documentation

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
􏰀 Description of purpose of program,

􏰀 Javadoc comment style for all methods and fields, 􏰀 Comments for non-trivial code segments

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
10%

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Presentation

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
􏰀 Format, clarity, completeness of output, 􏰀 User friendly interface

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
5%

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Code readability

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Meaningful identifiers, indentation, spacing

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
5%

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Assignment 1, Rev.1, Summer 2021 page 18 of 19

</div>
</div>
</div>
<div class="page" title="Page 19">
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8 9

</div>
</div>
<div class="layoutArea">
<div class="column">
19

</div>
<div class="column">
TList’s lookup and addSorted member functions

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>// where would tok be located on our list of tokens?
</pre>
<pre>TNode* TList::lookup(const Token&amp; tok) const
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>{
    TNode* head = this-&gt;headerPtr-&gt;next;
    while (head != this-&gt;trailerPtr)
    {
</pre>
<pre>        // compare the cstrings in the following two token objects;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>    // =0 means equal, &gt;0 means head-&gt;theToken &gt; tok
</pre>
<pre>    if (((head-&gt;theToken).compare( tok)) &gt;= 0)  break;
</pre>
<pre>    head = head-&gt;next;
}
</pre>
return head;

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
}

<pre>// Insert token at its sorted position
</pre>
<pre>void TList::addSorted(const Token&amp; aToken)
{
</pre>
<pre>    TNode* nodePtr = lookup(aToken);
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>if (nodePtr == trailerPtr) // aToken not on the list, and
{                          // greater than all the other tokens
</pre>
<pre>    addBefore(trailerPtr, aToken);
</pre>
<pre>}
else if ((*nodePtr).theToken == aToken) // equivalent to nodePtr-&gt;theToken;
{
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>// (*nodePtr).theToken is
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
10

11

12

13

14

15

16

17

18

19

20

21

22

23

24

25

26

27

28

29

30

31

32 }

33 return; 34 }

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>int lineNum = aToken.getLineNumber();
(nodePtr-&gt;theToken).addLineNumber(lineNum); // so fetch its line number and
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
}

else

<pre>                                // inserted before the node which nodePtr points at
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>{                               // otherwise, aToken is not on the list, and,
    addBefore(nodePtr, aToken); // to maintain sorted order of the list, it should be
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>// aToken is on the list,
// add it to its list of line numbers
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
