Download Link: https://assignmentchef.com/product/solved-ece30862-homework-9-linked-list-interface
<br>
For HW 9 we will write a Java program that defines and  uses a linked list interface to that forces implementors of the interface to support very basic linked list functionality.  The file Main.java contains the main function.  Your code should work with it and produce output similar to what is shown in the file <em>output.txt</em>.  <strong><em>Your code does not have to have the same number of lines listed below, these are basically guidelines to let you know approximately how long the code will be.</em></strong>

You will create three .java files with the following functionality:

<strong>MyList.java (6 lines, including blank lines, in my implementation):</strong>  This defines the <em>MyList</em> interface, which defines two abstract methods:

<em>public</em> <em>MyList next( )</em>; <em>public void printNode( ); </em>

<strong>IntList.java (20 lines, including blank lines, in my implementation):</strong>  This defines the <em>IntList</em> class which implements the <em>MyList</em> interface.

<strong>This class has two fields</strong>, <em>next</em>, which is a <em>IntList</em> reference, and <em>data</em>, which is an <em>int</em>.

<strong>The class defines a constructor and several functions:</strong>

<em>public IntList(IntList n, int data) </em>which adds <em>n</em> to the tail of the linked list. <em>public int getData( ) </em>which returns the value of <em>data</em>;

<em>public IntList next( )</em> which returns the next node in the linked list.  Note that this is the implementation of <em>public</em> <em>MyList next( )</em>; in the <em>MyList</em> interface.

<em>public void printNode( )</em> which uses <em>System.out.print</em> to print the kind of node, and the value of data.  Note that this is the implementation of <em>public void printNode( );</em> in the <em>MyList</em> interface.

<strong>LongList.java (20 lines, including blank lines, in my implementation):</strong>  This defines the <em>LongList</em> class which implements the <em>MyList</em> interface.   The functions are very similar to those in IntList.

<strong>This class has two fields</strong>, <em>next</em>, which is a <em>LongList</em> reference, and <em>data</em>, which is a <em>long</em>.

<strong>The class defines a constructor and several functions: </strong><em>public LongList(LongList n, long data) </em>which adds <em>n</em> to the front of the linked list; <em>public long getData( ) </em>which returns the value of <em>data</em>; <em>public LongList next( )</em> which returns the next node in the linked list;

<em>public void printNode( )</em> which uses <em>System.out.print</em> to print the kind of node, and the value of data.  Note that this is the implementation of <em>public void printNode( );</em> in the <em>MyList</em> interface.